# dubai
nu
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Недвижимость в Дубае</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Главный экран -->
    <section id="hero">
        <h1>Недвижимость в Дубае: Ваш ключ к роскошной жизни</h1>
        <p>Эксклюзивные предложения от ведущих застройщиков</p>
        <button>Подобрать квартиру</button>
        <button>Рассчитать ипотеку</button>
    </section>

    <!-- Вкладка товаров -->
    <section id="catalog">
        <h2>Наши предложения</h2>
        <!-- Фильтры и карточки товаров -->
    </section>

    <!-- Преимущества -->
    <section id="benefits">
        <h2>Почему выбирать нас?</h2>
        <div class="benefit">
            <h3>Опыт и надежность</h3>
            <p>Мы работаем на рынке недвижимости Дубая более 10 лет.</p>
        </div>
        <div class="benefit">
            <h3>Индивидуальный подход</h3>
            <p>Мы подбираем жилье, исходя из ваших потребностей и бюджета.</p>
        </div>
        <!-- Другие преимущества -->
    </section>

    <!-- Калькулятор ипотеки -->
    <section id="mortgage-calculator">
        <h2>Рассчитайте ипотеку</h2>
        <form>
            <label for="property-price">Стоимость недвижимости</label>
            <input type="number" id="property-price" name="property-price">

            <label for="down-payment">Первоначальный взнос</label>
            <input type="number" id="down-payment" name="down-payment">

            <label for="loan-term">Срок кредита</label>
            <input type="number" id="loan-term" name="loan-term">

            <label for="interest-rate">Процентная ставка</label>
            <input type="number" id="interest-rate" name="interest-rate">

            <button type="submit">Рассчитать</button>
        </form>
        <div id="mortgage-result"></div>
    </section>

    <!-- Отзывы -->
    <section id="testimonials">
        <h2>Отзывы наших клиентов</h2>
        <!-- Слайдер с отзывами -->
    </section>

    <!-- Контакты с Google Maps -->
    <section id="contact">
        <h2>Свяжитесь с нами</h2>
        <form>
            <label for="name">Имя</label>
            <input type="text" id="name" name="name">

            <label for="email">Email</label>
            <input type="email" id="email" name="email">

            <label for="phone">Телефон</label>
            <input type="tel" id="phone" name="phone">

            <label for="message">Сообщение</label>
            <textarea id="message" name="message"></textarea>

            <button type="submit">Отправить</button>
        </form>
        <div id="map"></div>
        <p>Адрес: Dubai, UAE</p>
        <p>Время работы: 9:00 - 18:00</p>
    </section>

    <!-- Подключение Google Maps -->
    <script src="https://maps.googleapis.com/maps/api/js?key=YOUR_API_KEY&callback=initMap" async defer></script>
    <script src="scripts.js"></script>
</body>
</html>
