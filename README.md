<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>손실부터 배우십시오</title>
  <style>
    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      font-family: "Noto Sans KR", Arial, sans-serif;
      background: #0b0d10;
      color: #f3f4f6;
      line-height: 1.8;
      letter-spacing: -0.02em;
    }

    section {
      max-width: 900px;
      margin: 0 auto;
      padding: 100px 24px;
      text-align: center;
      border-bottom: 1px solid rgba(255,255,255,0.08);
    }

    .hero {
      min-height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      background:
        radial-gradient(circle at top right, rgba(168,85,247,0.12), transparent 30%),
        radial-gradient(circle at top left, rgba(239,68,68,0.10), transparent 25%),
        linear-gradient(180deg, #0a0c0f 0%, #111418 100%);
    }

    h1 {
      font-size: clamp(38px, 6vw, 72px);
      line-height: 1.2;
      margin: 16px 0 20px;
      font-weight: 800;
    }

    h2 {
      font-size: clamp(28px, 4vw, 48px);
      line-height: 1.3;
      margin-bottom: 24px;
      font-weight: 800;
    }

    p {
      font-size: 18px;
      color: #d1d5db;
      margin: 0 0 18px;
    }

    .highlight {
      color: #f87171;
      font-weight: 700;
    }

    .point-text {
      color: #c084fc;
      font-weight: 700;
    }

    .scroll-down {
      margin-top: 32px;
      font-size: 14px;
      color: #9ca3af;
      letter-spacing: 0.05em;
    }

    .message-box {
      max-width: 640px;
      margin: 28px auto;
      padding: 24px;
      border-radius: 18px;
      background: rgba(255,255,255,0.04);
      border: 1px solid rgba(255,255,255,0.08);
      color: #e5e7eb;
    }

    .image-mock {
      max-width: 640px;
      margin: 40px auto 0;
      padding: 70px 20px;
      border-radius: 24px;
      background:
        linear-gradient(180deg, rgba(255,255,255,0.04), rgba(255,255,255,0.02)),
        radial-gradient(circle at center, rgba(239,68,68,0.12), transparent 40%);
      border: 1px solid rgba(255,255,255,0.08);
      font-size: 24px;
      font-weight: 700;
      color: #fff;
    }

    .list-item {
      padding: 14px 16px;
      margin-bottom: 12px;
      border-radius: 14px;
      background: rgba(255,255,255,0.03);
      border: 1px solid rgba(255,255,255,0.07);
      color: #e5e7eb;
    }

    strong {
      color: #fff;
    }

    @media (max-width: 768px) {
      section {
        padding: 72px 20px;
      }

      p {
        font-size: 17px;
      }

      .image-mock {
        font-size: 20px;
        padding: 50px 20px;
      }
    }
  </style>
</head>
<body>

  <section class="hero">
    <p>계속 손실보는 계좌,</p>
    <h1>아직도 수익으로<br>관리하고 계십니까?</h1>
    <p>손실 관리가 이미 된다면,<br>이 페이지는 굳이 읽지 않으셔도 좋습니다.</p>
    <div class="scroll-down">천천히 내려서 확인하십시오 ↓</div>
  </section>

  <section>
    <h2>수익을 쫓을수록<br><span class="highlight">계좌는 흔들립니다.</span></h2>
    <p>시장에는 늘 이런 말이 많습니다.</p>
    <div class="message-box">
      "이 자리만 알면 됩니다"<br>
      "이 지표면 충분합니다"<br>
      "이 기법으로 수익을 냅니다"
    </div>
    <p>왜 여전히 많은 사람들의 계좌는 무너질까요?</p>
    <p>답은 단순합니다.<br>대부분이 처음부터 <span class="highlight">수익을 목표</span>로 매매하기 때문입니다.</p>
  </section>

  <section>
    <p>수익을 목표로 하면 기대가 생기고,<br>기대가 생기면 판단은 흐려집니다.</p>
    <h2>기법이 아니라 <span class="point-text">기준</span>을 바꿔야 합니다.</h2>
    <p>이익을 기대하지 않고<br><strong>손실을 먼저 정하는 사고</strong></p>
    
    <div class="image-mock">
      손실이 먼저 정해지면<br>매매는 단순해집니다
    </div>
  </section>

  <section>
    <h2>핵심은 두 가지입니다.</h2>
    <div class="message-box">
      <p>1. <strong>차선이론</strong></p>
      <p>2. <strong>손실확정구간을 정하는 방법</strong></p>
    </div>
    <p>이건 타점을 찍어주는 방식이 아닙니다.<br>스스로 기준을 세우고, 그 안에서 움직이기 위한 도구입니다.</p>
  </section>

  <section>
    <h2>먼저 버릴 자리를 정하십시오</h2>
    <div style="text-align: left; max-width: 500px; margin: 0 auto;">
      <p class="point-text">이런 분은 보지 마세요</p>
      <div class="list-item">종목과 타점을 찍어주길 원하는 분</div>
      <div class="list-item">한 번의 큰 수익을 먼저 기대하는 분</div>
      <div class="list-item">자기 기준보다 남의 확신이 편한 분</div>

      <br>

      <p class="point-text">이런 분께 맞을 수 있습니다</p>
      <div class="list-item">손실을 줄이는 기준을 만들고 싶은 분</div>
      <div class="list-item">감정이 아닌 구조로 매매하고 싶은 분</div>
      <div class="list-item">복잡함보다 명확한 판단 기준을 원하는 분</div>
      <div class="list-item">시장에서 오래 남는 방식을 찾는 분</div>
    </div>
  </section>

  <section>
    <h2>손실부터 배우십시오</h2>
    <p>수익을 먼저 배우는 사람은 많습니다.<br>손실부터 배우는 사람은 많지 않습니다.</p>
    <p>그래서 결과도 갈립니다.</p>
  </section>

</body>
</html>
