---
layout: default
title: Область знаний
---

<link rel="stylesheet" href="{{ site.baseurl }}/assets/css/custom.css">

[На главную]({{ site.baseurl }})

# Область знаний

## Manual testing (Processes)

### 📌 Processes, Methodologies

| Методология | Описание (Novice) | Описание (Medium) | Описание (Advanced) |
|-------------|-------------------|-------------------|---------------------|
| agile, scrum, kanban, waterfall, kaskad, bdd, tdd | может перечислить методологии, рассказать об отличиях | опыт работы с Agile, перечисляет атрибуты Scrum и Kanban | опыт внедрения микропроцессов, может описать улучшения |

### 📌 Estimations

| Уровень | Описание |
|---------|----------|
| 🤓 Novice | опыт оценки личных задач |
| 🧐 Medium | опыт оценки задач, участие в командной оценке (planning poker) |
| 😎 Advanced | опыт общей оценки проекта и планирования релизов |

### 📌 Test documentation and bug tracking systems

| Уровень | Описание |
|---------|----------|
| 🤓 Novice | артефакты тестирования: test cases, check lists, bug reports; опыт работы с баг-трекингом |
| 🧐 Medium | разница между test case и check list, severity/priority, test plan, test strategy, сложные запросы |
| 😎 Advanced | test plan vs test strategy, организационная документация, опыт с дашбордами |

## Automation testing

### 📌 Automation testing, basic theory

| Уровень | Описание |
|---------|----------|
| 🤓 Novice | Что такое test automation, какие проблемы решает, цели, применимость |
| 🧐 Medium | Test automation для QA/QC/testing, test pyramid, виды тестирования |
| 😎 Advanced | Test strategy, внедрение automation, фигура тестирования для frontend/backend |

### 📌 Version Control System - Git

| Уровень | Описание |
|---------|----------|
| 🤓 Novice | Version Control System (что это и зачем нужно), как клонировать проект, рассказать о Git командах: git pull, git push, git commit (в случае если собеседуемый работал с Git), git branch, как сделать локальную ветку удаленной, git config (установить имя и email) |
| �� Medium | опция '--hard' (для git fetch или git reset) или как перезаписать локальные изменения удаленными, как перенести изменения с одной ветки на другую (3 способа), git rebase (что это и как работает, как откатить rebase), git reset, git stash, .gitignore, git log (как просматривать историю изменений), создание, ревью и слияние pull (merge) requests |
| 😎 Advanced | git cherry-pick (как выбирать коммиты), git submodules (как добавить submodule, обновить или удалить его), git hooks |

### 📌 CI, CD

| Уровень | Описание |
|---------|----------|
| 🤓 Novice | Что такое CI, слышал о CI инструментах (Jenkins, TeamCity, TFS) |
| 🧐 Medium | Имеет опыт работы с CI на проекте, может рассказать о CI pipeline на примере test pyramid и коммита разработчика в монолитном продукте, имеет опыт работы с одним из CI инструментов, в чем разница между Continuous Delivery и Continuous Deployment |
| 😎 Advanced | Имеет опыт настройки CI на проекте с микросервисной или сервисной архитектурой, может рассказать о pipeline, Infrastructure as code в CI, имеет опыт настройки CD, имеет опыт работы с Sonar и linter инструментами |

### 📌 Automation Tools (frameworks)

| Уровень | Описание |
|---------|----------|
| 🤓 Novice | Рассказать об инструменте, с которым работал (в общем - что это за инструмент и что он умеет), рассказать из каких блоков (частей) состоит тест, о каких еще фреймворках слышал, как запустить/пропустить отдельный тест |
| 🧐 Medium | Критерии выбора фреймворка, рассказать о hooks (before, after и так далее, различия между ними), рассказать о конфигурационном файле для своего фреймворка, как запускать тесты по тегам, Возможно ли запускать тесты параллельно? Если да - как это сделать?, как подключить reporter |
| �� Advanced | Интеграция с CI инструментами, Интеграция с TMS (test management systems), Расширение базовых возможностей фреймворка |

### 📌 Project management and comprehension tool (package manager)

