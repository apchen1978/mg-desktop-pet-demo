# MG — Desktop Pet · Web Mini Demo

Browser adaptation of the MG desktop pet, published as a portfolio piece.

## Try it

https://apchen1978.github.io/mg-desktop-pet-demo/

## Controls

- **Drag MG** around the stage to make it run (mouse or touch, direction-aware)
- Buttons: **Wave / Cute / Jump / Sleep / Reset**

## Notes

- **Web Mini Demo / Portfolio Adaptation**
- Original: Python + PySide6 Desktop App (private project)
- This is a browser demo of the original artwork — **not** the complete desktop application
- All animation frames are from the original MG artwork; no new art was created

## Run locally

Serve this folder with any static server, e.g.:

```sh
python -m http.server 8000
# open http://localhost:8000
```

## Verification

- Desktop 1440px and mobile 390px layout pass (no horizontal overflow)
- All frames load; no console errors; no unexpected network calls
- Touch drag works on mobile
