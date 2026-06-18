# u-buyer.com — китайский лендинг UBuyer

Статический лендинг для китайских селлеров Wildberries.

## Стек
- Статический HTML + CSS (без сборки)
- Хостинг: Cloudflare Pages → автодеплой при `git push` в `main`
- Домен: `u-buyer.com`

## Структура
```
.
├── index.html       Главная страница (китайский лендинг)
├── favicon.svg      Иконка (янтарная точка)
├── robots.txt       Открыт для индексации
└── _headers         Cloudflare HTTP-заголовки + кеш
```

## Деплой
Любой push в `main` автоматически разворачивается на Cloudflare Pages.

```bash
git add .
git commit -m "update: …"
git push
```

## Связь с основным проектом
Исходники и черновики лежат в репо «Самовыкупы»:
[13_СЕГМЕНТ-КИТАЙЦЫ/](https://github.com/TimWin93/samovikupy) (приватный).

Реальные изменения вносим только в этом репо — это источник правды для prod.
