# Vova.github.io
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            background-color: #121212;
            color: #ffffff;
            font-family: Arial, sans-serif;
        }
        .hidden {
            display: none;
        }
        .button {
            padding: 10px 20px;
            background-color: #1f1f1f;
            color: #ffffff;
            border: 1px solid #ffffff;
            border-radius: 5px;
            cursor: pointer;
            margin-top: 20px;
            transition: background-color 0.3s, border 0.3s;
        }
        .button:hover {
            background-color: #444444;
        }
         .completed {
            color: #ffffff;
            font-weight: bold;
            background-color: #121212; /* Цвет совпадает с фоном */
            border: 1px solid green; /* Зелёная рамка для успешной отправки */
            padding: 10px;
            border-radius: 5px;
            margin-top: 20px;
        }
        .error {
            color: red;
            font-weight: bold;
            background-color: #121212; /* Цвет совпадает с фоном */
            border: 1px solid red; /* Тонкая красная рамка */
            padding: 10px;
            border-radius: 5px;
            margin-top: 20px;
        }
        input[type="checkbox"] {
            display: none;
        }
        .custom-checkbox {
            position: relative;
            display: inline-block;
            width: 24px;
            height: 24px;
            border: 2px solid #666;
            border-radius: 4px;
            margin-right: 10px;
            background-color: #323232;
            transition: background-color 0.3s, border 0.3s;
        }
        input[type="checkbox"]:checked + .custom-checkbox {
            background-color: #4caf50;
            border-color: #4caf50;
        }
        input[type="checkbox"]:checked + .custom-checkbox:after {
            content: "✔";
            color: #ffffff;
            position: absolute;
            top: 0;
            left: 0;
            width: 24px;
            height: 24px;
            text-align: center;
            line-height: 24px;
        }
        #resultMessage {
            margin-top: 20px;
        } 
         .input-container {
            margin-top: 20px;
            border: 1px solid #ffffff;
            border-radius: 5px;
            position: relative;
        }
        .input-container input {
            width: 100%;
            padding: 10px;
            border: none;
            background-color: #1f1f1f;
            color: #ffffff;
            border-radius: 5px;
            opacity: 0.8;
        }
        .input-container input::placeholder {
            color: #ffffff;
            opacity: 0.5;
        }
        .logo {
            width: 200px;
            margin: 20px auto;
        }
    </style>
</head>
<body>
    <h1>Первоначальная настройка Планшета/Телефона</h1>
    <ul id="checklist">
        <li><label><input type="checkbox"> <span class="custom-checkbox"></span> Проверка обновления ONE UI на устройстве.</label></li>
        <li><label><input type="checkbox"> <span class="custom-checkbox"></span> Проверка включения тумблера "Определение даты и времени по геопозиции"</label></li>
        <li><label><input type="checkbox"> <span class="custom-checkbox"></span> Проверка работоспособности определения местоположения через приложение карт</label></li>
        <li><label><input type="checkbox"> <span class="custom-checkbox"></span> Проверка установлены ли приложения "MEDCONTROL", "Ассистент", "MEDCONTROL APP" на устройстве</label></li>
    </ul>
