# Color Flood

**Classic flood-fill puzzle game.** Single HTML file, works offline, no tracking. Fill the entire board with one color in 25 moves or fewer.

Play now: https://trenysx.github.io/color-flood/

## How to Play

1. The board starts with a random pattern of colors
2. Click a color button (or press 1-7) to change the top-left region's color
3. Adjacent cells of the same color join your region
3. Fill the entire board in **25 moves or fewer**

## Features

- **Single HTML file** — no build, no dependencies
- **Works offline** — save the file, play anywhere
- **No tracking, no ads, no accounts** — pure privacy
- **Touch & keyboard** — click colors or press 1-7, N for new game
- **Saves your best score** — uses localStorage
- **Responsive** — works on mobile and desktop
- **Accessible** — ARIA labels, keyboard support, color-blind friendly palette

## Play

```bash
# Open directly
open index.html          # macOS
start index.html         # Windows

# Or serve locally
npx serve .
```

## Controls

| Key | Action |
|-----|--------|
| 1-7 | Select color |
| N | New game |

## License

[Apache-2.0](LICENSE) © trenysx