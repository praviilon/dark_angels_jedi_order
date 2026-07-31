# Dark Angels Jedi Order — сайт клана

Восстановленная версия сайта **Dark Angels Jedi Order (DAJ)** — Star Wars: Jedi Academy roleplay-клана.
Оригинальный сайт (`dajclan.webs.com`) хостился на webs.com и перестал быть доступен напрямую;
контент восстановлен из копий в [Wayback Machine](https://web.archive.org/web/20210307102104/http://www.dajclan.webs.com/)
и пересобран в виде простого статического сайта на чистом HTML/CSS — без зависимостей от какого-либо движка
или платформы, кроме браузера.

## Структура

```
.
├── index.html                      — Главная
├── the-memorial-ground.html        — The Memorial Ground
├── saber-forms.html                — Saber Forms
├── daj-constitution.html           — DAJ Constitution
├── daj-teachings.html              — DAJ Teachings
├── daj-downloads.html              — DAJ Downloads
├── daj-history.html                — DAJ History
├── roleplay-and-duel-guides.html   — Roleplay and Duel Guides
├── style.css                       — Единый файл стилей
└── assets/
    ├── daj-logo.png                 — Логотип клана
    └── daj-padawan-tree.jpg         — Padawan-Master Tree
```

Сайт не использует сборщики, фреймворки или npm-зависимости — это чистые статические файлы,
которые можно открыть локально (двойным кликом по `index.html`) или разместить на любом
статическом хостинге, включая GitHub Pages.

## Как обновить контент

Каждая страница — обычный HTML-файл. Текст лежит внутри блоков `<section class="panel">…</section>`.
Чтобы изменить текст, откройте нужный `.html` файл в любом текстовом редакторе и отредактируйте
содержимое между тегами `<p>…</p>`.

## Размещение на GitHub Pages

См. инструкцию, приложенную отдельно (или раздел "Deploy" в истории чата).
