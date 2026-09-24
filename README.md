# vazne-media

Open-licensed exercise images for the Vazne (وزنه) app, served through a CDN
(`https://cdn.jsdelivr.net/gh/MehrdadNsr/vazne-media@<tag>/ex/<exercise_id>/<n>.webp`).

- `ex/<exercise_id>/<n>.webp`: images for one bank exercise, in display order.
- `ATTRIBUTION.md`: author, licence and source of every file (required by CC BY-SA).
- `manifest.json`: the same data, machine-readable.
- `tools/selection.py`: which wger images were chosen for which exercise.

Releases are tagged (`v1`, `v2`, …) and a tag is never moved, so app builds can cache files forever.
