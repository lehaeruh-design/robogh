<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Мой мир Roblox</title>
    <style>
        /* Это CSS стили - они делают сайт красивым */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #1a1a2e, #16213e); /* Тёмный градиентный фон */
            color: #f0f0f0;
            line-height: 1.6;
            padding: 20px;
        }

        .container {
            max-width: 1100px;
            margin: 0 auto;
            background: rgba(255, 255, 255, 0.05);
            backdrop-filter: blur(10px);
            border-radius: 20px;
            padding: 30px;
            box-shadow: 0 8px 32px 0 rgba(31, 38, 135, 0.37);
            border: 1px solid rgba(255, 255, 255, 0.1);
        }

        header {
            text-align: center;
            border-bottom: 3px solid #ffd700;
            padding-bottom: 20px;
            margin-bottom: 30px;
        }

        h1 {
            font-size: 3em;
            color: #ffd700;
            text-shadow: 0 0 10px rgba(255, 215, 0, 0.5);
            margin-bottom: 10px;
        }

        h1 img {
            width: 50px;
            height: 50px;
            vertical-align: middle;
        }

        h2 {
            color: #4ecdc4;
            margin: 25px 0 15px 0;
            border-left: 5px solid #ffd700;
            padding-left: 15px;
        }

        .game-card {
            background: rgba(0, 0, 0, 0.3);
            border-radius: 15px;
            padding: 20px;
            margin-bottom: 20px;
            display: flex;
            gap: 20px;
            align-items: center;
            border: 1px solid rgba(255, 255, 255, 0.1);
            transition: transform 0.3s, box-shadow 0.3s;
        }

        .game-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 30px rgba(255, 215, 0, 0.2);
            border-color: #ffd700;
        }

        .game-img {
            width: 100px;
            height: 100px;
            background: linear-gradient(45deg, #ff6b6b, #4ecdc4);
            border-radius: 20px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 40px;
            color: white;
            flex-shrink: 0;
        }

        .game-info {
            flex-grow: 1;
        }

        .game-info h3 {
            color: #ffd700;
            margin-bottom: 8px;
        }

        .btn {
            display: inline-block;
            background: linear-gradient(45deg, #ffd700, #ffac33);
            color: #1a1a2e;
            padding: 12px 25px;
            text-decoration: none;
            border-radius: 50px;
            font-weight: bold;
            margin-top: 15px;
            transition: transform 0.3s, box-shadow 0.3s;
            border: none;
            cursor: pointer;
        }

        .btn:hover {
            transform: scale(1.05);
            box-shadow: 0 5px 20px rgba(255, 215, 0, 0.4);
        }

        .code-block {
            background: rgba(0, 0, 0, 0.5);
            border-left: 4px solid #ffd700;
            padding: 15px;
            border-radius: 10px;
            font-family: 'Courier New', monospace;
            margin: 15px 0;
            overflow-x: auto;
        }

        footer {
            text-align: center;
            margin-top: 40px;
            padding-top: 20px;
            border-top: 1px solid rgba(255, 255, 255, 0.1);
            color: rgba(255, 255, 255, 0.6);
        }

        @media (max-width: 600px) {
            .container {
                padding: 15px;
            }
            
            h1 {
                font-size: 2em;
            }
            
            .game-card {
                flex-direction: column;
                text-align: center;
            }
            
            .game-img {
                width: 80px;
                height: 80px;
                font-size: 30px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <!-- Заголовок с эмодзи Roblox -->
            <h1>
                <span>⚡</span> Мой Roblox Мир <span>⚡</span>
            </h1>
            <p>Всё о лучших играх, гайдах и новостях Roblox</p>
        </header>

        <!-- Секция: О себе -->
        <section>
            <h2>👋 Привет, я Roblox-путешественник!</h2>
            <p>
                Я обожаю играть в Roblox и создавать свои миры. На этом сайте я собираю 
                лучшие игры, делюсь секретами и полезными гайдами для новичков и профи.
                Присоединяйся к приключениям!
            </p>
            <a href="#" class="btn">Мой профиль в Roblox</a>
        </section>

        <!-- Секция: Популярные игры -->
        <section>
            <h2>🎮 Топ игр, в которые я играю</h2>
            
            <div class="game-card">
                <div class="game-img">🚀</div>
                <div class="game-info">
                    <h3>Jailbreak</h3>
                    <p>Стань преступником или полицейским, устраивай побеги и ограбления. Одна из самых популярных игр в Roblox!</p>
                    <a href="https://www.roblox.com/games/606849621/Jailbreak" target="_blank" class="btn" style="padding: 8px 15px; font-size: 0.9em;">Играть</a>
                </div>
            </div>

            <div class="game-card">
                <div class="game-img">⚔️</div>
                <div class="game-info">
                    <h3>Blox Fruits</h3>
                    <p>Стань мастером боевых искусств, ищи дьявольские фрукты и сражайся с врагами в этом мире One Piece.</p>
                    <a href="https://www.roblox.com/games/2753915549/Blox-Fruits" target="_blank" class="btn" style="padding: 8px 15px; font-size: 0.9em;">Играть</a>
                </div>
            </div>

            <div class="game-card">
                <div class="game-img">🏰</div>
                <div class="game-info">
                    <h3>Brookhaven RP</h3>
                    <p>Идеальная игра для ролевых игр. Купи дом, машину и живи своей виртуальной жизнью.</p>
                    <a href="https://www.roblox.com/games/4924922222/Brookhaven-RP" target="_blank" class="btn" style="padding: 8px 15px; font-size: 0.9em;">Играть</a>
                </div>
            </div>
        </section>

        <!-- Секция: Промокоды и гайды -->
        <section>
            <h2>🔥 Свежие промокоды (Февраль 2026)</h2>
            <div class="code-block">
                <p>🎁 ROBLOX2026 — 10 минут ускорителя</p>
                <p>🎁 GOLDDRAGON — Скидка на дракона</p>
                <p>🎁 SPEEDRUN — 1000 бонусов</p>
                <p><small>(Это примеры, вставьте сюда реальные коды)</small></p>
            </div>
            <a href="#" class="btn">Больше кодов</a>
        </section>

        <!-- Секция: Советы для новичков -->
        <section>
            <h2>💡 Гайд для новичков: как начать</h2>
            <ul style="margin-left: 20px;">
                <li>👕 <strong>Кастомизация:</strong> Начни с бесплатных вещей в магазине аватара.</li>
                <li>🤝 <strong>Друзья:</strong> Добавляй в друзья активных игроков — вместе веселее.</li>
                <li>🔒 <strong>Безопасность:</strong> Никогда не вводи свой пароль на сторонних сайтах!</li>
                <li>🎥 <strong>Обучение:</strong> Посмотри гайды на YouTube, чтобы быстрее освоиться.</li>
            </ul>
        </section>

        <!-- Подвал сайта -->
        <footer>
            <p>Сделано с ❤️ для фанатов Roblox | Это неофициальный фан-сайт</p>
            <p>📧 Связаться со мной: fan.roblox@example.com</p>
        </footer>
    </div>
</body>
</html>
