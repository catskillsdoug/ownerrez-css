# ownerrez-css — DEPRECATED

OwnerRez Hosted Site (stay.reset.club) custom CSS. This repo deployed to
`css.reset.club` via Cloudflare Pages.

## Status

**Decommissioned 2026-05-11.** Source moved to `~/reset-brand`, served at
`brand.reset.club/ownz/`. The CF Pages project + `css.reset.club` DNS
record have been deleted.

- Frame CSS: <https://brand.reset.club/ownz/styles.css>
- Widget CSS: <https://brand.reset.club/ownz/widget.css>

## OwnerRez wire-up

Site-wide Header HTML:

```html
<link rel="stylesheet" href="https://brand.reset.club/ownz/styles.css">
```

Per-widget Custom CSS field (first line):

```css
@import url("https://brand.reset.club/ownz/widget.css");
```

## History

Kept for git history. Don't edit — edit `~/reset-brand/public/ownz/*` instead.
