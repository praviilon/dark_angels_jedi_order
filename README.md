# Dark Angels Jedi Order Website

The restored website of Dark Angels Jedi Order (DAJ) Roleplay Clan for the game Star Wars Jedi Knight 3: Jedi Academy.
The original website was hosted on webs.com and is no longer accessible.
It has been restored using Wayback Machine backups.

- [Link to the restored website](https://praviilon.github.io/dark_angels_jedi_order/index.html)
<!-- {- [Link to the archive of the original website](https://web.archive.org/web/20210307102104/http://www.dajclan.webs.com/)} -->

## Site Structure

```

├── index.html                      — Homepage
├── the-memorial-ground.html        — The Memorial Ground
├── saber-forms.html                — Saber Forms
├── daj-constitution.html           — DAJ Constitution
├── daj-teachings.html              — DAJ Teachings
├── daj-downloads.html              — DAJ Downloads
├── daj-history.html                — DAJ History
├── roleplay-and-duel-guides.html   — Roleplay and Duel Guides
├── style.css                       — Stylesheet
└── assets/
    ├── daj-logo.png                 — Clan logo
    └── daj-padawan-tree.svg         — Padawan-Master Tree image
```

The site doesn't use any build tools, frameworks, or npm dependencies — it's plain static
files that can be opened locally or deployed to any
static hosting service.

## Updating content

Each page is a regular HTML file. Text lives inside `<section class="panel">…</section>`
blocks. To change the text, open the relevant `.html` file in any text editor and edit
the content between the `<p>…</p>` tags.
