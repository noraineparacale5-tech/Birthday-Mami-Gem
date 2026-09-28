<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Happy Birthday Mami ko Sexy 💖</title>

<style>

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

html{
    scroll-behavior:smooth;
}

body{
    min-height:100vh;
    overflow-x:hidden;
    font-family:Arial,sans-serif;
    background:
        radial-gradient(circle at 50% 35%,#253d75 0%,#111936 35%,#190b2b 70%,#05030b 100%);
    color:white;
}

/* BACKGROUND */

.glow{
    position:fixed;
    width:350px;
    height:350px;
    border-radius:50%;
    background:#31d8ff;
    filter:blur(120px);
    opacity:.22;
    top:50%;
    left:50%;
    transform:translate(-50%,-50%);
    pointer-events:none;
}

/* STARS */

.star{
    position:fixed;
    color:white;
    animation:twinkle 1.8s infinite alternate;
    z-index:1;
}

@keyframes twinkle{

    from{
        opacity:.2;
        transform:scale(.6);
    }

    to{
        opacity:1;
        transform:scale(1.4);
    }

}

/* BALLOONS */

.balloon{
    position:fixed;
    font-size:55px;
    z-index:2;
    animation:balloonFloat 5s ease-in-out infinite;
}

.b1{
    left:3%;
    top:8%;
}

.b2{
    right:3%;
    top:10%;
    animation-delay:1s;
}

.b3{
    left:5%;
    bottom:10%;
    animation-delay:2s;
}

.b4{
    right:5%;
    bottom:12%;
    animation-delay:1.5s;
}

@keyframes balloonFloat{

    0%,100%{
        transform:translateY(0) rotate(-4deg);
    }

    50%{
        transform:translateY(-18px) rotate(4deg);
    }

}

/* MAIN */

.container{
    position:relative;
    z-index:5;
    min-height:100vh;
    display:flex;
    justify-content:center;
    align-items:center;
    padding:20px;
}

.card{
    width:100%;
    max-width:450px;
    padding:38px 25px;
    text-align:center;

    background:rgba(255,255,255,.10);

    border:1px solid rgba(255,255,255,.25);

    border-radius:30px;

    backdrop-filter:blur(15px);

    box-shadow:
        0 0 30px rgba(0,200,255,.25),
        0 0 70px rgba(200,60,255,.15);

    animation:appear 1.2s ease;
}

@keyframes appear{

    from{
        opacity:0;
        transform:scale(.75);
    }

    to{
        opacity:1;
        transform:scale(1);
    }

}

/* CAKE */

.cake{
    font-size:65px;

    animation:cakeGlow 1.5s infinite alternate;
}

@keyframes cakeGlow{

    from{
        filter:drop-shadow(0 0 2px gold);
    }

    to{
        filter:drop-shadow(0 0 20px gold);
    }

}

.small{
    margin-top:12px;
    font-size:12px;
    letter-spacing:3px;
    color:#9deaff;
    text-transform:uppercase;
}

h1{
    margin-top:12px;
    font-size:40px;

    background:linear-gradient(
        90deg,
        #fff,
        #72e8ff,
        #ff7eea,
        #ffe66d,
        #fff
    );

    background-size:300%;

    -webkit-background-clip:text;
    color:transparent;

    animation:shine 4s linear infinite;
}

@keyframes shine{

    from{
        background-position:0%;
    }

    to{
        background-position:300%;
    }

}

h2{
    margin-top:10px;
    font-size:23px;
    color:#ffe6fa;
}

.line{
    width:80px;
    height:2px;
    margin:20px auto;

    background:#62e9ff;

    box-shadow:0 0 15px #62e9ff;
}

.message{
    font-size:15px;
    line-height:1.8;
    color:#f5f5f5;
}

/* MAIN BUTTON */

button{
    font-family:Arial,sans-serif;
}

.mainButton{
    margin-top:25px;

    padding:15px 27px;

    border:none;
    border-radius:30px;

    background:
        linear-gradient(
            135deg,
            #008cff,
            #b83cff,
            #ff4fca
        );

    color:white;

    font-size:14px;
    font-weight:bold;

    box-shadow:
        0 0 15px rgba(0,200,255,.6),
        0 0 30px rgba(255,70,220,.3);

    cursor:pointer;

    transition:.2s;
}

.mainButton:active{
    transform:scale(.94);
}

/* BIGGEST SURPRISE */

#birthdayGame{

    display:none;

    position:fixed;

    inset:0;

    z-index:999;

    overflow-y:auto;

    padding:25px 15px;

    background:
        radial-gradient(
            circle at center,
            #43256b,
            #16112c 50%,
            #05030b
        );
}