| Уровень | Описание |
|---------|----------|
| 🤓 Novice | Зачем они нужны, О каких инструментах слышал, JS:<br>- Как установить библиотеку, npm, yarn (просто знать что существует) |
| 🧐 Medium | npm/yarn: {<br>package.json:<br>- Из каких блоков состоит, Как запустить скрипт и как запустить с переменными, Разница между dependencies/devDependencies - как установить пакет в эти блоки и как НЕ устанавливать dev при production деплое, Что такое package-lock.json/yarn.lock файл и зачем он нужен. Нужно ли коммитить lock файл в репозиторий?, Что такое SemVer? Что означают знаки в версии (^ ~ * и простое строгое определение версии). Какая версия библиотеки установлена в случае наличия lock файла и знака ^ в версии библиотеки? |
| 😎 Advanced | Использование внешних репозиториев, Параметризация при конфигурации (или установке) пакета |

### 📌 Locators

| Уровень | Описание |
|---------|----------|
| 🤓 Novice | Различия между CSS и XPath, Что можно использовать для поиска элементов? Какие атрибуты можно использовать для этого?, Найти элемент по CSS и по XPath |
| 🧐 Medium | Дать задачу с :not в CSS и not contains в XPath, Для чего нужны локаторы .// и ./?, XPath axes, document.querySelector() - что это и что может делать, Что такое jQuery |
| 😎 Advanced | Условный XPath (OR и так далее), Параметризированный составной локатор, Поиск псевдоэлементов ::before, ::after, Shadow root или shadow dom |

### 📌 Browser initialization

| Уровень | Описание |
|---------|----------|
| 🤓 Novice | Что такое Selenium WebDriver?, Где можно записать пути к драйверам?, Реализация инициализации WebDriver, Браузерные движки (gecko, webKit, edge) |
| 🧐 Medium | Реализация инициализации Singleton, abstract factory, Browser capabilities, Browser multiCapabilities, Remote webdriver, Headless mode |
| 😎 Advanced | Реализация собственной обертки элементов, Реализация и инициализация multiton или prototype, Подводные камни headless mode, Selenium logging |

### 📌 BDD

| Уровень | Описание |
|---------|----------|
| 🤓 Novice | Gherkin стиль, Feature, Scenario, Step |
| 🧐 Medium | Общий смысл BDD подхода в команде, Обзор BDD случаев, Правила для дизайна scenarios и features |
| 😎 Advanced | Процедура разработки BDD scenario и его последующей автоматизации, Архитектура BDD фреймворка для автоматизации тестов |

### 📌 Waiters

| Уровень | Описание |
|---------|----------|
| 🤓 Novice | Типы waiters, Различия между типами waiters |
| 🧐 Medium | Типы explicit wait, Типы implicit wait, Пример реализации explicit wait, Почему sleep плохая практика |
| 😎 Advanced | Fluent wait, Ожидание загрузки DOM дерева (JSExecutor), Ожидание ответов AJAX запросов (JSExecutor), Ожидание видимости элемента с использованием displayed, Как сделать собственные expected conditions |

### 📌 REST, SOAP, WebSockets

| Уровень | Описание |
|---------|----------|
| 🤓 Novice | Теоретические знания (что такое REST, SOAP, разница между ними), HTTP методы, Что такое идемпотентность и какие методы идемпотентны, Разница GET/POST, PUT/POST, Инструменты для отправки HTTP запросов (cURL, Postman) |
| 🧐 Medium | JSON, XML, Serialization, deserialization, Использование библиотек для работы с протоколами, Что такое WebSocket и как он работает?, CORS (что это и общее описание workflow) |
| 😎 Advanced | GraphQL, Requests pipeline |

### 📌 Framework architecture

| Уровень | Описание |
|---------|----------|
| 🤓 Novice | Понимание Page Object паттерна, Понимание 3-слойной архитектуры |
| 🧐 Medium | Имеет опыт разработки фреймворка автоматизации тестов на основе 3-слойной архитектуры, Понимание 4-слойной и 5-слойной архитектуры, Понимание Page Element паттерна, Сколько слоев нужно для автоматизированных тестов в Gherkin стиле |
| 😎 Advanced | Имеет опыт применения различных типов слоистой архитектуры в фреймворках автоматизации тестов для UI и API тестов, Архитектура на основе проекта разработчиков (плюсы, минусы), Архитектура на основе компонентов, Микросервисная архитектура, Архитектура contract testing |

### 📌 Loggers, reporters, metrics

| Уровень | Описание |
|---------|----------|
| 🤓 Novice | Что такое reporter, зачем они нужны, Как подключить HTML reporter под используемый инструмент |
| 🧐 Medium | Имеет опыт работы с популярными reporter (Allure, Report Portal), Паттерны проектирования, которые используются для reporting (delegate, decorator), Базовые метрики автоматизации тестирования |
| 😎 Advanced | Code coverage, инструменты для него, организация инфраструктуры и принципы построения code coverage, Организация и хранение отчетов под CI инструментом vs база данных, Переопределение методов популярных reporter (Allure, Report Portal) |

### 📌 Virtualization, containerization

| Уровень | Описание |
|---------|----------|
| 🤓 Novice | Понимание разницы между виртуализацией и контейнеризацией, Для чего нужна виртуализация?, Какие проблемы помогает решить виртуализация?, Преимущества контейнеризации при разработке автоматизированных тестов, Типы виртуализации |
| 🧐 Medium | Преимущества виртуализации, Кратко рассказать о жизненном цикле Docker контейнера, Что такое Dockerfile? Как его использовать?, Docker Hub, Container и image, Base image |
| 😎 Advanced | Оркестрация контейнеров, Что такое Docker Swarm?, Kubernetes, Как определить node в Kubernetes?, Какие недостатки есть у Kubernetes?, Что означает docker_host? |

### 📌 Test OPS

| Уровень | Описание |
|---------|----------|
| 🤓 Novice | Что такое TestOps?, TestOps VS DevOps |
| 🧐 Medium | Test coverage, Zero Bug Policy, Какие механизмы или инструменты можно использовать для реализации TestOps подхода в рамках CI/CD процесса |
| 😎 Advanced | Monitoring, Synthetic tests, Тестирование в production среде, Gradual deployment, A/B testing, Destructive testing |

### 📌 Mobile Automation

| Уровень | Описание |
|---------|----------|
| 🤓 Novice | Android:<br>- Типы мобильных приложений<br>- Что такое Appium?<br>- Locators<br>- Accessibility ID vs ID<br>- Activity/Package<br>- Test scope<br>iOS:<br>- XCUIApplication (start vs launch)<br>- launchEnvironment, launchArguments<br>- XCUIElement<br>- XCUIElementQuery<br>- XCTWaiter<br>- XCTestExpectations<br>- XCTAssert<br>- setUp(), tearDown(), AddTearDownBlock()<br>- Accessibility labels и identifiers<br>- XCUIDevice |
| 🧐 Medium | Android:<br>- Mandatory capability<br>- MobileElement<br>- AppiumDriver<br>- UiAutomator2<br>iOS:<br>(Повторение блока выше – см. оригинал) |
| 😎 Advanced | - Опыт работы с внешними мобильными фермами<br>- CI конфигурация для мобильной автоматизации<br>- Параллельное выполнение мобильных тестов |

### 📌 Mobile device farms

| Уровень | Описание |
|---------|----------|
| 🤓 Novice | Emulator vs simulator, Когда использовать фермы, Плюсы и минусы, Популярные мобильные фермы |
| 🧐 Medium | Настройка удаленной тестовой среды, Конфигурация устройств, Логирование, Отладка, Скриншоты, screencast |
| 😎 Advanced | Параллельное выполнение тестов, CI интеграция, Сбор метрик из прогонов тестов |

### 📌 Message Brokers, Monitoring, Logs

| Уровень | Описание |
|---------|----------|
| 🤓 Novice | Что такое message broker, Примеры, Инструменты сбора логов |
| 🧐 Medium | Что такое topic, Kafka vs RabbitMQ, Инструменты мониторинга |
| 😎 Advanced | Подключение к brokers, Чтение/запись сообщений, Компоненты Kafka |

### 📌 Databases

| Уровень | Описание |
|---------|----------|
| 🤓 Novice | Типы БД, Primary/Foreign keys, CRUD операции, Distinct/order by |
| 🧐 Medium | Опыт работы с БД в автоматизации, Настройка подключения к БД, Relational vs NoSQL, Joins, внутренние запросы, функции, группировка |
| 😎 Advanced | Использование PL/SQL в автоматизации, Views, stored procedures, triggers, indexes |

### 📌 Software Engineering Practices

| Уровень | Описание |
|---------|----------|
| 🤓 Novice | Парадигмы: FP vs OOP, Использование SOLID, Общие паттерны проектирования, Структуры данных (stack, queue, heap) |
| 🧐 Medium | Типы паттернов проектирования, Arrays, linked lists, dictionaries, Пространственная/временная сложность, Конфликты hash table, priority queues |
| 😎 Advanced | B-trees, Fibonacci heap, Red-black trees, Skip lists |

### 📌 TypeScript

| Уровень | Описание |
|---------|----------|
| 🤓 Novice | Типы (Basic, Interface, Functions), Access modifiers, Type vs Interface |
| 🧐 Medium | Составные типы, Enums, Generics, Implements |
| 😎 Advanced | File declaration, Namespaces, Продвинутые generics |

### 📌 JavaScript

| Уровень | Описание |
|---------|----------|
| 🤓 Novice | Типы данных, Объявление переменных, Scoping/Hoisting, Closures, Функции, Массивы, Базовая асинхронность |
| 🧐 Medium | Prototypes, Classes, Call/Bind/Apply, Spread/Rest, Destructuring, Async (Promise/Callbacks/Event loop), RegExp, Обработка ошибок |
| 😎 Advanced | Modules, Пользовательские ошибки, Fibers, Современные возможности языка |