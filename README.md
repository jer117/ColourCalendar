# Colour Calendar

A simple interactive calendar where you can colour days by category (Work, China, Nepal, Korea, India, United Arab Emirates). Click any day to cycle through colours; use the arrows to change months.

## How to run in the browser

### Option 1: Open the standalone HTML file (easiest)

1. **Double-click**  
   Open `index.html` in your project folder in any modern browser (Chrome, Firefox, Safari, Edge).

2. **Or from the terminal**  
   From the project folder, start a small server so the file is served correctly (recommended if you see any loading issues):

   ```bash
   cd /**path**/ColourCalendar
   npx --yes serve .
   ```

   Then open: **http://localhost:3000** (or the URL shown in the terminal).

   To stop the server: press `Ctrl+C` in the terminal.

## Files

| File | Description |
|------|-------------|
| `index.html` | Standalone version you can open or serve in a browser. |

## Features

- Navigate months with the left/right arrows.
- Click a day to cycle its colour (None → Work → China → Nepal → Korea → India → UAE → None).
- Colour choices are kept per day as you switch months.
