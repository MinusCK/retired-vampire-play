# Playtest v0.2.47 · 試玩

Play URL: https://minusck.github.io/retired-vampire-play/

Source: Origin `cheung-minus/retired-vampire` branch `cursor/cardview-astra-empty-v1-4c9b` commit `9a124157e845d3c044b9182941defc4a3853cba1` (Origin PR #152, stacked on #151; neither is merged).

Godot 4.7 web export, single-threaded, WASM heap 512 MiB. Corner is v0.2.47 · 試玩.

- Scare cards are assembled from the Astra empty chrome, with runtime name, ATK, type, stars, range and effect text.
- The effect text is centered in the cream desc plate.
- The element socket shows the v3 glyph for fire, ice, lightning, poison and blood cards.
- 廊燭點燃, 牆縫滲紅, 打翻藥櫃, 走廊漏電 and 棺蓋砰響 show the v2 prop portraits.
- 古堡穿堂龍捲 keeps its legacy full face.

`index.pck` is 101855396 bytes (sha256 `3364907e865a8e7db9231992f41cdc2a1bde206651b88b6a24dded7479ad6ae3`), under the 98 MiB cap and the GitHub 100 MiB limit. `index.wasm` is 39509338 bytes (sha256 `8ef15a50b35277cb9309cc0701fff37e61631f29e9f0d7ea637dc04c25f666f5`).

This folder is the complete Pages root. The parent box pushes it to `MinusCK/retired-vampire-play` `main`. This agent does not push to GitHub. It replaces `playtest-v0245-desccenter`.
