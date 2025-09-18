
📁 modulnye-doma-site/
├── index.html          → ты его скачиваешь из моего ZIP (я пришлю ниже)
├── 📁 images/          → сюда скопируешь ВСЕ свои фото (57.jpg, 344.jpg и т.д.)
└── 📁 videos/          → сюда скопируешь ВСЕ свои видео (1.mp4, 33.mp4 и т.д.)
<!doctype html>
<html lang="ru">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1,maximum-scale=1" />
  <meta name="description" content="Модульные дома и бани в Новочебоксарске под ключ за 7 дней. Цены от 850 000 ₽. Бесплатный расчёт и каталог по WhatsApp. Реальные фото и видео объектов.">
  <title>Модульные дома и бани в Новочебоксарске</title>
  <!-- Yandex.Metrika counter -->
  <script type="text/javascript" >
     (function(m,e,t,r,i,k,a){m[i]=m[i]||function(){(m[i].a=m[i].a||[]).push(arguments)};
     m[i].l=1*new Date();
     for (var j = 0; j < document.scripts.length; j++) {if (document.scripts[j].src === r) { return; }}
     k=e.createElement(t),a=e.getElementsByTagName(t)[0],k.async=1,k.src=r,a.parentNode.insertBefore(k,a)})
     (window, document, "script", "https://mc.yandex.ru/metrika/tag.js", "ym");

     ym(99999999, "init", {
          clickmap:true,
          trackLinks:true,
          accurateTrackBounce:true,
          webvisor:true
     });
  </script>
  <noscript><div><img src="https://mc.yandex.ru/watch/99999999" style="position:absolute; left:-9999px;" alt="" /></div></noscript>
  <!-- /Yandex.Metrika counter -->
  <style>
    :root{--accent:#2ea44f;--muted:#6b6b6b;--wood:#d9b38c}
    body{font-family:Inter,system-ui,Arial,sans-serif;margin:0;color:#222}
    a{color:inherit}
    header{background:#f5f5f5;padding:18px 20px;display:flex;align-items:center;justify-content:space-between;gap:12px}
    .brand{display:flex;align-items:center;gap:12px}
    .brand .logo{width:48px;height:48px;border-radius:8px;background:linear-gradient(135deg,var(--wood),#b8865b)}
    .hero{background-image:url('/images/banja_15_ext.jpg');background-size:cover;background-position:center;padding:56px 20px;color:#fff}
    .hero-inner{max-width:1100px;margin:0 auto;display:flex;gap:24px;align-items:center}
    .hero h1{font-size:28px;margin:0 0 8px}
    .hero p{margin:0 0 16px;color:rgba(255,255,255,0.9)}
    .btn{background:var(--accent);color:#fff;padding:12px 18px;border-radius:8px;text-decoration:none;font-weight:600}
    .container{max-width:1100px;margin:28px auto;padding:0 20px}
    .grid{display:grid;grid-template-columns:repeat(3,1fr);gap:18px}
    .card{background:#fff;border-radius:10px;box-shadow:0 6px 18px rgba(15,15,15,0.06);overflow:hidden}
    .card img{width:100%;height:200px;object-fit:cover;display:block}
    .card .body{padding:12px}
    .row{display:flex;gap:18px;align-items:center}
    .utp{display:flex;gap:12px;flex-wrap:wrap;margin:18px 0}
    .utp .item{background:#fff;padding:12px;border-radius:8px;min-width:150px;box-shadow:0 4px 12px rgba(0,0,0,0.04)}
    .gallery{display:grid;grid-template-columns:2fr 1fr;gap:12px}
    .gallery img{width:100%;height:100%;object-fit:cover;border-radius:8px}
    .video-wrap{border-radius:8px;overflow:hidden}
    form{background:#fff;padding:16px;border-radius:10px;box-shadow:0 6px 18px rgba(15,15,15,0.06)}
    label{display:block;font-size:14px;color:var(--muted);margin-bottom:6px}
    input,select{width:100%;padding:10px;border-radius:8px;border:1px solid #e3e3e3;margin-bottom:10px}
    footer{background:#fafafa;padding:18px 20px;color:var(--muted);text-align:center;margin-top:28px}
    @media(max-width:900px){.grid{grid-template-columns:1fr}.gallery{grid-template-columns:1fr}.hero-inner{flex-direction:column;align-items:flex-start}.card img{height:180px}}
  </style>
</head>
<body>
  <header>
    <div class="brand">
      <div class="logo" aria-hidden="true"></div>
      <div>
        <div style="font-weight:700">Модульные дома &amp; бани</div>
        <div style="font-size:12px;color:var(--muted)">Новочебоксарск · Чувашия</div>
      </div>
    </div>
    <div style="display:flex;gap:12px;align-items:center">
      <a class="btn" href="tel:+79196677372">Позвонить</a>
      <a class="btn" style="background:#0f9d58" href="https://wa.me/79196677372?text=Здравствуйте!%20Хочу%20получить%20каталог%20и%20цену">WhatsApp</a>
    </div>
  </header>

  <section class="hero">
    <div class="hero-inner">
      <div style="flex:1">
        <h1>Модульные дома и бани в Новочебоксарске — под ключ за 7 дней</h1>
        <p>Готовые проекты с утеплением, гарантией и доставкой по Чувашской Республике. Цены от 850 000 ₽ — ориентировочно. Некоторые изображения на сайте являются демонстрационными визуализациями (ландшафт, купели, бассейны) и приведены для примера опций. Все дополнительные опции предоставляются отдельно и согласуются индивидуально.</p>
        <a class="btn" href="#form">Получить каталог и цены</a>
      </div>
      <div style="width:360px">
        <form id="form" onsubmit="submitForm(event)">
          <label>Ваше имя</label>
          <input id="name" type="text" placeholder="Иван" required>
          <label>Телефон</label>
          <input id="phone" type="tel" placeholder="+7 (___) ___-__-__" required>
          <label>Что хотите?</label>
          <select id="projectType">
            <option value="banja">Баня (купель)</option>
            <option value="dom">Дом-баня с террасой</option>
            <option value="dacha">Компактный дом для дачи</option>
          </select>
          <button class="btn" style="width:100%" type="submit">Получить каталог в WhatsApp</button>
          <p style="font-size:13px;color:var(--muted);margin-top:8px">Мы свяжемся с вами в рабочее время. Данные не передаются третьим лицам.</p>
        </form>
      </div>
    </div>
  </section>

  <main class="container">
    <section>
      <h2>Почему выбирают нас</h2>
      <div class="utp">
        <div class="item">⚡ Монтаж 3–7 дней</div>
        <div class="item">❄ Утепление до −30°С</div>
        <div class="item">🔥 Печь в комплекте (для бань)</div>
        <div class="item">🏗 Утеплённый каркас дома</div>
        <div class="item">📦 Доставка — сейчас скидка 10%</div>
        <div class="item">🛠 Винтовой фундамент — доп. услуга</div>
        <div class="item">💧 Купель — по запросу; бассейн — НЕ предоставляем</div>
        <div class="item">✅ Гарантия</div>
        <div class="item">💰 Цены от 850 000 ₽</div>
      </div>
    </section>

    <div style="background:#fff;padding:12px;border-radius:8px;margin-bottom:12px;color:#555"><strong>Важно:</strong> Часть изображений на сайте — демонстрационные визуализации (ландшафт, купели, бассейны) созданные для примера. Мы не включаем купели/бассейны в базовую комплектацию — эти опции доступны при согласовании и расчёте стоимости. Уточняйте наличие и условия при заказе.<div style="margin-top:10px;padding-top:10px;border-top:1px dashed #eee"><strong>Акции и спецпредложения:</strong><ul style="margin:8px 0 0 20px;color:#444"><li>Скидка 10% на доставку при заказе в текущем месяце.</li><li>Бесплатная базовая проектировка при заключении договора.</li><li>Скидка 10% на монтаж для первых 3 клиентов в месяце.</li><li>При покупке модульной бани — 5 дубовых веников в подарок на первый пар.</li></ul></div></div>

    <section style="margin-top:6px">
      <h2>Наши проекты</h2>
      <div class="grid">
        <div class="card">
          <img src="/images/banja_15_ext.jpg" alt="Модульная баня 15 м² с уличной топкой и ветражным окном, реальное фото, Новочебоксарск">
          <div class="body">
            <strong>Баня</strong>
            <p style="color:var(--muted);margin:8px 0">От 850 000 ₽ • 15 м² • монтаж 3–7 дней • утепление, печь в комплекте, уличная топка<br><em style="color:#888">(На фото — реальный объект, Новочебоксарск, 2025)</em></p>
            <a class="btn" href="#form">Записаться на просмотр</a>
          </div>
        </div>

        <div class="card">
          <img src="/images/banja_warmfloor_ext.jpg" alt="Баня с тёплым полом и террасой, реальное фото, Новочебоксарск">
          <div class="body">
            <strong>Баня с террасой и тёплыми полами</strong>
            <p style="color:var(--muted);margin:8px 0">От 1 400 000 ₽ • тёплые полы • индивидуальная отделка возможна<br><em style="color:#888">(На фото — реальный объект, Новочебоксарск, 2025)</em></p>
            <a class="btn" href="#form">Узнать цену</a>
          </div>
        </div>

        <div class="card">
          <img src="/images/dom_30_ext.jpg" alt="Компактный модульный дом 30 м² с террасой, реальное фото, Новочебоксарск">
          <div class="body">
            <strong>Компактный дом для дачи</strong>
            <p style="color:var(--muted);margin:8px 0">От 2 200 000 ₽ • 30 m² • быстрая сборка • готовая отделка<br><em style="color:#888">(На фото — реальный объект, Новочебоксарск, 2025)</em></p>
            <a class="btn" href="#form">Получить расчёт</a>
          </div>
        </div>
      </div>
    </section>

    <section style="margin-top:18px">
      <h2>Как может выглядеть ваш участок</h2>
      <div class="grid">
        <div class="card">
          <img src="/images/concept_1.jpg" alt="Концепт ландшафтного дизайна: баня с бочкой-сауной и шезлонгом (AI-визуализация)">
          <div class="body">
            <p style="color:var(--muted);margin:8px 0"><em>Концепт: баня + бочка-сауна + зона отдыха</em></p>
          </div>
        </div>
        <div class="card">
          <img src="/images/concept_2.jpg" alt="Концепт ландшафтного дизайна: дом с бассейном и печью (AI-визуализация)">
          <div class="body">
            <p style="color:var(--muted);margin:8px 0"><em>Концепт: дом + бассейн + зона барбекю</em></p>
          </div>
        </div>
        <div class="card">
          <img src="/images/concept_3.jpg" alt="Концепт ландшафтного дизайна: дом с террасой и цветами (AI-визуализация)">
          <div class="body">
            <p style="color:var(--muted);margin:8px 0"><em>Концепт: дом + уютная терраса + сад</em></p>
          </div>
        </div>
      </div>
      <p style="text-align:center;margin-top:12px;color:var(--muted)">Мы бесплатно подготовим для вас индивидуальный концепт ландшафтного дизайна — чтобы вы сразу представляли, как будет выглядеть ваша баня или дом на участке.</p>
    </section>

    <section style="margin-top:18px">
      <h2>Быстрый калькулятор</h2>
      <div style="display:grid;grid-template-columns:1fr 320px;gap:18px">
        <div style="background:#fff;padding:14px;border-radius:8px">
          <p style="color:var(--muted)">Выберите параметры — получите ориентировочную цену</p>
          <div style="display:grid;grid-template-columns:1fr 1fr;gap:8px">
            <label>Площадь (м²)</label>
            <input id="area" type="number" value="18">
            <label>Фундамент</label>
            <select id="foundation"><option value="0">Не нужен</option><option value="15000">Ленточный +15 000 ₽</option><option value="30000">Плитный +30 000 ₽</option></select>
            <label>Отделка</label>
            <select id="finish"><option value="0">Стандарт</option><option value="35000">Комфорт +35 000 ₽</option><option value="85000">Премиум +85 000 ₽</option></select>
          </div>
          <div style="margin-top:12px">
            <button class="btn" onclick="calc()">Посчитать цену</button>
            <div id="price" style="margin-top:12px;font-weight:700"></div>
          </div>
        </div>

        <div class="video-wrap">
          <video src="/videos/video_factory.mp4" controls style="width:100%;height:100%;display:block"></video>
          <p style="text-align:center;color:var(--muted);margin-top:8px">Реальный объект в производстве: сборка, отделка, печь в комплекте</p>
        </div>
      </div>
    </section>

    <section style="margin-top:18px">
      <h2>Отзывы</h2>
      <div style="display:grid;grid-template-columns:1fr 1fr;gap:12px">
        <div style="background:#fff;padding:12px;border-radius:8px">«Поставили баню за 5 дней. Всё тепло и аккуратно — рекомендуем!»<div style="font-size:13px;color:var(--muted);margin-top:8px">— Олег, Новочебоксарск</div></div>
        <div style="background:#fff;padding:12px;border-radius:8px">«Отличное решение для дачи: компактно и уютно»<div style="font-size:13px;color:var(--muted);margin-top:8px">— Татьяна, Чебоксары</div></div>
      </div>
      <div class="video-wrap" style="margin-top:12px">
        <video src="/videos/video_experience.mp4" controls style="width:100%;height:300px;display:block"></video>
        <p style="text-align:center;color:var(--muted);margin-top:8px">Реальный опыт: чай, пар, веник, бассейн — всё как в сказке</p>
      </div>
    </section>

    <section style="margin-top:18px">
      <h2>Контакты</h2>
      <div style="display:flex;gap:18px;flex-wrap:wrap;align-items:flex-start">
        <div style="flex:1;min-width:260px">
          <p><strong>Телефон:</strong> <a href="tel:+79196677372">+7 (919) 667-73-72</a></p>
          <p><strong>WhatsApp:</strong> <a href="https://wa.me/79196677372?text=Здравствуйте!%20Хочу%20получить%20каталог">Написать в WhatsApp</a></p>
          <p><strong>Адрес:</strong> Новочебоксарск, ул. Промышленная, 59 (производство) — офис: удаленно (фриланс)</p>
        </div>
        <div style="flex:1;min-width:260px;background:#fff;padding:12px;border-radius:8px">
          <form onsubmit="event.preventDefault();alert('Спасибо! Мы свяжемся с вами');">
            <label>Имя</label>
            <input required>
            <label>Телефон</label>
            <input required>
            <button class="btn" style="width:100%">Отправить</button>
          </form>
        </div>
      </div>

      <div style="margin-top:20px; padding:12px; background:#f9f9f9; border-radius:8px; font-size:14px;">
        <strong>Юридическая информация:</strong><br>
        ИП [Ваше ФИО]<br>
        ИНН: 21XXXXXXXX | ОГРНИП: 32121XXXXXXXXXX<br>
        Адрес производства: г. Новочебоксарск, ул. Промышленная, 59<br><br>
        ✅ Работаем по договору подряда<br>
        ✅ Гарантия 12 месяцев на конструкцию и монтаж<br>
        ✅ Все работы согласовываются и оплачиваются по актам
      </div>
    </section>

  </main>

  <footer>
    © «Модульные дома & бани», Новочебоксарск · Тел.: +7 (919) 66
