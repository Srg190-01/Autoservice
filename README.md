# Autoservice<!DOCTYPE html>
<html lang="uk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Автосервіс "Швидкий ремонт"</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
        }
        header {
            background-color: #2c3e50;
            color: white;
            padding: 20px 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #34495e;
            padding: 10px 0;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            padding: 5px 10px;
        }
        nav a:hover {
            background-color: #2c3e50;
            border-radius: 5px;
        }
        .hero {
            text-align: center;
            padding: 50px 20px;
            background-color: #ecf0f1;
        }
        .services {
            display: flex;
            justify-content: center;
            gap: 20px;
            padding: 20px;
            flex-wrap: wrap;
        }
        .service {
            background-color: white;
            border: 1px solid #ddd;
            border-radius: 5px;
            padding: 20px;
            width: 250px;
            text-align: center;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        footer {
            text-align: center;
            background-color: #2c3e50;
            color: white;
            padding: 10px 0;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Ласкаво просимо до автосервісу "Швидкий ремонт"</h1>
        <p>Ваш надійний партнер в обслуговуванні автомобілів</p>
    </header>

    <nav>
        <a href="#about">Про нас</a>
        <a href="#services">Послуги</a>
        <a href="#contact">Контакти</a>
    </nav>

    <section class="hero">
        <h2>Якісний ремонт та обслуговування вашого авто</h2>
        <p>Ми гарантуємо швидкість, якість та доступні ціни</p>
    </section>

    <section id="services" class="services">
        <div class="service">
            <h3>Заміна масла</h3>
            <p>Швидко та професійно замінимо масло у вашому авто.</p>
        </div>
        <div class="service">
            <h3>Діагностика</h3>
            <p>Комп'ютерна діагностика всіх систем автомобіля.</p>
        </div>
        <div class="service">
            <h3>Шиномонтаж</h3>
            <p>Швидкий та якісний шиномонтаж.</p>
        </div>
        <div class="service">
            <h3>Ремонт двигуна</h3>
            <p>Ремонт будь-якої складності.</p>
        </div>
    </section>

    <footer>
        <p>&copy; 2024 Автосервіс "Швидкий ремонт". Усі права захищено.</p>
        <p>Телефон: +38 (050) 123-45-67 | Email: info@autoservice.ua</p>
    </footer>
</body>
</html>
