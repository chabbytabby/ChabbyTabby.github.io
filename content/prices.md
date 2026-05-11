---
title: "PRICES"
url: "/prices"
---
<style>
    /* --- PORTFOLIO & PRODUCTS STYLES --- */
    .portfolio-wrapper {
        color: #e0e0e0;
    }

    /* Intro Box */
    .intro-banner {
        background: #000;
        border: 2px dashed var(--hot-pink);
        border-radius: 12px;
        padding: 20px;
        text-align: center;
        margin-bottom: 35px;
        box-shadow: inset 0 0 15px rgba(255, 0, 255, 0.1);
    }
    
    .intro-banner h2 {
        color: #00ffcc;
        margin-top: 0;
        text-shadow: 2px 2px 0 #000;
        font-size: 1.4rem;
    }

    .section-header {
        color: var(--neon-yellow);
        font-size: 1.8rem;
        font-weight: 900;
        text-align: center;
        text-transform: uppercase;
        letter-spacing: 2px;
        text-shadow: 3px 3px 0 #000;
        border-bottom: 3px solid var(--hot-pink);
        padding-bottom: 10px;
        margin-bottom: 25px;
    }

    /* --- MAIN TIER CARDS --- */
    .tier-grid {
        display: grid;
        grid-template-columns: repeat(3, 1fr);
        gap: 20px;
        margin-bottom: 40px;
    }

    .tier-card {
        background: #111;
        border: 2px solid var(--hot-pink);
        border-radius: 12px;
        padding: 15px;
        transition: transform 0.2s ease, box-shadow 0.2s ease;
        display: flex;
        flex-direction: column;
    }

    .tier-card:hover {
        transform: translateY(-5px);
        box-shadow: 0 8px 20px rgba(255, 0, 255, 0.3);
    }

    .tier-card img {
        width: 100%;
        height: 200px;
        object-fit: cover;
        border-radius: 8px;
        border: 2px solid #333;
        margin-bottom: 15px;
    }

    .tier-title {
        color: #fff;
        font-size: 1.3rem;
        font-weight: bold;
        text-align: center;
        margin: 0 0 5px 0;
        text-transform: uppercase;
    }

    .tier-price {
        color: var(--neon-yellow);
        font-size: 1.4rem;
        font-weight: 900;
        text-align: center;
        margin-bottom: 15px;
        text-shadow: 1px 1px 0 #000;
    }

    .tier-desc {
        font-size: 0.9rem;
        text-align: center;
        margin-bottom: 15px;
        color: #ccc;
    }

    .tier-details {
        background: #000;
        border: 1px solid #333;
        border-radius: 6px;
        padding: 10px;
        font-size: 0.85rem;
        margin-top: auto; /* Pushes details to the bottom to align cards */
    }

    .tier-details div {
        margin-bottom: 5px;
        border-bottom: 1px dashed #222;
        padding-bottom: 4px;
    }
    .tier-details div:last-child { border-bottom: none; margin-bottom: 0; padding-bottom: 0; }
    .detail-label { color: var(--hot-pink); font-weight: bold; }

    /* --- MISC ITEMS GRID --- */
    .misc-grid {
        display: grid;
        grid-template-columns: repeat(2, 1fr);
        gap: 15px;
    }

    .misc-item {
        background: #000;
        border: 1px dashed #00ffcc;
        border-radius: 8px;
        padding: 15px;
        position: relative;
        transition: all 0.2s;
    }
    
    .misc-item:hover {
        border-style: solid;
        box-shadow: inset 0 0 10px rgba(0, 255, 204, 0.2);
    }

    .misc-header {
        display: flex;
        justify-content: space-between;
        align-items: center;
        margin-bottom: 8px;
        border-bottom: 1px solid #222;
        padding-bottom: 8px;
    }

    .misc-title { color: #00ffcc; font-weight: bold; font-size: 1.1rem; text-transform: uppercase; }
    .misc-price { color: var(--neon-yellow); font-weight: bold; font-size: 1.1rem; }
    .misc-desc { font-size: 0.85rem; color: #aaa; line-height: 1.4; }

    /* Mobile Adjustments */
    @media (max-width: 900px) {
        .tier-grid { grid-template-columns: 1fr; }
        .misc-grid { grid-template-columns: 1fr; }
    }
</style>
<div class="portfolio-wrapper">
    <div class="intro-banner">
        <h2>Hi there ! I see you are interested in my commissions ヾ(•ω•`)o</h2>
        <p>I do ask of you to read over my <a href="/tos" style="color: var(--hot-pink);">ToS</a> before commissioning me.</p>
        <p style="font-size: 0.9rem; color: #aaa;">If you want something else that isn't listed here, please give me a DM! I will be more than happy to give you a quote and see if I am capable of doing it.</p>
    </div>
    <h1 class="section-header">⭐ MAIN COMMISSIONS ⭐</h1>
    <div class="tier-grid">
        <div class="tier-card">
            <img src="/images/Image01.jpg" alt="Icon Example">
            <h3 class="tier-title">Icon</h3>
            <div class="tier-price">$30</div>
            <div class="tier-desc">A head shot of your character</div>
            <div class="tier-details">
                <div><span class="detail-label">Add. Character:</span> +$15</div>
                <div><span class="detail-label">Complexity:</span> +$5</div>
                <div><span class="detail-label">ETA:</span> ~ 3-7 days</div>
            </div>
        </div>
        <div class="tier-card">
            <img src="/images/Image04.jpg" alt="Half Body Example">
            <h3 class="tier-title">Half-Body / Nomnoms</h3>
            <div class="tier-price">$70</div>
            <div class="tier-desc">Thigh / Bust Shot</div>
            <div class="tier-details">
                <div><span class="detail-label">Add. Character:</span> +$25</div>
                <div><span class="detail-label">Complexity:</span> +$10</div>
                <div><span class="detail-label">ETA:</span> ~ 1-2 weeks</div>
            </div>
        </div>
        <div class="tier-card">
            <img src="/images/Image07.jpg" alt="Full Body Example">
            <h3 class="tier-title">Full-Body Illustration</h3>
            <div class="tier-price">$150 <span style="font-size: 0.8rem; color: #fff;">(or $90 Just Fullbody)</span></div>
            <div class="tier-desc">Includes full background with one character</div>
            <div class="tier-details">
                <div><span class="detail-label">Add. Character:</span> +$50</div>
                <div><span class="detail-label">Complexity:</span> +$10</div>
                <div><span class="detail-label">ETA:</span> ~ 2-4 weeks</div>
            </div>
        </div>
    </div>
    <h1 class="section-header">✨ MISC PRICE LIST ✨</h1>
    <p style="text-align: center; color: #aaa; margin-top: -15px; margin-bottom: 25px;">Category of tiny things I can offer. Please message me if you'd like to see examples!</p>
    <div class="misc-grid">
        <div class="misc-item">
            <div class="misc-header">
                <span class="misc-title">Beans</span>
                <span class="misc-price">$10</span>
            </div>
            <div class="misc-desc">A even tinier version of your character, details are bean-ified on a small blank canvas.</div>
        </div>
        <div class="misc-item">
            <div class="misc-header">
                <span class="misc-title">Emotes</span>
                <span class="misc-price">$5 / $20</span>
            </div>
            <div class="misc-desc">Per emote is $5, but a bundle of 5 will cost $20.</div>
        </div>
        <div class="misc-item">
            <div class="misc-header">
                <span class="misc-title">Flat Colored Sketches</span>
                <span class="misc-price">$25</span>
            </div>
            <div class="misc-desc">A full-body sketch of your character, any additional characters will cost the same price.</div>
        </div>
        <div class="misc-item">
            <div class="misc-header">
                <span class="misc-title">Sketch Pages</span>
                <span class="misc-price">$60</span>
            </div>
            <div class="misc-desc">A flat colored sketch page on a blank background.</div>
        </div>
        <div class="misc-item">
            <div class="misc-header">
                <span class="misc-title">Chibi Illustration</span>
                <span class="misc-price">$90 / $50</span>
            </div>
            <div class="misc-desc">$90 for full background. A bean character instead of chibi will cost less: $50 (details on background may be less detailed).</div>
        </div>
        <div class="misc-item">
            <div class="misc-header">
                <span class="misc-title">Reference Sheets</span>
                <span class="misc-price">$80+</span>
            </div>
            <div class="misc-desc">Starting price is 80, includes full-body front-view, half body back-view, and one expression head-shot. Quote based on request type.</div>
        </div>
    </div>
</div>