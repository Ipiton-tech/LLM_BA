---
title: LLM в работе бизнес-аналитика
description: Практическое руководство по использованию языковых моделей (ИИ) в задачах бизнес-анализа.
meta:
  title: "LLM для бизнес-аналитика — Практическое руководство"
  noIndex: false
---

# Использование языковой модели (LLM) в работе бизнес-аналитика

<small>_**Обновлено:** 30.05.2026_</small>

Практическое руководство по применению ИИ-инструментов в задачах бизнес-анализа.

---

::: page-constructor

blocks:
  # Hero-блок с описанием
  - type: 'header-block'
    width: 's'
    offset: 'default'
    title: 'LLM для бизнес-аналитика'
    resetPaddings: true
    verticalOffset: 'l'
    description: 'Практическое руководство по использованию языковых моделей (ИИ) в задачах бизнес-анализа. Узнайте, как повысить качество работы и сэкономить время.'
    background:
      color: '#E8F5EE'
      fullWidth: false
    buttons:
      - text: 'Введение'
        theme: 'outlined'
        size: 'promo'
        url: './pages/intro.md'
      - text: 'Инструменты'
        theme: 'outlined'
        size: 'promo'
        url: './pages/tools-gemini.md'
      - text: 'Сценарии'
        theme: 'outlined'
        size: 'promo'
        url: './pages/scenario-code.md'

:::

---

---

::: page-constructor

blocks:
  # Карточки с ИИ-инструментами
  - type: 'card-layout-block'
    title: 'ИИ-инструменты'
    colSizes:
      all: 12
      md: 6
      sm: 12
    indent:
      top: sm
    children:
      # Карточка Voice2Doc
      - type: 'layout-item'
        content:
          title: '🎙️ Voice2Doc'
          text: 'Транскрибация аудиозаписей встреч и трансформация в документы по шаблонам.'
          links:
            - text: 'Подробнее'
              url: './pages/tools-voice2doc.md'
              theme: 'normal'
              arrow: true
        border: true

      # Карточка Gemini Pro
      - type: 'layout-item'
        content:
          title: '🤖 Gemini Pro'
          text: 'Корпоративный AI-инструмент для анализа кода, рецензирования ТЗ и генерации артефактов.'
          links:
            - text: 'Подробнее'
              url: './pages/tools-gemini.md'
              theme: 'normal'
              arrow: true
        border: true

  # Карточки со сценариями использования
  - type: 'card-layout-block'
    title: 'Сценарии использования Gemini'
    colSizes:
      all: 12
      md: 4
      sm: 6
    indent:
      top: sm
    children:
      - type: 'layout-item'
        content:
          title: '📝 Анализ кода'
          text: 'Разбор кода 1С, генерация документации и тестов.'
          links:
            - text: 'Подробнее'
              url: './pages/scenario-code.md'
              theme: 'normal'
              arrow: true
        border: true

      - type: 'layout-item'
        content:
          title: '✅ Оценка ТЗ'
          text: 'Рецензирование технических заданий и выявление рисков.'
          links:
            - text: 'Подробнее'
              url: './pages/scenario-review.md'
              theme: 'normal'
              arrow: true
        border: true

      - type: 'layout-item'
        content:
          title: '🔧 Доработка ТЗ'
          text: 'Уточняющие вопросы и анализ рисков проекта.'
          links:
            - text: 'Подробнее'
              url: './pages/scenario-improve.md'
              theme: 'normal'
              arrow: true
        border: true

      - type: 'layout-item'
        content:
          title: '📋 Разработка ТЗ'
          text: 'Помощь в написании ТЗ на основе вводных данных.'
          links:
            - text: 'Подробнее'
              url: './pages/scenario-develop.md'
              theme: 'normal'
              arrow: true
        border: true

      - type: 'layout-item'
        content:
          title: '⏱️ Оценка задач'
          text: 'Почему ИИ не подходит для оценки трудоёмкости.'
          links:
            - text: 'Подробнее'
              url: './pages/scenario-estimate.md'
              theme: 'normal'
              arrow: true
        border: true

      - type: 'layout-item'
        content:
          title: '📊 Блок-схемы'
          text: 'Возможности и ограничения ИИ для блок-схем.'
          links:
            - text: 'Подробнее'
              url: './pages/scenario-flowchart.md'
              theme: 'normal'
              arrow: true
        border: true

:::

---
