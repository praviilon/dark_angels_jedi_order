# Dark Angels Jedi Order

The restored website of Dark Angels Jedi Order (DAJ) Roleplay Clan for the game Star Wars Jedi Knight 3: Jedi Academy.
The original website  (`dajclan.webs.com`) was hosted on webs.com.
It has been restored using Wayback Machine backups.

Site Structure:

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
├── style.css                       — style file
└── assets/
    ├── daj-logo.png                 — Clan logo
    └── daj-padawan-tree.jpg         — Padawan-Master Tree image
```

The site doesn't use any build tools, frameworks, or npm dependencies — it's plain static
files that can be opened locally (by double-clicking `index.html`) or deployed to any
static hosting service, including GitHub Pages.

## Updating content

Each page is a regular HTML file. Text lives inside `<section class="panel">…</section>`
blocks. To change the text, open the relevant `.html` file in any text editor and edit
the content between the `<p>…</p>` tags.

## Deploying to GitHub Pages

See the instructions provided separately (or the "Deploy" section in the chat history).
