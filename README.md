> **Disclaimer**
>
> I am **not** the original author of this mod loader.  
> The original author is **unknown**.  
> This repository exists solely to provide an easy and centralized way to **distribute and preserve** the WoWP mod loader.


# WoWP mod loader

## Download
[Download the latest version here](https://github.com/speedy373737/CustomQueueBackgrounds/releases/latest/download/CustomQueueBackgrounds.zip)

## Installation
1. Download the ZIP file from above.
2. Extract the archive.
3. Open the `WoWP_mod_loader` folder.
4. Copy **all folders inside** to: `res_mods/<current_version>/`
5. Do **not** copy the `WoWP_mod_loader` folder itself — only its contents.
6. Replace `<current_version>` with your game version (e.g. `2.1.33.0`).

## Usage
To install a mod that uses the mod loader, place it in: `res_mods/<current_version>/scripts/client/mods/`

## For Developers
1. Compile your mod into a `.pyc` file.
2. Prefix the filename with `mod_`.

Example: `mod_example.pyc`
> All files matching this pattern are automatically loaded into the game environment on startup.
