# Мастер Класс по Angular

Все идеи и пожелания по программе пожалуйста пишите в [issues](https://github.com/javascript-ru/angularpro/issues?q=is%3Aissue+is%3Aopen+sort%3Aupdated-desc).

## Продвинутая генерация контента
- ContentChild и ViewChild
- ngTemplateOutlet
- экспорт контроллера директивы с помощью exportAs
- Наследование компонентов
- Структурные директивы
- Динамические компоненты
    - ngCopomentOutlet нам в помощь
- Impure pipes
- Angular Elements

## Dependency Injection
- Рецепты создания провайдеров
- Использование InjectionToken
- Паттерны под капотом
- viewProviders
- ReflectiveInjector и StaticInjector

## Change Detection
- Механизм Change Detection
- Понимание Zonejs
    - runOutsideAngular
    - выключаем ngZone
- стратегия onPush
- работа с Observable и markForCheck
- detach/reattach

## Реактивный подход
- реактивный подход или нет?
- новое в RxJs6 и миграция
- беглый обзор операторов
- различные виды Subject
- unsubscribe и вопросы утечки памяти
- работаем с Расписаниями(Schedulers)
- юнит тесты для реактивных сущностей

## Роутер
- анимации при смене стейта
- ленивая загрузка и стратегии предзагрузки модулей
- динамическое изменения конфигурации стейтов

## Schematics
- принципы работы Angular Schematics
- создаем Schematics для своей библиотеки

## Service Workers
- запуск сервис воркеров
- настройка режима offline
- проверка обновлений
- push-уведомления

## Renderer
- Angular Ivy
    - сравниваем Ivy и Angular Renderer2
- SSR на основе angular-cli и express
    - Кешируем http запросы с помощью TransferState

## Сборка и оптимизация
- Оптимизация размера бандлов
- Создание Angular библиотек

## Безопасность
- canActivate Guard
- Интерсепторы авторизации
- Защита из коробки от XSS и XSRF
- Настраиваем Auth0
