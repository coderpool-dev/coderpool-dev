# Кирилл Нетесов

**PHP Backend Developer · Laravel / Symfony · 6+ лет коммерческого опыта**

Проектирую и довожу до production API и веб-сервисы: платежи, очереди, интеграции и realtime. Отвечаю за весь цикл — схема базы данных, код, тесты, CI/CD, деплой и поддержка.

[Telegram ↗](https://t.me/coderpool) · [Email ↗](mailto:cyrillnetyosov@yandex.ru)

## GoydaCord — голосовой мессенджер

Чаты, серверы, звонки и демонстрация экрана. Основной проект: бэкенд на Laravel, веб-клиент на Next.js, приложение на Electron. В демо-входе без регистрации открывается готовый DayZ-сервер с переписками, друзьями и превью стрима.

[**Открыть демо →**](https://goidacord.ru) · [Исходный код](https://github.com/coderpool-dev/goydacord-api) · [Архитектура](https://goidacord.ru/tech)

[![Интерфейс GoydaCord: DayZ-сервер, чат и превью стрима](https://raw.githubusercontent.com/coderpool-dev/goydacord-api/main/docs/screenshots/app-demo.webp?v=20260928)](https://goidacord.ru)

- Авторизация по устройствам, иерархия ролей и права на уровне каналов
- События в реальном времени через Laravel Reverb, голосовые комнаты на LiveKit
- Демо-аккаунты с подготовленными участниками, чатами и превью демонстрации экрана
- Загрузка файлов с докачкой
- Бизнес-логика в сервисах; PHPUnit и PHPStan/Larastan

`PHP 8.3` · `Laravel 12` · `MySQL` · `Redis` · `WebSocket` · `LiveKit`

## PREPISKA DayZ Launcher — Symfony-бэкенд и Windows-клиент

Сервис для игроков DayZ: каталог ~20 тыс. серверов, админка со статистикой и выпуском обновлений, клиент для Windows.

[Сайт](https://dayz.goidacord.ru) · [Исходный код](https://github.com/coderpool-dev/dayz_launcher)

- **Symfony 7.4 LTS, Doctrine, EasyAdmin:** API, админка со статистикой использования, управлением спонсорскими серверами и загрузкой новых версий
- **Производительность:** список серверов из внешних источников обновляется по cron под блокировкой, при недоступности источника отдаётся последний удачный снимок. Готовый ответ собирается раз в минуту и отдаётся файлом — раньше каждый запрос декодировал ~20 МБ JSON и упирался в лимит памяти PHP-FPM
- **Телеметрия клиентов** с rate limiting; **автообновление** с проверкой SHA-256
- Перенос с процедурного PHP на Symfony без изменения контракта API для уже установленных клиентов
- 28 тестов PHPUnit + 46 xUnit, CI в GitHub Actions, сборка и публикация установщика по git-тегу

`PHP 8.4` · `Symfony 7.4` · `Doctrine` · `EasyAdmin` · `C# / .NET 8` · `GitHub Actions`

[![Главный экран PREPISKA DayZ Launcher](https://raw.githubusercontent.com/coderpool-dev/dayz_launcher/main/docs/screenshots/01-home.png)](https://github.com/coderpool-dev/dayz_launcher)

## Сайт Тамбовского филиала РосНОУ — Joomla

Сайт вуза для абитуриентов, студентов и сотрудников: перенос на Joomla 6, настройка сервера, ускорение загрузки.

[Сайт](https://tambov-rosnou.ru) · [Исходный код](https://github.com/coderpool-dev/joomla-university-website)

<a href="https://github.com/coderpool-dev/joomla-university-website"><img src="https://raw.githubusercontent.com/coderpool-dev/joomla-university-website/main/docs/screenshots/homepage-preview.jpg" alt="Главная страница сайта Тамбовского филиала РосНОУ" width="480"></a>

`PHP 8.3` · `Joomla 6` · `MySQL` · `Nginx`

## Коммерческий опыт

- Сократил время формирования отчётов с **10 до 1,5 секунды** на таблицах с миллионами записей
- Интегрировал платёжные системы
- Вынес обработку документов в очереди

## Стек

**Backend:** PHP, Laravel, Symfony, Yii2, REST API

**Данные и очереди:** MySQL, PostgreSQL, Redis, RabbitMQ, Kafka

**Качество и инфраструктура:** PHPUnit, PHPStan, Docker, Linux, Nginx, CI/CD

---

Открыт к предложениям по PHP backend-разработке. Удалённо; офис или гибрид — Москва и Санкт-Петербург. **[Написать в Telegram →](https://t.me/coderpool)**
