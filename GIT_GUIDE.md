# 📘 Пошаговая инструкция: Git + GitHub для проекта "Сайт-визитка"

---

## 1️⃣ Подготовка: установка и настройка Git

```bash
# Проверить, установлен ли Git
git --version

# Если не установлен — скачать с https://git-scm.com/

# Первичная настройка (один раз)
git config --global user.name "Ваше Имя"
git config --global user.email "your@email.com"
```

---

## 2️⃣ Инициализация репозитория

```bash
# Перейти в папку проекта
cd путь/к/portfolio

# Инициализировать Git-репозиторий
git init
```

---

## 3️⃣ Создание 5 коммитов (пошагово)

### Коммит 1 — Инициализация проекта

```bash
# Добавить только index.html
git add index.html

git commit -m "init: project structure and index.html"
```

### Коммит 2 — Базовые стили

```bash
git add style.css

git commit -m "style: set up CSS variables and base typography"
```

### Коммит 3 — Навигация и футер

```bash
# Все изменения в html-файлах
git add index.html about.html contact.html

git commit -m "feat: add navigation and footer components"
```

### Коммит 4 — Страница «О себе»

```bash
git add about.html

git commit -m "feat: add about page with skills grid"
```

### Коммит 5 — Контактная форма

```bash
git add contact.html

git commit -m "feat: add contact form with JS validation"
```

---

## 4️⃣ Работа с дополнительной веткой

```bash
# Создать и переключиться на ветку feature/design-update
git checkout -b feature/design-update

# --- Внести изменения в дизайн ---
# (например, изменить цвета или шрифты в style.css)

# Зафиксировать изменения в ветке
git add style.css
git commit -m "feat: update color palette and hover effects"

# Вернуться в main
git checkout main

# Слить ветку в main
git merge feature/design-update

# Удалить ветку (опционально)
git branch -d feature/design-update
```

---

## 5️⃣ Создание репозитория на GitHub

1. Зайти на [github.com](https://github.com)
2. Нажать **New repository** (кнопка «+» в правом верхнем углу)
3. Настройки:
   - Repository name: `portfolio`
   - Description: `Персональный сайт-визитка`
   - Visibility: **Public**
   - ❌ НЕ ставить галочки на README / .gitignore (мы уже создали файлы)
4. Нажать **Create repository**

---

## 6️⃣ Подключение и загрузка на GitHub

```bash
# Подключить удалённый репозиторий (скопировать URL из GitHub)
git remote add origin https://github.com/ВАШ_ЛОГИН/portfolio.git

# Переименовать ветку в main (если нужно)
git branch -M main

# Загрузить код на GitHub
git push -u origin main
```

---

## 7️⃣ Публикация через GitHub Pages (бесплатный хостинг)

1. Открыть репозиторий на GitHub
2. Перейти: **Settings** → **Pages**
3. В разделе **Source** выбрать: Branch `main` / folder `/ (root)`
4. Нажать **Save**
5. Через 1–2 минуты сайт будет доступен по адресу:
   `https://ВАШ_ЛОГИН.github.io/portfolio`

---

## ✅ Чеклист для сдачи проекта

- [ ] `index.html` создан
- [ ] `about.html` создан
- [ ] `contact.html` создан
- [ ] `style.css` создан
- [ ] `README.md` оформлен
- [ ] Минимум **5 коммитов** в истории (`git log --oneline`)
- [ ] Использована **дополнительная ветка** (`feature/...`)
- [ ] Репозиторий **публичный** на GitHub
- [ ] Проект работает через **GitHub Pages**

---

## 🔧 Полезные команды Git

```bash
git status              # Посмотреть состояние файлов
git log --oneline       # Краткая история коммитов
git branch              # Список веток
git diff                # Посмотреть изменения
git add .               # Добавить все изменённые файлы
```
