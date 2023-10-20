# Design Backend Client Server CRM Management

Этот проект представляет собой систему управления отношениями с клиентами (CRM) с дизайнерским подходом, разработанную на фреймворке Laravel.

## Содержание

1. [Установка](#установка)
2. [Использование](#использование)
3. [Структура проекта](#структура-проекта)
4. [Лицензирование](#лицензирование)
5. [Безопасность](#безопасность)
6. [Контрибьюторы](#контрибьюторы)

## Установка

1. Клонируйте репозиторий из GitHub.
```bash
git clone https://github.com/SitesReviews/Design-backend-client-server-CRM-management.git
```
2. Установите зависимости Composer и NPM.
```bash
composer install
npm install
```
3. Скопируйте файл `.env.example` в файл `.env` и настройте его в соответствии с вашей средой.
```bash
cp .env.example .env
```
4. Запустите миграции базы данных и сиды (если есть).
```bash
php artisan migrate --seed
```
5. Запустите сервер разработки.
```bash
php artisan serve
```

## Использование

Для доступа к панели управления перейдите по URL: [http://localhost:8000](http://localhost:8000).

## Структура проекта

- `.github/`: Директория для конфигураций GitHub, включая настройки Dependabot.
- `app/`: Основной код приложения.
- `bootstrap/`: Файлы инициализации фреймворка.
- `config/`: Конфигурационные файлы приложения.
- `database/`: Файлы миграций базы данных и сиды.
- `docker/`: Файлы для работы с Docker.
- `lang/`: Директория для файлов локализации.
- `public/`: Публичные файлы, такие как индексные файлы, CSS, JavaScript и изображения.
- `resources/`: Виды (views), файлы стилей и JavaScript.
- `routes/`: Файлы маршрутизации приложения.
- `storage/`: Временные и лог-файлы.
- `tests/`: Тестовые файлы.
- `.editorconfig`: Файл конфигурации EditorConfig для поддержания согласованного стиля кодирования.
- `.env.example`: Пример файла конфигурации для окружения.
- `.gitattributes`: Файл Git для управления атрибутами файлов.
- `.gitignore`: Файл Git для указания файлов, которые следует игнорировать.
- `LICENSE`: Файл лицензии проекта.
- `README.md`: Основной файл документации проекта.
- `SECURITY.md`: Файл с информацией о политике безопасности.
- `artisan`: Скрипт для запуска команд Artisan (Laravel).
- `composer.json`: Файл конфигурации Composer, указывающий зависимости PHP проекта.
- `composer.lock`: Файл Composer, содержащий точные версии установленных зависимостей.
- `docker-compose.yml`: Файл конфигурации Docker Compose для управления сервисами Docker в проекте.
- `package-lock.json`: Файл NPM, содержащий точные версии установленных зависимостей.
- `package.json`: Файл конфигурации NPM, указывающий зависимости Node.js проекта.
- `phpunit.xml`: Файл конфигурации PHPUnit для управления тестированием.
- `postcss.config.js`: Файл конфигурации PostCSS для обработки CSS.
- `vite.config.js`: Файл конфигурации Vite для управления сборкой и разработкой проекта.

## Лицензирование

Проект распространяется под лицензией [MIT](LICENSE).

## Безопасность

Если вы нашли уязвимость в безопасности, пожалуйста, ознакомьтесь с нашей [политикой безопасности](SECURITY.md).

## Контрибьюторы

- [Список контрибьюторов](https://github.com/SitesReviews/Design-backend-client-server-CRM-management/graphs/contributors).

