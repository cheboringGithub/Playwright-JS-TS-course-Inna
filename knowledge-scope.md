## Manual testing (Processes)

### 📌 Processes, Methodologies
**Темы:**
- agile
- scrum
- kanban
- waterfall
- kaskad
- bdd
- tdd

| Уровень | Описание |
|--------|----------|
| 🤓 Novice | - может перечислить методологии<br>- может рассказать об общих различиях между методологиями |
| 🧐 Medium | - имеет опыт работы с одним из Agile фреймворков (методологий)<br>- может перечислить атрибуты Scrum и Kanban |
| 😎 Advanced | - имеет опыт внедрения микропроцессов тестирования в рамках методологии<br>- может описать моменты, которые можно улучшить в текущем проекте |

### 📌 Estimations
**Темы:**
- Estimations experience
- Functionality points
- Story points
- Scrum poker
- Gantt Chart & Project Planning

| Уровень | Описание |
|--------|----------|
| 🤓 Novice | - опыт оценки личных задач |
| 🧐 Medium | - имеет опыт оценки задач<br>- принимает участие в общей оценке задач команды (planning poker) |
| 😎 Advanced | - имеет опыт общей оценки проекта и планирования релизов |

### 📌 Test documentation and bug tracking systems
**Темы:**
- test case
- check list
- bug report
- test plan
- test strategy
- Jira
- TFS
- Redmine
- Reports
- Boards & dashboards
- Plugins & Tuning
- Queries

| Уровень | Описание |
|--------|----------|
| 🤓 Novice | - артефакты тестирования: test cases, check lists, bug reports<br>- имеет опыт работы с артефактами тестирования на проекте с использованием системы отслеживания багов |
| 🧐 Medium | - объясняет разницу между test case и check list<br>- severity и priority - определяет их для frontend или backend бага (например, сломанная кнопка)<br>- test plan<br>- test strategy<br>- имеет опыт создания сложных запросов и выборок в системе отслеживания багов |
| 😎 Advanced | - test plan vs test strategy - Организационная документация процесса тестирования: Test Policy & Organizational Test Strategy<br>- имеет опыт создания и работы с дашбордами в системе отслеживания багов |

## Automation testing

### 📌 Automation testing, basic theory
**Темы:**
- automation testing types
- testing pyramid (reverse testing pyramid)
- implementation automation criteria on the project

| Уровень | Описание |
|--------|----------|
| 🤓 Novice | - Что такое test automation<br>- Какие проблемы решает test automation<br>- Зачем нужен test automation<br>- Цели test automation<br>- Применим ли test automation ко всем проектам или типам тестов или нет? |
| 🧐 Medium | - Test automation с точки зрения QA, QC и testing<br>- Classic test pyramid<br>- Inverted test pyramid<br>- Фигура тестирования без разделения на frontend и backend<br>- Unit testing<br>- Integration testing<br>- UI testing<br>- Performance testing<br>- Security testing<br>- E2E testing<br>- Regression testing<br>- Functional testing<br>- Acceptance testing |
| 😎 Advanced | - Test strategy и milestone (по порядку) внедрения test automation в проект<br>- Фигура тестирования для frontend проекта<br>- Фигура тестирования для backend проекта |

### 📌 Version Control System - Git
**Темы:**
- git basics
- git branching
- git commands

| Уровень | Описание |
|--------|----------|
| 🤓 Novice | - Version Control System (что это и зачем нужно)<br>- Как клонировать проект<br>- Рассказать о Git командах: git pull, git push, git commit (в случае если собеседуемый работал с Git)<br>- git branch<br>- Как сделать локальную ветку удаленной<br>- git config (установить имя и email) |
| 🧐 Medium | - опция '--hard' (для git fetch или git reset) или как перезаписать локальные изменения удаленными<br>- Как перенести изменения с одной ветки на другую (3 способа)<br>- git rebase (что это и как работает, как откатить rebase)<br>- git reset<br>- git stash, .gitignore<br>- git log (как просматривать историю изменений)<br>- создание, ревью и слияние pull (merge) requests |
| 😎 Advanced | - git cherry-pick (как выбирать коммиты)<br>- git submodules (как добавить submodule, обновить или удалить его)<br>- git hooks |

