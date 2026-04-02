안녕하십니까? 
정상일 실장입니다.
<!DOCTYPE html>
<html lang="ko">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0">
<title>Dio.L9 - 정상일 실장</title>

<!-- 카카오톡 / 미리보기 설정 -->
<meta property="og:type" content="website">
<meta property="og:title" content="정상일 실장 · 평촌 디오르나인 안양역 분양 상담">
<meta property="og:description" content="✔ 오늘 계약·오늘 입주 ✔ 안양역 더블 초역세권 ✔ 대출규제·거주의무 없음 | 터치하시면 정상일 실장 모바일 명함으로 연결됩니다.">
<meta property="og:url" content="https://cyh1931-boop.github.io/dio-card6/">
<meta property="og:site_name" content="Dio.L9 평촌 디오르나인 안양역">

<link href="https://fonts.googleapis.com/css2?family=Noto+Serif+KR:wght@300;400;600&family=Noto+Sans+KR:wght@300;400;500;700&display=swap" rel="stylesheet">

<style>
  *{box-sizing:border-box;margin:0;padding:0;}
  :root{
    --gold:#b8965a;
    --gold-light:#d4b07a;
    --dark:#1a1a1a;
    --card-bg:#fffdf9;
    --pink-border:#e8c5cb;
  }
  body{
    background:#f0ece4;
    font-family:'Noto Sans KR',sans-serif;
    min-height:100vh;
    display:flex;
    flex-direction:column;
    align-items:center;
    padding:0 0 40px;
  }

  /* TOP BANNER */
  .banner{
    width:100%;
    background:#1a1a1a;
    color:#f5f0e8;
    padding:20px 20px 0;
    position:relative;
    overflow:hidden;
  }
  .banner::before{
    content:'';
    position:absolute;
    top:0;left:0;right:0;
    height:3px;
    background:linear-gradient(90deg,#b8965a,#d4b07a,#b8965a);
  }
  .brand-row{
    display:flex;
    align-items:center;
    gap:10px;
    margin-bottom:16px;
  }
  .brand-logo{
    font-family:'Noto Serif KR',serif;
    font-size:22px;
    font-weight:600;
    color:#d4b07a;
    letter-spacing:1px;
  }
  .brand-sub{
    font-size:9px;
    color:rgba(245,240,232,0.45);
    letter-spacing:2px;
    text-transform:uppercase;
    line-height:1.3;
  }

  .msg-box{
    background:rgba(255,255,255,0.05);
    border:1px solid rgba(184,150,90,0.2);
    border-radius:12px;
    padding:16px 18px;
    margin-bottom:20px;
    font-size:13px;
    line-height:1.85;
    color:rgba(245,240,232,0.88);
  }
  .msg-box p{margin-bottom:10px;}
  .msg-box p:last-child{margin-bottom:0;}

  .msg-section{
    margin:8px 0 4px;
    font-size:12px;
    font-weight:500;
    color:#d4b07a;
    letter-spacing:0.3px;
  }
  .msg-list{
    list-style:none;
    padding-left:8px;
    margin-bottom:6px;
  }
  .msg-list li{
    font-size:12px;
    color:rgba(245,240,232,0.78);
    padding:2px 0;
    line-height:1.6;
  }
  .msg-list li::before{content:'· ';color:#b8965a;}

  /* CARD */
  .card-wrap{
    width:calc(100% - 32px);
    max-width:400px;
    margin:0 16px;
    margin-top:-1px;
  }
  .card{
    background:var(--card-bg);
    border-radius:16px;
    border:2px solid var(--pink-border);
    overflow:hidden;
    box-shadow:0 8px 32px rgba(0,0,0,0.18);
    position:relative;
  }
  .card-inner{
    padding:24px 24px 20px;
    position:relative;
  }
  .card-logo{
    position:absolute;
    top:20px;right:20px;
    text-align:right;
  }
  .card-logo-main{
    font-family:'Noto Serif KR',serif;
    font-size:20px;
    font-weight:600;
    color:#1a1a1a;
    letter-spacing:1px;
    line-height:1;
  }
  .card-logo-sub{
    font-size:8px;
    color:#aaa;
    letter-spacing:1.5px;
    text-transform:uppercase;
    margin-top:2px;
  }
  .name-block{
    margin-top:48px;
    margin-bottom:14px;
  }
  .name-kr{
    font-family:'Noto Serif KR',serif;
    font-size:26px;
    font-weight:600;
    color:#1a1a1a;
    letter-spacing:4px;
  }
  .name-rank{
    display:inline-block;
    font-size:12px;
    color:#888;
    font-weight:400;
    margin-left:10px;
    letter-spacing:0.5px;
  }
  .divider{
    height:1px;
    background:linear-gradient(to right,var(--pink-border),transparent);
    margin:0 0 14px;
  }
  .contact-row{
    display:flex;
    align-items:center;
    gap:10px;
    margin-bottom:10px;
  }
  .contact-icon{
    width:28px;height:28px;
    background:#1a1a1a;
    border-radius:7px;
    display:flex;align-items:center;justify-content:center;
    flex-shrink:0;
  }
  .contact-icon svg{width:13px;height:13px;fill:#d4b07a;}
  .contact-label{font-size:9px;color:#bbb;letter-spacing:1.5px;text-transform:uppercase;margin-bottom:1px;}
  .contact-value{font-size:13.5px;color:#1a1a1a;font-weight:500;}
  .contact-value a{color:#1a1a1a;text-decoration:none;}

  .card-footer{
    display:flex;
    align-items:center;
    justify-content:space-between;
    padding:12px 24px 16px;
    border-top:1px solid var(--pink-border);
    background:rgba(232,197,203,0.1);
  }
  .addr-text{font-size:10.5px;color:#888;line-height:1.5;flex:1;padding-right:12px;}
  .on-logo{
    flex-shrink:0;
    width:44px;height:44px;
    border-radius:50%;
    background:#1a1a1a;
    display:flex;align-items:center;justify-content:center;
    font-family:'Noto Serif KR',serif;
    font-size:15px;
    font-weight:700;
    color:#fff;
    letter-spacing:-0.5px;
  }

  /* BUTTONS */
  .btn-wrap{
    width:calc(100% - 32px);
    max-width:400px;
    margin:16px 16px 0;
    display:grid;
    grid-template-columns:1fr 1fr;
    gap:10px;
  }
  .btn{
    display:flex;
    align-items:center;
    justify-content:center;
    gap:8px;
    padding:14px 10px;
    border-radius:12px;
    font-size:13px;
    font-weight:500;
    font-family:'Noto Sans KR',sans-serif;
    text-decoration:none;
    cursor:pointer;
    transition:opacity 0.2s,transform 0.1s;
    border:none;
    -webkit-tap-highlight-color:transparent;
  }
  .btn:active{transform:scale(0.97);opacity:0.85;}
  .btn svg{width:16px;height:16px;flex-shrink:0;}
  .btn-call{background:#1a1a1a;color:#f5f0e8;}
  .btn-call svg{fill:#d4b07a;}
  .btn-web{background:#b8965a;color:#fff;}
  .btn-web svg{fill:#fff;}
  .btn-sms{
    grid-column:1/-1;
    background:#f5f0e8;
    color:#1a1a1a;
    border:1px solid #e0d5c5;
    font-size:12px;
  }
  .btn-sms svg{fill:#b8965a;}

  /* CTA */
  .cta{
    width:calc(100% - 32px);
    max-width:400px;
    margin:12px 16px 0;
    background:linear-gradient(135deg,#1a1a1a 0%,#2d2416 100%);
    border-radius:14px;
    padding:18px 20px;
    display:flex;
    align-items:center;
    justify-content:space-between;
    gap:12px;
  }
  .cta-text{
    font-size:13px;
    color:rgba(245,240,232,0.75);
    line-height:1.5;
  }
  .cta-text strong{
    display:block;
    font-size:15px;
    font-weight:700;
    color:#d4b07a;
    margin-bottom:2px;
  }
  .cta-btn{
    flex-shrink:0;
    background:#b8965a;
    color:#fff;
    border:none;
    border-radius:10px;
    padding:10px 16px;
    font-size:12px;
    font-weight:600;
    font-family:'Noto Sans KR',sans-serif;
    cursor:pointer;
    white-space:nowrap;
    text-decoration:none;
    -webkit-tap-highlight-color:transparent;
  }
</style>
</head>
<body>

<!-- TOP BANNER -->
<div class="banner">
  <div class="brand-row">
    <div>
      <div class="brand-logo">Dio.L9</div>
      <div class="brand-sub">Luxury Limited House</div>
    </div>
  </div>

  <div class="msg-box">
    <p>✅ <strong style="color:#d4b07a;">오늘 계약, 오늘 입주 가능!</strong><br>
    안양 기입주 아파트, 지금 바로 입주할 수 있는 실입주·투자 기회입니다.</p>

    <p>🏡 <strong style="color:#d4b07a;">원스톱 계약 서비스</strong><br>
    취득세부터 대출, 입주 절차까지 한 번에 깔끔하게 처리해 드립니다.</p>

    <div class="msg-section">🏢 단지·타입 안내</div>
    <ul class="msg-list">
      <li>지하 6층 ~ 지상 25층, 안정적인 대단지 구조</li>
      <li>전용 74A · 74B · 84A, 3개 타입 구성</li>
      <li>🚉 안양역 더블 초역세권 입지 (도보 생활권)</li>
    </ul>

    <div class="msg-section">💰 투자·실거주 메리트</div>
    <ul class="msg-list">
      <li>주변 단지 대비 합리적인 시세</li>
      <li>대출 규제 없음, 거주의무 없음</li>
      <li>은행 협약 대출 최대 70% 가능</li>
      <li>분양 총액의 5% 특별 할인 제공</li>
    </ul>

    <div class="msg-section">🛍️ 생활 인프라 & 커뮤니티</div>
    <ul class="msg-list">
      <li>종합병원·아울렛·안양지하상가 도보 이용 가능</li>
      <li>입주민 특화 커뮤니티 시설 (여가·운동·소통)</li>
    </ul>

    <p style="margin-top:10px;">📌 <strong style="color:#d4b07a;">방문 예약 필수</strong> — 방문 전 예약 후 내방해 주시면, 현장 안내와 대출 가능 여부까지 맞춤 상담 도와드립니다.</p>
  </div>
</div>

<!-- CARD -->
<div class="card-wrap">
  <div class="card">
    <div class="card-inner">
      <div class="card-logo">
        <div class="card-logo-main">Dio.L9</div>
        <div class="card-logo-sub">Luxury Limited House</div>
      </div>

      <div class="name-block">
        <span class="name-kr">정 상 일</span>
        <span class="name-rank">실장</span>
      </div>
      <div class="divider"></div>

      <div class="contact-row">
        <div class="contact-icon">
          <svg viewBox="0 0 24 24"><path d="M6.62 10.79a15.05 15.05 0 0 0 6.59 6.59l2.2-2.2a1 1 0 0 1 1.01-.24c1.12.37 2.33.57 3.58.57a1 1 0 0 1 1 1V20a1 1 0 0 1-1 1C9.61 21 3 14.39 3 6a1 1 0 0 1 1-1h3.5a1 1 0 0 1 1 1c0 1.25.2 2.45.57 3.57a1 1 0 0 1-.45 1.22z"/></svg>
        </div>
        <div>
          <div class="contact-label">Mobile</div>
          <div class="contact-value"><a href="tel:01040356912">010-4035-6912</a></div>
        </div>
      </div>
    </div>

    <div class="card-footer">
      <div class="addr-text">경기도 안양시 만안구 안양로 243<br>(1BL 3층 홍보관)</div>
      <div class="on-logo">ON</div>
    </div>
  </div>
</div>

<!-- ACTION BUTTONS -->
<div class="btn-wrap">
  <a class="btn btn-call" href="tel:01040356912">
    <svg viewBox="0 0 24 24"><path d="M6.62 10.79a15.05 15.05 0 0 0 6.59 6.59l2.2-2.2a1 1 0 0 1 1.01-.24c1.12.37 2.33.57 3.58.57a1 1 0 0 1 1 1V20a1 1 0 0 1-1 1C9.61 21 3 14.39 3 6a1 1 0 0 1 1-1h3.5a1 1 0 0 1 1 1c0 1.25.2 2.45.57 3.57a1 1 0 0 1-.45 1.22z"/></svg>
    전화 연결
  </a>
  <a class="btn btn-web" href="https://cyh1931.creatorlink.net/" target="_blank" rel="noopener noreferrer">
    <svg viewBox="0 0 24 24"><path d="M12 2a10 10 0 1 0 0 20A10 10 0 0 0 12 2zm-1 17.93V18a1 1 0 0 0-1-1H8a3 3 0 0 1-3-3v-1l4 4v1c0 .34.03.67.07 1zm6.32-2.06l-1.32-1.32a1 1 0 0 0-.71-.29H13v-2a1 1 0 0 0-1-1H9v-2h2a1 1 0 0 0 1-1V7h2a2 2 0 0 1 2 2v1.5l2 2a8 8 0 0 1-1.68 3.37z"/></svg>
    홈페이지
  </a>
  <a class="btn btn-sms" href="sms:01040356912">
    <svg viewBox="0 0 24 24"><path d="M20 2H4a2 2 0 0 0-2 2v18l4-4h14a2 2 0 0 0 2-2V4a2 2 0 0 0-2-2z"/></svg>
    문자 보내기
  </a>
</div>

<!-- CTA -->
<div class="cta">
  <div class="cta-text">
    <strong>📌 방문 예약 상담</strong>
    전화 또는 문자로 예약 후 방문해 주세요
  </div>
  <a class="cta-btn" href="tel:01040356912">예약 전화</a>
</div>

</body>
</html>
