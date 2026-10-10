# OceanQuest — Development and School USB Guide

## Folder overview

- `layouts/index.html`: Hugo homepage template (HTML + Hugo `range` for creatures)
- `data/creatures.json`: creature facts rendered by Hugo
- `data/places.json`: reference location data (current interactive map also has corresponding data in `static/js/main.js`; keep them synchronized if changing locations)
- `content/_index.md`: Markdown starting point; the homepage currently uses custom template copy
- `static/css/style.css`: visual theme and responsive layout
- `static/js/main.js`: dive, comparison, GPS, gallery, guardian, quiz, and audio interactions
- `static/images/`: original offline SVG illustrations
- `static/sources.html`: sources and credits page
- `public/`: ready-to-open offline site

## Windows

1. Download and install Hugo from the official installation guide: https://gohugo.io/installation/windows/
2. Extract this ZIP.
3. Open PowerShell in the `ocean-explorer` folder.
4. Run `hugo version`, then `hugo server`.
5. Open `http://localhost:1313`.
6. Run `hugo --cleanDestinationDir` to rebuild `public`.

## macOS

With Homebrew installed: `brew install hugo`. Alternatively use the official release binary.

```bash
cd /path/to/ocean-explorer
hugo version
hugo server
# Stop with Ctrl+C
hugo --cleanDestinationDir
```

## Linux

Install Hugo from the official instructions or your package manager. Then run the same commands as on macOS.

## USB rehearsal checklist

- [ ] Open `public/index.html` using a `file://` URL.
- [ ] Turn Wi-Fi off.
- [ ] Test navigation buttons and links.
- [ ] Dive through all five ocean zones.
- [ ] Switch all three comparisons.
- [ ] Reveal all four GPS locations.
- [ ] Open marine-life facts.
- [ ] Check and uncheck ocean promises.
- [ ] Finish the quiz and restart it.
- [ ] Open the sources page and return to the homepage.
- [ ] Test on the actual school computer if possible.
- [ ] Bring a backup USB and a copy on the development laptop.

## Troubleshooting

**Page has no styling:** You copied `index.html` without `css/`, or changed the folder layout. Copy the entire `public` contents.

**Images missing:** Check that `images/earth.svg`, `images/reef.svg`, and `images/deep.svg` are present beside `index.html` inside `images/`.

**Hugo command not found:** Install Hugo and reopen your terminal, or use the already-built `public` folder without Hugo.

**Sound not working:** Browser audio requires a click. Sound is optional and is off by default.

**Map doesn't look like a real map:** It is an educational schematic; the GPS marker uses coordinates, not exact coastline geometry.

**Source Markdown doesn't change the homepage:** The homepage is a custom Hugo template. Edit `layouts/index.html` or add `{{ .Content }}` to display `content/_index.md`.
