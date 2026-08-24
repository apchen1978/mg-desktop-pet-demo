# MG — Desktop Pet · Web Mini Demo v3

Browser adaptation of the MG desktop pet, published as a portfolio piece.

## Try it

https://apchen1978.github.io/mg-desktop-pet-demo/

## Controls

- **Drag MG** around the stage to make it run (mouse or touch, direction-aware)
- Buttons: **Wave / Cute / Jump / Sleep / Reset** + **v2 expression pack: Dance / Happy / Think / Excited / Heart / Blush**
- Keyboard: `w` wave · `c` cute · `j` jump · `s` sleep · `d` dance · `h` happy · `k` think · `x` excited · `l` heart · `b` blush · `Esc` reset

## 16 poses (v3)

- Original 10: idle, run L/R, wave, cute, jump, sleep, wake, review
- v2 expression pack: dance (step loop + bob), happy (jump + squash), think (wait + float), excited (sprint + bob), heart (floating hearts), blush (pulsing cheeks)
- All assets are **WebP-optimized** (~0.6 MB total vs 2.4 MB in the PNG version)

## Notes

- **Web Mini Demo / Portfolio Adaptation**
- Original: Python + PySide6 Desktop App (private project)
- This is a browser demo of the original artwork — **not** the complete desktop application
- v2 poses reuse existing art with procedural motion / generated overlay frames only (no new AI art)

## Run locally

Serve this folder with any static server, e.g.:

```sh
python -m http.server 8000
# open http://localhost:8000
```

## Verification

- Desktop 1440px and mobile 390px layout pass (no horizontal overflow)
- All 58 WebP frames load; no console errors; no unexpected network calls
- Touch drag works on mobile
