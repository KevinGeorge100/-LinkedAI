# LinkedAI

An AI-powered, client-side dashboard utility for automating job scraping and pipeline generation using custom Boolean constructs and strict ID-based filtering.

## Features
- **Zero-Dependency Architecture**: Runs entirely locally in your browser. Single HTML file.
- **Strict ID Mapping**: Bypass fuzzy matching by strictly scraping LinkedIn using numeric Company IDs.
- **Dynamic Dork Generation**: Automatically converts your target list into a Google Dork string to scrape indexed external jobs when the native platform fails.
- **Dark Mode Aesthetic**: Sleek, glassmorphism UI built with Tailwind CSS.

## Usage
1. Open `index.html` in any modern web browser.
2. Ensure you have mapped your target companies with their numeric IDs.
3. Define your target Job Role (e.g., `Intern`) and Location filter.
4. Click to launch either the **Checkbox Filter Pipeline** (Native) or **Google Index Scraper** (External).
