# Regexa

Regexa breaks down any regex pattern token by token and explains each part in plain English, while highlighting matches live as you type.

## What it does

- **Token explainer** — type a pattern and each piece gets explained individually (e.g. `\d+` → "one or more digits")
- **Live match highlighting** — paste any text and see matches highlight in real time as you edit your pattern
- **Common patterns library** — click to load email, URL, phone number, hex color, date, and more
- **Cheat sheet** — quick reference for the most used regex tokens, always visible on the side
- **Flag support** — toggle `g`, `i`, `m` and other flags directly in the input

## How to use it

Just open the site and start typing.

Live site: `https://ManuCovr.github.io/regexa`

A pattern like `\d{3}-\d{4}` will immediately show you:

```
\d   → any digit (0–9)
{3}  → exactly 3 times
-    → literal "-"
\d   → any digit (0–9)
{4}  → exactly 4 times
```

## Running it locally

Single HTML file, nothing to install.

```bash
git clone https://github.com/ManuCovr/regexa.git
cd regexa
npx serve .
```

Or just open `index.html` directly in your browser.

## Built with

- Vanilla HTML, CSS, JS
- All regex parsing and match highlighting done with native browser APIs

## Fork it

1. Fork the repo
2. Go to Settings → Pages → deploy from `main`
3. Live at `https://ManuCovr.github.io/regexa`

## License

MIT

```
MIT License

Copyright (c) 2025 Manuel Bernardes

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
