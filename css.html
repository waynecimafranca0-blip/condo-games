<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Condo Games</title>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, Helvetica, sans-serif;
    min-height: 100vh;
    color: white;
    background:
        radial-gradient(circle at 20% 20%, #382080 0%, transparent 35%),
        radial-gradient(circle at 80% 80%, #0066ff 0%, transparent 30%),
        #050510;
    overflow-x: hidden;
}

/* Animated grid */
body::before {
    content: "";
    position: fixed;
    inset: 0;
    background-image:
        linear-gradient(rgba(255,255,255,.025) 1px, transparent 1px),
        linear-gradient(90deg, rgba(255,255,255,.025) 1px, transparent 1px);
    background-size: 45px 45px;
    animation: gridMove 15s linear infinite;
    pointer-events: none;
}

@keyframes gridMove {
    from {
        transform: translateY(0);
    }

    to {
        transform: translateY(45px);
    }
}

/* Floating particles */
.particle {
    position: fixed;
    width: 4px;
    height: 4px;
    background: white;
    border-radius: 50%;
    opacity: .35;
    animation: float 8s infinite ease-in-out;
    pointer-events: none;
}

.p1 {
    left: 10%;
    top: 80%;
}

.p2 {
    left: 25%;
    top: 20%;
    animation-delay: 2s;
}

.p3 {
    left: 70%;
    top: 70%;
    animation-delay: 1s;
}

.p4 {
    left: 85%;
    top: 25%;
    animation-delay: 3s;
}

.p5 {
    left: 50%;
    top: 90%;
    animation-delay: 4s;
}

@keyframes float {
    0%,100% {
        transform: translateY(0) scale(1);
        opacity: .2;
    }

    50% {
        transform: translateY(-80px) scale(1.8);
        opacity: .8;
    }
}

/* Header */
header {
    position: relative;
    z-index: 2;
    text-align: center;
    padding: 70px 20px 35px;
}

.logo {
    display: inline-block;
    font-size: 15px;
    letter-spacing: 5px;
    color: #9fa8ff;
    margin-bottom: 15px;
    text-transform: uppercase;
}

h1 {
    font-size: clamp(40px, 8vw, 76px);
    font-weight: 900;
    letter-spacing: -3px;

    background:
        linear-gradient(
            90deg,
            #ffffff,
            #9f8cff,
            #55bfff,
            #ffffff
        );

    background-size: 300%;

    -webkit-background-clip: text;
    color: transparent;

    animation: gradientText 5s linear infinite;
}

@keyframes gradientText {
    0% {
        background-position: 0%;
    }

    100% {
        background-position: 300%;
    }
}

.subtitle {
    color: #a9aac0;
    margin-top: 15px;
    font-size: 16px;
}

/* Game grid */
.games {
    position: relative;
    z-index: 2;

    max-width: 1200px;
    margin: 40px auto 80px;

    padding: 0 25px;

    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 25px;
}

/* Game card */
.game-card {
    position: relative;

    min-height: 430px;

    border-radius: 25px;

    overflow: hidden;

    background: rgba(255,255,255,.06);

    border: 1px solid rgba(255,255,255,.12);

    backdrop-filter: blur(15px);

    transition:
        .5s cubic-bezier(.2,.8,.2,1);

    box-shadow:
        0 20px 50px rgba(0,0,0,.3);
}

.game-card:hover {
    transform:
        translateY(-15px)
        scale(1.02);

    border-color:
        rgba(140,130,255,.7);

    box-shadow:
        0 25px 70px rgba(76,55,255,.25),
        0 0 30px rgba(100,100,255,.12);
}

/* Game image */
.game-image {
    height: 220px;

    position: relative;

    overflow: hidden;
}

.game-image::after {
    content: "";

    position: absolute;

    inset: 0;

    background:
        linear-gradient(
            transparent 30%,
            rgba(5,5,16,.95) 100%
        );
}

.game1 {
    background:
        linear-gradient(
            135deg,
            #5225ff,
            #0c9dff
        );
}

.game2 {
    background:
        linear-gradient(
            135deg,
            #ff245e,
            #7b20ff
        );
}

.game3 {
    background:
        linear-gradient(
            135deg,
            #00b894,
            #0066ff
        );
}

/* Number placeholder */
.placeholder {
    height: 100%;

    display: flex;

    align-items: center;
    justify-content: center;

    font-size: 70px;
    font-weight: 900;

    opacity: .2;
}

/* Card content */
.content {
    padding: 5px 25px 25px;

    position: relative;

    z-index: 2;

    margin-top: -5px;
}

.tag {
    display: inline-block;

    font-size: 11px;

    color: #c7c4ff;

    background:
        rgba(110,90,255,.18);

    border:
        1px solid rgba(130,120,255,.25);

    padding: 6px 10px;

    border-radius: 20px;

    margin-bottom: 12px;
}

h2 {
    font-size: 25px;

    margin-bottom: 8px;
}

.description {
    color: #a7a7b8;

    font-size: 14px;

    line-height: 1.5;

    min-height: 43px;
}

/* Play button */
.play-btn {
    width: 100%;

    border: none;

    margin-top: 20px;

    padding: 14px;

    border-radius: 13px;

    color: white;

    font-weight: bold;

    font-size: 15px;

    cursor: pointer;

    background:
        linear-gradient(
            90deg,
            #6547ff,
            #268cff
        );

    box-shadow:
        0 8px 25px rgba(70,80,255,.25);

    transition: .3s;
}

.play-btn:hover {
    transform: translateY(-2px);

    box-shadow:
        0 12px 35px rgba(70,80,255,.45);
}

.play-btn:active {
    transform: scale(.97);
}

/* Footer */
footer {
    position: relative;

    z-index: 2;

    text-align: center;

    padding: 25px;

    color: #66677b;

    font-size: 13px;
}

/* Loading screen */
#loadingScreen {
    position: fixed;

    inset: 0;

    z-index: 9999;

    display: none;

    align-items: center;
    justify-content: center;

    flex-direction: column;

    background:
        radial-gradient(
            circle at center,
            #17134c,
            #03030b 65%
        );
}

