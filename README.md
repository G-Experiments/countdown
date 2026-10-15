# Reisiger 1000 Days

Office countdown display: **θ days < λ assets < α distributions**.

Live at **https://g-experiments.github.io/countdown/** — open it on any screen, no login needed.

## Updating the numbers

Edit [`counts.json`](counts.json) on GitHub (pencil icon → change → *Commit changes*):

```json
{
  "start": "2026-10-15",
  "assets": 12,
  "distributions": 3,
  "updated": "2026-11-02"
}
```

| Field | Meaning |
|---|---|
| `start` | Day 1 of the 1000-day countdown (midnight SAST) |
| `assets` | Assets created |
| `distributions` | Distribution networks unlocked |
| `updated` | Date shown in the footer as "Updated …" |

Open screens pick up the change within about 2–5 minutes (GitHub Pages deploy + the page's 2-minute check). Press **F** for full screen on a keyboard-equipped screen.
