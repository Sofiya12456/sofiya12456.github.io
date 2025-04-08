
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Одностраничный сайт</title>
    <link rel="stylesheet" href="2.css">
</head>
<body>

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
        <p>Здесь будет размещено какое-то изображение.</p>
    </div>
    <div id="audio" class="section">
        <h2>Аудио</h2>
        <audio controls>
            <source src="audio.MP3" type="audio/mpeg">
            Ваш браузер не поддерживает аудио элемент.
        </audio>
    </div>

    <div id="video" class="section">
        <h2>Видео</h2>
        <video controls>
            <source src="movie.mp4" type="video/mp4">
            Ваш браузер не поддерживает видео элемент.
        </video>
        <div>
            <!-- https://www.youtube.com/watch?v=DsCEcVwhQxg -->
        </div>
    </div>

    <div id="map" class="section">
        <h2>Карта</h2>
        <div>
            <!-- Здесь должен быть вставлен код из Google Maps -->
        </div>
    </div>

    <div id="animation" class="section">
        <h2>Анимация</h2>
        <p class="animate">Пример текста с анимацией.</p>
    </div>

    <script src="3.js"></script>
</body>
</html>
