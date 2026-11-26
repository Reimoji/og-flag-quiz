# Flag Rush

A timed flag quiz in the browser. It covers all 193 UN member states, plus the two UN observer states (Vatican City and Palestine).

## Games

- **Name the flag** – one flag, four country names.
- **Find the flag** – one country name, four flags.

## Difficulty

- **Easy** – about 70 well-known flags, wrong answers picked at random.
- **Medium** – all 195 flags, wrong answers from the same region.
- **Hard** – only flags with look-alikes (Pan-Arab tricolours, Nordic crosses, Chad / Romania, Indonesia / Monaco …). The wrong answers come from the same look-alike family.

15 flags per round, 10 seconds each. A right answer scores 50, plus up to 100 more for speed. Best scores are kept in the browser's local storage. Keys 1–4 answer, Enter moves on.

## Run locally

The page loads `flags.json` with `fetch`, so open it through a local server rather than double-clicking the file:

```bash
python3 -m http.server 8000
```

Then go to http://localhost:8000.

## Host on GitHub Pages

Settings → Pages → Deploy from a branch → `main` / root.

## Credits

Flag images: [flag-icons](https://github.com/lipis/flag-icons) v7.2.3 by Panayiotis Lipiridis, MIT licence (see `LICENSE-flag-icons`). All flags are drawn at 4:3.
