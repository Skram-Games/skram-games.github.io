# skram-games.github.io

This repo hosts the live web build of **Skrambeasts**, a barcode-scanning monster-collector game by [Skram-Games](https://github.com/Skram-Games).

**Live site:** https://skram-games.github.io/SkramBeasts/

## What's here

- `SkramBeasts/index.html` - the full game (HTML/CSS/JS, single file, no build step), served directly by GitHub Pages.
- `.well-known/` - domain verification files (e.g. for Google Play / Digital Asset Links, used by the Android TWA wrapper).
- `.nojekyll` - tells GitHub Pages to skip Jekyll processing and serve the files as-is.

## About Skrambeasts

Every real-world barcode hides its own Skrambeast. Scan a barcode to discover, catch, battle, and collect - then build a Squad, climb the Arena, push through The Hive, and compete with friends.

Skrambeasts is also available as an Android app, built from this same codebase via a Trusted Web Activity (TWA) wrapper.

## Notes

This repo is the **deployment target** only. Game development happens in the main [Skrambeasts](https://github.com/Skram-Games) repo; changes are copied here (as `index.html`) to go live.

Skrambeasts is currently in open Beta.
