# StS80 IconRig

**Make Windows `.ico` files from images, and read or replace the icons inside EXE and DLL files.**
Portable. Free. No installer, no internet.

<img width="1400" height="1150" alt="iconrig-screenshot" src="https://github.com/user-attachments/assets/02b1d2cc-f725-436c-ad08-654b41121c5d" />

## Download

Go to **[Releases](../../releases/latest)** and download `StS80_IconRig.exe`.

- Windows 10 / 11
- Needs .NET Framework 4.8, which is already part of Windows 10 and 11
- One file, about 383 KB. Just run it.

## What it does

**Images to icons**
- Takes PNG, JPG, BMP, GIF, TIFF or ICO files, one or many at once.
- You choose exactly which sizes go into the `.ico` (16 to 256 px) and see what each size costs in KB.
- Four ways to fit a non-square image: fit, stretch, crop, or a manual crop you pick yourself.
- Trim transparent borders, solid background, rounded corners, retro pixel styles (1-bit, 8-bit, 16-bit).
- Author and copyright written inside the icon file. Batch save for a whole list.
- One-click web / favicon pack: `favicon.ico`, `apple-touch-icon.png`, Android icons, `site.webmanifest` and the HTML snippet.

**Icons inside EXE and DLL files**
- Extract every icon group of a file into `.ico` files, or single sizes as PNG.
- Put your own icon into an EXE or DLL, as a **new copy** (default, the original is never touched) or by **replacing the original** (a backup is always made first).
- Warns before you try: signed files, installers, protected system files.

**Icon check**
- Shows real defects in any icon: blown-up blurry layers, missing 256 x 256, sizes Windows never asks for, duplicates.

**Also:** live preview on a light and dark taskbar and in an Explorer list, 7 languages, 5 themes + 1 unmapped deep-space signal (try typing the right words).

## Privacy

No telemetry. No internet access. No background activity.
It writes only where you tell it to, plus two small places:
- `Documents\StS80 IconRig\` for icons, extractions, web packs and copies
- `%APPDATA%\StS80IconRig\` for the recent-files list (and settings, only if you turn on "Remember settings")

Delete those folders to leave nothing behind.

## Check your download

Every release lists a SHA-256 hash. To check the file you downloaded, run in PowerShell:

```powershell
Get-FileHash .\StS80_IconRig.exe -Algorithm SHA256
```

The result must match the hash in the release notes and in the `.sha256` file. If it does not, do not run the file.

## Windows may warn you

The program is not code-signed, so Windows SmartScreen can show "Windows protected your PC".
Click **More info**, then **Run anyway**, after you have checked the hash above.

## License

Free for personal and commercial use. Icons you create with it are entirely yours.

© 2026 BugMob. All rights reserved. The source code is not published. Modifying, decompiling, rebranding, selling or redistributing the program, in whole or in part, requires written permission from the author. Provided “as is”, without warranty.

Full terms: https://bugmob.com/terms

## Links

- Website: [bugmob.com/iconrig](https://bugmob.com/iconrig?iz=github)
- Microsoft Store: [StS80 IconRig](https://apps.microsoft.com/detail/9N978VZ263Z9)
