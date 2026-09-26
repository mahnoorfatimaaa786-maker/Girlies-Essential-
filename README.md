# Girlies-Essential-
A modern and responsive website for a girls' lifestyle brand.
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Girlies Essentials ♡</title>

    <link rel="stylesheet" href="style.css">
</head>

<body>

<!-- TOP BAR -->

<div class="top-bar">
    <span>💕 Be your own kind of beautiful</span>
    <span>Stay Positive • Stay Healthy • Stay You ✨</span>
</div>


<!-- NAVBAR -->

<header>

    <div class="logo">
        Girlies 🎀
        <small>ESSENTIALS ♡</small>
    </div>

    <button class="menu-btn" onclick="toggleMenu()">
        ☰
    </button>

    <nav id="navbar">

        <a href="index.html">Home</a>
        <a href="#categories">Explore</a>
        <a href="morning.html">Morning</a>
        <a href="fitness.html">Fitness</a>
        <a href="meals.html">Meals</a>
        <a href="skincare.html">Skincare</a>

    </nav>

</header>



<!-- HERO -->

<section class="hero" id="home">

    <div class="hero-text">

        <p class="welcome">
            WELCOME, GIRLIE ♡
        </p>

        <h1>
            Take care of your
            <span>body, skin & soul.</span>
        </h1>

        <p>
            Your cute little guide to self-care,
            healthy habits, fitness, skincare,
            meals and everyday girlie essentials.
        </p>


        <div class="hero-buttons">

            <a href="#categories">
                Explore My World ✨
            </a>

            <a href="morning.html" class="white-btn">
                Start Your Journey ♡
            </a>

        </div>

    </div>


    <div class="hero-girl">

        <img
            src="girlie.png"
            alt="Girlies"
        >

        <div class="bubble">
            Love yourself
            <br>
            first 💗
        </div>

    </div>

</section>



<!-- CATEGORIES -->

<section class="categories" id="categories">

    <p class="small-title">
        EXPLORE YOUR GIRLIE WORLD 🎀
    </p>

    <h2>
        Everything you need,
        in one place.
    </h2>

    <p class="intro">
        Pick your vibe and enter your little world ♡
    </p>


    <div class="category-grid">
        <!-- =========================
     MONTHLY GIRLIES CALENDAR
========================= -->

<section class="monthly-calendar" id="calendar">

    <div class="calendar-heading">
        <span>MY LITTLE MONTH 🎀</span>

        <h2>30 Days of Little Joys ♡</h2>

        <p>
            Har din ek choti si activity choose karo,
            complete karo aur apna little win check karo ✨
        </p>
    </div>

    <div class="calendar-box">

        <div class="calendar-top">

            <button onclick="previousMonth()">‹</button>

            <h3 id="monthTitle"></h3>

            <button onclick="nextMonth()">›</button>

        </div>

        <div class="weekdays">
            <span>Sun</span>
            <span>Mon</span>
            <span>Tue</span>
            <span>Wed</span>
            <span>Thu</span>
            <span>Fri</span>
            <span>Sat</span>
        </div>

        <div class="calendar-grid" id="calendarGrid"></div>

        <div class="calendar-progress">

            <div class="progress-text">
                <span>🎀 Your little progress</span>
                <strong id="progressText">0%</strong>
            </div>

            <div class="progress-bar">
                <div id="progressFill"></div>
            </div>

        </div>

    </div>

    <div class="activity-popup" id="activityPopup">

        <div class="popup-card">

            <button
                class="close-popup"
                onclick="closeActivity()">
                ×
            </button>

            <div id="popupEmoji">🎀</div>

            <h3 id="popupTitle">
                Today's Little Activity
            </h3>

            <p id="popupActivity">
                Take a little moment for yourself.
            </p>

            <button
                class="complete-btn"
                onclick="completeActivity()">
                ✓ I Did It!
            </button>

        </div>

    </div>

