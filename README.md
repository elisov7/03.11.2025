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
            padding: 50px;
        }
        
        /* ИЗМЕНЕНИЕ: Первый блок - картинка слева, текст справа */
        .header-section {
            display: flex;
            align-items: center;
            gap: 30px;
            margin-bottom: 50px;
            background-color: #1e1e1e;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.7);
        }
        
        .header-image {
            width: 200px;
            height: auto;
            border-radius: 10px;
            flex-shrink: 0;
        }
        
        .header-text {
            flex: 1;
        }
        
        h1, h2 {
            color: #ffcc00;
            font-weight: bold;
        }
        
        h1 {
            font-size: 4em;
            margin-bottom: 20px;
            text-align: left;
        }
        
        h2 {
            font-size: 2.5em;
            margin-top: 20px;
            text-align: left;
        }

        /* Остальные стили остаются без изменений */
        p {
            font-size: 1.2em;
            line-height: 1.6;
            margin: 20px 0;
            color: #bbb;
        }
        .section {
            margin: 50px 0;
        }
        .plan-section {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 50px;
            background-color: #1e1e1e;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.7);
        }
        .plan-section .text {
            max-width: 45%;
            text-align: left;
        }
        .plan-section iframe {
            width: 100%;
            height: 500px;
            border: none;
            border-radius: 10px;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.6);
        }
        .card {
            background-color: #1e1e1e;
            padding: 25px;
            border-radius: 10px;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.7);
            margin-bottom: 30px;
        }
        .checklist {
            list-style-type: none;
            padding: 0;
            margin: 20px 0;
            font-size: 1.2em;
            text-align: left;
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
            top: 0;
            color: #ffcc00;
        }
        
        @media (max-width: 768px) {
            .header-section {
                flex-direction: column;
                text-align: center;
            }
            .header-image {
                width: 150px;
            }
            .plan-section {
                flex-direction: column;
            }
            .plan-section .text, .plan-section iframe {
                max-width: 100%;
                margin: 0 auto;
            }
            h1 {
                font-size: 2.5em;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- ИЗМЕНЕНИЕ: Новый блок заголовка -->
        <div class="header-section">
            <img src="https://cs1.livemaster.ru/storage/ac/2e/21e59096db881af7b7a111e10apq--kartiny-i-panno-poster-plakat-volk-s-uoll-strit-50h70sm.jpg" 
                 alt="Секретная операция" 
                 class="header-image">
            <div class="header-text">
                <h1>Операция «ДР 3.11»</h1>
                <h2>Совершенно секретно</h2>
            </div>
        </div>

        <!-- Остальной код без изменений -->
        <div class="section">
            <div class="plan-section">
                <div class="text">
                    <h2>План операции</h2>
                    <p>Ты думаешь, дни рождения — это просто торт и свечки? Заблуждение. Это система. И мы найдем способ ее обойти.</p>
                    <p>Вот план, который не одобрен ни одним государством.</p>
                    <p><strong>Объект:</strong> Предпраздничная нелегальная сходка (код: «Разминка»).</p>
                    <p><strong>Дата вторжения:</strong> 2 ноября.</p>
                    <p><strong>Время:</strong> 20:00.</p>
                    <p><strong>Место сбора:</strong> Моя штаб-квартира (г. Самара, ул. Новосоветская 36, кв.1).</p>
                </div>
                <iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/bp2WmMXQBjI" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen referrerpolicy="strict-origin-when-cross-origin"></iframe>
            </div>
        </div>

        <!-- Остальные секции без изменений -->
    </div>
</body>
</html>
