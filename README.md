# Melee Picker (GitHub Pages)

A tiny static Super Smash Bros. Melee no-repeat picker.

## Features

- No backend
- Cookie-based state storage
- No-repeat random picks until reset
- Undo last pick
- Single-file deploy for GitHub Pages

## Quick deploy on GitHub Pages

1. Create a new GitHub repo.
2. Upload `index.html` to the repo root.
3. Go to **Settings -> Pages**.
4. Under **Build and deployment**, set:
   - **Source:** Deploy from a branch
   - **Branch:** `main` (or `master`)
   - **Folder:** `/root`
5. Save.
6. GitHub will publish a URL for the page.

## Notes

- State is stored in the browser cookie named `melee_picker_state`.
- Because state is in the browser, each device/browser keeps its own run.
- This is ideal for a quick trusted-looking free surface without any server.

## Optional next goblin patches

- Add character portraits
- Add best-of-N strike mode
- Add stage picker
- Add shareable seed/run export
