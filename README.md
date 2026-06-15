<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Phantom Reaper AI</title>

<style>
body{
    margin:0;
    font-family:Arial, sans-serif;
    background:#070707;
    color:white;
}

/* Animated background */
.hero{
    text-align:center;
    padding:110px 20px;
    background:linear-gradient(-45deg,#0a0a0a,#111,#0a0a0a,#0f0f0f);
    background-size:400% 400%;
    animation:gradient 8s ease infinite;
}

@keyframes gradient{
    0%{background-position:0% 50%}
    50%{background-position:100% 50%}
    100%{background-position:0% 50%}
}

header{
    text-align:center;
    padding:20px;
    background:#0d0d0d;
    border-bottom:1px solid #222;
}

header h1{
    color:#00ff88;
    font-size:3rem;
    letter-spacing:3px;
}

.hero h2{
    font-size:2.8rem;
}

.hero p{
    max-width:750px;
    margin:auto;
    line-height:1.6;
    opacity:0.85;
}

.btn{
    display:inline-block;
    margin-top:25px;
    padding:15px 35px;
    background:#00ff88;
    color:black;
    font-weight:bold;
    text-decoration:none;
    border-radius:10px;
    transition:0.3s;
}

.btn:hover{
    transform:scale(1.05);
    background:#00cc6a;
}

.section{
    padding:70px 20px;
    text-align:center;
}

h2{
    color:#00ff88;
    margin-bottom:25px;
}

.grid{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(260px,1fr));
    gap:20px;
    max-width:1100px;
    margin:auto;
}

.card{
    background:#121212;
    padding:22px;
    border-radius:12px;
    border:1px solid #222;
    transition:0.3s;
}

.card:hover{
    transform:translateY(-5px);
    border-color:#00ff88;
}

/* Pricing upgrade */
.price{
    font-size:2.2rem;
    color:#00ff88;
}

.badge{
    background:#00ff88;
    color:black;
    padding:5px 10px;
    border-radius:6px;
    font-size:12px;
}

/* Dashboard */
.dashboard{
    max-width:850px;
    margin:auto;
    background:#111;
    padding:25px;
    border-radius:12px;
    border:1px solid #222;
    text-align:left;
}

/* WhatsApp floating */
.whatsapp{
    position:fixed;
    bottom:20px;
    right:20px;
    background:#00ff88;
    color:black;
    padding:15px 18px;
    border-radius:50px;
    font-weight:bold;
    text-decoration:none;
    box-shadow:0 0 20px rgba(0,255,136,0.4);
}

footer{
    text-align:center;
    padding:20px;
    background:#0d0d0d;
    margin-top:40px;
    border-top:1px solid #222;
}
</style>
</head>

<body>

<header>
    <h1>PHANTOM REAPER AI</h1>
    <p>Institution-Grade Automated Forex Trading System</p>
</header>

<!-- HERO -->
<section class="hero">
    <h2>Trade Like Institutions. Not Retail Traders.</h2>
    <p>
        Phantom Reaper AI is an advanced algorithmic trading system built to analyze liquidity,
        market structure, and volatility — executing precision trades automatically with risk control.
    </p>

    <a href="https://wa.me/256748758798" class="btn">Start on WhatsApp</a>
</section>

<!-- FEATURES -->
<section class="section">
    <h2>Core Engine Features</h2>

    <div class="grid">

        <div class="card">
            <h3>Liquidity Detection</h3>
            <p>Identifies stop hunts and smart money zones.</p>
        </div>

        <div class="card">
            <h3>Smart Entries</h3>
            <p>Precision entries based on structure shifts.</p>
        </div>

        <div class="card">
            <h3>Risk Engine</h3>
            <p>Automatic drawdown control & capital protection.</p>
        </div>

    </div>
</section>

<!-- STRATEGY -->
<section class="section">
    <h2>Swing + Scalper Hybrid System</h2>

    <div class="grid">

        <div class="card">
            <h3>⚡ Scalper Mode</h3>
            <p>Fast execution trades on M1–M5 for intraday profits.</p>
        </div>

        <div class="card">
            <h3>📊 Swing Mode</h3>
            <p>H1–H4 structure-based trades for bigger moves.</p>
        </div>

        <div class="card">
            <h3>🧠 AI Switching</h3>
            <p>Automatically adapts to volatility conditions.</p>
        </div>

    </div>
</section>

<!-- DASHBOARD -->
<section class="section">
    <h2>Live System Overview</h2>

    <div class="dashboard">
        <p>📈 Win Rate: 82% – 89% (Model Backtest)</p>
        <p>💰 Avg Monthly Growth: +18% to +35%</p>
        <p>⚡ Active Market Monitoring: 24/5</p>
        <p>🔒 Risk Level: Controlled / Adaptive</p>
    </div>
</section>

<!-- PRICING -->
<section class="section">
    <h2>Pricing Plans</h2>

    <div class="grid">

        <div class="card">
            <span class="badge">Starter</span>
            <h3>Basic Access</h3>
            <p class="price">$200</p>
            <p>Core AI system + setup guide</p>
            <a class="btn" href="https://wa.me/256748758798">Buy Now</a>
        </div>

        <div class="card">
            <span class="badge">Pro</span>
            <h3>Advanced System</h3>
            <p class="price">$350</p>
            <p>Full AI engine + multi-timeframe logic</p>
            <a class="btn" href="https://wa.me/256748758798">Buy Now</a>
        </div>

        <div class="card">
            <span class="badge">Elite</span>
            <h3>Institutional Mode</h3>
            <p class="price">$500</p>
            <p>Full access + VIP support + priority updates</p>
            <a class="btn" href="https://wa.me/256748758798">Buy Now</a>
        </div>

    </div>
</section>

<!-- CONTACT -->
<section class="section">
    <h2>Need Help?</h2>
    <p>Talk directly to our team via WhatsApp for instant setup & support.</p>
    <a class="btn" href="https://wa.me/256748758798">Chat on WhatsApp</a>
</section>

<footer>
    <p>© 2026 Phantom Reaper AI. All Rights Reserved.</p>
</footer>

<!-- FLOAT BUTTON -->
<a class="whatsapp" href="https://wa.me/256748758798">
    WhatsApp
</a>

</body>
</html>
