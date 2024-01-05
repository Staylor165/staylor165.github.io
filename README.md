# staylor165.github.io
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Taco Bell Campaign</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Atkinson+Hyperlegible:wght@400;700&display=swap" rel="stylesheet">

    <style>
        body {
            font-family: 'Atkinsin Hyperlegible';
            margin: 0;
            padding: 0;
            background-color: #fcf8f0; 
            color: #323232; 
            position: relative;
            min-height: 100vh;
        }

        .container {
            max-width: 1400px;
            margin: 0 auto;
            padding: 20px;
        }

        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 0;
            margin-top: 0;
            background: url('taco-bell-cover.jpeg');
            background-position: 0% 0%;
        }

        .logo {
            width: 90px;
            height: auto;
            font-weight: bold;
        }

        .social-icons {
            font-size: 24px;
            margin-top: 10px;
        }

        .social-icons img {
            width: 60px;
            height: auto;
            margin-right: 10px;
            font-weight: bold;
        }

        .end-card {
            text-align: center; /* Center the text */
            padding: 20px;
            margin-top: 20px;
        }

        .cta-button {
            display: inline-block;
            padding: 15px 30px;
            background-color: #682A8D; /* Purple color */
            color: #fff;
            text-decoration: none;
            border-radius: 8px;
            font-weight: bold;
            margin-top: 20px;
            font-size: 18px;
            transition: background-color 0.3s ease, color 0.3s ease;
            position: absolute;
            bottom: 20px;
            right: 20px;
        }

        .cta-button:hover {
            background-color: #A07EBA; /* Lighter purple on hover */
        }

        .marketing-copy {
            margin-top: 20px;
            font-size: 16px;
            line-height: 1.6;
            text-align: justify; /* Justify the text */
        }

        .marketing-heading {
            font-size: 24px;
            font-weight: bold;
        }

        .sub-heading {
            font-size: 18px;
            font-weight: bold;
        }

        .bold-names {
            color: #A07EBA;
            font-weight: 900;
            text-decoration: underline;
            cursor: pointer;
        }

        .image-container {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            margin-top: 20px;
        }

        .zigzag-image {
            width: 30%; /* Adjust the width as needed */
            height: auto;
            margin-bottom: 20px;
        }

        .social-buttons {
            margin-top: 30px;
        }

        .social-button {
            display: inline-block;
            margin-right: 15px;
            background-color: #4267B2;
            color: #fff;
            padding: 10px 15px;
            text-decoration: none;
            border-radius: 8px;
            transition: background-color 0.3s ease;
        }

        .social-button:hover {
            background-color: #365899;
        }

        @media screen and (max-width: 800px) {
            .cta-button,
            .social-button {
                padding: 12px 20px;
                font-size: 16px;
            }

            .zigzag-image {
                width: 100%;
            }
        }

        @media screen and (max-width: 480px) {
            .cta-button,
            .social-button {
                padding: 10px 15px;
                font-size: 14px;
            }
        }
    </style>
</head>
<body>

    <div class="container">
        <header>
            <img src="Taco_Bell.svg" alt="Taco Bell Logo" class="logo">
            <div class="social-icons">
                <a href="#" target="new"><img src="facebook.png" alt="facebook logo"></a>
                <a href="#" target="new"><img src="twitter.png" alt="twitter logo"></a>
                <a href="#" target="new"><img src="youtube.png" alt="youtube logo"></a>
            </div>
        </header>

        <div class="end-card">
            <h1>Taco Bell Dollar Cravings Value Menu</h1>
            <div class="marketing-heading">ORDER YOUR FAVORITE TACO BELL CRAVINGS VALUE MENU ONLINE OR VISIT US AT THE TACO BELL LOCATION NEAREST YOU</div>
            <p class="marketing-copy">Do you have a craving for Mexican inspired food and have a dollar in your pocket? If that’s the case, do we have a menu for you! At Taco Bell, you can find a variety of your favorite menu items for only one dollar. Find our take out specials near you today.</p>
            <p class="marketing-copy">Got $3? Well, now you have an entire three-course meal! Start your meal off with an appetizer like the <a href="https://www.tacobell.com/food/sides/cheesy-roll-up" class="bold-names">Cheesy Roll Up</a> or <a href="https://www.tacobell.com/food/nachos/chips-and-nacho-cheese-sauce" class="bold-names">Chips and Nacho Cheese Sauce</a>. For the main dish, give the iconic <a href="https://www.tacobell.com/food/burritos/beefy-melt-burrito" class="bold-names">Beefy Melt Burrito</a> a try or enjoy the <a href="https://www.tacobell.com/food/cravings-value-menu/cheesy-bean-and-rice-burrito" class="bold-names">Cheesy Bean and Rice Burrito</a> instead. Top off your meal with a mouth-watering, dessert from the Taco Bell Cravings Value Menu such as <a href="https://www.tacobell.com/food/sweets/cinnamon-twists" class="bold-names">Cinnamon Twists</a>. Order fast food near you online from the Cravings Value Menu at Taco Bell today!</p>

            <div class="image-container">
                <img src="tacobell.jpg" alt="Image 1" class="zigzag-image">
                <img src="tacobell2.jpeg" alt="Image 2" class="zigzag-image">
                <img src="tacobell3.jpeg" alt="Image 3" class="zigzag-image">
            </div>

            <a href="https://www.tacobell.com/food/cravings-value-menu" class="cta-button" target="new">Explore Now</a>
        </div>
    </div>

</body>
</html>
