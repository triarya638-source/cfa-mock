# CFA Mock Exams

Static site (GitHub Pages friendly). Open `index.html`; no build step.

- `data/m1s1.js … m3s2.js` – one file per mock/session (90 questions each)
- `assets/img/` – exhibit images, linked from the questions that need them
- Answer keys: only **Mock 2 · Session 2** has one. For other sets, `hasKey` is `false` and each question has `"correct": null`.
  To add a key, set `"correct"` to 0/1/2 (A/B/C) on each question, optionally add `"explain"` and `"topic"`, and set `"hasKey": true`.
