# PACKFORM - Template-to-3D Mockup Generator

A runnable browser MVP combining a protected 2D pouch dieline workspace with synchronized WebGL 3D preview.

## Run

```bash
npm install
npm run dev
```

## Included

- Pouch template structure with front, back, side and bottom panels
- Protected cut/fold geometry
- Image upload and editable text artwork
- Move, resize, rotate, duplicate, delete and layers display
- Real-time 2D-canvas texture mapping to an orbitable 3D package
- Dieline-only PDF and print-layout PDF export
- WebM recording of the 3D preview

## Production roadmap

This MVP demonstrates the end-to-end interaction. Reliable arbitrary PDF/EPS dieline inference and production-grade CMYK/vector PDF/EPS output require a server-side prepress pipeline, geometry validation, ICC color management and packaging-specific fold solvers. Add those before using exported files for manufacturing.