.gameBox{

    width:100%;
    max-width:500px;

    margin:30px auto;

    padding:30px 20px;

    text-align:center;

    background:rgba(255,255,255,.09);

    border:1px solid rgba(255,255,255,.2);

    border-radius:30px;

    backdrop-filter:blur(15px);

    box-shadow:
        0 0 40px rgba(170,70,255,.25);
}

.gameProgress{

    font-size:12px;

    letter-spacing:3px;

    color:#bfefff;

    margin-bottom:25px;
}

.gameLevel{
    display:none;
}

#game1{
    display:block;
}

.gameLevel h2{

    font-size:28px;

    margin-bottom:12px;

    color:white;
}

.gameLevel p{

    line-height:1.7;

    color:#eee;
}

/* STAR GAME */

.starGame{

    position:relative;

    height:250px;

    margin:20px 0;

    border-radius:20px;

    background:rgba(0,0,0,.2);

    border:1px solid rgba(255,255,255,.08);
}

.gameStar{

    position:absolute;

    width:50px;
    height:50px;

    border:none;

    background:transparent;

    color:#ffe66d;

    font-size:35px;

    cursor:pointer;

    filter:
        drop-shadow(0 0 8px #ffe66d);

    transition:.2s;
}

.gameStar:active{
    transform:scale(.8);
}

.gameStar:nth-child(1){

    top:15px;
    left:15%;
}

.gameStar:nth-child(2){

    top:80px;
    right:15%;
}

.gameStar:nth-child(3){

    bottom:20px;
    left:30%;
}

.gameStar:nth-child(4){

    top:145px;
    left:8%;
}

.gameStar:nth-child(5){

    bottom:25px;
    right:18%;
}

.gameStar.found{

    opacity:.12;

    pointer-events:none;

    transform:scale(.5);
}

/* CHOICES */

.giftChoices,
.answerChoices{

    display:flex;

    gap:12px;

    justify-content:center;

    flex-wrap:wrap;

    margin-top:25px;
}

.giftChoices button,
.answerChoices button{

    min-width:110px;

    padding:15px 18px;

    border:1px solid rgba(255,255,255,.25);

    border-radius:15px;

    background:rgba(255,255,255,.1);

    color:white;

    font-weight:bold;

    cursor:pointer;

    transition:.2s;
}

.giftChoices button:active,
.answerChoices button:active{

    transform:scale(.94);

}

#giftResult,
#answerResult,
#starResult{

    margin-top:20px;

    min-height:28px;

    color:#ffeaa0;

}

/* FINAL MESSAGE */

#finalMessage{

    display:none;

    animation:finalReveal 1.2s ease;

}

.unlockText{

    color:#ffe66d;

    font-size:12px;

    letter-spacing:3px;

    margin-bottom:20px;

}

#finalMessage h1{

    font-size:38px;

    margin:10px 0;

    background:linear-gradient(
        90deg,
        #fff,
        #ffe66d,
        #ff82df,
        #fff
    );

    background-size:300%;

    -webkit-background-clip:text;

    color:transparent;

    animation:finalShine 3s linear infinite;

}

.finalLine{

    width:90px;

    height:2px;

    margin:20px auto;

    background:#ffe66d;

    box-shadow:0 0 15px #ffe66d;

}

.personalMessage{

    margin-top:25px;

    padding:22px;

    border-radius:20px;

    background:rgba(255,255,255,.1);

    border:1px solid rgba(255,255,255,.2);

    line-height:1.8;

    font-size:15px;

    color:#fff;
}

.finalButton{

    margin-top:25px;

    padding:13px 22px;

    border:1px solid #ffe66d;

    border-radius:25px;

    background:transparent;

    color:#ffe66d;

    font-weight:bold;

}

/* ANIMATIONS */

@keyframes finalReveal{

    from{
        opacity:0;
        transform:scale(.7);
    }

    to{
        opacity:1;
        transform:scale(1);
    }

}

@keyframes finalShine{

    from{
        background-position:0%;
    }

    to{
        background-position:300%;
    }

}

/* FLOATING SPARKLES */

.sparkle{

    position:fixed;

    bottom:-30px;

    pointer-events:none;

    z-index:2000;

    animation:floatUp 5s linear forwards;
}

