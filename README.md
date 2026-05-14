<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kodak Kart | Coming Soon</title>
    <style>
        /* CSS Reset & Basics */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Helvetica Neue', Arial, sans-serif;
        }

        body {
            height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            background-color: #f4f4f4;
            color: #222;
            text-align: center;
            padding: 20px;
        }

        /* Main Container */
        .container {
            max-width: 650px;
            background: #ffffff;
            padding: 60px 40px;
            border-radius: 8px;
            box-shadow: 0 15px 35px rgba(0,0,0,0.05);
        }

        /* Logo Placeholder */
        .logo {
            font-size: 2.2rem;
            font-weight: 800;
            letter-spacing: 3px;
            text-transform: uppercase;
            margin-bottom: 30px;
            color: #111;
        }

        /* Image Logo (Hidden by default until you have one) */
        .logo-img {
            display: none; /* Change to block when logo is ready */
            max-width: 200px;
            margin: 0 auto 30px auto;
        }

        /* Typography */
        h1 {
            font-size: 2.5rem;
            margin-bottom: 15px;
            font-weight: 700;
            letter-spacing: -0.5px;
        }

        p {
            font-size: 1.1rem;
            color: #666;
            line-height: 1.6;
            margin-bottom: 35px;
        }

        /* Notify Form */
        .notify-form {
            display: flex;
            flex-direction: column;
            gap: 12px;
            max-width: 450px;
            margin: 0 auto;
        }

        @media (min-width: 480px) {
            .notify-form {
                flex-direction: row;
            }
        }

        input[type="email"] {
            flex: 1;
            padding: 14px 18px;
            border: 1px solid #e0e0e0;
            border-radius: 4px;
            font-size: 1rem;
            outline: none;
            transition: border-color 0.3s ease;
        }

        input[type="email"]:focus {
            border-color: #111;
        }

        button {
            padding: 14px 28px;
            background-color: #111;
            color: #fff;
            border: none;
            border-radius: 4px;
            font-size: 1rem;
            font-weight: 600;
            cursor: pointer;
            text-transform: uppercase;
            letter-spacing: 1px;
            transition: background-color 0.3s ease, transform 0.1s ease;
        }

        button:hover {
            background-color: #333;
        }
        
        button:active {
            transform: scale(0.98);
        }

        /* Footer/Social */
        .footer {
            margin-top: 40px;
            font-size: 0.85rem;
            color: #999;
            text-transform: uppercase;
            letter-spacing: 1px;
        }
    </style>
</head>
<body>

    <div class="container">
        <!-- Replace the div below with an <img> tag when your logo is ready -->
        <div class="logo">KODAK KART</div>
        <!-- <img src="your-logo.png" alt="Kodak Kart Logo" class="logo-img"> -->
        
        <h1>Redefining Your Wardrobe.</h1>
        <p>We are currently crafting a new standard in everyday style. Be the first to know when our exclusive clothing collection drops.</p>
        
        <form class="notify-form" action="#" method="POST" onsubmit="event.preventDefault(); alert('Thank you! We will notify you when we launch.');">
            <input type="email" placeholder="Enter your email address" required>
            <button type="submit">Notify Me</button>
        </form>
        
        <div class="footer">
            &copy; 2026 Kodak Kart. All rights reserved.
        </div>
    </div>

</body>
</html>
