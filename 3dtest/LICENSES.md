# LICENSES — 생존자 군단 3D test

Download date: 2026-10-17 13:32 KST (all from official sites via curl).

## Quaternius Zombie Apocalypse Kit — NOT USED
- Page https://quaternius.com/packs/zombieapocalypsekit.html showed 'License CC0' on 2026-10-17 13:32 KST (license button -> /license.html, link to creativecommons.org/publicdomain/zero/1.0/).
- Download is a Google Drive folder (1mWP6sCHun7OUMHQeDNZLrXTteXlzWg_t); every file returned 'Too many users have viewed or downloaded this file recently' -> no files obtained, no license file inspected. GPT's QAL claim could not be confirmed either way.

## Three.js r180 (lib/) — MIT, Copyright 2010-2025 Three.js Authors (npm package three@0.180.0)

## Kenney nature-kit — CC0 1.0
- Page: https://kenney.nl/assets/nature-kit
- Zip: dl/nature-kit.zip
- License file (verbatim):
```
	Nature Kit (2.1)
	Created/distributed by Kenney (www.kenney.nl)
	Creation date: 29-04-2020 01:02
			------------------------------
	License: (Creative Commons Zero, CC0)
	http://creativecommons.org/publicdomain/zero/1.0/
	This content is free to use in personal, educational and commercial projects.
	Support us by crediting Kenney or www.kenney.nl (this is not mandatory)
			------------------------------
	Donate:   http://support.kenney.nl
	Request:  http://request.kenney.nl
	Patreon:  http://patreon.com/kenney/
	Follow on Twitter for updates:
	http://twitter.com/KenneyNL
```
## Kenney survival-kit — CC0 1.0
- Page: https://kenney.nl/assets/survival-kit
- Zip: dl/survival-kit.zip
- License file (verbatim):
```
	Survival Kit (2.0)
	Created/distributed by Kenney (www.kenney.nl)
	Creation date: 03-04-2024 14:59
			------------------------------
	License: (Creative Commons Zero, CC0)
	http://creativecommons.org/publicdomain/zero/1.0/
	You can use this content for personal, educational, and commercial purposes.
	Support by crediting 'Kenney' or 'www.kenney.nl' (this is not a requirement)
			------------------------------
	• Website : www.kenney.nl
	• Donate  : www.kenney.nl/donate
	• Patreon : patreon.com/kenney
	Follow on social media for updates:
	• Twitter:   twitter.com/KenneyNL
	• Instagram: instagram.com/kenney_nl
	• Mastodon:  mastodon.gamedev.place/@kenney
```
## Kenney city-kit-roads — CC0 1.0
- Page: https://kenney.nl/assets/city-kit-roads
- Zip: dl/city-kit-roads.zip
- License file (verbatim):
```
	City Kit Roads (2.2)
	Created/distributed by Kenney (www.kenney.nl)
	Creation date: 10-10-2026 12:35
			------------------------------
	License: (Creative Commons Zero, CC0)
	http://creativecommons.org/publicdomain/zero/1.0/
	You can use this content for personal, educational, and commercial purposes.
	Support by crediting 'Kenney' or 'www.kenney.nl' (this is not a requirement)
			------------------------------
	• Website : www.kenney.nl
	• Donate  : www.kenney.nl/donate
	• Patreon : patreon.com/kenney
	Follow on social media for updates:
	• Twitter:	 twitter.com/KenneyNL
	• BlueSky:	 kenney.bsky.social
	• Instagram: instagram.com/kenney_nl
```
## Kenney tower-defense-kit — CC0 1.0
- Page: https://kenney.nl/assets/tower-defense-kit
- Zip: dl/tower-defense-kit.zip
- License file (verbatim):
```
	Tower Defense Kit (2.1)
	Created/distributed by Kenney (www.kenney.nl)
	Creation date: 16-09-2024 09:24
			------------------------------
	License: (Creative Commons Zero, CC0)
	http://creativecommons.org/publicdomain/zero/1.0/
	You can use this content for personal, educational, and commercial purposes.
	Support by crediting 'Kenney' or 'www.kenney.nl' (this is not a requirement)
			------------------------------
	• Website : www.kenney.nl
	• Donate  : www.kenney.nl/donate
	• Patreon : patreon.com/kenney
	Follow on social media for updates:
	• Twitter:   twitter.com/KenneyNL
	• Instagram: instagram.com/kenney_nl
	• Mastodon:  mastodon.gamedev.place/@kenney
```
## Files used
- assets/tree_oak.glb, tree_default.glb, tree_pineRoundA.glb, tree_pineRoundC.glb, tree_fat.glb, rock_largeA.glb — Kenney Nature Kit
- assets/surv/box-large.glb, barrel.glb, fence-fortified.glb, Textures/colormap.png — Kenney Survival Kit
- assets/city/construction-barrier.glb, Textures/colormap.png — Kenney City Kit (Roads)
- assets/td/wood-structure-high.glb, Textures/colormap.png — Kenney Tower Defense Kit
- Soldiers, zombies, boss, gate, road/grass textures, sky, hills: made procedurally in code (no third-party assets).

