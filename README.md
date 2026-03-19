* { margin: 0; padding: 0; box-sizing: border-box; }
    body { 
        font-family: 'Pretendard', sans-serif; 
        background-color: var(--bg-color); 
        color: var(--text-color); 
        line-height: 1.8; 
        word-break: keep-all;
    }

    section { padding: 100px 20px; max-width: 800px; margin: 0 auto; text-align: center; }

    /* Hero Section */
    .hero { height: 100vh; display: flex; flex-direction: column; justify-content: center; }
    .hero h1 { font-size: 2.5rem; margin-bottom: 20px; font-weight: 800; }
    .hero p { font-size: 1.2rem; color: var(--sub-text); }
    .scroll-down { margin-top: 50px; font-size: 0.9rem; color: var(--point-color); animation: bounce 2s infinite; }

    /* Content Sections */
    .highlight { color: var(--accent-color); font-weight: bold; }
    .point-text { color: var(--point-color); font-weight: bold; }
    .message-box { 
        background: #1e293b; 
        padding: 40px; 
        border-radius: 20px; 
        margin: 40px 0; 
        border: 1px solid #334155;
    }

    h2 { font-size: 2rem; margin-bottom: 30px; }
    p { margin-bottom: 20px; font-size: 1.1rem; }

    /* Image Placeholder Style */
    .image-mock {
        background: linear-gradient(135deg, #38bdf8, #818cf8);
        width: 100%;
        height: 250px;
        display: flex;
        align-items: center;
        justify-content: center;
        border-radius: 15px;
        margin: 40px 0;
        font-weight: bold;
        color: white;
        font-size: 1.5rem;
    }

    /* List Style */
    .list-container { text-align: left; display: inline-block; margin-top: 20px; }
    .list-item { margin-bottom: 15px; display: flex; align-items: flex-start; }
    .list-item::before { content: "✕"; color: var(--accent-color); margin-right: 15px; font-weight: bold; }
    .list-item.check::before { content: "✓"; color: var(--point-color); }

    /* CTA Button */
    .cta-button {
        display: inline-block;
        background-color: var(--point-color);
        color: var(--bg-color);
        padding: 20px 50px;
        border-radius: 50px;
        font-weight: 800;
        font-size: 1.3rem;
        text-decoration: none;
        margin-top: 40px;
        transition: transform 0.3s;
    }
    .cta-button:hover { transform: scale(1.05); }

    @keyframes bounce { 0%, 20%, 50%, 80%, 100% {transform: translateY(0);} 40% {transform: translateY(-10px);} 60% {transform: translateY(-5px);} }
</style>
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
        
        <br
