# Ndjengue English — media

Audio packs used by the **Ndjengue English** Android app. This repository contains only
generated speech audio; the app's source code is kept private.

- `packs/index.json` — list of published packs (voice × level, number of clips, size).
- `packs/<voice>/<LEVEL>.zip` — Opus clips (mono, 24 kHz, ~20 kbps) named `sha1(text)[:16].ogg`.
  `ALL` contains the placement test and conversation lines.

Voices were synthesised with **Kokoro-82M v1.0** (weights licensed Apache-2.0) via
`kokoro-onnx` (MIT): `af_heart`, `am_michael` (US English), `bf_emma`, `bm_george` (UK English).
Packs are published only when a level is complete; more levels are added as generation finishes.

The audio in this repository is released under the Apache License 2.0, following the model licence.
