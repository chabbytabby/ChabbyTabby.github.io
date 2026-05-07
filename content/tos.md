---
title: "tos"
date: 2026-05-02
---
<style>
    /* --- PRICES & TOS PAGE STYLES --- */
    .tos-container {
        background: #111;
        border: 2px solid var(--hot-pink);
        border-radius: var(--inner-radius);
        padding: 25px;
        margin-bottom: 30px;
        box-shadow: 0 10px 30px rgba(255, 0, 255, 0.15);
    }

    .tos-header {
        color: var(--neon-yellow);
        font-size: 1.6rem;
        font-weight: 900;
        margin-top: 0;
        margin-bottom: 20px;
        border-bottom: 2px dashed var(--hot-pink);
        padding-bottom: 15px;
        text-transform: uppercase;
        text-shadow: 2px 2px 0px #000;
    }

    .tos-section-title {
        color: var(--hot-pink);
        font-size: 1.1rem;
        font-weight: bold;
        margin-top: 25px;
        margin-bottom: 12px;
        background: #222;
        display: inline-block;
        padding: 4px 12px;
        border-radius: 4px;
        border: 1px solid #333;
    }

    .tos-list {
        list-style: none;
        padding-left: 0;
        color: #e0e0e0;
        font-size: 0.9rem;
        line-height: 1.6;
    }

    .tos-list li {
        margin-bottom: 12px;
        position: relative;
        padding-left: 24px;
    }

    .tos-list li::before {
        content: "▸"; /* Retro arrow */
        color: var(--neon-yellow);
        position: absolute;
        left: 0;
        font-weight: bold;
        font-size: 1.1rem;
    }

    .hl-yellow { color: var(--neon-yellow); font-weight: bold; }
    .hl-red { color: #ff3366; font-weight: bold; text-decoration: underline; }
    .hl-pink { color: var(--hot-pink); font-weight: bold; }

    /* --- WILL / WON'T DRAW GRID --- */
    .draw-grid {
        display: grid;
        grid-template-columns: 1fr 1fr;
        gap: 20px;
        margin-top: 10px;
    }

    .draw-box {
        background: #000;
        border: 2px dashed #333;
        border-radius: 12px;
        padding: 20px;
        transition: all 0.2s ease;
    }

    .draw-box.will { border-color: #00ffcc; box-shadow: inset 0 0 15px rgba(0, 255, 204, 0.1); }
    .draw-box.wont { border-color: #ff3366; box-shadow: inset 0 0 15px rgba(255, 51, 102, 0.1); }

    .draw-box:hover { transform: translateY(-3px); }

    .draw-title {
        font-size: 1.2rem;
        font-weight: 900;
        margin-top: 0;
        margin-bottom: 15px;
        text-align: center;
        text-transform: uppercase;
        letter-spacing: 1px;
    }

    .will .draw-title { color: #00ffcc; text-shadow: 2px 2px 0px #000; }
    .wont .draw-title { color: #ff3366; text-shadow: 2px 2px 0px #000; }

    .draw-list {
        list-style: none;
        padding: 0;
        margin: 0;
        color: #ccc;
        font-size: 0.95rem;
        text-align: center;
        line-height: 1.8;
    }

    /* Mobile adjustments */
    @media (max-width: 768px) {
        .draw-grid { grid-template-columns: 1fr; }
    }
</style>

<div class="tos-container">
    <h1 class="tos-header">📋 TERMS OF SERVICE</h1>
    <p style="color: #aaa; font-size: 0.85rem; font-style: italic; margin-top: -10px; margin-bottom: 20px;">Please read this thoroughly before commissioning!</p>
    <div class="tos-section-title">Before Ordering</div>
    <ul class="tos-list">
        <li><span class="hl-pink">Know what you want!</span> I don't mind giving my opinion, but please have an idea ahead of time (unless you are giving me full artistic liberty).</li>
        <li><span class="hl-pink">Save your future ideas!</span> I appreciate your enthusiasm, but too much info about future commissions might make me forget important details for your current one! ;v;</li>
        <li>I will usually make multiple sketches before proceeding with coloring and will ask if you'd like alterations.</li>
        <li>Have a <span class="hl-yellow">CLEAR updated reference</span> prepared. If you don't have one, please provide a listed description, moodboard, or collage! Doodles and sketches help me immensely!</li>
    </ul>
    <div class="tos-section-title">Rules & Rights</div>
    <ul class="tos-list">
        <li>Do <span class="hl-red">NOT</span> resell or redistribute the image to third-parties.</li>
        <li>Do <span class="hl-red">NOT</span> edit or alter my artwork without permission (filters are OK).</li>
        <li><span class="hl-red">DO NOT TRACE MY ARTWORK.</span> It is strictly for your PERSONAL USE!</li>
        <li>I reserve the rights over the final artwork (including posting it online to my social media).</li>
        <li><span class="hl-red">DO NOT RUN MY ART THROUGH AI</span> or you will be permanently blacklisted.</li>
        <li>Please do not try to bargain. My prices are set and I will not be lowering them.</li>
        <li><em>Psst... Please send me a pumpkin emoji 🎃 for a discount! (This proves you read my ToS ^_^)</em></li>
    </ul>
    <div class="tos-section-title">Edits & Credit</div>
    <ul class="tos-list">
        <li>Any changes during the sketch phase are OK! However, multiple changes <span class="hl-pink">after flat colors</span> will lead to an additional fee (+ $10).</li>
        <li>If you prefer I do not post the art to my socials, there is an privacy fee of $5.</li>
        <li>Please <span class="hl-yellow">CREDIT ME</span> or ask if you are going to repost the art somewhere else.</li>
    </ul>
    <div class="tos-section-title">Payment & Refunds</div>
    <ul class="tos-list">
        <li><span class="hl-yellow">PayPal or Ko-fi Only.</span></li>
        <li><span class="hl-pink">Upfront payment required!</span> I do not begin until payment is received.</li>
        <li>If you would like a refund before I begin or within the sketching phase, I will give a full refund.</li>
        <li>I do <span class="hl-red">not</span> offer full refunds for finished works. (If there are long wait times, I will make an exception and issue a partial refund).</li>
        <li>There may be times I fully refund you if I am unable to work on your commission (usually due to mental health reasons, as I would hate to keep you waiting).</li>
    </ul>
    <div class="tos-section-title">Estimated Time</div>
    <ul class="tos-list">
        <li>Depending on the commission type, it should take <span class="hl-yellow">3 days to 1 month</span> to complete after I have started the sketch.</li>
        <li>I will give you an estimated timeframe on when it should be completed!</li>
        <li>Large commissions may take longer (Ref sheets, backgrounds, multiple characters).</li>
        <li>I will try my absolute best to keep you updated via Trello. Feel free to DM me if you'd like to see progress!</li>
    </ul>
    <p style="text-align: center; color: var(--hot-pink); font-weight: bold; margin-top: 25px;">Any other concerns, please contact me! Thank you!</p>
</div>

<div class="draw-grid">
    <div class="draw-box will">
        <h2 class="draw-title">✔️ WILL DRAW</h2>
        <ul class="draw-list">
            <li>Furry / Anthro</li>
            <li>Humans / Nekomimi</li>
            <li>Feral (STRICTLY SFW)</li>
            <li>Mecha (Partial)</li>
            <li>NSFW Pinups <span style="color: #fff; font-size: 0.8rem;">(Please Ask!)</span></li>
        </ul>
    </div>
    <div class="draw-box wont">
        <h2 class="draw-title">❌ WILL NOT DRAW</h2>
        <ul class="draw-list">
            <li>Fetish Content</li>
            <li>Vent Art</li>
            <li>Incest</li>
            <li>Loli / Shota / Babyfur</li>
            <li><span style="color: #fff; font-size: 0.8rem; font-style: italic; display: block; margin-top: 10px;">Please ask before commissioning if not listed here. I will typically make my views clear if it makes me uncomfortable.</span></li>
        </ul>
    </div>
</div>
