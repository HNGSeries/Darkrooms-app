<p align="center">
  <img src=".github/assets/banner.png" alt="Darkrooms: the film lab for M-Film rolls, on your computer" width="100%">
</p>

<p align="center">
  <a href="../../releases/latest"><img alt="Latest release" src="https://img.shields.io/github/v/release/HNGSeries/Darkrooms-app?style=for-the-badge&label=Darkrooms&color=eca834&labelColor=181614"></a>
  <img alt="Windows · macOS" src="https://img.shields.io/badge/Windows%20%C2%B7%20macOS-181614?style=for-the-badge">
  <a href="https://github.com/HNGSeries/mfilm-canon-film-simulation"><img alt="For M-Film" src="https://img.shields.io/badge/for-M--Film-eca834?style=for-the-badge&labelColor=181614"></a>
</p>

<h3 align="center">
  <a href="../../releases/latest">⬇&nbsp; Download Darkrooms</a>
</h3>

<p align="center">
  Plug in the camera, pick a roll, and watch it develop.<br>
  Every pixel of the RAW, in the very colours the camera gives it.
</p>

<br>

<p align="center">
  <img src=".github/assets/screenshot.png" alt="Darkrooms waiting for the camera" width="88%">
</p>

<br>

## What it does

[M-Film](https://github.com/HNGSeries/mfilm-canon-film-simulation) turns a Canon camera that runs Magic Lantern into
a film camera: load a roll, shoot it, develop it. The camera can develop a roll by itself, slowly and at a smaller size.
Darkrooms does it on your computer, fast and at full size.

|  |  |
|---|---|
| 🎞️ **Every roll, found by itself** | Plug the camera in with its USB cable, or put its card in a reader. Darkrooms lists each roll: its film and its frames. |
| 🖼️ **Full resolution** | Each frame is developed from the whole RAW: 5184 × 3456 on an 18 MP camera, every pixel. |
| 🎨 **The camera's own colours** | Darkrooms develops as the camera's darkroom does and reads the same colour tables, so a roll comes out the same in both. 68 film stocks. |
| 📁 **Prints, filed like a lab would** | One folder per roll, named as the camera names it (`Sep0906 Portra400`), with a contact sheet. |
| 🔄 **Keeps itself up to date** | When a new version is out it says so, shows what's new, and installs it with one click. |
| 🔒 **Private** | Your pictures never leave your computer. |

## Download

Get the newest build from **[Releases](../../releases/latest)**. Pick the file for your computer:

| Computer | File | How to open it |
|---|---|---|
| 🪟 **Windows 10 / 11** | `Darkrooms-windows-x64.zip` | Unzip, open the `Darkrooms` folder and run `Darkrooms.exe`. |
| 🍎 **Mac with Apple silicon** (M1 and later) | `Darkrooms-macos-apple-silicon.zip` | Unzip, drag `Darkrooms.app` to Applications and open it. |
| 🍏 **Mac with Intel** | `Darkrooms-macos-intel.zip` | Same. |

> [!NOTE]
> Darkrooms isn't signed with Microsoft or Apple yet, so the first time your computer asks before it opens it.
> - **Windows:** *More info* → *Run anyway*.
> - **Mac:** *System Settings → Privacy & Security*, scroll down, *Open Anyway* (macOS 14 and older: right-click the app → *Open*).
>
> If a Mac still won't open it: `xattr -dr com.apple.quarantine "/Applications/Darkrooms.app"`

> [!TIP]
> Keep Darkrooms where you can write to it (on a Mac, in Applications) so it can update itself.

## Free and Full

| | Free | Darkrooms Full |
|---|---|---|
| Rolls a day | 1, of up to 36 frames (the same roll again that day doesn't count) | as many as you like |
| Every film, full size, EXIF, contact sheets | ✓ | ✓ |
| *Fast*: every core at once | | ✓ |
| Price | free, with a Google account | **US$2.99 a month** or **US$14.99 once** (checkout shows your currency), updates included |

Buy Full in the program: click the badge at the top right and sign in with Google.
One Google account works on two computers at a time, Free or Full.
A monthly plan can be cancelled any time in the program (*Manage the subscription*); it stays on until the end of
the month paid for. [Privacy](https://darkrooms-licence.suphalapruksasathit.workers.dev/privacy).

## Help

- **The camera's files** (what goes on the card) are on **[M-Film's releases](https://github.com/HNGSeries/mfilm-canon-film-simulation/releases/latest)**, not here.
- **Something wrong?** [Open an issue](../../issues), and say which computer and which version of Darkrooms.
- **How the darkroom develops:** [M-Film's notes](https://github.com/HNGSeries/mfilm-canon-film-simulation/blob/main/ml-dev/DEVELOPING.md).

<br>

<p align="center">
  <sub>This repository holds Darkrooms' builds and release notes only.<br>
  Darkrooms 0.2.1 and older were published in <a href="https://github.com/HNGSeries/mfilm-canon-film-simulation/releases?q=Darkrooms&expanded=true">M-Film's releases</a>, and 0.2.2 went there as well, so those versions find their update.</sub>
</p>
