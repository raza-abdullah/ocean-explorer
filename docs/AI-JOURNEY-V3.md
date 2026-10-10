# OceanQuest V3 — AI Build Journey and Young Explorer

This release builds on **OceanQuest Enhancements V2**. It adds a dedicated `ai-journey.html` page and replaces the homepage's placeholder AI section with a student introduction and a link to the journey.

## Changes

- **Meet the Young Explorer:** Abdullah Raza, Grade 6, New Middle East International School.
- **My AI Build Journey:** seven real development chapters, lessons learned, and actual conversation prompts.
- Links from homepage navigation, homepage AI section and footer.
- Offline-ready `public/ai-journey.html` and matching CSS.
- Hugo compatibility: `locale` instead of `languageCode`, and `hugo.Data` instead of `.Site.Data`.

## Apply safely to your Git checkout

This ZIP is based on the previous V2 package, **not on your current live GitHub checkout**. If you've made additional changes since V2, merge these files carefully rather than replacing the whole repository.

1. In your existing checkout, commit or stash any changes first.
2. Compare the following files against this ZIP:
   - `layouts/index.html`
   - `static/css/style.css`
   - `hugo.toml`
3. Copy `static/ai-journey.html` (new file).
4. Merge the changes above into your current files.
5. Run `hugo server`, visit the homepage and `/ai-journey.html`.
6. Run `hugo --cleanDestinationDir`, and check both pages in `public/` directly from `file://`.
7. Commit and push to trigger GitHub Pages.

```sh
hugo server
hugo --cleanDestinationDir
git add layouts/index.html static/ai-journey.html static/css/style.css hugo.toml
git commit -m "feat: add student profile and AI build journey"
git push origin main
```

## Privacy and accuracy

The page displays the student's full name, grade and school on the **public GitHub Pages site**. Obtain parent/guardian approval before publishing. Remove the school name from the public page if preferred. The timeline reflects the development conversation, which involved adult assistance; do not claim the child personally entered every prompt. No fabricated screenshots are included.

## Offline preview

The ZIP includes a `public/` preview that can be opened using `public/index.html`, without a server. For the authoritative deployable output, rebuild using your installed Hugo version. Hugo is not installed in the packaging environment, so the Hugo build itself has not been executed here.