### 📌 CI, CD
**Темы:**
- CI
- Continuous Delivery
- Continuous Deployment
- Jenkins
- Team City
- Bamboo
- TFS
- Gitlab vs CircleCi

| Уровень | Описание |
|--------|----------|
| 🤓 Novice | - Что такое CI<br>- Слышал о CI инструментах (Jenkins, TeamCity, TFS) |
| 🧐 Medium | - Имеет опыт работы с CI на проекте<br>- Может рассказать о CI pipeline на примере test pyramid и коммита разработчика в монолитном продукте<br>- Имеет опыт работы с одним из CI инструментов<br>- В чем разница между Continuous Delivery и Continuous Deployment |
| 😎 Advanced | - Имеет опыт настройки CI на проекте с микросервисной или сервисной архитектурой, может рассказать о pipeline<br>- Infrastructure as code в CI<br>- Имеет опыт настройки CD<br>- Имеет опыт работы с Sonar и linter инструментами |

### 📌 Automation Tools (frameworks)
**Темы:**
- Playwright

| Уровень | Описание |
|--------|----------|
| 🤓 Novice | - Рассказать об инструменте, с которым работал (в общем - что это за инструмент и что он умеет)<br>- Рассказать из каких блоков (частей) состоит тест<br>- О каких еще фреймворках слышал<br>- Как запустить/пропустить отдельный тест |
| 🧐 Medium | - Критерии выбора фреймворка<br>- Рассказать о hooks (before, after и так далее, различия между ними)<br>- Рассказать о конфигурационном файле для своего фреймворка<br>- Как запускать тесты по тегам<br>- Возможно ли запускать тесты параллельно? Если да - как это сделать?<br>- Как подключить reporter |
| 😎 Advanced | - Интеграция с CI инструментами<br>- Интеграция с TMS (test management systems)<br>- Расширение базовых возможностей фреймворка |

### 📌 Project management and comprehension tool (package manager)
**Темы:**
- npm
- nodeJS

