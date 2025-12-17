# Kinematics – Projectiles Dataset

This folder contains a curated set of 8 high-quality, original projectile-motion
problems designed for:

1. Physics education (HS → intro undergrad),
2. Training a diagram-generation model (Nano Banana),
3. Supporting structured note-completion in the Noted app.

### Structure

- `dataset_info.json` — metadata and schema description.
- `problems/` — each problem as a standalone JSON object.
- `images/` — placeholder for future SVG diagrams.

### Diagram Notes

Each JSON file includes a field `diagram_request` describing the exact
elements to draw. A diagram generator (LLM or classical pipeline) can use this
description to produce consistent vector diagrams.

### License

All problems are original content and licensed **CC-BY-Internal** unless
relicensed later.
