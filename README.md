# Мастер-класс по Angular

Этот мастер-класс даст возможность Angular-разработчикам в сжатые сроки овладеть продвинутыми темами.

# Как проходит обучение

Занятие проходит в формате 8-часового вебинара (с часовым перерывом на обед).
Преподаватель последовательно разбирает темы программы. В любой момент можно задавать вопросы, если что-то не понятно.
Мастер класс рассчитан на ограниченное количество участников, чтобы мы смогли гарантировать, что успеем ответить на все вопросы.

# Требования

Для максимально эффективного прохождения МК необходимо иметь следующие знания: 

- JavaScript: уверенное знание основ
- EcmaScript2015: классы, стрелочные функции
- TypeScript: типы, интерфейсы, модификаторы доступа, декораторы
- Angular: уверенное знание основ

# Программа

Мастер-класс позволит вам лучше понять, как работает Angular, и, используя полученые знания, оптимизировать существующие приложения. 

Мы внимательно следим за развитием Angular и будем использовать самые новые подходы. 

Все идеи и пожелания по программе, пожалуйста, пишите в [issues](https://github.com/javascript-ru/angularpro/issues?q=is%3Aissue+is%3Aopen+sort%3Aupdated-desc).

## Сложные страницы: продвинутая генерация контента
- ContentChild и ViewChild
- ngTemplateOutlet
- Наследование компонентов
- Структурные директивы
- Динамические компоненты, ngComponentOutlet
- Impure pipes
- Angular Elements

## Продвинутое Dependency Injection
- Рецепты создания провайдеров
- Использование InjectionToken
- Паттерны под капотом
- viewProviders
- ReflectiveInjector и StaticInjector

## Механизм синхронизации в деталях
- Change Detection
  - ExpressionChangedAfterItHasBeenCheckedError
- Понимание Zonejs
  - runOutsideAngular
  - выключаем ngZone
- Стратегия onPush
- Работа с Observable и markForCheck
- detach/reattach

## Реактивный подход
- Понимание реактивного подхода
- Новое в RxJs6 и миграция
- Беглый обзор операторов
- Различные виды Subject
- unsubscribe и вопросы утечки памяти
- Работаем с Расписаниями(Schedulers)
- Юнит тесты для реактивных сущностей

## Продвинутый роутинг
- Анимации при смене состояния
- Ленивая загрузка и стратегии предзагрузки модулей
- Динамическое изменения конфигурации состояний

## Schematics
- Принципы работы Angular Schematics
- Создаем Schematics для своей библиотеки

## Service Workers
- Паттерны применения, достоинства
- Запуск сервис воркеров
- Настройка режима offline
- Проверка обновлений
- push-уведомления

## Renderer
- Использование Ivy, нового рендерера Angular
  - Сравнение Ivy и Angular Renderer2
- SSR на основе angular-cli и express
  - Кешируем http запросы с помощью TransferState

## Сборка и оптимизация
- Оптимизация размера бандлов
- Создание Angular библиотек
- Модульная организация приложения
- Больше одного приложения одновременно

## Авторизация и безопасность
- canActivate Guard
- Интерсепторы авторизации 
- Защита из коробки от XSS и XSRF
- Использование Auth0
