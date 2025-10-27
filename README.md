<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Операция «ДР 3.11»</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #121212;
            color: white;
            overflow-x: hidden;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        h1, h2 {
            color: #ffcc00;
            font-weight: bold;
        }
        h1 {
            font-size: 2.5em;
            margin-bottom: 15px;
        }
        h2 {
            font-size: 1.8em;
            margin-top: 15px;
        }
        p {
            font-size: 1.1em;
            margin: 15px 0;
            color: #bbb;
        }
        .plan-section {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 30px;
            background-color: #1e1e1e;
            padding: 20px;
            border-radius: 10px;
            flex-wrap: wrap;
            gap: 20px;
        }
        .plan-section .text {
            flex: 1;
            min-width: 300px;
        }
        .first-image {
            max-width: 200px;
            width: 100%;
            height: auto;
            border-radius: 10px;
        }
        .card {
            background-color: #1e1e1e;
            padding: 20px;
            border-radius: 10px;
            margin-bottom: 20px;
        }
        .red-text {
            color: #ff3333;
            font-weight: bold;
        }
        .checklist {
            list-style-type: none;
            padding: 0;
        }
        .checklist li {
            margin: 10px 0;
            padding-left: 25px;
            position: relative;
        }
        .checklist li::before {
            content: "✔";
            position: absolute;
            left: 0;
            color: #ffcc00;
        }
        @media (max-width: 768px) {
            .plan-section {
                flex-direction: column;
                text-align: center;
            }
            .first-image {
                max-width: 150px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- Заголовок с картинкой -->
        <div class="plan-section">
            <img src="https://via.placeholder.com/200x300/333333/ffffff?text=🐺+ОПЕРАЦИЯ" 
                 alt="Секретная операция" 
                 class="first-image">
            <div class="text">
                <h1>Операция «ДР 3.11»</h1>
                <h2>Совершенно секретно</h2>
            </div>
        </div>

        <!-- План операции -->
        <div class="plan-section">
            <div class="text">
                <h2>План операции</h2>
                <p>Ты думаешь, дни рождения — это просто торт и свечки? Заблуждение. Это система. И мы найдем способ ее обойти.</p>
                <p><strong>Объект:</strong> Предпраздничная нелегальная сходка (код: «Разминка»).</p>
                <p><strong>Дата вторжения:</strong> 2 ноября.</p>
                <p><strong>Время:</strong> 20:00.</p>
                <p><strong>Место сбора:</strong> Моя штаб-квартира (г. Самара, ул. Новосоветская 36, кв.1).</p>
            </div>
            <div style="flex: 1; min-width: 300px; background: #2a2a2a; padding: 20px; border-radius: 10px; text-align: center;">
                <p>🎬 Видео инструкция</p>
                <p><em>Видео будет доступно на месте</em></p>
            </div>
        </div>

        <!-- Финансирование -->
        <div class="card">
            <h3>Финансирование операции</h3>
            <p class="red-text"><strong>На явке (дом):</strong> Расходы покрываю я. Это фонд моего личного спокойствия.</p>
            <p class="red-text"><strong>На точке X (бар):</strong> Я обеспечиваю один шот на брата. Это не доброта — это тактика. Дальше — партизанская экономика, каждый за себя. Welcome to the real world.</p>
        </div>

        <!-- Чек-лист -->
        <div class="card">
            <h3>Твой чек-лист на выживание</h3>
            <ul class="checklist">
                <li class="red-text">Паспорт. Без него ты никто. Тебя сотрут на входе.</li>
                <li class="red-text">Деньги. Ликвидность = свобода действий. Не подведи группу.</li>
            </ul>
        </div>

        <!-- Контакты -->
        <div class="card">
            <h3>Способ связи</h3>
            <p>Подтверди явку. От количества тел зависит, сколько мне закупать ресурсов для этой авантюры.</p>
            <p>Дай знать мне в Telegram (@elisov_7) или ВКонтакте.</p>
        </div>

        <div class="card">
            <p><strong>[Кодовое имя: Именинник]</strong></p>
        </div>
    </div>
</body>
</html>
