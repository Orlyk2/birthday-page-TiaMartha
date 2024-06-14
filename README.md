<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Feliz Cumpleaños Martha Josefina</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #fff5e6;
            color: #333;
            margin: 0;
            padding: 0;
            text-align: center;
        }
        .container {
            margin: 0 auto;
            padding: 20px;
        }
        .birthday-message {
            margin-top: 20px;
            padding: 20px;
            border: 5px solid #ffb3b3;
            border-radius: 20px;
            background-color: #ffe6e6;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.2);
            display: inline-block;
        }
        .birthday-message h1 {
            font-size: 3em;
            animation: colorChange 2s infinite, move 1s infinite alternate;
        }
        .birthday-message p {
            font-size: 1.5em;
            animation: colorChange 2s infinite, move 1s infinite alternate;
        }
        @keyframes colorChange {
            0% { color: #ff66b2; }
            20% { color: #ff9933; }
            40% { color: #ffff66; }
            60% { color: #66ff66; }
            80% { color: #66b3ff; }
            100% { color: #ff66b2; }
        }
        @keyframes move {
            0% { transform: translateY(0); }
            100% { transform: translateY(-10px); }
        }
        .roses {
            margin: 20px 0;
        }
        .roses img {
            width: 50px;
            margin: 0 5px;
        }
        .video-container {
            margin-top: 20px;
            padding: 20px;
            border: 3px solid #ffccff;
            border-radius: 15px;
            background-color: #ffffff;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            display: inline-block;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="birthday-message">
            <h1>¡Feliz Cumpleaños Martha Josefina!</h1>
            <p>Que tengas un día maravilloso lleno de alegría y felicidad.</p>
            <div class="roses">
                <img src="https://www.pngall.com/wp-content/uploads/2016/04/Rose-Flower-PNG-Image.png" alt="Rose">
                <img src="https://www.pngall.com/wp-content/uploads/2016/04/Rose-Flower-PNG-Image.png" alt="Rose">
                <img src="https://www.pngall.com/wp-content/uploads/2016/04/Rose-Flower-PNG-Image.png" alt="Rose">
                <img src="https://www.pngall.com/wp-content/uploads/2016/04/Rose-Flower-PNG-Image.png" alt="Rose">
                <img src="https://www.pngall.com/wp-content/uploads/2016/04/Rose-Flower-PNG-Image.png" alt="Rose">
            </div>
        </div>
        <div class="video-container">
            <video controls width="600">
                <source src="your-video-url.mp4" type="video/mp4">
                Tu navegador no soporta el elemento de video.
            </video>
        </div>
    </div>
</body>
</html>
