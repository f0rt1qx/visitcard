# 🖼️ Персональный сайт-визитка

> Минималистичный персональный сайт-портфолио с редакционной эстетикой.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

---

## 📋 Описание проекта

Персональный сайт-визитка, созданный в рамках учебного проекта.
Сайт представляет собой трёхстраничное портфолио с навигацией, анимациями и контактной формой.

**Живой просмотр:** [https://alexmorozov.github.io/portfolio](https://alexmorozov.github.io/portfolio)

---

## 🗂️ Структура проекта

```
portfolio/
├── index.html      # Главная страница — Hero-секция и preview проектов
├── about.html      # Страница «Обо мне» — биография, статистика, навыки
├── contact.html    # Страница контактов — форма и ссылки на соцсети
├── style.css       # Общие стили для всех страниц
└── README.md       # Документация проекта
```

---

## ✨ Функциональность

| Страница       | Описание                                            |
|----------------|-----------------------------------------------------|
| `index.html`   | Hero-блок с именем, описанием и превью проектов     |
| `about.html`   | Статистика, текст о себе, сетка навыков с полосками |
| `contact.html` | Контактная информация + форма обратной связи        |

**Дополнительные детали:**
- Фиксированная навигация с подсветкой активной страницы
- CSS-анимации: плавное появление элементов (`fadeUp`), расширение полосок навыков
- Адаптивная вёрстка — корректно отображается на мобильных устройствах
- Подключены Google Fonts: `Cormorant Garamond` + `DM Mono`
- Базовая валидация контактной формы на JavaScript

---

## 🛠️ Технологии

- **HTML5** — семантическая разметка
- **CSS3** — переменные, Grid, Flexbox, анимации, `backdrop-filter`
- **JavaScript (Vanilla)** — валидация формы
- **Google Fonts** — типографика

---

## 🚀 Запуск проекта

**Вариант 1 — Локально:**
```bash
git clone https://github.com/alexmorozov/portfolio.git
cd portfolio
# Откройте index.html в браузере
open index.html        # macOS
start index.html       # Windows
xdg-open index.html    # Linux
```

**Вариант 2 — Live Server (VS Code):**
```
Установите расширение «Live Server» → ПКМ на index.html → Open with Live Server
```

---

## 🌿 Ветки (Git Workflow)

| Ветка          | Описание                                   |
|----------------|--------------------------------------------|
| `main`         | Стабильная продакшн-версия                 |
| `feature/design-update` | Разработка нового дизайна        |

---

## 📌 История коммитов

```
feat: add contact form with JS validation       # commit 5
feat: add about page with skills grid           # commit 4
feat: add navigation and footer components      # commit 3
style: set up CSS variables and base typography # commit 2
init: project structure and index.html          # commit 1
```

---

## 🎓 Учебные цели

- [x] Создание многостраничного сайта (HTML + CSS)
- [x] Работа с Git: создание репозитория, коммиты, ветки
- [x] Размещение проекта на GitHub Pages
- [x] Оформление документации (README.md)
- [x] Адаптивная вёрстка

---

## 👤 Автор

**Алексей Морозов**

- GitHub: [@alexmorozov](https://github.com/alexmorozov)
- Email: alex@morozov.dev
- Telegram: [@alexmorozov](https://t.me/alexmorozov)

---

*Проект создан в учебных целях. 2025.*
