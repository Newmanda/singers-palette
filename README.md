# Singer’s Symbol Palette

A compact, standalone browser utility for singers, voice teachers, and music theory students.

**[Launch Singer’s Symbol Palette](https://newmanda.github.io/singers-palette/)**

## Features

- IPA symbol sets for English, French, German, and Italian.
- Musical accidentals, Roman numerals, intervals, and harmonic labels.
- Rich-text copying with vertically stacked figured bass and a Unicode fallback.
- Unicode IPA composition and individual symbol copying.
- Recently used symbols and locally saved preferences.
- Automatic light and dark mode.

## Usage

Open `index.html` in a modern browser. No build step, dependencies, or server-side code are required. For web hosting, serve the file over HTTPS for best clipboard compatibility. Rich-text paste support varies by destination application.

## Hosting

Copy `index.html` and the accompanying `fonts/` directory into a static directory on your website, or enable GitHub Pages from Settings → Pages, using the main branch and root directory. On supported versions of Safari, use File → Add to Dock to launch the hosted page as a web app.

The current application is version 17. Preferences are stored in the browser; they do not automatically transfer between different websites or browsers.

## Font

The self-hosted Charis font and its SIL Open Font License are bundled together in `fonts/`.
