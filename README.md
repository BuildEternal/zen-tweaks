# Zen Tweaks

A collection of minor UI tweaks aimed at subtly improving the Zen user experience.

<!-- markdownlint-disable-next-line MD033 -->
<img
  width="240"
  alt="zen-badge-light"
  src="https://github.com/user-attachments/assets/d6ab3ddf-6630-4062-92d0-22497d2a3f9a"
/>

## Overview

**Zen Tweaks** comes with the following configurable features:

- Remove Edge Gaps
- Remove Tab Shadow
- Split Mode: Fix Misaligned Dragger
- Split Mode: Remove Tab Gaps
- Split Mode: Remove Tab Highlight

## Manual Installation

This mod must be installed manually.

1. Open `about:profiles` in Zen. Locate the *Root Directory* field and click *Show in Finder*.
2. Locate the `zen-themes.json` file and open it in a text editor. Add the following JSON field.
    >
    ```json
    "zen-tweaks": {
      "id": "zen-tweaks",
      "name": "Zen Tweaks",
      "description": "A collection of minor UI improvements to Zen.",
      "homepage": "https://github.com/BuildEternal/zen-tweaks",
      "style": "https://raw.githubusercontent.com/BuildEternal/zen-tweaks/main/chrome.css",
      "readme": "https://raw.githubusercontent.com/BuildEternal/zen-tweaks/main/README.md",
      "author": "BuildEternal",
      "preferences": "https://raw.githubusercontent.com/BuildEternal/zen-tweaks/main/preferences.json"
    }
    ```
    >
3. Go to Zen's settings and click on *Zen Mods*. Click *Check for Updates*.

## Credits

- Forked from [No-Gaps](https://github.com/Comp-Tech-Guy/No-Gaps) by [CompTechGuy](https://github.com/Comp-Tech-Guy).
