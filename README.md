# vazne-media

Exercise images for the Vazne (وزنه) app, served through a CDN
(`https://cdn.jsdelivr.net/gh/MehrdadNsr/vazne-media@<tag>/ex/<exercise_id>/<n>.webp`).

- `ex/<exercise_id>/<n>.webp`: images for one bank exercise, in display order.
- `ATTRIBUTION.md`: author, licence and source of every file (required by CC BY-SA).
- `manifest.json`: the same data, machine-readable.
- `tools/selection.py`: which wger images were chosen for which exercise.

App builds pin a commit hash (e.g. `@c3842c7…`), so files at that URL never change and can be cached forever.

## Sources

- [wger](https://wger.de): Everkinetic line drawings, wger's own (incl. AI-generated) images, a few
  original line drawings by named contributors — CC BY-SA 3.0 / 4.0.
- [free-exercise-db](https://github.com/yuhonas/free-exercise-db): photos published as public domain
  (Unlicense).
- Drawings made for Vazne (AI-generated) — CC BY-SA 4.0.

Every file's author, licence and source is in `ATTRIBUTION.md`.

## Removal requests

If you hold the rights to an image here and want it removed, write to hi@vazne.app (which file /
which exercise). It is taken out of the app with the next update.
