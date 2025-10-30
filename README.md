# Maze of the Pigman

A short horror survival maze where you scavenge nine peanuts while a relentless Pigman stalks you in the dark. Manage your stamina, listen for footsteps, and escape before you're caught.

## How to Play

1. Open `Index.html` in a modern desktop browser (Chrome, Edge, Firefox, Safari). For the best audio experience, allow the page to autoplay sound or interact once to start playback.
2. Click **Enter the Maze**.
3. Move with **WASD** or the arrow keys.
4. Hold **Shift** to sprint. Stamina drains quickly when sprinting and refills when you slow down.
5. Collect all **nine glowing peanuts** to unlock the exit and win.
6. Avoid the Pigman. If he touches you, you lose and are greeted with a jump scare.

## Features

- Hand-crafted maze rendered on an HTML5 canvas with dynamic lighting.
- Sprint mechanic with visible stamina bar and color-shift feedback when low.
- Smart Pigman pathfinding that accelerates as you gather more peanuts.
- Atmospheric UI overlay, ambient hum, and distinct audio cues for victory and defeat.
- Responsive layout that scales down gracefully on smaller screens.

## Advanced: Serve Locally (Optional)

Local web servers avoid browser autoplay or local file security restrictions. From PowerShell, run:

```powershell
python -m http.server 8000
```

Then open [http://localhost:8000/Index.html](http://localhost:8000/Index.html) in your browser.

## Credits

- Tiny audio cues courtesy of the public-domain samples hosted by [naptha/tiny-sfx](https://github.com/naptha/tiny-sfx).