| Уровень | Описание |
|--------|----------|
| 🤓 Novice | - Зачем они нужны<br>- О каких инструментах слышал<br>JS:<br>- Как установить библиотеку<br>- npm<br>- yarn (просто знать что существует) |
| 🧐 Medium | npm/yarn: {<br>package.json:<br>- Из каких блоков состоит<br>- Как запустить скрипт и как запустить с переменными<br>- Разница между dependencies/devDependencies - как установить пакет в эти блоки и как НЕ устанавливать dev при production деплое<br>- Что такое package-lock.json/yarn.lock файл и зачем он нужен. Нужно ли коммитить lock файл в репозиторий?<br>- Что такое SemVer? Что означают знаки в версии (^ ~ * и простое строгое определение версии). Какая версия библиотеки установлена в случае наличия lock файла и знака ^ в версии библиотеки? |
| 😎 Advanced | - Использование внешних репозиториев<br>- Параметризация при конфигурации (или установке) пакета |

### 📌 Locators
**Темы:**
- css
- xpath
- jquery
- document.querySelector()

| Уровень | Описание |
|--------|----------|
| 🤓 Novice | - Различия между CSS и XPath<br>- Что можно использовать для поиска элементов? Какие атрибуты можно использовать для этого?<br>- Найти элемент по CSS и по XPath |
| 🧐 Medium | - Дать задачу с :not в CSS и not contains в XPath<br>- Для чего нужны локаторы .// и ./?<br>- XPath axes<br>- document.querySelector() - что это и что может делать<br>- Что такое jQuery |
| 😎 Advanced | - Условный XPath (OR и так далее)<br>- Параметризированный составной локатор<br>- Поиск псевдоэлементов ::before, ::after<br>- Shadow root или shadow dom |

### 📌 Browser initialization
**Темы:**
- singleton
- multiton
- prototype
- factory method
- abstract factory
- remote webdriver
- browser capabilities
- browser options
- headless

| Уровень | Описание |
|--------|----------|
| 🤓 Novice | - Что такое Selenium WebDriver?<br>- Где можно записать пути к драйверам?<br>- Реализация инициализации WebDriver<br>- Браузерные движки (gecko, webKit, edge) |
| 🧐 Medium | - Реализация инициализации Singleton, abstract factory<br>- Browser capabilities<br>- Browser multiCapabilities<br>- Remote webdriver<br>- Headless mode |
| 😎 Advanced | - Реализация собственной обертки элементов<br>- Реализация и инициализация multiton или prototype<br>- Подводные камни headless mode<br>- Selenium logging |

### 📌 BDD
**Темы:**
- Cucumber

| Уровень | Описание |
|--------|----------|
| 🤓 Novice | - Gherkin стиль<br>- Feature<br>- Scenario<br>- Step |
| 🧐 Medium | - Общий смысл BDD подхода в команде<br>- Обзор BDD случаев<br>- Правила для дизайна scenarios и features |
| 😎 Advanced | - Процедура разработки BDD scenario и его последующей автоматизации<br>- Архитектура BDD фреймворка для автоматизации тестов |

### 📌 Waiters
**Темы:**
- explicit wait
- implicit wait
- js executor

| Уровень | Описание |
|--------|----------|
| 🤓 Novice | - Типы waiters<br>- Различия между типами waiters |
| 🧐 Medium | - Типы explicit wait<br>- Типы implicit wait<br>- Пример реализации explicit wait<br>- Почему sleep плохая практика |
| 😎 Advanced | - Fluent wait<br>- Ожидание загрузки DOM дерева (JSExecutor)<br>- Ожидание ответов AJAX запросов (JSExecutor)<br>- Ожидание видимости элемента с использованием displayed<br>- Как сделать собственные expected conditions |

### 📌 REST, SOAP, WebSockets
**Темы:**
- REST
- SOAP
- WebSockets
- CRUD
- JSON
- XML
- serialization
- deserialization
- http libs

| Уровень | Описание |
|--------|----------|
| 🤓 Novice | - Теоретические знания (что такое REST, SOAP, разница между ними)<br>- HTTP методы<br>- Что такое идемпотентность и какие методы идемпотентны<br>- Разница GET/POST, PUT/POST<br>- Инструменты для отправки HTTP запросов (cURL, Postman) |
| 🧐 Medium | - JSON, XML<br>- Serialization, deserialization<br>- Использование библиотек для работы с протоколами<br>- Что такое WebSocket и как он работает?<br>- CORS (что это и общее описание workflow) |
| 😎 Advanced | - GraphQL<br>- Requests pipeline |

### 📌 Framework architecture
**Темы:**
- Page Object
- Multi Layered architecture
- Test writing criteria

| Уровень | Описание |
|--------|----------|
| 🤓 Novice | - Понимание Page Object паттерна<br>- Понимание 3-слойной архитектуры |
| 🧐 Medium | - Имеет опыт разработки фреймворка автоматизации тестов на основе 3-слойной архитектуры<br>- Понимание 4-слойной и 5-слойной архитектуры<br>- Понимание Page Element паттерна<br>- Сколько слоев нужно для автоматизированных тестов в Gherkin стиле |
| 😎 Advanced | - Имеет опыт применения различных типов слоистой архитектуры в фреймворках автоматизации тестов для UI и API тестов<br>- Архитектура на основе проекта разработчиков (плюсы, минусы)<br>- Архитектура на основе компонентов<br>- Микросервисная архитектура<br>- Архитектура contract testing |

### 📌 Loggers, reporters, metrics
**Темы:**
- playwright html report
- allure
- report portal
- extended report
- html report
- junit reporter
- htm reporter

| Уровень | Описание |
|--------|----------|
| 🤓 Novice | - Что такое reporter, зачем они нужны<br>- Как подключить HTML reporter под используемый инструмент |
| 🧐 Medium | - Имеет опыт работы с популярными reporter (Allure, Report Portal)<br>- Паттерны проектирования, которые используются для reporting (delegate, decorator)<br>- Базовые метрики автоматизации тестирования |
| 😎 Advanced | - Code coverage, инструменты для него, организация инфраструктуры и принципы построения code coverage<br>- Организация и хранение отчетов под CI инструментом vs база данных<br>- Переопределение методов популярных reporter (Allure, Report Portal) |

### 📌 Virtualization, containerization
**Темы:**
- docker
- ansible
- kubernetes
- agent
- TFS
- Jenkins
- Team City
- Bamboo
- Azure Services
- Selenoid
- Selenium grid

| Уровень | Описание |
|--------|----------|
| 🤓 Novice | - Понимание разницы между виртуализацией и контейнеризацией<br>- Для чего нужна виртуализация?<br>- Какие проблемы помогает решить виртуализация?<br>- Преимущества контейнеризации при разработке автоматизированных тестов<br>- Типы виртуализации |
| 🧐 Medium | - Преимущества виртуализации<br>- Кратко рассказать о жизненном цикле Docker контейнера<br>- Что такое Dockerfile? Как его использовать?<br>- Docker Hub<br>- Container и image<br>- Base image |
| 😎 Advanced | - Оркестрация контейнеров<br>- Что такое Docker Swarm?<br>- Kubernetes<br>- Как определить node в Kubernetes?<br>- Какие недостатки есть у Kubernetes?<br>- Что означает docker_host? |

### 📌 Test OPS
**Темы:**
- TestOps
- AWS (Certification)
- Microsoft Azure
- Google Developers

| Уровень | Описание |
|--------|----------|
| 🤓 Novice | - Что такое TestOps?<br>- TestOps VS DevOps |
| 🧐 Medium | - Test coverage<br>- Zero Bug Policy<br>- Какие механизмы или инструменты можно использовать для реализации TestOps подхода в рамках CI/CD процесса |
| 😎 Advanced | - Monitoring<br>- Synthetic tests<br>- Тестирование в production среде<br>- Gradual deployment<br>- A/B testing<br>- Destructive testing |

### 📌 Mobile Automation
**Темы:**
- Appium
- Selendroid
- Espresso
- Kaspresso
- Xamarin.UITest
- XCUITest
- TestProject
- Detox

| Уровень | Описание |
|--------|----------|
| 🤓 Novice | Android:<br>- Типы мобильных приложений<br>- Что такое Appium?<br>- Locators<br>- Accessibility ID vs ID<br>- Activity/Package<br>- Test scope<br>iOS:<br>- XCUIApplication (start vs launch)<br>- launchEnvironment, launchArguments<br>- XCUIElement<br>- XCUIElementQuery<br>- XCTWaiter<br>- XCTestExpectations<br>- XCTAssert<br>- setUp(), tearDown(), AddTearDownBlock()<br>- Accessibility labels и identifiers<br>- XCUIDevice |
| 🧐 Medium | Android:<br>- Mandatory capability<br>- MobileElement<br>- AppiumDriver<br>- UiAutomator2<br>iOS:<br>(Повторение блока выше – см. оригинал) |
| 😎 Advanced | - Опыт работы с внешними мобильными фермами<br>- CI конфигурация для мобильной автоматизации<br>- Параллельное выполнение мобильных тестов |

### 📌 Mobile device farms
**Темы:**
- BrowserStack
- Kobiton
- AWS Device Cloud
- Xamarin Test Cloud

| Уровень | Описание |
|--------|----------|
| 🤓 Novice | - Emulator vs simulator<br>- Когда использовать фермы<br>- Плюсы и минусы<br>- Популярные мобильные фермы |
| 🧐 Medium | - Настройка удаленной тестовой среды<br>- Конфигурация устройств<br>- Логирование<br>- Отладка<br>- Скриншоты, screencast |
| 😎 Advanced | - Параллельное выполнение тестов<br>- CI интеграция<br>- Сбор метрик из прогонов тестов |

### 📌 Message Brokers, Monitoring, Logs
**Темы:**
- Kafka
- RabbitMQ
- ActiveMQ
- Kibana
- Splunk
- LogCat
- Sentry
- Zabbix
- Datadog
- Grafana

| Уровень | Описание |
|--------|----------|
| 🤓 Novice | - Что такое message broker<br>- Примеры<br>- Инструменты сбора логов |
| 🧐 Medium | - Что такое topic<br>- Kafka vs RabbitMQ<br>- Инструменты мониторинга |
| 😎 Advanced | - Подключение к brokers<br>- Чтение/запись сообщений<br>- Компоненты Kafka |

### 📌 Databases
**Темы:**
- MS SQL
- PL/SQL
- Oracle
- NoSQL
- PostgreSQL
- Indexes
- Triggers
- Views

| Уровень | Описание |
|--------|----------|
| 🤓 Novice | - Типы БД<br>- Primary/Foreign keys<br>- CRUD операции<br>- Distinct/order by |
| 🧐 Medium | - Опыт работы с БД в автоматизации<br>- Настройка подключения к БД<br>- Relational vs NoSQL<br>- Joins, внутренние запросы, функции, группировка |
| 😎 Advanced | - Использование PL/SQL в автоматизации<br>- Views, stored procedures, triggers, indexes |

### 📌 Software Engineering Practices
**Темы:**
- OOP
- Functional programming
- SOLID
- Code Standards
- Smells
- Refactoring
- Review
- Debugging

| Уровень | Описание |
|--------|----------|
| 🤓 Novice | - Парадигмы: FP vs OOP<br>- Использование SOLID<br>- Общие паттерны проектирования<br>- Структуры данных (stack, queue, heap) |
| 🧐 Medium | - Типы паттернов проектирования<br>- Arrays, linked lists, dictionaries<br>- Пространственная/временная сложность<br>- Конфликты hash table, priority queues |
| 😎 Advanced | - B-trees<br>- Fibonacci heap<br>- Red-black trees<br>- Skip lists |

### 📌 TypeScript
**Темы:**
- TS Basics
- Type System
- Compiler
- Interfaces
- Generics
- Modifiers

| Уровень | Описание |
|--------|----------|
| 🤓 Novice | - Типы (Basic, Interface, Functions)<br>- Access modifiers<br>- Type vs Interface |
| 🧐 Medium | - Составные типы<br>- Enums<br>- Generics<br>- Implements |
| 😎 Advanced | - File declaration<br>- Namespaces<br>- Продвинутые generics |

### 📌 JavaScript
**Темы:**
- Data types
- Scoping
- Operators
- Arrays
- Closures
- Prototypes
- Classes
- Inheritance
- Promises
- Event Loop
- RegExp

| Уровень | Описание |
|--------|----------|
| 🤓 Novice | - Типы данных<br>- Объявление переменных<br>- Scoping/Hoisting<br>- Closures<br>- Функции<br>- Массивы<br>- Базовая асинхронность |
| 🧐 Medium | - Prototypes<br>- Classes<br>- Call/Bind/Apply<br>- Spread/Rest<br>- Destructuring<br>- Async (Promise/Callbacks/Event loop)<br>- RegExp<br>- Обработка ошибок |
| 😎 Advanced | - Modules<br>- Пользовательские ошибки<br>- Fibers<br>- Современные возможности языка |