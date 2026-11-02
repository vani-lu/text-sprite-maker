# Text Sprite Maker

A tiny browser-based tool for generating text SVGs. Useful for making crisp, scalable text sprites for games, icons, or UI assets.

## Features

- Live preview with a dark interface
- Choose Arial Rounded MT Bold or the local Seto Font
- Adjustable canvas size, font size, letter spacing, position, and scaling
- Pick any fill color
- Download as `.svg` or copy the SVG code to the clipboard

## Usage

1. Open `text-sprite-maker.html` in any modern web browser.
2. Type your text and tweak the settings in the left panel.
3. Click **Download SVG** or **Copy SVG code**.

No build step or server is required; everything runs locally in the browser.

## File

- `text-sprite-maker.html` — the complete tool in a single file

## Local Seto Font

Place `setofont.ttf` in `setofont/` beside the HTML file, then choose **Seto Font** in the font selector. The entire `setofont/` folder is ignored by Git and is not included in commits or pushes; other checkouts need their own local copy.

Text-mode SVGs require the selected font on the viewing device (Seto uses the family name `SetoFont`). Enable **把文字转换成路径** before exporting to make an SVG that does not depend on the font being installed or loaded.
