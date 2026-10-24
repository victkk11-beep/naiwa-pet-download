# Naiwa Pet

[简体中文](./README.md) · [English](./README.en.md)

An unofficial custom ChatGPT pet asset pack featuring the Naiwa v2 sprite sheet, with previews of its left/right-looking idle and belly-laugh animations. The previews are extracted from the current pet atlas; the character artwork has not been redrawn.

[Download the complete asset pack](https://github.com/victkk11-beep/naiwa-pet-download/raw/refs/heads/main/naiwa-pet-download.zip) · [Download the v2 sprite sheet](https://github.com/victkk11-beep/naiwa-pet-download/raw/refs/heads/main/naiwa-pet-spritesheet-v2.png)

## Animation previews

**Idle: looking left and right, with blinking**

![Six frames of Naiwa's idle animation](./assets/idle-look-frames.png)

![Naiwa idle animation loop](./assets/idle-look.gif)

**Hover: laughing while holding its belly**

![Five frames of Naiwa's laughing animation](./assets/hover-laugh-frames.png)

![Naiwa laughing animation loop](./laugh-preview.gif)

These previews are exported from the corresponding animation rows in the current v2 sprite sheet. The atlas is a transparent PNG, 1536 × 2288 pixels, arranged as 8 columns by 11 rows, with 192 × 208 pixels per frame.

## Download and use

1. Download and extract the ZIP, or download `naiwa-pet-spritesheet-v2.png` on its own.
2. In the ChatGPT desktop app, open **Settings → Pets → Create pet**. This opens a new pet-creation chat.
3. Attach the PNG in that chat and say: **“Please use this v2 sprite sheet as the Naiwa pet. Preserve the atlas pixels and do not redraw the character.”**
4. When creation is complete, return to **Settings → Pets**, select **Refresh**, then choose Naiwa.

See the [official ChatGPT Pets guide](https://learn.chatgpt.com/docs/pets) for details. This repository contains the v2 atlas. The web **Upload pet** flow currently requires a 1536 × 1872 sprite sheet, so use the desktop app's **Create pet** flow for this asset.

## Files

- `naiwa-pet-spritesheet-v2.png`: the complete transparent v2 atlas used to create the pet.
- `naiwa-pet-download.zip`: the atlas, bilingual guides, and animation previews.
- `laugh-preview.gif`: a looping belly-laugh preview.
- `assets/idle-look.gif`, `assets/hover-laugh.gif`: animation loops exported from the current atlas.
- `assets/*-frames.png`: contact sheets showing the individual animation frames.

## FAQ

**Does the pet laugh out loud?**

The asset pack contains no audio; the animation previews are silent.

**Why can't I upload this on the web?**

This is a v2 atlas (1536 × 2288). The official Pets guide lists 1536 × 1872 for web uploads. Use **Create pet** in the ChatGPT desktop app.

## Attribution

This is an unofficial fan-made work based on visual references supplied by the user. It is not affiliated with, endorsed by, or sponsored by the Naiwa app or its publisher. Rights to the character and related marks belong to their respective owners. This repository does not claim ownership of the character or grant a license to use the underlying character assets. Contact the rights holder before redistribution, commercial use, or any other use that requires authorization.
