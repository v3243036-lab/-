# -
Всем привет, я начинающий веб - разработчик создаю простые но качественные сайты 
<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Фитнес тренер — Онлайн тренировки</title>

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }

    body {
      background: #f7f7f7;
      color: #222;
      line-height: 1.6;
    }

    header {
      background: linear-gradient(135deg, #111, #333);
      color: #fff;
      padding: 80px 20px;
      text-align: center;
    }

    header h1 {
      font-size: 36px;
      margin-bottom: 15px;
    }

    header p {
      font-size: 18px;
      margin-bottom: 30px;
    }

    .btns {
      display: flex;
      justify-content: center;
      gap: 15px;
      flex-wrap: wrap;
    }

    .btn {
      padding: 14px 26px;
      border-radius: 30px;
      text-decoration: none;
      color: #fff;
      font-weight: bold;
      transition: 0.3s;
    }

    .whatsapp {
      background: #25D366;
    }

    .telegram {
      background: #229ED9;
    }

    .btn:hover {
      opacity: 0.85;
    }

    section {
      padding: 60px 20px;
      max-width: 1100px;
      margin: auto;
    }

    section h2 {
      text-align: center;
      margin-bottom: 40px;
      font-size: 28px;
    }

    .services, .reviews {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }

    .card {
      background: #fff;
      padding: 25px;
      border-radius: 15px;
      box-shadow: 0 5px 15px rgba(0,0,0,0.08);
    }

    .card h3 {
      margin-bottom: 10px;
      color: #111;
    }

    .contacts {
      text-align: center;
    }

    .contacts p {
      margin-bottom: 20px;
      font-size: 18px;
    }

    footer {
      background: #111;
      color: #fff;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }

    @media (max-width: 600px) {
      header h1 {
        font-size: 28px;
      }

      header p {
        font-size: 16px;
      }
    }
  </style>
</head>
<body>

  <!-- ГЛАВНАЯ -->
  <header>
    <h1>Персональный фитнес-тренер</h1>
    <p>Онлайн и офлайн тренировки • Результат с первого месяца</p>

    <div class="btns">
      <a href="https://wa.me/77054941495" class="btn whatsapp">WhatsApp</a>
      <a href="https://t.me/konDima23" class="btn telegram">Telegram</a>
    </div>
  </header>

  <!-- УСЛУГИ -->
  <section>
    <h2>Услуги</h2>
    <div class="services">
      <div class="card">
        <h3>Персональные тренировки</h3>
        <p>Индивидуальный план тренировок под твои цели и уровень.</p>
      </div>

      <div class="card">
        <h3>Онлайн сопровождение</h3>
        <p>Тренировки и контроль через мессенджеры и видео.</p>
      </div>

      <div class="card">
        <h3>Питание</h3>
        <p>Простые и рабочие рекомендации по питанию.</p>
      </div>
    </div>
  </section>

  <!-- ОТЗЫВЫ -->
  <section>
    <h2>Отзывы</h2>
    <div class="reviews">
      <div class="card">
        <p>🔥 За 2 месяца минус 7 кг. Лучший тренер!</p>
        <strong>— Алексей</strong>
      </div>

      <div class="card">
        <p>💪 Тренировки понятные и эффективные.</p>
        <strong>— Марина</strong>
      </div>

      <div class="card">
        <p>✅ Отличный результат без травм.</p>
        <strong>— Данияр</strong>
      </div>
    </div>
  </section>

  <!-- КОНТАКТЫ -->
  <section class="contacts">
    <h2>Контакты</h2>
    <p>Свяжитесь со мной удобным способом</p>

    <div class="btns">
      <a href="https://wa.me/77000000000" class="btn whatsapp">Написать в WhatsApp</a>
      <a href="https://t.me/username" class="btn telegram">Написать в Telegram</a>
    </div>
  </section>

  <footer>
    <p>© 2025 Фитнес тренер. Все права защищены.</p>
  </footer>

</body>
</html>
