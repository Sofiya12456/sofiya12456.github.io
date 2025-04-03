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
            <source src="audio.mp3" type="audio/mpeg">
            Ваш браузер не поддерживает аудио.
        </audio>
    </div>

    <div id="video" class="section">
        <h2>Видео</h2>
        <iframe width="600" height="315" src="https://www.youtube.com/embed/xAwB9lQnxAY" 
        frameborder="0" allowfullscreen></iframe>
    </div>

    <div id="map" class="section">
        <h2>Карта</h2>
        <iframe 
            src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d771.5805364515563!2d76.90948096967547!3d43.235194075155166!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x38836ed0664b1c3f%3A0x974c48f4f2f35112!2z0JrRg9C30L3QtdGB0LrQsNGPINGD0LsuLCAz0JAsINCQ0LvQtdC60YHRgiAxMDAwMDA!5e0!3m2!1sru!2skz!4v1712145600000" 
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
