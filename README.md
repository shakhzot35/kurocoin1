<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Legend of Kuro</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #121212;
            color: white;
            text-align: center;
            overflow: hidden;
        }
        .container {
            max-width: 800px;
            margin: 50px auto;
            padding: 20px;
        }
        .kuro {
            position: absolute;
            width: 150px;
            bottom: 0;
            left: 50%;
            transform: translateX(-50%);
            animation: moveKuro 3s infinite alternate ease-in-out;
        }
        @keyframes moveKuro {
            0% { transform: translateX(-50%) translateY(0); }
            100% { transform: translateX(-50%) translateY(-20px); }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>The Legend of Kuro: The Crypto Cat</h1>
        <p>In a small, quiet town, hidden between neon-lit skyscrapers and old cobblestone streets, lived <b>Kuro</b>—a sleek black cat with glowing yellow eyes...</p>
        <p>(Full story goes here...)</p>
    </div>
    <img src="kuro.png" class="kuro" alt="Kuro the Cat">
</body>
</html>
