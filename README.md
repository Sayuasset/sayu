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
