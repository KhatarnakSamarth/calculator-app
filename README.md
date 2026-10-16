# Tiply

A simple, responsive tip calculator built as a single HTML page with inline CSS and JavaScript.

## Features

- Enter a bill amount and choose a 10%, 15%, 20%, or 25% tip.
- Enter a custom tip percentage when the presets do not fit.
- Split the total between any number of people.
- See the tip, total bill, and per-person amount update instantly.
- Reset the calculator to its starting values.

## Run locally

No build tools or dependencies are required. Open [`index.html`](index.html) in a browser, or serve the folder with any static file server:

```bash
python3 -m http.server
```

Then visit `http://localhost:8000`.

## Project structure

The complete app lives in [`index.html`](index.html), including the markup, responsive styles, and calculator logic.