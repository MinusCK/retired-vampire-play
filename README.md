# Playtest v0.2.49 · 試玩

Play URL (after the parent pushes): https://minusck.github.io/retired-vampire-play/
Temporary URL served from the agent VM: https://deaths-activated-stuck-distinguished.trycloudflare.com

Source: Origin `cheung-minus/retired-vampire` branch `cursor/opus55-slab-terrain-redesign-bc61` commit `40142f00de1e81b18de968ba7ec56137c7024035` (Origin PR #154, not merged).

Godot 4.7 web export (release, single-threaded) with the repo's `Web` preset. The corner reads v0.2.49 · 試玩. This was checked in Chrome through the trycloudflare URL, on both the title screen and a live battle.

- The battle floor is the v4 stone slabs: floor_v3-style flat lilac-grey flagstones with sparse moss and cracks. The two rows in front of the castle have red danger grout with ember cracks.
- All eight terrain types use the v4 cel atlases: fire, ice, blood_seep, poison, water, electric, shadow_mist and rubble.

`index.pck` is 101997780 bytes (sha256 `a47fe3dad7d4889793a4d9b5ab11f7f10dfd809b6ec0c5f8400badae05eb8448`). That is under the 98 MiB cap and GitHub's 100 MiB limit. `index.wasm` is 39509339 bytes (sha256 `7eda98958eb09135a1acb54a4323a00b1a55af1997f15fa1cdc2b93e3df46656`).

This folder is the complete Pages root and contains no Godot source. The parent box pushes it to `MinusCK/retired-vampire-play` `main` for https://minusck.github.io/retired-vampire-play/. This agent does not push to GitHub. This build replaces playtest v0.2.47.
