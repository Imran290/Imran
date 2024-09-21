# Imran <!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <title>Мой Новый Сайт</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

<header>
    <div class="container">
        <h1>Мой Новый Сайт</h1>
        <nav>
            <ul>
                <li><a href="#home">Главная</a></li>
                <li><a href="#about">О нас</a></li>
                <li><a href="#services">Услуги</a></li>
                <li><a href="#contact">Контакты</a></li>
            </ul>
        </nav>
    </div>
</header>

<section id="home" class="banner">
    <div class="container">
        <h2>Добро пожаловать!</h2>
        <p>Мы предлагаем лучшие решения для вашего бизнеса.</p>
        <button onclick="learnMore()">Узнать больше</button>
    </div>
</section>

<section id="about" class="content">
    <div class="container">
        <h2>О нас</h2>
        <p>Здесь вы можете рассказать о своей компании, ее истории и ценностях.</p>
    </div>
</section>

<section id="services" class="content">
    <div class="container">
        <h2>Наши Услуги</h2>
        <div class="services">
            <div class="service">
                <h3>Услуга 1</h3>
                <p>Описание услуги 1.</p>
            </div>
            <div class="service">
                <h3>Услуга 2</h3>
                <p>Описание услуги 2.</p>
            </div>
            <div class="service">
                <h3>Услуга 3</h3>
                <p>Описание услуги 3.</p>
            </div>
        </div>
    </div>
</section>

<section id="contact" class="content">
    <div class="container">
        <h2>Контакты</h2>
        <form id="contactForm" onsubmit="submitForm(event)">
            <input type="text" name="name" placeholder="Ваше имя" required>
            <input type="email" name="email" placeholder="Ваш email" required>
            <textarea name="message" placeholder="Ваше сообщение" required></textarea>
            <button type="submit">Отправить</button>
        </form>
    </div>
</section>

<footer>
    <div class="container">
        <p>© 2024 Мой Новый Сайт. Все права защищены.</p>
    </div>
</footer>

<script src="script.js"></script>
</body>
</html>
