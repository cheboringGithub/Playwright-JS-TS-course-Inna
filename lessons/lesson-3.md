---
layout: default
title: Занятие 3
---
<a href="{{ site.baseurl }}" class="main-link-home">&#8592; На главную</a>

# Занятие 3

---

## Тема 1: CI/CD

**Основные вопросы:**
- Что такое *CI* (`Continuous Integration`) и *CD* (`Continuous Delivery`/`Deployment`)?
- Какие задачи решает *CI/CD*?
- Какие существуют популярные инструменты для *CI/CD*?
- Что такое `GitHub Actions` и как они работают?
- Как настроить простой *workflow* в `GitHub Actions`?

**Полезные ссылки:**
- [Документация GitHub Actions](https://docs.github.com/en/actions)
- [Видео с теорией и примерами](https://www.youtube.com/watch?v=e0A2hDObLmg)

---

## Тема 2: Docker

**Основные вопросы:**
- Что такое *контейнеризация*?
- В чем отличие контейнеризации от виртуализации?
- Какие преимущества даёт использование `Docker`?
- Как устроен `Dockerfile`?
- Как собрать и запустить контейнер в `Docker`?
- Как использовать `Docker Compose`?
- Что такое `Docker image`?
- Что такое `Kubernetes`?
- Какие проблемы решает `Kubernetes` и почему иногда просто `Docker` недостаточно?

**Полезные ссылки:**
- [Официальная документация Docker](https://docs.docker.com/)
- [Мануалы по различным темам](https://docs.docker.com/manuals/)

---

## Практическая часть

- Создать *pipeline* (`workflow`) в `GitHub Actions`, который запускается вручную (`workflow_dispatch`) с возможностью выбора браузера и сьюта тестов.
- Создать *pipeline*, который запускается по расписанию (`cron`).

**Полезные ссылки:**
- [Документация Playwright по интеграции](https://playwright.dev/docs/ci-intro#setting-up-github-actions)
- [GitHub Actions: Events that trigger workflows](https://docs.github.com/en/actions/using-workflows/events-that-trigger-workflows)
- [GitHub Actions: Workflow syntax for GitHub Actions](https://docs.github.com/en/actions/using-workflows/workflow-syntax-for-github-actions)
- [Документация по cron](https://crontab.guru/) 