## Rigged character models (added 2026-10-17 ~14:10 KST) — downloaded from Poly Pizza (static.poly.pizza), each page lists license "Public Domain" (= CC0 1.0), creator Quaternius
| file (models/) | Poly Pizza page | title | license |
|---|---|---|---|
| PpLF4rt4ah.glb | https://poly.pizza/m/PpLF4rt4ah | Character Soldier — Quaternius | Public Domain / CC0 |
| VlXjG0N8Eg.glb | https://poly.pizza/m/VlXjG0N8Eg | Zombie — Quaternius | Public Domain / CC0 |
| 5vO2YJsPEf.glb | https://poly.pizza/m/5vO2YJsPEf | Orc — Quaternius (used as boss, weapon removed, recoloured) | Public Domain / CC0 |
No CC-BY models are used (CC-BY items seen and skipped: 22K0aSZkHV "Zombie", jkrEvQZb8J "Animated Zombie", oAArCNHjFB "Soldier" — Quaternius, CC-BY 3.0).
Modifications: materials recoloured in code (blue uniform/helmet, grey-green zombie tint, grey-flesh boss), unused weapons removed, meshes merged at load time.
- three/addons SkeletonUtils.js — MIT (three.js r180).

## v10 visual pass (2026-10-17 ~15:10 KST) — zombie + boss replaced
### Kenney Animated Characters Survivors — CC0 1.0 (USED: zombie + boss base)
- Page: https://kenney.nl/assets/animated-characters-survivors (page shows "License Creative Commons CC0", checked 2026-10-17 14:46 KST)
- Zip: dl/ac_survivors.zip (official kenney.nl media link). Kenney's old numbered names ("Animated Characters 1/2/3") now redirect to an error page; the pack with the human zombie skins is listed as "Survivors" (tags: zombie, survivor). Also downloaded "Animated Characters Retro" (CC0, same license text) for comparison — not used.
- License file (verbatim):
```
	

	Animated Characters Survivors (1.1)

	Created/distributed by Kenney (www.kenney.nl)

			------------------------------

	License: (Creative Commons Zero, CC0)
	http://creativecommons.org/publicdomain/zero/1.0/

	You can use this content for personal, educational, and commercial purposes.

	Support by crediting 'Kenney' or 'www.kenney.nl' (this is not a requirement)

			------------------------------

	• Website : www.kenney.nl
	• Donate  : www.kenney.nl/donate

	• Patreon : patreon.com/kenney
	
	Follow on social media for updates:

	• Twitter:	 twitter.com/KenneyNL
	• Instagram: instagram.com/kenney_nl
	• Mastodon:	 mastodon.gamedev.place/@kenney
```
- Files used: Model/characterMedium.fbx + Animations/idle.fbx, run.fbx, jump.fbx -> converted to models/kzombie.glb (three.js FBXLoader + GLTFExporter, scale tracks removed).
- Skin: Skins/Source/zombieA.svg edited -> models/kz_skin.png (zombie) and models/kb_skin.png (boss), 512x512; models/kz_emis.png, kb_emis.png = eye glow masks.
  Edits: skin recoloured to #A7B39B, hair darkened, shirt brown / pants blue-grey, original tongue + teeth removed and redrawn as a dark mouth with 3 big teeth, new brows/eyes (glowing yellow-green), boss version with a bigger sagging jaw and torn shirt holes. All drawn in code; no image-generation used.
- Boss = same Kenney body with bone proportions changed in code (wide chest, big arms, short thick legs, small head, hunch). Not a third-party boss model.
### No longer used (files still in models/ for comparison page index_v3quat.html, not referenced by index.html)
- VlXjG0N8Eg.glb (Quaternius Zombie, CC0) and 5vO2YJsPEf.glb (Quaternius Orc, CC0). Soldier PpLF4rt4ah.glb (Quaternius, CC0) is still used.
- three/addons used at build time only (not shipped): FBXLoader.js, GLTFExporter.js, fflate — MIT (three.js r180).
