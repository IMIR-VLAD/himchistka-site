<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Химчистка мебели</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background-color: #f5f5f5;
      color: #333;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #004d40;
      color: white;
      padding: 20px;
      text-align: center;
    }
    nav {
      background: #00796b;
      padding: 10px;
      text-align: center;
    }
    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }
    main {
      padding: 30px;
      max-width: 900px;
      margin: auto;
    }
    section {
      margin-bottom: 40px;
    }
    footer {
      background-color: #004d40;
      color: white;
      text-align: center;
      padding: 15px;
    }
    .cta {
      background-color: #26a69a;
      padding: 20px;
      text-align: center;
      color: white;
      font-size: 1.2em;
      border-radius: 8px;
    }
    form {
      display: flex;
      flex-direction: column;
      gap: 15px;
      max-width: 500px;
      margin: 0 auto;
    }
    input, textarea, button {
      padding: 10px;
      border: 1px solid #ccc;
      border-radius: 5px;
      font-size: 1em;
    }
    button {
      background-color: #00796b;
      color: white;
      cursor: pointer;
      transition: background-color 0.3s;
    }
    button:hover {
      background-color: #004d40;
    }
    img {
      max-width: 100%;
      height: auto;
      border-radius: 10px;
      margin-top: 20px;
    }
    @media (max-width: 600px) {
      nav a {
        display: block;
        margin: 10px 0;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>Профессиональная химчистка мебели</h1>
    <p>Очистим любую мягкую мебель быстро, качественно и безопасно</p>
  </header>

  <nav>
    <a href="#about">О нас</a>
    <a href="#services">Услуги</a>
    <a href="#gallery">Галерея</a>
    <a href="#contact">Контакты</a>
  </nav>

  <main>
    <section id="about">
      <h2>О компании</h2>
      <p>Мы специализируемся на химчистке мягкой мебели более 10 лет. Используем только безопасные и сертифицированные средства. Работаем как с частными, так и с корпоративными клиентами.</p>
    </section>

    <section id="services">
      <h2>Наши услуги</h2>
      <ul>
        <li>Химчистка диванов, кресел, пуфов</li>
        <li>Удаление пятен, запахов, аллергенов</li>
        <li>Антибактериальная обработка</li>
        <li>Выезд на дом</li>
      </ul>
    </section>

    <section id="gallery">
      <h2>Примеры работ</h2>
      <img src="https://via.placeholder.com/800x400?text=До+и+После" alt="До и после химчистки">
    </section>

    <section class="cta">
      <p>Позвоните нам: <strong>+7 (999) 123-45-67</strong> или оставьте заявку на сайте</p>
    </section>

    <section id="contact">
      <h2>Контактная форма</h2>
      <form>
        <input type="text" placeholder="Ваше имя" required>
        <input type="tel" placeholder="Телефон" required>
        <textarea rows="4" placeholder="Комментарий или адрес"></textarea>
        <button type="submit">Отправить заявку</button>
      </form>

      <h3>Наши контакты</h3>
      <p>Email: info@himchistka.ru</p>
      <p>Адрес: г. Москва, ул. Чистая, 10</p>
      <p>График: Пн–Сб с 9:00 до 20:00</p>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 Химчистка мебели. Все права защищены.</p>
  </footer>
</body>
</html>
