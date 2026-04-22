# Denim 909 — Asset Checklist

## Required before launch

- [ ] **Booking email** — replace `TODO_EMAIL` in `index.html` (search: `TODO_EMAIL`)
- [ ] **Press photos** — replace `.photo-placeholder` divs in `#photos` section with `<img>` tags
  - 2–3 landscape press photos
  - 1 live performance photo
- [ ] **Tech rider PDF** — upload and add download link in `#tech` section

## Optional / nice to have

- [ ] Full live set link (YouTube unlisted, 30–60 min) — embed alongside highlight video
- [ ] SoundCloud link — add to music section if profile exists
- [ ] Favicon — add `<link rel="icon">` in `<head>`
- [ ] OG image — add `<meta property="og:image">` for social sharing previews

## How to add press photos

Replace each `<div class="photo-placeholder">...</div>` with:

```html
<img src="path/to/photo.jpg" alt="Denim 909 live performance" style="width:100%;display:block;aspect-ratio:4/3;object-fit:cover;">
```
