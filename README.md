# Harwyn Lance Arabi — Portfolio
Dark, responsive portfolio built with HTML, CSS, and vanilla JavaScript.

## Files
- `index.html` — portfolio content
- `style.css` — layout, animations, transitions
- `script.js` — mobile menu, scroll reveals, reading progress, active nav link, click sounds with a mute toggle, copy-email button
- `assets/profile.jpg` — portrait
- `assets/cal2hub-logo.jpg` — Cal2Hub logo
- `assets/neurocomm-board.png` — final NeuroComm prototype

## Sound
Click sounds are generated in the browser with the Web Audio API, so there are no audio files to host. The speaker button in the header mutes them, and the choice is saved in the visitor's browser. To start muted for first-time visitors, set `DEFAULT_ON` to `false` at the top of `script.js`.

## Accessibility
- Animations, hover movement, and scroll reveals switch off when the visitor's system is set to reduce motion.
- Keyboard users get a skip link, visible focus outlines, and a menu that closes with Escape.
- Images have alt text, and the sound toggle reports its on/off state to screen readers.

## Preview
Open `index.html` in a browser, or use VS Code Live Server.

## GitHub Pages
1. Create a repository named exactly `hxrwyn.github.io`.
2. Upload all files and the `assets` folder to the repository root.
3. Go to Settings → Pages → Deploy from a branch → `main` → `/(root)` → Save.
4. When deployment finishes, visit https://hxrwyn.github.io/

Before publishing, confirm that you're comfortable displaying your photo and email publicly.
