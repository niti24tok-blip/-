<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Мой Mini App</title>
    <script src="https://telegram.org/js/telegram-web-app.js"></script>
    <style>
        body {
            font-family: sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
            margin: 0;
        }
        .card {
            background: rgba(255, 255, 255, 0.1);
            padding: 20px;
            border-radius: 15px;
            backdrop-filter: blur(10px);
            text-align: center;
            border: 1px solid rgba(255, 255, 255, 0.2);
        }
        button {
            background: #fff;
            color: #764ba2;
            border: none;
            padding: 10px 20px;
            border-radius: 10px;
            font-weight: bold;
            cursor: pointer;
            margin-top: 15px;
        }
    </style>
</head>
<body>
    <div class="card">
        <h1>Привет! 👋</h1>
        <p>Это ваш первый сайт внутри Telegram.</p>
        <button onclick="Telegram.WebApp.close()">Закрыть окно</button>
    </div>
</body>
</html>
