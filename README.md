# Zen Tweaks

A collection of minor UI tweaks aimed at subtly improving the Zen user experience.

<!-- markdownlint-disable-next-line MD033 -->
<img
  width="240"
  alt="zen-badge-light"
  src="https://github.com/user-attachments/assets/d6ab3ddf-6630-4062-92d0-22497d2a3f9a"
/>

## Overview

*Zen Tweaks* comes with a number of features that can toggled on or off. Below is a compact list of these features.
More details can be found in the [**Features**](#features) section below.

- ☑️ **Compact Mode: Disable Sidebar Popup**
- ☑️ **Remove Edge Gaps**
- ☑️ **Remove Tab Shadow**
- ☑️ **Split Mode: Fix Misaligned Dragger**
- ☑️ **Split Mode: Remove Tab Gaps**
- ☑️ **Split Mode: Remove Tab Highlight**

## Manual Installation

This mod must be installed manually.

1. Open `about:profiles` in Zen. Locate the *Root Directory* field and click *Show in Finder*.
2. Locate the `zen-themes.json` file and open it in a text editor. Add the following JSON field.
    >
    ```json
    "zen-tweaks": {
      "id": "zen-tweaks",
      "name": "Zen Tweaks",
      "description": "A collection of minor UI improvements for Zen.",
      "homepage": "https://github.com/BuildEternal/zen-tweaks",
      "style": "https://raw.githubusercontent.com/BuildEternal/zen-tweaks/main/chrome.css",
      "readme": "https://raw.githubusercontent.com/BuildEternal/zen-tweaks/main/README.md",
      "author": "BuildEternal",
      "preferences": "https://raw.githubusercontent.com/BuildEternal/zen-tweaks/main/preferences.json"
    }
    ```
    >
3. Go to Zen's settings and click on *Zen Mods*. Click *Check for Updates*.

### Updating This Mod

This mod must be updated manually.

1. Open `about:profiles` in Zen. Locate the *Root Directory* field and click *Show in Finder*.
2. Locate the `zen-themes.json` file and open it in a text editor. Update the version number to current.
3. Navigate to `chrome/zen-themes/`. Once there, delete the `zen-tweaks` folder.
4. Go to Zen's settings and click on *Zen Mods*. Click *Check for Updates*.

### Uninstalling This Mod

This mod must be uninstalled manually.

1. Open `about:profiles` in Zen. Locate the *Root Directory* field and click *Show in Finder*.
2. Locate the `zen-themes.json` file and open it in a text editor. Remove the JSON field corresponding to this mod.
3. Navigate to `chrome/zen-themes/`. Once there, delete the `zen-tweaks` folder.

## Features

Below is a detailed list of all features in *Zen Tweaks*. All features can be toggled on or off, and some features have
additional settings. Most features are off by default.

### ☑️ Compact Mode: Disable Sidebar Popup

Prevents the sidebar from appearing on hover when it is hidden in compact mode. Note that this can make compact mode
difficult to disable without the hotkey.

*Can be toggled on or off.*

### ☑️ Remove Edge Gaps

Removes the gaps around the edge of the window for a cleaner look.

*Can be set to **Always**, **Only in Compact Mode**, or **Off***

### ☑️ Remove Tab Shadow

Removes the shadow behind the tab window.

*Can be toggled on or off.*

### ☑️ Split Mode: Fix Misaligned Dragger

Realigns the dragger in split mode to be centered, since it is misaligned by default.

*Can be toggled on or off.*

### ☑️ Split Mode: Remove Tab Gaps

Removes the gaps between tab windows in split mode.

*Can be toggled on or off.*

### ☑️ Split Mode: Remove Tab Highlight

Removes the highlight on the focused tab window in split mode.

*Can be toggled on or off.*

## Credits

- Forked from [No-Gaps](https://github.com/Comp-Tech-Guy/No-Gaps) by [CompTechGuy](https://github.com/Comp-Tech-Guy).
