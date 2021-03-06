﻿# Todo

- [x] сделать метод для запуска обработчиков событий с параметром асинхронного запуска
- [x] сделать автосоздание сущностей БД
- [x] регистрация таймеров 
- [x] защищенный запуск действий таймеров (через хелпер + запись в лог)
- [x] объединить TimerCollection и плагин?
- [x] миграции для скриптов
- [x] скриптовые команды
- [x] фильтр списка плагинов по типу/интерфейсу (+ рефакторинг БД и скриптов)
- [x] разобраться с приведением числовых типов при вызове методов (всегда приходит вещественный тип)
- [x] возвращаемые значения для сценариев
- [x] доступ к методам, сценариям и логированию через поля объекта host
- [x] API для настроек приложения
- [x] вынести connection string в настройки
- [x] кэширование конфигурации БД (кэшируется срезствами EF)
- [x] вынести порт веб-сервера в настройки
- [x] параметры для методов HTTP API
- [x] загрузка ресурсов по HTTP
- [x] сделать кэширование ресурсов и заголовки ответа
- [x] сделать хэндлер для ресурсов асинхронным
- [x] выпилить интерфейсы I*Owner
- [x] Выпилить MEF
- [x] атрибуты для js и css ресурсов
- [x] логирование через microsoft.extensions.logging (?) - привести в порядок
- [x] пустая стартовая страница по умолчанию + настройки стартовой страницы
- [x] скриптовые события
- [х] починить двойное нажатие ENTER для выхода! https://youtrack.jetbrains.com/issue/RIDER-4677
- [x] NLog => Serilog
- [x] починить запуск в фоновом режиме

- [x] атрибуты для разделов (тип, заголовок, порядок сортировки)
- [x] списки разделов (~~системный и общий, отображать заголовок, переход в разделы, верстка списков~~)
- [x] отображение страницы ошибки (метод в application, заголовок и текст)
- [x] отображение ошибок загрузи
- [x] загрузка стилей (признак автозагрузки)
- [x] стили для списка разделов: margin-bottom: 12px; color: #999;
- [x] ПРИДУМАТЬ ПРАВИЛА ФОРМИРОВАНИЯ URL и исправить во всех проектах
- [x] ПРОВЕРИТЬ ВСЕ МЕТОДЫ HTTP API СЦЕНАРИЕВ
- [x] дописать readme для плагинов webserver (про ресурсы) и webui (про отображеие ошибки и про автозагрузку css)
- [x] проверить выполнение подписанных сценариев
- [x] общие сценарные и плагинные события для планировщика

- [ ] дописать в README про буферы
- [ ] определиться с терминологией планировщика
- [ ] рефакторинг поиска методов: сделать версию, где тип делегата приходит параметром Type

- [ ] ИЗБАВИТЬСЯ ОТ ДУБЛИРОВАНИЯ КОДА В js разделов
- [ ] ПРОВЕРИТЬ доступ к методам и сценариям через поля
  - типы параметров, 
  - значения параметров по умолчанию, 
  - возвращаемое значение, 
  - вызов по названию поля
  - несуществующие названия
- [ ] ПРОВЕРИТЬ НЕОБХОДИМОСТЬ ДЕЙСТВИЙ ПРИ УДАЛЕНИИ РАЗДЕЛОВ И ПРЕДСТАВЛЕНИЙ
- [ ] сделать применение миграций в порядке зависимости библиотек


### webui
- [x] moment
- [x] настройка для списка разделов
- [x] починить ширину ссылки в шапке на маленьких экранах
- [x] переименовать модуль welcome в dummy и написать пояснительный текст

## alpha1

- [x] http listener (~~api~~, ~~resources~~)
- [x] scripts (~~web~~ ~~api~~, ~~events~~)
- [x] web-ui (~~core: обшие библиотеки, точка входа, layout~~)

## alpha2

- [x] web-ui (~~app list~~)
- [x] scripts UI(~~запуск скриптов~~, ~~сохранение~~, ~~удаление~~, ~~fullscreen~~, ~~theme~~, ~~подписка на события~~)
- [x] ~~плагин email~~

## alpha3
- [ ] scheduler
- [ ] локализация (после релиза .NET Core 2.0)

### core

- [ ] http listener (signalr)

### hardware

- [ ] noolite (Core, API, UI)
- [ ] видеонаблюдение
- [ ] плагин для homebridge, загружающий устройства из TH и перенаправляющий запросы к нему

### protocols

- [ ] mqtt 
- [ ] rabbitmq http://www.rabbitmq.com/dotnet.html

### messenger

- [ ] telegram bot https://www.nuget.org/packages/Telegram.Bot/
- [ ] slack
- [ ] SMS

### others

- [ ] графики
- [ ] web-ui (dashboards),
- [ ] microclimate (Core, UI)
- [ ] weather
- [ ] dynamic DNS [инструкция](https://habrahabr.ru/post/310534), [токены](https://pddimp.yandex.ru/api2/admin/get_token?domain_name=thinking-home.ru)
- [ ] audio ?
- [ ] http запросы
- [ ] twitter https://coretweet.github.io

====

- [ ] сделать поддержку нескольких СУБД

