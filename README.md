# Anar Ibadov — портфолио

Веб-разработчик из Азербайджана. Делаю сайты-визитки, лендинги и веб-сервисы, а также Telegram-ботов.
Работаю на русском и азербайджанском языках.

**Связаться:** [LinkedIn](https://www.linkedin.com/in/anar-ibadov/)

> Это витрина: здесь только описания и скриншоты. Исходный код проектов приватный и в открытом доступе не публикуется.
> Код и материалы можно показать по запросу в рамках обсуждения заказа.

---

## Alsat — сайт объявлений для Азербайджана

Бесплатная доска объявлений на азербайджанском и русском языках. Живой сайт: <https://alsat.anaris0909.workers.dev>

![Alsat, главная страница (RU)](assets/alsat-ru-desktop.jpg)

**Что умеет**
- Два уровня категорий (транспорт, электроника, недвижимость, б/у вещи, одежда, аксессуары); категории редактируются в админке.
- Подача объявления без регистрации, у каждого объявления свой номер, поиск по номеру, фильтры по городу и цене.
- Связь с продавцом по звонку или WhatsApp, номер объявления подставляется в сообщение автоматически.
- Редактирование объявления по номеру и PIN, жалобы, лимит объявлений в сутки, защита от ботов.
- Админка: модерация, фото, категории, страницы и статьи на двух языках.

**Стек:** TypeScript, Hono, Cloudflare Workers, Cloudflare D1 (SQL).

| Версия на азербайджанском | Мобильная версия |
|---|---|
| ![Alsat AZ](assets/alsat-az-desktop.jpg) | ![Alsat mobile](assets/alsat-ru-mobile.jpg) |

---

## Vertex — корпоративный сайт (демо-шаблон)

Собственный дизайн корпоративного сайта для бизнеса и услуг: HTML, CSS и JavaScript без библиотек и чужих файлов.
Это демонстрационный сайт: цифры и тексты на нём примерные, под клиента они заменяются.

![Vertex, главный экран](assets/vertex-desktop.jpg)

**Блоки:** главный экран со статистикой, услуги, о компании, этапы работы, кейсы, команда, тарифы, отзывы, вопросы и ответы, форма заявки.

**Стек:** HTML5, CSS3, JavaScript (без фреймворков), адаптивная вёрстка.

<details>
<summary>Страница целиком</summary>

![Vertex, страница целиком](assets/vertex-full.jpg)

</details>

---

## AutoParts — интернет-магазин автозапчастей (демо-версия)

Платформа интернет-магазина автозапчастей для рынка Украины на нескольких языках (украинский, русский, английский).
Показана демонстрационная версия с тестовыми данными, живого сайта у проекта нет.

![AutoParts, главная](assets/autoparts-home.jpg)

**Что сделано**
- Витрина: подбор запчастей по автомобилю, поиск по артикулу, каталог с фильтрами по категориям и брендам, сортировка, карточки товаров, корзина.
- Админка: поставщики, импорт прайсов, сопоставление брендов, наценки.
- Заказы: платежи (LiqPay, WayForPay, monobank), доставка «Новой почтой», уведомления.
- Несколько независимых сервисов (каталог, заказы, поставщики) с общим описанием API.

**Стек:** TypeScript, Next.js, Tailwind CSS, NestJS, PostgreSQL, Redis, OpenSearch, Docker.

| Каталог | Мобильная версия |
|---|---|
| ![AutoParts, каталог](assets/autoparts-catalog.jpg) | ![AutoParts mobile](assets/autoparts-mobile.jpg) |

---

## A.İbadov IT-Edu — учебный сайт по IT-специальностям

Сайт на азербайджанском языке с учебными программами, тестами и базой знаний. Направления: IT Help Desk, компьютерный оператор, графический дизайн. Живой сайт: <https://ibadov-it-edu.vercel.app>

![IT-Edu, главная](assets/it-desktop.jpg)

**Что сделано**
- Уроки, презентации и тесты по направлениям, собираемые из данных скриптом сборки.
- Отдельные страницы направлений, статьи, видеоуроки.
- Адаптивная вёрстка, кнопка WhatsApp, подключение Google Search Console.

**Стек:** HTML5, CSS3, JavaScript, Node.js (сборка), Vercel.

![IT-Edu, мобильная версия](assets/it-mobile.jpg)

---

## Balıqçı.az — портал о рыбалке в Азербайджане

Информационный портал на азербайджанском языке: прогноз погоды по регионам, энциклопедия рыб, карта мест, новости, галерея, лента уловов и админка. Живой сайт: <https://baliqchi-portal.vercel.app>

![Balıqçı.az, главная](assets/baliqchi-desktop.jpg)

**Стек:** HTML5, CSS3, JavaScript, Vercel.

![Balıqçı.az, мобильная версия](assets/baliqchi-mobile.jpg)

---

## R.R. Logistics — сайт международной логистической компании

Сайт компании, занимающейся международными грузоперевозками (Астара, Азербайджан). Живой сайт: <https://rr-logistics.org>

![R.R. Logistics, главная (AZ)](assets/rr-az-desktop.jpg)

**Что сделано**
- Три языка интерфейса: азербайджанский, русский, английский.
- Страницы услуг, галерея, форма запроса стоимости: заявка уходит владельцу в Telegram.
- Кнопка WhatsApp, баннер согласия на cookie, карта сайта и мета-теги для поиска.
- Админка с входом по паролю для управления галереей.
- Быстрая загрузка: сайт собирается из статических страниц, скрипты и стили минифицируются при сборке.

**Стек:** HTML5, CSS3, JavaScript, Vercel (serverless-функция для заявок), Telegram Bot API.

| Русская версия | Мобильная версия |
|---|---|
| ![R.R. Logistics RU](assets/rr-ru-desktop.jpg) | ![R.R. Logistics mobile](assets/rr-az-mobile.jpg) |

---

## FUNTIK Sushi & Pizza — интернет-магазин доставки еды (проект для клиента)

Интернет-магазин суши и пиццы для рынка Германии. Живой сайт: <https://funtik.store>
Это работа для клиента, исходный код принадлежит заказчику и здесь не публикуется.

![FUNTIK, главная (DE)](assets/funtik-de-desktop.jpg)

**Что сделано**
- Каталог с модификаторами (размер пиццы, добавки) и аллергенами по немецким требованиям.
- Корзина, оформление заказа с доставкой или самовывозом, расчёт по расстоянию.
- Оплата онлайн (карта, SEPA, PayPal) или наличными, чек в PDF после заказа.
- Четыре языка: немецкий, английский, русский и арабский (с написанием справа налево).
- Юридические страницы Impressum, Datenschutz, AGB.

**Стек:** Next.js (React), TypeScript, Tailwind CSS, Supabase (PostgreSQL), Stripe, next-intl.

| Русская версия | Мобильная версия |
|---|---|
| ![FUNTIK RU](assets/funtik-ru-desktop.jpg) | ![FUNTIK mobile](assets/funtik-de-mobile.jpg) |

---

## Адаптации готовых HTML-шаблонов (27 сайтов)

Это сайты на основе готовых HTML-шаблонов (в основном HTML Codex, htmlcodex.com). Дизайн и вёрстка шаблонов принадлежат их авторам,
я их не выдаю за собственные разработки. Здесь показана моя работа по доводке шаблонов до рабочих сайтов для русскоязычной аудитории.

**Что сделано с шаблонами** (набор доработок немного различается от сайта к сайту)
- Перевод на русский язык: тексты, заголовки страниц, мета-теги.
- Обновление библиотек (jQuery, Bootstrap), проверка целостности внешних скриптов (SRI), исправление разметки, доступность (подписи иконок и полей).
- Защита форм от случайной перезагрузки, исправление переноса слов на мобильных.
- Единый стиль навигации: тёмная липкая шапка с выпадающими списками.
- SEO: уникальные заголовки и описания внутренних страниц, ключевые слова (на части сайтов).
- Для BabyCare дополнительно сделаны версии на азербайджанском и английском языках с переключателем.

<table>
<tr><td width="33%"><img src="assets/templates/biznews.jpg" alt="BizNews"><br><b>BizNews</b><br>деловые новости</td><td width="33%"><img src="assets/templates/boxup.jpg" alt="Boxup"><br><b>Boxup</b><br>технологическая компания</td><td width="33%"><img src="assets/templates/cental.jpg" alt="Cental"><br><b>Cental</b><br>прокат автомобилей</td></tr>
<tr><td width="33%"><img src="assets/templates/cepair.jpg" alt="Cepair"><br><b>Cepair</b><br>ремонт компьютеров</td><td width="33%"><img src="assets/templates/coraluxe.jpg" alt="Coraluxe"><br><b>Coraluxe</b><br>курортный отель</td><td width="33%"><img src="assets/templates/daycare-website-template.jpg" alt="BabyCare"><br><b>BabyCare</b><br>детский сад, версии RU / AZ / EN</td></tr>
<tr><td width="33%"><img src="assets/templates/ecourses.jpg" alt="ECourses"><br><b>ECourses</b><br>онлайн-курсы</td><td width="33%"><img src="assets/templates/elearning.jpg" alt="eLearning"><br><b>eLearning</b><br>обучение онлайн</td><td width="33%"><img src="assets/templates/electro.jpg" alt="Electro"><br><b>Electro</b><br>магазин электроники</td></tr>
<tr><td width="33%"><img src="assets/templates/faster.jpg" alt="Faster"><br><b>Faster</b><br>логистическая компания</td><td width="33%"><img src="assets/templates/fruitables.jpg" alt="Fruitables"><br><b>Fruitables</b><br>овощи и фрукты</td><td width="33%"><img src="assets/templates/hotelier.jpg" alt="Hotelier"><br><b>Hotelier</b><br>отель и номера</td></tr>
<tr><td width="33%"><img src="assets/templates/industrix.jpg" alt="Industrix"><br><b>Industrix</b><br>промышленные решения</td><td width="33%"><img src="assets/templates/influency.jpg" alt="Influency"><br><b>Influency</b><br>инфлюенсер-маркетинг</td><td width="33%"><img src="assets/templates/italian-cuisine.jpg" alt="Italian Cuisine"><br><b>Italian Cuisine</b><br>ресторан</td></tr>
<tr><td width="33%"><img src="assets/templates/kider.jpg" alt="Kider"><br><b>Kider</b><br>детский сад и подготовка к школе</td><td width="33%"><img src="assets/templates/lawfice.jpg" alt="Lawfice"><br><b>Lawfice</b><br>юридическая фирма</td><td width="33%"><img src="assets/templates/mobile-app-html-template.jpg" alt="FitApp"><br><b>FitApp</b><br>приложение для фитнеса</td></tr>
<tr><td width="33%"><img src="assets/templates/news.jpg" alt="News"><br><b>News</b><br>новостной портал</td><td width="33%"><img src="assets/templates/news24.jpg" alt="News 24"><br><b>News 24</b><br>новостной портал</td><td width="33%"><img src="assets/templates/pet-shop-website-template.jpg" alt="Pet Shop"><br><b>Pet Shop</b><br>зоомагазин</td></tr>
<tr><td width="33%"><img src="assets/templates/physical-therapy-website-template.jpg" alt="Terapia"><br><b>Terapia</b><br>центр физиотерапии</td><td width="33%"><img src="assets/templates/pigra.jpg" alt="Pigra"><br><b>Pigra</b><br>личное портфолио</td><td width="33%"><img src="assets/templates/product-landing-page.jpg" alt="Watch"><br><b>Watch</b><br>лендинг умных часов</td></tr>
<tr><td width="33%"><img src="assets/templates/royal-hotel.jpg" alt="Royal Hotel"><br><b>Royal Hotel</b><br>бронирование номеров</td><td width="33%"><img src="assets/templates/seocom.jpg" alt="SEOcom"><br><b>SEOcom</b><br>SEO-агентство</td><td width="33%"><img src="assets/templates/software-landing-page-template.jpg" alt="soFFer"><br><b>soFFer</b><br>программа для бизнеса</td></tr>
</table>

---

## Что могу сделать для вас

- Сайт-визитка или лендинг.
- Корпоративный сайт с формой заявки.
- Веб-сервис с базой данных и админкой.
- Telegram-бот для уведомлений и учёта заказов.

## Права

© 2026 Anar Ibadov. Все права защищены. Скриншоты и описания размещены только для ознакомления, копирование и повторное использование без письменного разрешения запрещены. Подробнее в файле [LICENSE](LICENSE).

---

# Anar Ibadov — portfolio (EN)

Web developer based in Azerbaijan: business websites, landing pages, web services and Telegram bots.
This repository is a showcase only (descriptions and watermarked screenshots). Source code is private and available on request.
Contact: [LinkedIn](https://www.linkedin.com/in/anar-ibadov/).
