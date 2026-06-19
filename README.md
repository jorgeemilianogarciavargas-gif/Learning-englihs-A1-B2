# Fluentia

Fluentia is a browser-based English learning app designed to guide a learner from A1 toward higher CEFR levels with daily practice, speaking prompts, listening support, error review, and progress tracking.

## Current Features

- A1 practice route with unlockable units.
- Progression gated by 100% completion.
- 30-minute practice session timer.
- Immediate correction and explanations.
- Error review queue stored locally.
- Listening buttons using the browser speech engine.
- Speaking prompts for reading answers aloud.
- Progress saved in `localStorage`.

## Run Locally

Open:

```text
outputs/lingua/index.html
```

Or run a local server:

```powershell
cd outputs/lingua
python -m http.server 8765
```

Then visit:

```text
http://127.0.0.1:8765
```

## Roadmap

- Expand A1 with more units and mixed review.
- Add A2, B1, and B2 practice routes.
- Add richer listening exercises.
- Add writing prompts and corrections.
- Add spaced repetition scheduling.
- Add GitHub Pages deployment.
