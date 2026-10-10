# OceanQuest — The Secret World Under the Ocean

A colorful, interactive, **offline-first** Hugo website for a school presentation. Includes an ocean-depth explorer, ocean/land comparisons, latitude-longitude mystery map, marine life, conservation promises, and a five-question quiz.

## Quickest way to show it (NO INSTALLATION)

1. Open the `public` folder.
2. Double-click `index.html` in Chrome, Edge, Firefox, or Safari.
3. Explore everything with Wi-Fi switched off.

The `public` folder is a ready-to-present copy included in this ZIP.

## Develop with Hugo

Install Hugo from https://gohugo.io/installation/ (standard or extended version works; no theme is needed). Open a terminal inside the project folder (where `hugo.toml` lives).

```bash
hugo version
hugo server --disableFastRender
```

Visit http://localhost:1313/ in your browser. Stop the server with Ctrl+C.

Edit the homepage template at `layouts/index.html`, CSS at `static/css/style.css`, JavaScript at `static/js/main.js`, and creature facts at `data/creatures.json`. `content/_index.md` is an example Markdown content file; the custom homepage currently gets its visible copy from the template and JSON. To display more Markdown content, use `{{ .Content }}` in the homepage template.

To build:

```bash
hugo --cleanDestinationDir
```

This regenerates the `public` folder. **Important:** Hugo cleans the destination before building. The `static/sources.html` file is copied automatically.

## Copy to USB

1. Run `hugo --cleanDestinationDir` (or use the bundled `public` if you haven't edited anything).
2. Copy **the contents of** `public/` to a folder named `OceanQuest` on the USB drive. Copy the `css`, `js`, and `images` folders, `index.html`, and `sources.html` together.
3. On the school computer, open `USB/OceanQuest/index.html` directly in a browser.
4. Switch Wi-Fi off and test every section. No Hugo, Node, Python, internet, or web server is needed at school.

Do **not** copy only `index.html`; the supporting asset folders are required.

## Presentation (5 minutes)

- 0:00–0:40 — Introduce the idea: why oceans are a hidden world.
- 0:40–2:00 — Dive through ocean depth zones and compare Everest with Challenger Deep.
- 2:00–3:00 — Demonstrate latitude/longitude treasure hunt and marine-life facts.
- 3:00–3:40 — Show the quiz and ocean protection promises.
- 3:40–5:00 — Explain 2–3 real ChatGPT prompts, what the AI generated, what you tested, and what you improved yourself.

## Personalize the AI story

The website's AI journey section is a **placeholder**, not a claim that the student personally performed those steps. Replace it with actual examples and screenshots after developing the project together. Consider adding the student's own questions and discoveries.

## Offline technical notes

- All navigation uses fragment links, relative CSS/JS paths, and local SVG images.
- No remote fonts, CDNs, external scripts, fetch calls, APIs, or maps.
- Sound is optional and synthesized locally by the browser after clicking the sound button.
- External links appear only on the sources page and are not required for the experience.
- The SVG world map is schematic. The location marker is mathematically positioned from coordinates, but coastlines are approximate.
- The site uses system emoji; rendering differs across operating systems.
- The site supports reduced-motion preferences, keyboard buttons, and a skip link.

## Suggested next improvements

Replace or supplement original SVG illustrations with properly licensed local marine photographs (with credits), expand the Markdown content, add original student-drawn illustrations, and verify each new fact against NOAA/NASA/UNESCO.
