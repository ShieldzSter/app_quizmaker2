# Quizmaker 2.1

A fully self-contained, interactive quiz builder and player — no frameworks, no dependencies, no server required. One single `index.html` file.

## Features

- **Multiple question types**
  - Multiple choice (single answer)
  - Multiple select (checkboxes)
  - True / False
  - Short answer (text input)
  - Matching pairs
  - Ordering (drag-to-rank)
- **Custom themes** — choose colors, gradients, fonts, and button styles
- **Quiz settings** — passing score threshold, shuffle questions, show/hide feedback
- **Custom pass/fail messages**
- **Live player preview** — test your quiz before publishing
- **Persistent storage** — quizzes are saved in `localStorage` and survive page refreshes
- **Score & results screen** — shows score, pass/fail status, and per-question review

## Getting Started

### Run Locally

1. Download `index.html`
2. Open it in any modern browser (Chrome, Edge, Firefox, Safari)
3. No installation, no build step, no internet connection required

### Deploy to GitHub Pages

1. Push `index.html` to the **root** of your GitHub repository
2. Go to **Settings → Pages**
3. Set Source to `main` branch, `/ (root)` folder
4. Click **Save**
5. Visit your live URL:
   ```
   https://your-username.github.io/your-repo-name/
   ```
   Allow 1–3 minutes for the first deploy to build.

## Usage

1. Click **+ New Quiz** on the home screen
2. Give your quiz a title and configure settings (theme, pass score, etc.)
3. Click **+ Add Slide** to add questions
4. Select a question type, fill in the question and answer options
5. Click **Preview** to test the quiz as a player would see it
6. Quizzes are saved automatically — return any time to edit or play

## File Structure

```
your-repo/
└── index.html    ← The entire app (HTML + CSS + JS, all inline)
└── README.md
```

No additional files are needed. The app has zero external dependencies.

## Browser Support

| Browser | Supported |
|---------|-----------|
| Chrome 90+ | ✅ |
| Edge 90+ | ✅ |
| Firefox 88+ | ✅ |
| Safari 14+ | ✅ |

## Storage

Quizzes are stored in your browser's `localStorage`. They are:
- Private to your browser — not synced to any server
- Persistent across page refreshes and browser restarts
- Cleared if you clear your browser's site data

## License

MIT — free to use, modify, and distribute.
