# Catch Counter

Counts juggling runs between drops from phone video, then plots the run-length survival curve and per-catch drop chance.

Live site: https://cfloyd2002.github.io/catch-counter/

- **Live**: uses the camera and microphone directly (needs HTTPS, which GitHub Pages provides).
- **Record / Upload**: analyses a saved clip.
- Throws are found by fitting free-fall parabolas to the ball positions; drops are floor thuds in the audio.
- Runs are stored in this browser (localStorage). Use **Export CSV** to move them elsewhere.
