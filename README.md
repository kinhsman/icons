# icons

Public pictures for my projects: logos and icons other apps link to (phone notifications,
chat alerts, web pages). Everything here is public; nothing private goes in.

## Layout

One folder per project, then one folder per kind of picture:

```
<project>/<kind>/<name>.<ext>
```

| Folder | What | Written by |
| --- | --- | --- |
| `money/merchants/` | Merchant logos from the money app (money.sanglam.cc) | the money-hub helper, automatically |

A new project gets its own top-level folder (`wheeltradr/`, `owly/`, ...) with a short
`README.md` saying what is in it and whether a program writes it. Don't hand-edit a folder a
program writes: the next publish puts it back.

## Files

- Names: lowercase, dashes, no spaces (`chase.png`, `tesla-logo.svg`). A folder a program writes
  may name files by a fingerprint of their content instead (`3f9a1c0b7d2e.png`), so a changed
  picture gets a new name and no cache ever serves the old one.
- Formats: PNG for anything a phone shows (ntfy takes only PNG or JPEG), SVG or WebP for web pages.
- Size: square, 128 or 256 pixels, a few KB each.

## Linking

Through jsDelivr's free CDN, either pinned to a commit (never stale) or to the branch:

```
https://cdn.jsdelivr.net/gh/kinhsman/icons@<commit>/<path>
https://cdn.jsdelivr.net/gh/kinhsman/icons@main/<path>
```

The branch link can lag behind a change for a while (jsDelivr caches it); pin a commit when a
new picture must show at once. `https://raw.githubusercontent.com/kinhsman/icons/main/<path>`
also works, without the CDN.

## Logos

Brand logos belong to their owners and are here only to label transactions and alerts in my
own apps.
