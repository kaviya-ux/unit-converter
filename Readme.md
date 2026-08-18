# Unit Converter

A simple, single-file unit converter built with HTML, Tailwind CSS, and vanilla JavaScript. Convert between length, weight, and temperature units instantly — no build tools, no dependencies, no backend.

## Features

- Convert between three categories: **Length**, **Weight**, and **Temperature**
- Length: meters, kilometers, centimeters, millimeters, miles, yards, feet, inches
- Weight: grams, kilograms, milligrams, pounds, ounces
- Temperature: Celsius, Fahrenheit, Kelvin
- Instant results as you type — no "convert" button needed
- Clean, responsive UI styled with Tailwind CSS

## Tech Stack

- HTML5
- [Tailwind CSS](https://tailwindcss.com/) (via CDN)
- Vanilla JavaScript (no frameworks, no libraries)

## How It Works

- Length and weight conversions go through a common **base unit** (meters for length, grams for weight). Every value is first converted to the base unit, then converted from the base unit to the target unit.
- Temperature is handled separately since it isn't a simple multiplication — it uses the standard Celsius/Fahrenheit/Kelvin formulas.

## Running Locally

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/unit-converter.git
   ```
2. Open `index.html` in your browser.

No installation, no npm, no build step required.

## Possible Improvements

- Add more categories (area, volume, speed)
- Add a swap button to flip "from" and "to" units
- Add keyboard shortcuts
- Persist last-used units with localStorage

## License

Free to use for learning or personal projects.