@keyframes floatUp{

    from{
        transform:translateY(0) rotate(0deg);
        opacity:1;
    }

    to{
        transform:translateY(-110vh) rotate(360deg);
        opacity:0;
    }

}

/* MOBILE */

@media(max-width:400px){

    .card{
        padding:30px 18px;
    }

    h1{
        font-size:34px;
    }

    .balloon{
        font-size:40px;
    }

    .gameBox{
        padding:25px 15px;
    }

}

</style>
</head>

<body>

<div class="glow"></div>


<!-- BACKGROUND STARS -->

<div class="star" style="top:7%;left:15%;font-size:20px;">✦</div>
<div class="star" style="top:18%;left:82%;font-size:14px;">✧</div>
<div class="star" style="top:35%;left:7%;font-size:18px;">✦</div>
<div class="star" style="top:72%;left:91%;font-size:20px;">✧</div>
<div class="star" style="top:85%;left:15%;font-size:16px;">✦</div>
<div class="star" style="top:55%;left:95%;font-size:15px;">✧</div>
<div class="star" style="top:12%;left:50%;font-size:18px;">✦</div>


<!-- BALLOONS -->

<div class="balloon b1">🎈</div>
<div class="balloon b2">🎈</div>
<div class="balloon b3">🎈</div>
<div class="balloon b4">🎈</div>


<!-- MAIN PAGE -->

<div class="container">

<div class="card">

    <div class="cake">
        🎂
    </div>

    <div class="small">
        A Special Surprise For You
    </div>

    <h1>
        Happy Birthday
    </h1>

    <h2>
        To My Wonderful Mami Gem 💖
    </h2>

    <div class="line"></div>

    <p class="message">

        Today is a very special day because
        we get to celebrate someone very special.

        <br><br>

        Happy Birthday, Mami! 🎉

        <br><br>

        I wish you good health, happiness,
        peace, love, and many more beautiful
        years ahead.

        <br><br>

        May your special day be filled with
        laughter, wonderful memories, and
        all the blessings you deserve.

        <br><br>

        Thank you for being a wonderful Mami. 💗

    </p>


    <button
        class="mainButton"
        onclick="startBirthdayGame()">

        🎁 OPEN THE BIGGEST SURPRISE

    </button>

</div>

</div>


<!-- MUSIC -->

<audio id="birthdayMusic" loop>

    <source
        src="music.mp3"
        type="audio/mpeg">

</audio>


<!-- BIGGEST SURPRISE GAME -->

<div id="birthdayGame">

<div class="gameBox">


    <div class="gameProgress">

        CHALLENGE
        <span id="level">1</span>
        OF 3

    </div>


    <!-- CHALLENGE 1 -->

    <div
        id="game1"
        class="gameLevel">

        <h2>
            Find the Hidden Stars
        </h2>

        <p>
            Tap all 5 hidden stars to unlock
            the next challenge.
        </p>


        <div class="starGame">

            <button
                class="gameStar"
                onclick="findStar(this)">
                ★
            </button>

            <button
                class="gameStar"
                onclick="findStar(this)">
                ★
            </button>

            <button
                class="gameStar"
                onclick="findStar(this)">
                ★
            </button>

            <button
                class="gameStar"
                onclick="findStar(this)">
                ★
            </button>

            <button
                class="gameStar"
                onclick="findStar(this)">
                ★
            </button>

        </div>


        <p id="starResult">

            Stars found: 0 / 5

        </p>

    </div>


    <!-- CHALLENGE 2 -->

    <div
        id="game2"
        class="gameLevel">

        <h2>
            Choose the Special Gift
        </h2>

        <p>
            One of these gifts contains
            the next surprise.
        </p>


        <div class="giftChoices">

            <button
                onclick="chooseGift(false)">
                Gift A
            </button>

            <button
                onclick="chooseGift(true)">
                Gift B
            </button>

            <button
                onclick="chooseGift(false)">
                Gift C
            </button>

        </div>


        <p id="giftResult"></p>

    </div>


    <!-- CHALLENGE 3 -->

    <div
        id="game3"
        class="gameLevel">

        <h2>
            One Last Question
        </h2>

        <p>
            What does Mami deserve
            on her special day?
        </p>


        <div class="answerChoices">

            <button
                onclick="chooseAnswer(false)">
                More Stress
            </button>

            <button
                onclick="chooseAnswer(true)">
                Love & Happiness
            </button>

            <button
                onclick="chooseAnswer(false)">
                More Problems
            </button>

        </div>


        <p id="answerResult"></p>

    </div>


    <!-- FINAL MESSAGE -->

    <div id="finalMessage">

        <div class="unlockText">

            FINAL SURPRISE UNLOCKED

        </div>


        <h1>

            HAPPY BIRTHDAY, MAMI GEMMA!

        </h1>


        <div class="finalLine"></div>


        <p>
            You completed all the challenges!
        </p>

        <p>
            But the real surprise is this...
        </p>


        <div class="personalMessage">

            Miii, I made this little game
            especially for you because I wanted
            your birthday surprise to be
            something different.

            <br><br>

            Thank you for all the love, care,
            laughter, and beautiful memories.

            <br><br>

            I hope you always remember that
            you are loved, appreciated, and
            very special to us.

            <br><br>

            May you have good health,
            happiness, peace, and many more
            wonderful birthdays to come.

            <br><br>

            <b>
                Happy Birthday, Mami Gem!
            </b>

            <br><br>

            I hope you enjoyed your little
            birthday adventure. 💗

        </div>


        <button
            class="finalButton"
            onclick="createFinalSparkles()">

            A Little More Magic

        </button>

    </div>


