# Echos of Nou

> A 2D vertical platformer where Xiangxi Nuo folklore meets cyber-folk aesthetics. Climb from the misty river valley to the abandoned ancestral shrine — one breath, one mask, one jump at a time.

<img width="927" height="927" alt="游戏封面" src="https://github.com/user-attachments/assets/f0364a49-ecfd-4195-ba23-22fdc070d8b9" />


---

## About the Game

<img width="1456" height="816" alt="jamieX_httpss mj runtHSyvsIoGoQ_Cinematic_game_environment_co_715f66c0-1534-49df-9810-a416762cb371_1" src="https://github.com/user-attachments/assets/c3781422-37b7-423d-906c-98acf8395c7a" />

You play as **A'Nuo**, a Tujia (Tujia) youth wearing a shattered Nuo mask. Starting from the deepest, darkest river valley, your goal is to complete an extreme vertical climb to the ancestral shrine at the mountain peak — a place abandoned by the gods.

Master the abilities of four different **Nuo Masks** to traverse treacherous terrain, anchor your progress through ancient shrines scattered along the climb, and ultimately ignite the Nuo Fire with your fragile mortal body.

This prototype focuses on the platforming experience and level puzzle-solving. A roguelite expansion is planned for the future — see the [Roadmap](#roadmap) below.

---

## Download
 
Get the latest build for your platform:
 
| Platform | File | Size | Download |
|----------|------|------|----------|
| 🪟 Windows | `EchosOfNou-Windows-v1.0.0.zip` | 62.8 MB | [Download](https://github.com/Jamie-X/EchosOfNou_2DVerticalPlatformerGame/releases/latest/download/EchosOfNou-Windows-v1.0.0.zip) |
| 🍎 macOS | `EchosOfNou-macOS-v1.0.0.dmg` | 104 MB | [Download](https://github.com/Jamie-X/EchosOfNou_2DVerticalPlatformerGame/releases/latest/download/EchosOfNou-macOS-v1.0.0.dmg) |
| 🤖 Android | `EchosOfNou-Android-v1.0.0.apk` | 110 MB | [Download](https://github.com/Jamie-X/EchosOfNou_2DVerticalPlatformerGame/releases/latest/download/EchosOfNou-Android-v1.0.0.apk) |
| 📱 iOS | — | — | Coming soon |
 
> 📦 For older versions, patch notes, and SHA-256 checksums, see the [Releases page](https://github.com/Jamie-X/EchosOfNou_2DVerticalPlatformerGame/releases).
 
---
 
## First Launch
 
Echos of Nou is an unsigned indie release, which means your operating system will likely show a security warning the first time you run it. This is expected — the game is safe, it just hasn't gone through the (expensive) commercial signing process. Here's how to get past the warning on each platform.
 
### 🪟 Windows
 
1. Extract `EchosOfNou-Windows-v1.0.0.zip` to a folder of your choice.
2. Open the extracted folder and double-click `EchosOfNou.exe`.
3. Windows SmartScreen may show a blue **"Windows protected your PC"** dialog.
4. Click **More info** → then click **Run anyway**.
The warning will not appear again on subsequent launches.
 
> ⚠️ Keep `EchosOfNou.exe` and `EchosOfNou.pck` in the same folder — the game loads its data from the `.pck` file at startup. If you move or rename one, do the same to the other.
 
### 🍎 macOS
 
1. Open `EchosOfNou-macOS-v1.0.0.dmg` and drag **Echos of Nou** into your **Applications** folder.
2. Open Applications, then **right-click** (or Control-click) **Echos of Nou** and choose **Open**.
3. macOS Gatekeeper will warn that the developer is unidentified. Click **Open** in the dialog.
If the dialog only offers "Move to Trash" with no "Open" option (newer macOS versions), do this instead:
 
1. Try to launch the game once normally — it will be blocked.
2. Open **System Settings → Privacy & Security**.
3. Scroll down to find the message *"Echos of Nou was blocked..."* and click **Open Anyway**.
4. Enter your password to confirm.
You only need to do this once per install.
 
### 🤖 Android
 
1. Download `EchosOfNou-v1.0.0.apk` to your device.
2. Tap the file to install. Android will warn that you're installing from an unknown source.
3. Tap **Settings** in the warning, then enable **Allow from this source** for your browser or file manager.
4. Return to the install prompt and tap **Install**.
After installation, you can disable that permission again if you'd like.
 
---
 
## Core Gameplay Loop
 
The current build is a classic **Climb → Fall → Checkpoint Retry** platformer that emphasizes muscle memory and timely mask-switching.
 
- **Auto-Walk + Charged Jump** — A'Nuo walks horizontally on her own. Hold `Space` to stop and charge a jump (up to 2 seconds for max height).
- **Vertical Climbing** — Read the terrain, dodge deadly traps, and chain mask abilities to clear seemingly impossible gaps.
- **Forgiving Death** — No permadeath in the prototype. A fall triggers a "fate thread" transition that returns you to your last activated shrine.
- **Mask Switching** — Hot-swap between Nuo Masks to solve traversal puzzles unique to each section of the mountain.
---
 
## Game Modes
 
Pick the experience that fits how you want to play:
 
### 🌫 Normal Mode
The intended journey. A'Nuo starts with only her basic jump, and the four Nuo Masks unlock one by one as you climb the mountain. Difficulty is tuned to match your growing toolkit.
 
### 📖 Story Mode
Designed for players here for the world, the art, and the music. **All four masks are unlocked from the start**, so you can dash, wall-jump, and invert gravity past tricky sections and focus on the Xiangxi folktale at the heart of the game.
 
### ⏱ Speedrun Mode
For the hardcore. Includes a millisecond-precise in-game timer, skips non-essential cutscenes, and rewards perfectly tuned mask-switching muscle memory. Valley floor to peak — as fast as you can.
 
---
 
## The Four Nuo Masks
 
The "one-button action" is the heart of the combat-traversal system. The same `Space` key produces wildly different abilities depending on which mask A'Nuo wears.
 
| Mask | Style | Toggle Key | Ability |
|------|-------|-----------|---------|
| 🕊 **The Pathfinder** | Aerial Dash | `Shift` (no time limit) | "White Gull Dash" — high-speed mid-air dash that ignores gravity. For crossing wide chasms and dodging horizontal traps. |
| 🪨 **The Mountain Breaker** | Cliff Cling | `Q` (manual toggle) | "Wall Cling Suspension" / "Breaker Grapple" — grip vertical walls and reverse-bounce. The only way up sheer terrain. |
| 🔮 **The Eightfold King** | Anti-Gravity | `E` (manual toggle) | "Gravity Inversion" — fall upward and walk on ceilings. Reshapes the puzzle logic of every room. |
| 🔥 **The Nuo-Fire Warlord** | Double Jump | Double-tap `Space` | "Nuo-Fire Ascension" — kick off burning Nuo fire mid-air for a second jump. High mobility, high recovery. |
 
---
 
## The Checkpoint System
 
Extreme platforming is hard enough — losing all your progress to one slip is not the kind of suffering this game serves up.
 
- **Shrine Activation** — Walk past an Ancient Shrine or glowing Bonfire and it activates automatically.
- **Fall Protection** — Falling triggers a "fate thread pulling" transition that respawns A'Nuo at the last shrine.
- **Progress Anchoring** — Checkpoints lock in your absolute height. Every breakthrough sticks.
---
 
## Vertical Biomes
 
The mountain is divided into four biomes, each evolving the visual language as you ascend:
 
1. **🌊 Bottom Layer — Misty River Pass**
   Dark teal tones, ruined stone bridges, ghost-light grass. The tutorial area for basic jumping and the dash mask.
2. **⚰️ Middle Layer — Valley of Suspended Coffins**
   Sheer cliffs studded with wooden coffins embedded in the mountainside. The Mountain Breaker's playground.
3. **🏮 Mid-High Layer — Stilted Cliff Village**
   Tujia *Diaojiaolou* (stilted houses) clinging to the rock face, red lanterns, dilapidated planks. The terrain narrows mercilessly.
4. **🔥 Peak — Ancestral Shrine Peak**
   Warm gold and crimson Nuo fires, a massive bronze Eight Trigrams diagram, an endless sea of clouds under a starry sky.
---
 
## Audiovisual Pipeline
 
**Visual Art** — High-resolution vertical backgrounds are generated in Midjourney, then imported into Photoshop / Aseprite and downsampled with the *Nearest Neighbor* algorithm to unify everything under a coherent pixel-art style.
 
**Audio** — Cyber-Folk. Background music is generated in Suno with a seamless loop. Heavy synth bass and tribal war drums form the foundation; piercing traditional Chinese **Suona** cuts in during critical jumps and crisis moments as an emotional anchor.
 
---
 
## Roadmap
 
The current build is a "suffering platformer" prototype. Planned evolution into a **Platformer Roguelite**:
 
- [ ] **Combat** — Forest monsters during the climb, exorcised with the masks of the Tujia *Badai* (Shamans).
- [ ] **Bronze Loom Blessing System** — Run-based enhancements (fire-trail dashes, max HP boosts, and more).
- [ ] **Permadeath & Meta-Progression** — Safe checkpoints removed; falls cost HP. On death, return to the valley floor and spend collected resources to permanently unlock starting masks and abilities.
- [ ] **Procedural Dungeons** — Level chunks vertically stitched together at random for infinite replay.
---
 
## Tech Stack
 
- **Engine** — Godot 4.6.2
- **Art** — Midjourney → Photoshop / Aseprite (Nearest Neighbor downsample)
- **Audio** — Suno (seamless-loop cyber-folk)
- **Build Targets** — Windows, macOS, Android, iOS
---
 
## Credits
 
**Indie Developer** — Jamie Xingye Xiang
 
Inspired by Xiangxi Tima (Nuo) culture, Tujia folklore, and the Tujia people of western Hunan.
 
---
 
## Acknowledgments
 
Echos of Nou stands on the shoulders of generous open-source maintainers and asset creators. Huge thanks to the following:
 
### Code & Engine
 
- **[godot4-2d-platformer-template](https://github.com/EladKarni/godot4-2d-platformer-template)** by [Elad Karni](https://github.com/EladKarni) — the foundational platformer scaffolding that Echos of Nou's mask-switching and vertical climbing mechanics are built on top of. Released under the MIT License.
### Art Assets
 
- **[The DARK Series — Roots & Trees](https://penusbmic.itch.io/)** by [Penusbmic](https://penusbmic.itch.io/) — atmospheric pixel-art tileset and prop pack used throughout the cliff and forest biomes. Their ongoing DARK Series shaped a lot of the game's visual mood. Used and modified with permission under their commercial-use license.
If you enjoy the look of the game, check out [Penusbmic's itch.io page](https://penusbmic.itch.io/) for more pixel art packs and free assets — and consider [supporting them on Patreon](https://www.patreon.com/penusbmic).
 
See the [LICENSE](./LICENSE) file for full attribution and license terms.
 
---
 
## License
 
Echos of Nou's original code is released under the MIT License. See [LICENSE](./LICENSE) for the full text, including attribution to upstream open-source work.
 
Third-party assets and code are licensed under their respective terms. The art assets from Penusbmic's DARK Series are used as a paid licensee with the creator's permission for commercial use and modification. If you'd like to use these assets in your own project, please purchase your own license from [Penusbmic's itch.io page](https://penusbmic.itch.io/).
 
---
 
## Reporting Bugs / Feedback
 
Found a soft-lock? Got a balance complaint about the Eightfold King? [Open an issue](../../issues/new) — feedback during the prototype phase is genuinely valuable.
 
---
 
*"The gods abandoned the peak. A'Nuo did not."*
