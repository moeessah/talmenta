TALMENTA SPLIT

Pages
- index.html = video hero homepage
- talmenta-glass.html = glass version
- talmenta-plain.html = plain version

Shared assets
- css/talmenta-shared.css = shared site styling + system light/dark theme
- js/talmenta-shared.js = shared interactions

Version-only assets
- css/talmenta-video.css + js/talmenta-video.js
- css/talmenta-glass.css + js/talmenta-glass.js
- css/talmenta-plain.css

Put the existing talmentapics/ folder beside these files, preserving its current paths.
Each page has its own light/dark theme toggle. The first visit follows the visitor's computer/browser prefers-color-scheme setting; after a manual toggle, the chosen theme is remembered in localStorage.
