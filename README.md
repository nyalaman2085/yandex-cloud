# Yandex-Inspired Search Homepage

A responsive search homepage concept built with HTML, CSS, and browser JavaScript.

## Features

- Text search opens Yandex search results in a new tab
- Image search opens Yandex Images for the entered query
- Voice input uses the browser Speech Recognition API when supported
- Quick service shortcuts link to external destinations
- The date widget uses the device's current date
- Sample weather/story cards are explicitly labeled as placeholder content

## Run locally

\`\`\`bash
python3 -m http.server 8000
\`\`\`

Open http://localhost:8000/.

## Project structure

- \`index.html\` — markup and small interaction scripts
- \`style.css\` — layout and responsive styles
- \`assets/icons/\` — decorative service icons

## Limitations

- This is an independent interface demo, not an official Yandex product.
- Search and service links open external websites; the page does not implement its own search index.
- Voice search availability depends on browser support and permissions.
- Weather and story cards are not live data.

## Tech stack

HTML5 · CSS · JavaScript · browser Web Speech API
