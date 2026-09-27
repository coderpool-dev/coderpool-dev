# Кирилл Нетесов

**Backend-разработчик PHP · Laravel · Symfony · 6+ лет коммерческого опыта**

Разрабатываю API, сервисы обработки данных и веб-приложения. Работаю с платежами, очередями, интеграциями и realtime. Веду задачи от проектирования базы данных до тестов, развёртывания и поддержки в production.

[Telegram](https://t.me/coderpool) · [Email](mailto:cyrillnetyosov@yandex.ru) · [GoydaCord](https://goidacord.ru)

## Проекты

### [GoydaCord API](https://github.com/coderpool-dev/goydacord-api)

Бэкенд голосового мессенджера с личными чатами, серверами, ролями, голосовыми каналами и файлообменом. Отвечаю за бэкенд и разрабатываю веб- и десктоп-клиенты.

- REST API на Laravel 12: Sanctum, сессии по устройствам, сервисный слой, policies и API Resources.
- Сообщения и статусы присутствия через Laravel Reverb; голосовые комнаты на LiveKit, TURN/STUN на coturn.
- Иерархия ролей, права отдельных каналов и серверная модерация голосовых комнат.
- Загрузка файлов частями с докачкой, проверкой смещения и защитой от параллельной записи; потоковая отдача с поддержкой HTTP Range.
- Feature- и unit-тесты на PHPUnit, статический анализ PHPStan/Larastan, проверка стиля Laravel Pint.

**Стек:** PHP 8.3, Laravel 12, MySQL, Redis, Reverb, LiveKit. Клиенты — Next.js, TypeScript и Electron.

[Попробовать демо](https://goidacord.ru) · [Архитектура](https://goidacord.ru/tech) · [Код](https://github.com/coderpool-dev/goydacord-api)

### [PREPISKA DayZ Launcher](https://github.com/coderpool-dev/dayz_launcher)

Лаунчер для Windows: поиск серверов DayZ, подготовка модов и запуск игры с нужными параметрами.

- PHP API собирает, нормализует и кэширует список серверов.
- Клиент получает список модов через API и A2S, проверяет их наличие и управляет подписками Steam Workshop.
- Интерфейс на HTML/CSS/JavaScript работает внутри WebView2; взаимодействие со Steam вынесено в отдельный процесс.
- Тесты на xUnit, сборка и выпуск установщика через GitHub Actions.

**Стек:** C#, .NET 8, WinForms, WebView2, Steamworks, PHP 8.

### [Сайт университета на Joomla](https://github.com/coderpool-dev/joomla-university-website)

Публичная портфолио-версия проекта: перенос сайта и подготовка окружения на Nginx, PHP-FPM и MySQL. В репозитории — структура сайта, пример конфигурации и заметки по развёртыванию. Данные и материалы организации исключены из публикации.

В рамках работы над порталом мигрировал Joomla 3 → 4, дорабатывал модули расписания и обратной связи, подключал заявки и уведомления об ошибках к Telegram.

## Коммерческий опыт

- **Производительность.** В корпоративной системе документооборота ускорил формирование отчётов с 10 до 1,5 секунды на таблицах с миллионами записей: оптимизировал SQL, добавил индексы и кэширование в Redis.
- **Очереди и микросервисы.** Участвовал в переносе модуля с Laravel на сервисы Symfony. Настраивал RabbitMQ с подтверждениями доставки и dead-letter очередью, Kafka-консьюмеры для фоновой обработки XML и Excel.
- **Платежи.** Интегрировал ЮKassa, QIWI и Antilopay: проверка подписи webhook, идемпотентная обработка, статусы, сверка и возвраты.
- **Интеграции и поддержка.** Работал с Telegram Bot API, Twitch OAuth/Helix и REST-обменом с 1С-Битрикс. Обновлял PHP и фреймворки, дорабатывал проекты на Yii2 и Joomla.

## Технологии

| Направление | Инструменты |
| --- | --- |
| Backend | PHP, Laravel, Symfony, Yii2, REST API, WebSocket |
| Данные | MySQL, PostgreSQL, MongoDB, Redis |
| Очереди | Laravel Queues, RabbitMQ, Apache Kafka |
| Качество | PHPUnit, PHPStan / Larastan, Laravel Pint |
| Инфраструктура | Docker, Linux, Nginx, PHP-FPM, GitHub Actions, Git |
| Клиентская разработка | Vue 3, React, Next.js, TypeScript, Electron |

## Связь

Обсудить проект или работу: **[@coderpool](https://t.me/coderpool)** или **[cyrillnetyosov@yandex.ru](mailto:cyrillnetyosov@yandex.ru)**.

Работаю удалённо; рассматриваю офис и гибрид в Москве и Санкт-Петербурге. Английский — B2.
