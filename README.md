# Aayush Kumar — Portfolio Board

A scrolling 3D portfolio. As you scroll, a Three.js camera travels across a corkboard where every project is pinned up: real screenshots, sticky notes and red string. The text sits on paper cards in real HTML, so it stays readable, selectable and accessible.

**Sections:** ARTHIS.space and ARTHIS.land (websites) · HexaBed and the ARTHIS app (game apps) · Game Factory, Reel Factory and Clymora (AI systems) · 28 Blender add-ons · Kaleshi Family and Diorama Build reels plus the AKverse YouTube UI kit · contact.

- Single `index.html`, no build step. Three.js r128 loads from cdnjs.
- `assets/` holds the images, taken from the ARTHIS repos and the 3D gallery portfolio.
- Falls back to a flat corkboard with inline images when WebGL is unavailable, and respects `prefers-reduced-motion`.

**Host it:** Settings → Pages → deploy from this branch (or `main` after merging). Locally: `python3 -m http.server` and open http://localhost:8000.
