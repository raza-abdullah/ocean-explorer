# OceanQuest V2 enhancements

- Latitude Lab with interactive north/south latitude slider, tropical/temperate/polar educational explanations.
- Three ecosystem cards with locally stored illustrations and land analogies.
- Offline-ready copies in `public/`.
- All features work without APIs, CDNs, or internet.

## Update an existing checkout
Copy the files from this package over the matching paths in your existing Git checkout. Review differences before committing.

```bash
hugo server
hugo --cleanDestinationDir
```

Then push changes to `main` to trigger GitHub Pages.

## Image upgrade
This version uses original local SVG illustrations rather than external photos. Add real marine photos only when their license and attribution are confirmed.

## Validation
Open `public/index.html` directly from disk and test the latitude slider, gallery, quiz and navigation. Also test the deployed Pages site.
