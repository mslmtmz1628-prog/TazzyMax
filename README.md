# TazzyMax
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>TazzyMax ($TMAX) | Spin To The Max</title>

<style>
* { box-sizing: border-box; }

body {
    margin: 0;
    font-family: Arial, Helvetica, sans-serif;
    background: radial-gradient(circle at top, #200000, #000);
    color: #fff;
    text-align: center;
}

/* HEADER */
header {
    background: linear-gradient(90deg, #ff2a00, #ff7a00);
    padding: 22px;
    font-size: 2em;
    font-weight: bold;
    box-shadow: 0 0 30px rgba(255,80,0,0.8);
}

/* HERO */
.hero {
    padding: 60px 20px;
}

.hero img {
    width: 100%;
    max-width: 520px;
    border-radius: 18px;
    box-shadow: 0 0 45px rgba(255,80,0,1);
}

.hero h1 {
    margin-top: 30px;
    font-size: 2em;
}

.hero p {
    color: #ccc;
    max-width: 600px;
    margin: 15px auto;
    line-height: 1.5;
}

/* BUY BUTTON */
.buy-btn {
    display: inline-block;
    margin-top: 30px;
    padding: 18px 44px;
    background: #00ff66;
    color: #000;
    font-size: 1.3em;
    font-weight: bold;
    border-radius: 16px;
    text-decoration: none;
    box-shadow: 0 0 30px rgba(0,255,120,0.9);
    animation: pulse 1.5s infinite;
}

@keyframes pulse {
    0% { transform: scale(1); }
    50% { transform: scale(1.05); }
    100% { transform: scale(1); }
}

/* COUNTDOWN */
.countdown {
    margin-top: 25px;
    font-size: 1.1em;
    color: #ffb000;
}

/* SECTIONS */
.section {
    padding: 70px 20px;
}

.section img {
    width: 100%;
    max-width: 520px;
    border-radius: 18px;
    box-shadow: 0 0 35px rgba(0,160,255,0.7);
}

.section h2 {
    margin-top: 30px;
    color: #ff7a00;
}

/* CONTRACT */
.contract {
    margin-top: 30px;
    background: #111;
    padding: 15px;
    border-radius: 12px;
    display: inline-block;
    font-size: 0.9em;
}

.contract button {
    margin-left: 10px;
    padding: 6px 12px;
    background: #ff4500;
    border: none;
    color: #fff;
    border-radius: 6px;
    cursor: pointer;
}

/* SOCIAL BAR */
.social-bar {
    position: fixed;
    bottom: 0;
    width: 100%;
    background: #000;
    border-top: 1px solid #ff4500;
    display: flex;
    justify-content: center;
    gap: 40px;
    padding: 12px 0;
    z-index: 100;
}

.social-bar a {
    color: #fff;
    text-decoration: none;
    font-weight: bold;
}

footer {
    padding: 80px 20px 120px;
    font-size: 0.8em;
    color: #aaa;
}
</style>
</head>

<body>

<header>
    TazzyMax ($TMAX) 🌪️
</header>

<!-- HERO -->
<section class="hero">
    <img src="IMG_1_HERO" alt="TazzyMax Hero">

    <h1>STOP SPINNING YOUR WHEELS.<br>START SPINNING FOR GAINS!</h1>

    <p>
        TazzyMax is the ultimate velocity meme coin.
        Maximum Chaos. Maximum Fun. Maximum Gains.
    </p>

    <a href="#" class="buy-btn">BUY $TMAX 🚀</a>

    <div class="countdown" id="countdown">
        Launching Soon on Pump.fun
    </div>

    <div class="contract">
        Contract: <span id="contract">0xCOMINGSOON</span>
        <button onclick="copyContract()">COPY</button>
    </div>
</section>

<!-- HYPE -->
<section class="section">
    <img src="IMG_2_HYPE" alt="Spin To The Max">
    <h2>SPIN TO THE MAX</h2>
</section>

<!-- BUY -->
<section class="section">
    <img src="IMG_3_BUY" alt="Buy TMAX">
    <h2>READY FOR LAUNCH</h2>
</section>

<!-- LOGO -->
<section class="section">
    <img src="IMG_4_LOGO" alt="TazzyMax Logo" style="max-width:260px;">
    <h2>MAXIMUM FUN.<br>MAXIMUM CHAOS.<br>MAXIMUM GAINS.</h2>
</section>

<footer>
    © 2025 TazzyMax. All Rights Reserved.
</footer>

<!-- SOCIAL BAR -->
<div class="social-bar">
    <a href="https://t.me/TazzyMax" target="_blank">💬 Telegram</a>
    <a href="https://x.com/tazzymax?s=21" target="_blank">🐦 X (Twitter)</a>
</div>

<script>
function copyContract() {
    const text = document.getElementById("contract").innerText;
    navigator.clipboard.writeText(text);
    alert("Contract copied!");
}
</script>

</body>
</html>
