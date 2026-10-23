# RGNT Group — сайт

Статический сайт: один файл `index.html` (без сборки и зависимостей).
Three.js подгружается с cdnjs, шрифт Inter Tight — с Google Fonts.

## Деплой на Vercel

### Способ 1: через GitHub
1. Создайте репозиторий и загрузите в него эти файлы.
2. На vercel.com: Add New → Project → выберите репозиторий.
3. Framework Preset: **Other**. Build Command и Output Directory оставьте пустыми. Нажмите Deploy.

### Способ 2: через терминал
```
npm i -g vercel
cd rgnt-vercel
vercel login
vercel --prod
```

## Что заменить перед запуском
- Почта `hello@rgnt.group` (поиск по файлу).
- Ссылки на Instagram и LinkedIn (сейчас `href="#"`).
- Cookie-баннер и политика: если подключите аналитику (например, Google Analytics), обновите текст политики.
- Шрифт Suisse Int'l платный: если есть лицензия, добавьте `@font-face` с вашими файлами, он уже стоит первым в списке шрифтов.
