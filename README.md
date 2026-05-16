# Randomizer

A simple, editorial-style random picker for the indecisive.

Add a list of names (or anything else), then either shuffle them into a random order or pick a single winner. Built as a single HTML file — no dependencies, no build step, no backend.

## Live demo

Once published via GitHub Pages: `https://<your-username>.github.io/randomizer/`

## Features

- **Shuffle mode** — randomize the full list into a new order
- **Pick one** — choose a single random winner with a smooth reveal
- **Local save** — your list is stored in the browser via `localStorage`, so it persists between visits
- **No dependencies** — pure HTML, CSS, and JavaScript
- **Mobile-friendly** — responsive layout that works on phones, tablets, and desktops
- **Editorial brutalist design** — bold display serif (Fraunces) paired with mono details (JetBrains Mono)

## Usage

1. Open `index.html` in any modern browser
2. Add names using the input field (press Enter or tap **+ ADD**)
3. Tap **Shuffle** for a random order, or **Pick one** for a single winner
4. Use **Clear all entries** to reset

## Deploy to GitHub Pages

1. Push this repository to GitHub
2. Go to **Settings → Pages**
3. Under **Source**, select the `main` branch and `/ (root)` folder
4. Save — your site will be live at `https://<your-username>.github.io/<repo-name>/` in a minute or two

## File structure

```
randomizer/
├── index.html       # The full app — open this in a browser
├── README.md        # This file
├── LICENSE          # MIT license
└── .gitignore       # Files to ignore in git
```

## Tech

- Plain HTML, CSS, JavaScript
- [Fraunces](https://fonts.google.com/specimen/Fraunces) and [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono) via Google Fonts
- `localStorage` for persistence

## License

MIT — see [LICENSE](LICENSE).
