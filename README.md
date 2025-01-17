<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Мир Танков</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #1c1c1c;
            color: #ffffff;
        }
        header {
            background-color: #333333;
            padding: 20px;
            text-align: center;
        }
        header h1 {
            color: #f0ad4e;
        }
        nav {
            background-color: #444444;
            display: flex;
            justify-content: center;
            padding: 10px 0;
        }
        nav a {
            color: #ffffff;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }
        nav a:hover {
            color: #f0ad4e;
        }
        main {
            padding: 20px;
        }
        section {
            margin-bottom: 40px;
            text-align: center;
        }
        section h2 {
            color: #f0ad4e;
            margin-bottom: 20px;
        }
        .tank-images img {
            width: 300px;
            height: auto;
            margin: 10px;
            border: 3px solid #f0ad4e;
        }
        footer {
            background-color: #333333;
            color: #999999;
            text-align: center;
            padding: 10px 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Мир Танков</h1>
        <p>Познакомьтесь с легендарной техникой!</p>
    </header>
    <nav>
        <a href="#wwii">Танки Второй мировой войны</a>
        <a href="#modern">Современные танки</a>
        <a href="#facts">Интересные факты</a>
    </nav>
    <main>
        <section id="wwii">
            <h2>Танки Второй мировой войны</h2>
            <p>Эти машины сыграли решающую роль в исторических сражениях. Среди них такие модели, как Т-34, «Тигр» и Sherman.</p>
            <div class="tank-images">
                <img src="https://upload.wikimedia.org/wikipedia/commons/8/86/T-34-85_latrun-1.jpg" alt="Т-34">
                <img src="https://upload.wikimedia.org/wikipedia/commons/e/ef/Tiger_I_late_production.jpg" alt="Танк Тигр">
                <img src="https://upload.wikimedia.org/wikipedia/commons/d/db/Sherman_tank.jpg" alt="Танк Sherman">
            </div>
        </section>
        <section id="modern">
            <h2>Современные танки</h2>
            <p>Современные танки оснащены передовыми технологиями и представляют вершину инженерной мысли. Среди них Leopard 2, M1 Abrams и Т-14 «Армата».</p>
            <div class="tank-images">
                <img src="https://upload.wikimedia.org/wikipedia/commons/3/3f/Leopard_2_A5_der_Bundeswehr.jpg" alt="Leopard 2">
                <img src="https://upload.wikimedia.org/wikipedia/commons/1/1e/M1_Abrams_main_battle_tank.jpg" alt="M1 Abrams">
                <img src="https://upload.wikimedia.org/wikipedia/commons/5/5e/T-14_Armata_Rehearsal_2015.jpg" alt="Т-14 Армата">
            </div>
        </section>
        <section id="facts">
            <h2>Интересные факты о танках</h2>
            <p>🔹 Первый танк был построен в 1915 году в Великобритании.<br>
               🔹 Т-34 признан одним из лучших танков Второй мировой войны.<br>
               🔹 Современные танки могут развивать скорость до 70 км/ч.
            </p>
        </section>
    </main>
    <footer>
        <p>&copy; 2025 Мир Танков. Все права защищены.</p>
    </footer>
</body>
</html>