/* Loading title */
.loader-logo {
    font-size: 38px;

    font-weight: 900;

    margin-bottom: 30px;

    background:
        linear-gradient(
            90deg,
            #ffffff,
            #8c7cff,
            #42aaff
        );

    -webkit-background-clip: text;

    color: transparent;

    animation: pulse 1.5s infinite;
}

@keyframes pulse {
    0%,100% {
        transform: scale(1);

        opacity: .7;
    }

    50% {
        transform: scale(1.08);

        opacity: 1;
    }
}

/* Loading circle */
.loader-ring {
    width: 65px;

    height: 65px;

    border:
        4px solid
        rgba(255,255,255,.1);

    border-top-color: #7d6cff;

    border-right-color: #31a5ff;

    border-radius: 50%;

    animation:
        spin 1s linear infinite;
}

@keyframes spin {
    to {
        transform: rotate(360deg);
    }
}

/* Loading text */
.loading-text {
    margin-top: 25px;

    color: #aaaabd;

    font-size: 14px;
}

/* Progress bar */
.progress {
    width: 240px;

    height: 5px;

    margin-top: 15px;

    background:
        rgba(255,255,255,.1);

    border-radius: 20px;

    overflow: hidden;
}

.progress-bar {
    width: 0%;

    height: 100%;

    background:
        linear-gradient(
            90deg,
            #765cff,
            #35a8ff
        );

    animation:
        progress 2.5s linear forwards;
}

@keyframes progress {
    to {
        width: 100%;
    }
}

/* Mobile */
@media (max-width: 900px) {

    .games {
        grid-template-columns: 1fr;

        max-width: 550px;
    }

    .game-card {
        min-height: 410px;
    }
}

