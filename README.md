# Colour Calendar

A simple interactive calendar where you can colour days by category (Work, China, Nepal, Korea, India, United Arab Emirates). Click any day to cycle through colours; use the arrows to change months.

## How to run in the browser

### Option 1: Open the standalone HTML file (easiest)

1. **Double-click**  
   Open `index.html` in your project folder in any modern browser (Chrome, Firefox, Safari, Edge).

2. **Or from the terminal**  
   From the project folder, start a small server so the file is served correctly (recommended if you see any loading issues):

   ```bash
   cd /Users/jeremiahosullivan/Development/ColourCalendar
   npx --yes serve .
   ```

   Then open: **http://localhost:3000** (or the URL shown in the terminal).

   To stop the server: press `Ctrl+C` in the terminal.

### Option 2: Use the React component in your own app

`ColourCalendar.html` is a React component (JSX). To use it in a React app (e.g. Vite):

1. Copy the component into your app (e.g. `src/components/ColorCalendar.jsx`).
2. Install dependencies: `react`, `lucide-react`, and Tailwind CSS.
3. Import and render `<ColorCalendar />` in your app.

## Files

| File | Description |
|------|-------------|
| `index.html` | Standalone version you can open or serve in a browser. |
| `ColourCalendar.html` | React component source (for use in a React project). |

## Features

- Navigate months with the left/right arrows.
- Click a day to cycle its colour (None → Work → China → Nepal → Korea → India → UAE → None).
- Colour choices are kept per day as you switch months.
