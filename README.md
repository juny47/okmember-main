<!-- 파일명: okmember.html -->
<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>OK멤버 기능 소개</title>
  <style>
    body { font-family: 'Noto Sans KR', sans-serif; margin: 0; padding: 0; background-color: #fff; color: #333; }
    header { background: #f5f5f5; padding: 10px 20px; display: flex; justify-content: space-between; align-items: center; }
    nav a { margin: 0 10px; text-decoration: none; color: #000; }
    .hero { background: #222; height: 400px; display: flex; align-items: center; justify-content: center; text-align: center; color: #fff; }
    .hero h1 { font-size: 32px; margin-bottom: 10px; }
    .hero p { font-size: 20px; }
    .section { max-width: 1200px; margin: 50px auto; padding: 0 20px; }
    .section h2 { font-size: 28px; margin-bottom: 20px; border-bottom: 2px solid #000; padding-bottom: 10px; }
    .features { display: flex; flex-wrap: wrap; gap: 30px; }
    .feature-item { width: calc(20% - 20px); border: 1px solid #ddd; padding: 20px; box-sizing: border-box; }
    .feature-item h3 { font-size: 18px; margin-top: 10px; }
    .feature-item p { font-size: 14px; color: #555; }
    .more-btn { text-align: center; margin: 30px 0; }
    .type-section { background: #f9f9f9; padding: 50px 20px; }
    .type-options { display: flex; justify-content: space-around; margin-top: 30px; }
    .type-box { border: 1px solid #ccc; padding: 20px; width: 30%; text-align: center; }
    .footer { background: #f2f2f2; padding: 30px 20px; text-align: center; }
    .partners { display: flex; justify-content: center; gap: 20px; margin-top: 20px; }
    .partners img { width: 100px; }
  </style>
</head>
<body>

  <header>
    <div class="logo">OK멤버</div>
    <nav>
      <a href="#">소개</a>
      <a href="#">주요기능</a>
      <a href="#">가격안내</a>
      <a href="#">고객지원</a>
      <a href="#">문의</a>
    </nav>
  </header>

  <section class="hero">
    <div>
      <h1>우리 단체 수첩,<br>이제 스마트폰에 담으세요</h1>
      <p>모임을 연결하는 수첩, OK멤버!</p>
    </div>
  </section>

  <section class="section">
    <h2>주요 기능</h2>
    <div class="features">
      <div class="feature-item">
        <h3>01. AI 모바일회원수첩</h3>
        <p>내가 만난 사람을 자동으로 기억하고 메모 남길 수 있는 회원수첩</p>
      </div>
      <div class="feature-item">
        <h3>02. 경조사 알림</h3>
        <p>문자/대량메일 발송으로 단체정보 빠르게 전달</p>
      </div>
      <div class="feature-item">
        <h3>03. 행사참석 관리</h3>
        <p>행사 연락처 수집부터 참석자까지 한 번에 관리</p>
      </div>
      <div class="feature-item">
        <h3>04. 회비 자동 결제</h3>
        <p>안정적인 활동비 모금 및 관리</p>
      </div>
      <div class="feature-item">
        <h3>05. 비즈니스 제휴서비스</h3>
        <p>광고, 제휴, 기부금 연계로 혜택 제공</p>
      </div>
    </div>
  </section>

  <div class="more-btn">
    <button>더 많은 기능 보러 가기 →</button>
  </div>

  <section class="type-section">
    <h2>우리 단체에 맞는 모바일 회원수첩을 체험해 보세요</h2>
    <div class="type-options">
      <div class="type-box">
        <h3>일반형</h3>
        <p>100명 미만 단체에 적합</p>
        <button>체험하기</button>
      </div>
      <div class="type-box">
        <h3>AI 기능형</h3>
        <p>스마트한 기능으로 차별화</p>
        <button>문의하기</button>
      </div>
      <div class="type-box">
        <h3>비즈형</h3>
        <p>홍보·제휴 중심의 확장형</p>
        <button>문의하기</button>
      </div>
    </div>
  </section>

  <footer class="footer">
    <h2>함께하는 단체들</h2>
    <div class="partners">
      <img src="partner1.png" alt="partner1" />
      <img src="partner2.png" alt="partner2" />
      <img src="partner3.png" alt="partner3" />
      <img src="partner4.png" alt="partner4" />
    </div>
  </footer>

</body>
</html>