@media (max-width: 500px) {

    header {
        padding-top: 50px;
    }

    h1 {
        font-size: 42px;
    }

    .games {
        padding: 0 15px;
    }
}
</style>
</head>

<body>

<!-- Floating particles -->
<div class="particle p1"></div>
<div class="particle p2"></div>
<div class="particle p3"></div>
<div class="particle p4"></div>
<div class="particle p5"></div>


<!-- Loading Screen -->
<div id="loadingScreen">

    <div class="loader-logo">
        CONDO GAMES
    </div>

    <div class="loader-ring"></div>

    <div
        class="loading-text"
        id="loadingText">

        Loading game...

    </div>

    <div class="progress">

        <div class="progress-bar"></div>

    </div>

</div>


<!-- Main Header -->
<header>

    <div class="logo">
        WELCOME TO
    </div>

    <h1>
        CONDO GAMES
    </h1>

    <p class="subtitle">
        Choose a game and start playing.
    </p>

</header>


<!-- Games -->
<main class="games">


    <!-- GAME 1 -->

    <div class="game-card">

        <div class="game-image game1">

            <div class="placeholder">
                01
            </div>

        </div>

        <div class="content">

            <span class="tag">
                GAME 01
            </span>

            <h2>
                ETFB But You An Hacker
            </h2>

            <p class="description">
                Jump into ETFB as a hacker and take over the game.
            </p>

            <button
                class="play-btn"
                onclick="
                    launchGame(
                        'ETFB But You An Hacker',
                        'https://roblox.com.bz/games/111744299662364/ETFB-But-You-An-Hacker?privateServerLinkCode=38924127377513873488199247090150'
                    )
                ">

                ▶ PLAY GAME

            </button>

        </div>

    </div>


    <!-- GAME 2 -->

    <div class="game-card">

        <div class="game-image game2">

            <div class="placeholder">
                02
            </div>

        </div>

        <div class="content">

            <span class="tag">
                GAME 02
            </span>

            <h2>
                X5 New Word The Best Game
            </h2>

            <p class="description">
                Experience the new word edition of X5 — the best game around.
            </p>

            <button
                class="play-btn"
                onclick="
                    launchGame(
                        'X5 New Word The Best Game',
                        'https://roblox.com.bz/games/102919673732823/X5-New-word-The-Best-Game?privateServerLinkCode=38924127377513873488199247090150'
                    )
                ">

                ▶ PLAY GAME

            </button>

        </div>

    </div>


    <!-- GAME 3 -->

    <div class="game-card">

        <div class="game-image game3">

            <div class="placeholder">
                03
            </div>

        </div>

        <div class="content">

            <span class="tag">
                GAME 03
            </span>

            <h2>
                Kick a Baddie
            </h2>

            <p class="description">
                Time to kick some baddies — jump in and play now.
            </p>

            <button
                class="play-btn"
                onclick="
                    launchGame(
                        'Kick a Baddie',
                        'https://roblox.com.bz/games/114055952820658/Kick-a-Baddie?privateServerLinkCode=38924127377513873488199247090150'
                    )
                ">

                ▶ PLAY GAME

            </button>

        </div>

    </div>

</main>


<footer>
    © 2026 Condo Games • Select a game to continue
</footer>


<script>

function launchGame(gameName, gameLink) {

    const loading =
        document.getElementById(
            "loadingScreen"
        );

    const loadingText =
        document.getElementById(
            "loadingText"
        );

    loadingText.textContent =
        "Loading " + gameName + "...";

    loading.style.display =
        "flex";


    /*
        Wait 2.5 seconds before
        opening the selected game.
    */

    setTimeout(function() {

        if (
            gameLink.startsWith("http")
        ) {

            window.location.href =
                gameLink;

        } else {

            alert(
                "Game link hasn't been added yet!"
            );

            loading.style.display =
                "none";
        }

    }, 2500);

}

</script>

</body>
</html>