</section>


        <!-- FITNESS -->

        <a href="fitness.html" class="category-card">

            <div class="category-icon">
                🏋🏻‍♀️
            </div>

            <h3>
                Girlies Fitness
            </h3>

            <p>
                Cute workouts, stretching
                and healthy movement.
            </p>

            <strong>
                Explore →
            </strong>

        </a>



        <!-- MEALS -->

        <a href="meals.html" class="category-card">

            <div class="category-icon">
                🍓
            </div>

            <h3>
                Girlies Meals
            </h3>

            <p>
                Easy meals, snacks and
                yummy food inspiration.
            </p>

            <strong>
                Explore →
            </strong>

        </a>



        <!-- BAG -->

        <a href="bag.html" class="category-card">

            <div class="category-icon">
                👜
            </div>

            <h3>
                My Girlies Bag
            </h3>

            <p>
                Everyday essentials
                every girl needs.
            </p>

            <strong>
                Explore →
            </strong>

        </a>



        <!-- SKINCARE -->

        <a href="skincare.html" class="category-card">

            <div class="category-icon">
                🧴
            </div>

            <h3>
                Skincare
            </h3>

            <p>
                Simple routines and
                everyday glow care.
            </p>

            <strong>
                Explore →
            </strong>

        </a>



        <!-- BODY CARE -->

        <a href="bodycare.html" class="category-card">

            <div class="category-icon">
                🛁
            </div>

            <h3>
                Body Care
            </h3>

            <p>
                Shower, freshness,
                hair and body care.
            </p>

            <strong>
                Explore →
            </strong>

        </a>



        <!-- SELF CARE -->

        <a href="selfcare.html" class="category-card">

            <div class="category-icon">
                💗
            </div>

            <h3>
                Self Care
            </h3>

            <p>
                Slow down, reset,
                relax and recharge.
            </p>

            <strong>
                Explore →
            </strong>

        </a>



        <!-- MORNING -->

        <a href="morning.html" class="category-card">

            <div class="category-icon">
                🌞
            </div>

            <h3>
                Morning Routine
            </h3>

            <p>
                Start your day with
                calm girlie energy.
            </p>

            <strong>
                Explore →
            </strong>

        </a>



        <!-- STUDY -->

        <a href="study.html" class="category-card">

            <div class="category-icon">
                📚
            </div>

            <h3>
                Study Girl Era
            </h3>

            <p>
                Focus, notes, habits
                and productive vibes.
            </p>

            <strong>
                Explore →
            </strong>

        </a>



        <!-- PERIOD -->

        <a href="period.html" class="category-card">

            <div class="category-icon">
                🌸
            </div>

            <h3>
                Period Care
            </h3>

            <p>
                Gentle and practical
                period-care information.
            </p>

            <strong>
                Explore →
            </strong>

        </a>



        <!-- REMEDIES -->

        <a href="remedies.html" class="category-card">

            <div class="category-icon">
                🌿
            </div>

            <h3>
                Girlies Remedies
            </h3>

            <p>
                Simple wellness ideas
                and comfort routines.
            </p>

            <strong>
                Explore →
            </strong>

        </a>

    </div>

</section>



<!-- LITTLE MESSAGE -->

<section class="detail-section pink">

    <div class="section-heading">

        <p class="small-title">
            A LITTLE REMINDER 💗
        </p>

        <h2>
            You deserve your own little reset.
        </h2>

        <p>
            Drink some water, take a breath,
            do something you love and remember
            that small steps count too.
        </p>

    </div>


    <div class="info-grid">


        <div class="info-card">

            <h3>
                🌸 Take It Slow
            </h3>

            <p>
                You don't have to do everything
                at once.
            </p>

        </div>


        <div class="info-card">

            <h3>
                🎀 Romanticize Your Day
            </h3>

            <p>
                Make ordinary little moments
                feel special.
            </p>

        </div>


        <div class="info-card">

            <h3>
                💕 Choose Yourself
            </h3>

            <p>
                Make space for the things
                that make you feel good.
            </p>

        </div>

    </div>

</section>



<!-- FOOTER -->

<footer>

    <h3>
        Girlies Essentials ♡
    </h3>

    <p>
        Your little corner for self-care,
        wellness & girlie things 🎀
    </p>

</footer>



<script src="script.js"></script>

</body>

</html>