# Playtest v0.2.57 · 回合試作

Play URL: https://minusck.github.io/retired-vampire-play/

Source: Origin `cheung-minus/retired-vampire` branch `cursor/astra-grounds-trial-c59c` commit `0a8cdde566c3ccae5cc3d3afc0ed10ac06b2df36` (Origin PR #158, not merged).

Godot 4.7.2 web export (release, single-threaded, mobile textures, 512MiB wasm, no COOP/COEP). The loader and the in-game corner both read v0.2.57. The base pack and the ultimate pack are separate files. Both download and pass a size and SHA-256 check before the battle starts.

`base.5dc35b5297ab65148fef763618cd1ccffda78148e535cde269b12219e3671535.pck` is 31796884 bytes (sha256 `5dc35b5297ab65148fef763618cd1ccffda78148e535cde269b12219e3671535`). `ult.5c1505259e3463a7f23c85e7e945a2ee12de809003a96b6d2917ea7232147a16.pck` is 66130248 bytes (sha256 `5c1505259e3463a7f23c85e7e945a2ee12de809003a96b6d2917ea7232147a16`). `index.html` is 2288246 bytes (sha256 `04ba21412b6a209496d013ea9a1c995bfcd9b36931714ea9076ed17fd74db044`).

This folder is the complete Pages root and contains no Godot source. Rollback of the previous playtest is tag `playtest-v0.2.51` at commit `89657a26cd798d7a547eeacffcef1dfad663d8f3`. Origin PR #158 is not merged.
