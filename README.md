# CampusFlow — Практическая работа №1

## О проекте
Учебный проект по дисциплине «Веб-разработка и дизайн».
Практическая работа №1: инженерный анализ макета и подготовка фундамента проекта.

## Команды

- `npm install` — установка зависимостей
- `npm run dev` — запуск dev-сервера (http://localhost:5173)
- `npm run build` — production-сборка
- `npm run lint` — проверка JS (ESLint)
- `npm run lint:css` — проверка CSS (Stylelint)
- `npm run format` — форматирование (Prettier)

## Структура проекта

- `index.html` — семантический каркас экрана Каталог
- `decomposition.md` — декомпозиция: страницы, компоненты, состояния
- `src/main.js`, `src/style.css` — точка входа и стили
- `eslint.config.mjs`, `stylelint.config.mjs`, `.prettierrc` — конфиги линтеров

## Статус линтеров

- **ESLint**: конфигурация создана, в среде Node v24 возможны предупреждения о загрузке конфигурации.
- **Stylelint**: конфигурация создана, в среде Windows + Node v24 выдаёт `No configuration provided` (известная проблема).
- **Prettier**: работает нормально.