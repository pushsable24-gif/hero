# Storm × Afterglow

An editable React + TypeScript prototype for the supplied creative brief. Start with:

```sh
npm install
npm run dev
```

The concept heading “Storm × Afterglow” is a working title taken from the brief. The outlined logo slots are placeholders only; replace them with the supplied logo asset when available. Main copy and navigation labels are in `src/App.tsx`; colors, typography, and layout are in `src/styles.css`.

## Current implementation

- A timed opening threshold with an intro skip control, layered storm atmosphere, animated rain, a flash, and a transition into the homepage.
- A custom canvas scene with layered terrain silhouettes, ambient light, pointer trails, and expanding click ripples.
- An interactive canvas with draw, breeze, dissolve, energy, ripple, palette, and clear controls.
- Responsive Home, About, Projects, Playground, and Contact sections, with reduced-motion CSS and a sound toggle that starts a quiet synthesized drone only after the visitor enables it.

The scene is rendered procedurally with Canvas 2D and CSS. This first pass does not yet include Three.js/WebGL, volumetric smoke, physically simulated ground fractures and water, procedural branching lightning, or the exact logo geometry. The TypeScript check and production bundle build pass. Browser visual inspection remains incomplete because the browser could not connect to the local preview server in this environment.
