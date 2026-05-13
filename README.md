
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ресторан "Вкусно и Сладко"</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #fafafa;
            color: #333;
        }
        header {
            background-color: #8B0000;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #a52a2a;
        }
        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            transition: background 0.3s;
        }
        nav a:hover {
            background-color: #7b1f1f;
        }
        .hero {
            background: url('https://picsum.photos/1200/500?food') center/cover no-repeat;
            height: 400px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-size: 2em;
            text-shadow: 2px 2px 5px rgba(0,0,0,0.7);
        }
        .menu {
            padding: 40px 20px;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }
        .dish {
            background: white;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 2px 8px rgba(0,0,0,0.1);
            transition: transform 0.3s;
        }
        .dish:hover {
            transform: scale(1.03);
        }
        .dish img {
            width: 100%;
            height: 180px;
            object-fit: cover;
        }
        .dish h3 {
            margin: 10px;
        }
        .dish p {
            margin: 0 10px 10px;
            color: #666;
        }
        footer {
            background-color: #8B0000;
            color: white;
            text-align: center;
            padding: 15px;
            margin-top: 20px;
        }
    </style>
</head>
<body>

<header>
    <h1>Ресторан "Вкусно и Сладко"</h1>
    <p>Лучшие блюда города</p>
</header>

<nav>
    <a href="#menu">Меню</a>
    <a href="#about">О нас</a>
    <a href="#contact">Контакты</a>
</nav>

<section class="hero">
    Добро пожаловать!
</section>

<section id="menu" class="menu">
    <div class="dish">
        <img src="karbonara.jpg" alt="Блюдо 1">
        <h3>Паста Карбонара</h3>
        <p>Классическая итальянская паста с беконом и сливочным соусом.</p>
    </div>
    <div class="dish">
        <img src="steyk.jpg" alt="Блюдо 2">
        <h3>Стейк Рибай</h3>
        <p>Сочный стейк средней прожарки с овощами гриль.</p>
    </div>
    <div class="dish">
        <img src="cesar.jpg" alt="Блюдо 3">
        <h3>Салат Цезарь</h3>
        <p>Хрустящий салат с курицей, сухариками и соусом Цезарь.</p>
    </div>
</section>

<section id="about" style="padding: 40px 20px;">
    <h2>О нас</h2>
    <p>Наш ресторан предлагает только свежие и качественные продукты. Мы готовим с любовью и заботой о каждом госте.</p>
</section>

<section id="contact" style="padding: 40px 20px;">
    <h2>Контакты</h2>
    <p>Адрес: ул. Примерная, 10</p>
    <p>Телефон: +7 (777) 123-45-67</p>
</section>

<footer>
    &copy; 2026 Ресторан "Вкусно и Сладко". Все права защищены.
</footer>

</body>
</html>
