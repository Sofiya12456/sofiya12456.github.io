
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Мой одностраничный сайт</title>
    <link rel="stylesheet" href="2.css"> <!-- Подключение стилей -->
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

    <!-- Раздел "Главная" -->
    <div id="home" class="section active">
        <h2>Добро пожаловать!</h2>
        <p>Это главная страница моего сайта.</p>
    </div>

    <!-- Раздел "Обо мне" -->
    <div id="about" class="section">
        <h2>Обо мне</h2>
        <p>Меня зовут София и я учусь на первом курсе в UIB - Университете Международного Бизнеса имени Кенжегали Сагадиева.</p>
    </div>

    <!-- Раздел "Навыки" -->
    <div id="skills" class="section">
        <h2>Навыки</h2>
        <p> </p>
    </div>

    <!-- Раздел "Изображение" -->
    <div id="image" class="section">
        <h2>Изображение</h2>
        <img src="image.jpg" type="image/jpg">
    </div>

    <!-- Раздел "Аудио" -->
    <div id="audio" class="section">
        <h2>Аудио</h2>
        <audio controls>
            <source src="audio.MP3" type="audio/mpeg">
        </audio>
    </div>

    <!-- Раздел "Видео" -->
    <div id="video" class="section">
        <h2>Видео</h2>
        <!-- Локальное видео -->
        <video controls>
            <source src="movie.mp4" type="video/mp4">
        </video>
    </div>

 <!-- Раздел "Карта" -->
    <div id="map" class="section">
        <h2>Карта</h2>
        <!-- Вставьте код карты Google Maps -->
        <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2906.439293581118!2d76.94742947615516!3d43.24221427112458!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x38836ee584fe528b%3A0xcb1413802f5325fb!2z0KPQvdC40LLQtdGA0YHQuNGC0LXRgiDQnNC10LbQtNGD0L3QsNGA0L7QtNC90L7Qs9C-INCR0LjQt9C90LXRgdCw!5e0!3m2!1sru!2skz!4v1743410760041!5m2!1sru!2skz" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
    </div>

    <!-- Раздел "Анимация" -->
    <div id="animation" class="section">
    <h2>Анимация</h2>
    <p class="animate">Этот текст плавно появляется при загрузке.</p>
</div>

    <script src="3.js"></script> <!-- Подключение JavaScript -->
</body>
</html>
