<html lang="ru">
<head>
    <meta charset="UTF-8">
    <title>С 8 Марта!</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background: linear-gradient(to right, #ffccff, #ff99cc);
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }
        .card {
            background-color: #ffffff;
            padding: 20px;
            border-radius: 15px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            text-align: center;
            max-width: 90%;
            border: 2px solid #ff69b4;
        }
        .card h1 {
            color: #ff1493;
            font-size: 2.5em;
            margin: 0;
        }
        .card p {
            color: #333333;
            font-size: 1.2em;
        }
        .card .message {
            font-style: italic;
            margin-top: 20px;
        }
        .card .flower {
            margin-top: 20px;
            animation: float 3s infinite;
        }
        @keyframes float {
            0%, 100% {
                transform: translateY(0);
            }
            50% {
                transform: translateY(-10px);
            }
        }
        .card .button {
            margin-top: 10px;
        }
        .card .button a {
            background-color: #ff69b4;
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 25px;
            transition: background-color 0.3s, transform 0.3s, box-shadow 0.3s;
            display: inline-block;
            box-shadow: 0px 5px 15px rgba(0, 0, 0, 0.3);
            font-size: 1em;
        }
        .card .button a:hover {
            background-color: #ff1493;
            transform: translateY(-5px);
            box-shadow: 0px 10px 20px rgba(0, 0, 0, 0.3);
        }
    </style>
    <script>
        function showMessage(name) {
            let message = '';
            switch (name) {
                case 'Аня Потехина':
                    message = 'С 8 Марта, Аня Потехина! Желаем тебе всегда оставаться такой же яркой и жизнерадостной! Пусть каждый день приносит тебе счастье и радость!';
                    break;
                case 'Аня Шнитко':
                    message = 'С 8 Марта, Аня Шнитко! Пусть этот день подарит тебе много улыбок и тёплых слов. Желаем тебе весеннего настроения и неисчерпаемого оптимизма!';
                    break;
                case 'Полина Кашеня':
                    message = 'С 8 Марта, Полина Кашеня! Пусть этот день принесёт тебе много радости, счастья и незабываемых моментов. Желаем тебе всего самого наилучшего!';
                    break;
                case 'Ксюша Петрученя':
                    message = 'С 8 Марта, Ксюша Петрученя! Желаем тебе оставаться такой же милой и доброй. Пусть каждый день будет наполнен любовью и гармонией!';
                    break;
                case 'Лена Кузьмич':
                    message = 'С 8 Марта, Лена Кузьмич! Пусть этот день будет наполнен улыбками и прекрасным настроением. Желаем тебе счастья, здоровья и море приятных впечатлений!';
                    break;
                case 'Рома Селедчик':
                    message = 'С 8 Марта, Рома Селедчик! Ты лох!';
                    break;
                case 'Дима Козел':
                    message = 'С 8 Марта, Дима Козел! Ты лох!';
                    break;
                default:
                    message = 'С 8 Марта! Желаем тебе счастья, здоровья и любви!';
                    break;
            }
            alert(message);
        }
    </script>
</head>
<body>
    <div class="card">
        <h1>С 8 Марта!</h1>
        <p>Дорогие женщины,</p>
        <p>Поздравляем вас с Международным женским днём!</p>
        <p>Желаем вам счастья, здоровья и любви.</p>
        <p>Пусть каждый день приносит вам радость и улыбки!</p>
        <div class="message">
            <p>С наилучшими пожеланиями</p>
        </div>
        <div class="flower">
            <img src="https://cdn.culture.ru/images/659b411e-d5c4-55ea-997b-2053463ad50f" alt="Цветок" width="100">
        </div>
        <div class="button">
            <a href="javascript:void(0);" onclick="showMessage('Аня Потехина')">Открыть для Ани Потехиной</a>
        </div>
        <div class="button">
            <a href="javascript:void(0);" onclick="showMessage('Аня Шнитко')">Открыть для Ани Шнитко</a>
        </div>
        <div class="button">
            <a href="javascript:void(0);" onclick="showMessage('Полина Кашеня')">Открыть для Полины Кашени</a>
        </div>
        <div class="button">
            <a href="javascript:void(0);" onclick="showMessage('Ксюша Петрученя')">Открыть для Ксюши Петрученя</a>
        </div>
        <div class="button">
            <a href="javascript:void(0);" onclick="showMessage('Лена Кузьмич')">Открыть для Лены Кузьмич</a>
        </div>
        <div class="button">
            <a href="javascript:void(0);" onclick="showMessage('Рома Селедчик')">Открыть для Ромы Селедчик</a>
        </div>
        <div class="button">
            <a href="javascript:void(0);" onclick="showMessage('Дима Козел')">Открыть для Димы Козла</a>
        </div>
    </div>
</body>
</html>
