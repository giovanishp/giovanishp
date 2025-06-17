<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Mis Directos</title>
    <style>
        body {
            background-color: #000000;
            color: #fff;B
            font-family: Arial, sans-serif;
            text-align: center;
        }
        h1 {
            color: #a78bfa;
        }
        .enlaces {
            margin: 20px 0;
        }
        .enlaces a {
            color: #38bdf8;
            text-decoration: none;
            margin: 0 10px;
            font-size: 18px;
        }
        .enlaces a:hover {
            text-decoration: underline;
        }
        .stream {
            margin: 30px auto;
            max-width: 800px;
        }
        iframe {
            width: 100%;
            height: 450px;
            border: none;
            border-radius: 10px;
        }
    </style>
</head>
<body>
    <h1>¡Bienvenido a mis directos!</h1>
    <div class="enlaces">
        <a href="https://www.twitch.tv/giovanishp" target="_blank">Twitch</a>
        <a href="https://www.youtube.com/@giovanishp" target="_blank">YouTube</a>
        <a href="https://www.instagram.com/giovanishp" target="_blank">instagram</a>
    </div>
    <div class="stream">
        <!-- Reemplaza el src con el enlace de tu canal de Twitch o YouTube -->
        <iframe
            src="https://player.twitch.tv/?channel=giovanishpL&parent=localhost"
            allowfullscreen>
        </iframe>
    </div>
</body>
</html>
