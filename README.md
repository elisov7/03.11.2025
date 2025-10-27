<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Операция «ДР 3.11»</title>
    <style>
        /* Весь ваш CSS стиль здесь */
        body { font-family: 'Arial', sans-serif; margin: 0; padding: 0; background-color: #121212; color: white; overflow-x: hidden; }
        .container { max-width: 1200px; margin: 0 auto; padding: 50px; }
        h1, h2 { color: #ffcc00; font-weight: bold; }
        h1 { font-size: 4em; margin-bottom: 20px; text-align: left; }
        h2 { font-size: 2.5em; margin-top: 20px; text-align: left; }
        p { font-size: 1.2em; line-height: 1.6; margin: 20px 0; color: #bbb; }
        .important { color: #ff3333; font-weight: bold; }
        .btn { background-color: #ffcc00; color: black; padding: 15px 30px; font-size: 1.3em; border: none; border-radius: 5px; cursor: pointer; transition: background-color 0.3s; display: block; width: 250px; margin: 40px auto; }
        .btn:hover { background-color: #e6b800; }
        .section { margin: 50px 0; }
        .plan-section { display: flex; justify-content: space-between; align-items: center; margin-bottom: 50px; background-color: #1e1e1e; padding: 30px; border-radius: 10px; box-shadow: 0 0 15px rgba(0, 0, 0, 0.7); }
        .plan-section .text { max-width: 45%; text-align: left; }
        .plan-section .text p { font-size: 1.1em; color: #ccc; }
        .plan-section iframe { width: 100%; height: 500px; border: none; border-radius: 10px; box-shadow: 0 0 15px rgba(0, 0, 0, 0.6); }
        .card { background-color: #1e1e1e; padding: 25px; border-radius: 10px; box-shadow: 0 0 15px rgba(0, 0, 0, 0.7); margin-bottom: 30px; transition: transform 0.3s ease; }
        .card:hover { transform: scale(1.05); }
        .card h3 { font-size: 2em; color: #ffcc00; margin-bottom: 15px; }
        .checklist { list-style-type: none; padding: 0; margin: 20px 0; font-size: 1.2em; text-align: left; }
        .checklist li { margin: 10px 0; padding-left: 25px; position: relative; }
        .checklist li::before { content: "✔"; position: absolute; left: 0; top: 0; color: #ffcc00; }
        .footer { background-color: #1e1e1e; padding: 30px; border-radius: 10px; box-shadow: 0 0 15px rgba(0, 0, 0, 0.7); margin-top: 50px; }
        .footer p { font-size: 1.2em; color: #bbb; text-align: center; }
        .footer .btn { background-color: #e6b800; margin: 20px auto; display: block; }
        img { max-width: 40%; height: auto; border-radius: 10px; }
        @media (max-width: 768px) { 
            .plan-section { flex-direction: column; text-align: center; } 
            .plan-section .text, .plan-section iframe { max-width: 100%; margin: 0 auto; } 
            h1 { font-size: 2.5em; } 
            p, .checklist li { font-size: 1em; } 
        }
    </style>
</head>
<body>
    <!-- Ваша HTML структура -->
    <div class="container">
        <!-- Раздел с картинкой слева и текстом справа -->
        <div class="plan-section">
            <img src="https://cs1.livemaster.ru/storage/ac/2e/21e59096db881af7b7a111e10apq--kartiny-i-panno-poster-plakat-volk-s-uoll-strit-50h70sm.jpg" alt="Секретная операция">
            <div class="text">
                <h1>Операция «ДР 3.11»</h1>
                <h2>Совершенно секретно</h2>
            </div>
        </div>
        
        <!-- Остальная часть вашего HTML кода -->
        <!-- ... -->
    </div>
</body>
</html>
