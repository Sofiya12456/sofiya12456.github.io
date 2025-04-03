<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Одностраничный сайт</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <!-- Навигационное меню -->
    <nav>
        <ul>
            <li><a href="#home" class="nav-link">Главная</a></li>
            <li><a href="#about" class="nav-link">Обо мне</a></li>
            <li><a href="#skills" class="nav-link">Навыки</a></li>
            <li><a href="#image" class="nav-link">Изображение</a></li>
            <li><a href="#audio" class="nav-link">Аудио</a></li>
            <li><a href="#video" class="nav-link">Видео</a></li>
            <li><a href="#map" class="nav-link">Карта</a></li>
            <li><a href="#animation" class="nav-link">Анимация</a></li>
        </ul>
    </nav>

    <!-- Разделы сайта -->
    <div id="home" class="section active">
        <h2>Добро пожаловать!</h2>
        <p>Это главная страница нашего одностраничного сайта.</p>
    </div>

    <div id="about" class="section">
        <h2>Обо мне</h2>
        <p>Здесь вы можете узнать немного о моем профиле.</p>
    </div>

    <div id="skills" class="section">
        <h2>Навыки</h2>
        <p>Этот раздел посвящен моим навыкам и умениям.</p>
    </div>

    <div id="image" class="section">
        <h2>Изображение</h2>
        <p>Здесь будет размещено изображение.</p>
        <img src="image.jpg" alt="Пример изображения">
    </div>

    <div id="audio" class="section">
        <h2>Аудио</h2>
        <audio controls>
            <source src="audio.MP3" type="audio/mpeg">
            Ваш браузер не поддерживает аудио.
        </audio>
    </div>

    <div id="video" class="section">
        <h2>Видео</h2>
        <video controls width="600">
            <source src="video/sample.mp4" type="video/mp4">
            Ваш браузер не поддерживает видео.
        </video>
        <h3>Видео с YouTube</h3>
        <iframe width="600" height="315" src="[https://www.youtube.com/embed/dQw4w9WgXcQ](https://youtu.be/xAwB9lQnxAY?si=FBYQlMAHVi9NSn3-)" 
        frameborder="0" allowfullscreen></iframe>
    </div>

    <div id="map" class="section">
        <h2>Карта</h2>
        <iframe 
            src="[https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d233667.8223921103!2d-118.69193052620744!3d34.02016129990307!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x80c2b0c4d5e8d14d%3A0x70beefdb1a3ad6f1!2sLos%20Angeles%2C%20CA%2C%20USA!5e0!3m2!1sen!2sru!4v1615675649304!5m2!1sen!2sru](https://maps.app.goo.gl/hfCqixPkPALQNExZ7)" 
            width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy">
        </iframe>
    </div>

    <div id="animation" class="section">
        <h2>Анимация</h2>
        <p class="animate">Пример текста с анимацией.</p>
    </div>

    <script src="script.js"></script>
</body>
</html>
