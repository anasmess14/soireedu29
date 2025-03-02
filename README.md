<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Soirée du 29</title>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@600&family=Raleway:wght@300;400&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            height: 100vh;
            padding: 40px;
            background: radial-gradient(circle at top, #ff7e5f, #2c003e, #0d0d0d);
            color: #fff;
            font-family: 'Raleway', sans-serif;
            text-align: center;
            position: relative;
            overflow: hidden;
        }

        .title {
            font-size: 4rem;
            font-family: 'Playfair Display', serif;
            text-transform: uppercase;
            letter-spacing: 2px;
            color: #ffd700;
            text-shadow: 0 0 15px rgba(255, 215, 0, 0.4);
            animation: fadeIn 1.5s ease-in-out;
        }

        .details {
            font-size: 1.8rem;
            font-weight: 400;
            opacity: 0.9;
            line-height: 1.5;
            margin-top: 20px;
            animation: fadeIn 2s ease-in-out 0.5s forwards;
            opacity: 0;
        }

        .message {
            font-size: 2.5rem;
            font-weight: bold;
            font-style: italic;
            color: #ffcc70;
            text-shadow: 0 0 10px rgba(255, 204, 112, 0.6);
            margin-top: 50px;
            animation: fadeIn 3s ease-in-out 1s forwards;
            opacity: 0;
        }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(-20px); }
            to { opacity: 1; transform: translateY(0); }
        }
    </style>
</head>
<body>

    <!-- Audio en arrière-plan -->
    <audio autoplay loop>
        <source src="https://github.com/ton_nom_utilisateur/soireed29/raw/main/jul-la-faille.mp3" type="audio/mp3">
        Ton navigateur ne prend pas en charge l'élément audio.
    </audio>

    <div class="title">Soirée du 29</div>
    
    <div class="details">
        🗓️ 29 Juin 2025 <br>
        📍 Harensesteenweg 459, 1800 Vilvoorde
    </div>

    <div class="message">À suivre...</div>
</body>
</html># soir-e-du-29
