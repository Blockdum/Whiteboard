# Whiteboard on your phone (GitHub Pages)

This folder is the web version of Whiteboard, set up so you can install it on a phone.

## Turning it on (once)
1. Put this `docs` folder in the main branch of the Blockdum/Whiteboard repository.
2. On GitHub: Settings, then Pages. Under "Build and deployment", choose "Deploy from a branch", branch `main`, folder `/docs`, then Save.
3. After a minute or two it's live at https://blockdum.github.io/Whiteboard/

## Installing it on a phone
- iPhone (Safari): open the address, tap Share, then "Add to Home Screen".
- Android (Chrome): open the address, tap the ⋮ menu, then "Install app" (or "Add to Home screen").
It then opens full screen like an app, and works without internet.

## Updating it
Each release, replace `docs/index.html` with the new `Whiteboard.html` (renamed to index.html), and change the version number on the `CACHE` line in `sw.js` so phones pick up the update.

Boards on the phone are saved on the phone. They don't sync with the Windows app: use Save/Open (.whiteboard files) or Live share to move work between them.
