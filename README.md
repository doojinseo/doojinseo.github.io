# #random-doo

Personal blog: https://doojinseo.github.io

## Current deployment

The homepage is the reviewed v13 DP-inspired interface, with records, trainer card, log, and a local draft editor. `index.html` is self-contained (fonts and thumbnail assets included). Jekyll front matter disables the inherited layout for this page; the rest of the existing Jekyll site is preserved.

**The editor saves only in the current browser. It does not publish to GitHub.** Drafts, photos and locally saved posts are not shared across devices. Use the export button to keep a copy. The seven built-in records are explicitly labeled examples. Comments and owner-authenticated publishing are not connected yet.

Spotify and YouTube previews require the external service; playback can be restricted by the service.

## Deploy and restore

GitHub Pages builds `main` from the repository root. The previous public site is preserved on `backup/before-v13-2026-11-10` and in Git history. Revert the v13 deployment commit to restore it.

The local editable source and earlier mockup versions remain in `C:/Users/Jinseo/random-doo-preview` and were not uploaded. Editing `_posts/` still creates legacy Jekyll post pages; the new homepage does not yet load those posts automatically.

## Assets

DungGeunMo font: https://github.com/Dalgona/DungGeunMo (SIL Open Font License 1.1).
Pok?mon is owned by its respective rights holders; this personal fan interface is unofficial.
