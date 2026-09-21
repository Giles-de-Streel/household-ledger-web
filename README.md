# Household Ledger (web build)

Static, installable copy of the household ledger app. Data is stored in each user's own Google Drive, not in this repository.

Files: `index.html` (the app), `manifest.webmanifest` + `icon-*.png` (install to home screen), `sw.js` (offline fallback).

**Generated file set: do not edit here.** Source lives in the private `household-budget` repo; `python build-web.py --publish` there regenerates and pushes these files. Served by GitHub Pages at https://giles-de-streel.github.io/household-ledger-web/. The Google OAuth client must list `https://giles-de-streel.github.io` as an authorized JavaScript origin.
