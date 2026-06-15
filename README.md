# PG for MySQL Devs

An interactive, single-page field guide for experienced MySQL developers learning PostgreSQL. Skips the SQL basics you already know and focuses on the dialect differences, gotchas, and upgrades — auto-increment vs. sequences, quoting rules, JSONB, upserts, indexing, and more.

**[Live demo →](https://pg-for-mysql-devs.vercel.app)**

## Features

- **Side-by-side translations** — every concept shown as "MySQL way" vs "PostgreSQL way"
- **Searchable cheat sheet** — filter ~25 quick syntax translations
- **Self-check quiz** — 5 questions with explanations
- **Progress tracking** — mark modules done, see your progress in the sidebar
- **Copy buttons** — one click to copy any code snippet
- **Responsive** — works on desktop and mobile

## Tech

Single self-contained HTML file. No build step, no dependencies, no framework. Fonts load from Google Fonts CDN with system font fallbacks.

## Running locally

Just open `index.html` in a browser, or serve it:

```bash
npx serve .
```


## Contributing

Found an inaccuracy or a missing gotcha? Open an issue or PR — corrections and additional MySQL↔Postgres translations are welcome.

## License

MIT
