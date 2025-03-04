<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Automate Like Anna - Sell While You Sleep</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(135deg, #ff6600, #ffcc00);
            text-align: center;
            animation: backgroundAnimation 10s infinite alternate;
        }
        
        @keyframes backgroundAnimation {
            0% { background: linear-gradient(135deg, #ff6600, #ffcc00); }
            100% { background: linear-gradient(135deg, #cc5500, #ffaa00); }
        }

        .container {
            max-width: 800px;
            margin: 50px auto;
            padding: 20px;
            background: white;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            border-radius: 10px;
        }
        h1 {
            color: #ff6600;
        }
        h2 {
            color: #333;
        }
        p {
            font-size: 18px;
            line-height: 1.6;
            color: #555;
        }
        .cta-button {
            display: inline-block;
            margin-top: 20px;
            padding: 15px 30px;
            background-color: #ff6600;
            color: white;
            font-size: 20px;
            font-weight: bold;
            border: none;
            border-radius: 5px;
            text-decoration: none;
            cursor: pointer;
        }
        .cta-button:hover {
            background-color: #cc5500;
        }
        .testimonial {
            margin-top: 30px;
            padding: 20px;
            background: #f1f1f1;
            border-left: 5px solid #ff6600;
            font-style: italic;
            color: #333;
        }
        .countdown {
            font-size: 24px;
            font-weight: bold;
            color: red;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>AUTOMATE LIKE ANNA</h1>
        <h2>Sell More. Work Less. Make Money While You Sleep.</h2>
        <p>
            Imagine waking up to new sales, messages handled, and leads converted—all while you slept. 
            What if your Instagram account could respond to every DM and comment **automatically** while you focused on growing your business?
        </p>
        <p>
            **AUTOMATE LIKE ANNA** is the ultimate system for business owners who want to streamline their Instagram sales process, 
            engage customers instantly, and boost revenue effortlessly.
        </p>
        <h2>⚠️ Hurry! This Offer Ends In:</h2>
        <div class="countdown" id="countdown">05:00</div>
        <h2>Why Keep Struggling When You Can Automate?</h2>
        <p>
            ✅ Save **hours** every day—no more manually replying to messages. <br>
            ✅ Increase engagement—customers get **instant** responses. <br>
            ✅ Convert leads into sales—without lifting a finger. <br>
            ✅ Focus on growth—let automation handle the rest.
        </p>
        <h2>What Others Are Saying</h2>
        <div class="testimonial">
            "This changed my business overnight! I was spending hours replying to DMs, but now I wake up to new orders effortlessly. Highly recommend!" - Sarah T.
        </div>
        <div class="testimonial">
            "I never realized how much time I was wasting before using Automate Like Anna. Now, I can focus on growth while sales come in automatically!" - James K.
        </div>
        <div class="testimonial">
            "Best investment I've made for my business. It's like having a personal assistant working 24/7!" - Amanda L.
        </div>
        <a href="https://selar.com/p/i0g1na?affiliate=le2h" class="cta-button">Get Instant Access Now!</a>
    </div>
    
    <script>
        let timeLeft = 300; // 5 minutes in seconds
        const countdownElement = document.getElementById('countdown');
        
        function updateCountdown() {
            const minutes = Math.floor(timeLeft / 60);
            const seconds = timeLeft % 60;
            countdownElement.textContent = `${minutes}:${seconds < 10 ? '0' : ''}${seconds}`;
            
            if (timeLeft > 0) {
                timeLeft--;
                setTimeout(updateCountdown, 1000);
            } else {
                countdownElement.textContent = "Time’s Up!";
            }
        }
        
        updateCountdown();
    </script>
</body>
</html>
