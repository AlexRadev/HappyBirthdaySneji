
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy Birthday!</title>
    <style>
        /* Add your custom CSS styles here */
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #f9f9f9;
            color: #333;
            margin: 0;
            padding: 0;
        }

        h1 {
            color: #ff6b6b;
        }

        .birthday-img {
            font-size: 100px;
            margin-top: 20px;
        }

        .birthday-cake {
            max-width: 300px;
            margin-top: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        .birthday-wishes {
            margin-top: 20px;
            font-size: 20px;
            line-height: 1.5;
        }

        .balloons {
            font-size: 30px;
            animation: floatBalloons 3s infinite;
        }

        @keyframes floatBalloons {
            0% {
                transform: translateY(0);
            }
            50% {
                transform: translateY(-20px);
            }
            100% {
                transform: translateY(0);
            }
        }

        .btn-container {
            margin-top: 30px;
        }

        .btn-container button {
            padding: 10px 20px;
            font-size: 18px;
            background-color: #ff6b6b;
            color: #fff;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            margin: 5px;
        }

        /* Add more custom styles as needed */
    </style>
</head>
<body>
    <header>
        <h1>Happy Birthday!</h1>
    </header>

    <main>
        <section>
            <div class="birthday-img">
                🎈🎈🎈🎈🎈
            </div>
            <img src="https://example.com/birthday_cake.jpg" alt="Birthday Cake" class="birthday-cake">
            <div class="birthday-wishes">
                <p>Dear Sneji,</p>
                <p>Wishing you a day filled with joy, laughter, and all the things that make you happy.</p>
                <p>As you turn 24, may this year be full of amazing moments and new adventures!</p>
                <p>I love you more than anything in this world, and I am grateful for every day we share together.</p>
                <p>With love and warmest wishes,</p>
                <p>Alex</p>
            </div>
            <div class="balloons">
                🎈🎈🎈🎈🎈
            </div>
            <div class="btn-container">
                <button onclick="flyBalloons()">Click on Me</button>
                <button onclick="openGiftsPage()">Open Presents Page</button>
                <button onclick="showLove()">Show Love</button>
            </div>
        </section>
    </main>

    <footer>
        <p>Happy Birthday! 🎉🎂🎈</p>
    </footer>

    <script>
        function flyBalloons() {
            const balloons = document.querySelector('.balloons');
            balloons.style.animation = 'floatBalloons 3s infinite';
        }

        function openGiftsPage() {
            window.open('', '_blank').document.write('<h1>Are you ready for tomorrow to find all presents for you!</h1>');
        }

        function showLove() {
            alert('I love you more than anything! ❤️');
        }
    </script>
</body>
</html>
