<!DOCTYPE html>
<html lang="bg">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ZoonX Магазин</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <!-- Хедър с лого -->
    <header>
        <div class="logo">
            <img src="zoonx-logo.png" alt="ZoonX Лого"> <!-- Тук постави логото на ZoonX -->
        </div>
        <h1>Добре дошли в ZoonX</h1>
        <p>Иновации и качество на най-добри цени</p>
        <div class="cart">
            <button id="cartButton">Кошница (0)</button>
        </div>
    </header>

    <!-- Описание на бранда ZoonX -->
    <section class="about">
        <h2>За нас</h2>
        <p>ZoonX е лидер в иновациите и качествените продукти. Ние предлагаме най-новите технологични решения, които да подобрят живота ви.</p>
    </section>

    <!-- Продуктова галерия -->
    <section class="products">
        <div class="product">
            <img src="product1.jpg" alt="Продукт 1">
            <h3>Продукт 1</h3>
            <p>Цена: 50 лв</p>
            <button class="addToCart" data-product="1" data-price="50">Добави в кошницата</button>
        </div>
        <div class="product">
            <img src="product2.jpg" alt="Продукт 2">
            <h3>Продукт 2</h3>
            <p>Цена: 30 лв</p>
            <button class="addToCart" data-product="2" data-price="30">Добави в кошницата</button>
        </div>
        <!-- Може да добавиш още продукти тук -->
    </section>

    <!-- Модален прозорец за кошницата -->
    <div id="cartModal" class="cartModal">
        <div class="cartModalContent">
            <h2>Твоята кошница</h2>
            <ul id="cartItems"></ul>
            <p id="totalPrice">Обща сума: 0 лв</p>
            <button id="checkoutButton">Поръчай сега</button>
            <button id="closeCart">Затвори</button>
        </div>
    </div>

    <script src="script.js"></script>
</body>
</html>

