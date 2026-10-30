# Solaris 3D — Interactive Solar System & Tidal Locking Simulator

An interactive 3D solar system and astrophysics lab built with Three.js, running entirely in the browser from a single HTML file.

**Live demo:** https://manojknaikade.github.io/3d-solar-system-tidal-locking

## Run locally

Open `index.html` in a modern browser (internet connection needed for the CDN-hosted Three.js, Tailwind, and fonts).

Photographic planet maps load only over http(s); opened as a `file://` page the app falls back to its procedural textures. To see them locally, serve the folder:

```bash
python3 -m http.server 8765
```

## Credits

Planet, Moon and Saturn ring maps in `textures/` are from [Solar System Scope](https://www.solarsystemscope.com/textures/), licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