</div>

</div>


<script>

/* =================================
   START GAME
================================= */

function startBirthdayGame(){

    const music =
        document.getElementById(
            "birthdayMusic"
        );

    if(music){

        music.play().catch(function(){

            console.log(
                "Music needs user interaction."
            );

        });

    }

    document.getElementById(
        "birthdayGame"
    ).style.display = "block";

}


/* =================================
   CHALLENGE 1
================================= */

let starsFound = 0;


function findStar(star){

    if(
        star.classList.contains(
            "found"
        )
    ){

        return;

    }


    star.classList.add("found");

    starsFound++;


    document.getElementById(
        "starResult"
    ).innerHTML =
        "Stars found: "
        + starsFound
        + " / 5";


    if(starsFound === 5){

        document.getElementById(
            "starResult"
        ).innerHTML =
            "✨ All stars found! Challenge unlocked!";


        setTimeout(function(){

            document.getElementById(
                "game1"
            ).style.display = "none";


            document.getElementById(
                "game2"
            ).style.display = "block";


            document.getElementById(
                "level"
            ).innerHTML = "2";

        },900);

    }

}


/* =================================
   CHALLENGE 2
================================= */

function chooseGift(correct){

    const result =
        document.getElementById(
            "giftResult"
        );


    if(correct){

        result.innerHTML =
            "✨ Correct! You found the special gift!";


        setTimeout(function(){

            document.getElementById(
                "game2"
            ).style.display = "none";


            document.getElementById(
                "game3"
            ).style.display = "block";


            document.getElementById(
                "level"
            ).innerHTML = "3";

        },900);


    }else{

        result.innerHTML =
            "Not this one. Try another gift!";

    }

}


/* =================================
   CHALLENGE 3
================================= */

function chooseAnswer(correct){

    const result =
        document.getElementById(
            "answerResult"
        );


    if(correct){

        result.innerHTML =
            "✨ Correct! Unlocking your final surprise...";


        setTimeout(function(){

            document.getElementById(
                "game3"
            ).style.display = "none";


            document.getElementById(
                "level"
            ).innerHTML = "✓";


            document.getElementById(
                "finalMessage"
            ).style.display = "block";


            createFinalSparkles();

        },1000);


    }else{

        result.innerHTML =
            "Hmm... try again!";

    }

}


/* =================================
   FINAL SPARKLES
================================= */

function createFinalSparkles(){

    const symbols = [
        "✨",
        "💖",
        "⭐",
        "✦",
        "💫"
    ];


    for(
        let i = 0;
        i < 50;
        i++
    ){

        const sparkle =
            document.createElement(
                "div"
            );


        sparkle.className =
            "sparkle";


        sparkle.innerHTML =
            symbols[
                Math.floor(
                    Math.random()
                    * symbols.length
                )
            ];


        sparkle.style.left =
            Math.random()
            * 100
            + "vw";


        sparkle.style.fontSize =
            (12 +
            Math.random() * 25)
            + "px";


        sparkle.style.animationDuration =
            (3 +
            Math.random() * 4)
            + "s";


        document.body.appendChild(
            sparkle
        );


        setTimeout(function(){

            sparkle.remove();

        },7000);

    }

}

</script>

</body>
</html>
