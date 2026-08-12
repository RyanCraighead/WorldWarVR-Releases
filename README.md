# WorldAtWarVR

WorldAtWarVR is an unofficial VR mod for the Windows version of **Call of Duty: World at War**. It adds stereo OpenXR rendering, 6DOF head tracking, motion-controller aiming, VR input, room-space menu panels, and a standalone launcher.

> **Pre-release status:** Zombies is the primary supported mode. Multiplayer and Campaign are experimental. Read [Known Issues](KNOWN-ISSUES.md) before downloading.

## Download and install

Download the latest **`WorldAtWarVR-Setup.exe`** from [GitHub Releases](https://github.com/RyanCraighead/WorldAtWarVR-Releases/releases), run it, and open **WorldAtWarVR** from the Start Menu.

The launcher normally finds a Steam installation automatically. If it does not, choose **Browse** and select the Call of Duty: World at War installation folder. Pick a launch target and VR quality preset, then select **Launch in VR**. The chosen folder and settings are remembered.

## Current mode support

| Mode | Status | Notes |
|---|---|---|
| Zombies | **Working / primary** | The most tested and recommended way to play. |
| Local/offline multiplayer | **Experimental** | Some maps or modes remain broken. Optional automatic bots are available for local play when the supported user-supplied bot package is present. |
| Campaign | **Experimental** | Incompletely tested. Progression may currently fail around the second mission. |
| Online multiplayer | **Unsupported** | Not supported or tested. |

## Launcher options

- Automatic Steam installation detection or a manually selected compatible game folder
- **Main Menu — Zombies and Campaign** or **Multiplayer** launch targets
- Optional automatic bots for local/offline multiplayer
- **Recommended**, **High Quality**, and **Performance** VR resolution presets
- Saved settings, so normal setup is required only once

## Requirements

- A lawfully obtained, compatible Windows installation of Call of Duty: World at War
- Windows 10 version 2004 (build 19041) or newer, 64-bit
- An OpenXR-compatible PC VR headset and active OpenXR runtime
- Two tracked motion controllers for the complete control scheme

The game, maps, and bot package are not included. See [Requirements](REQUIREMENTS.md) for details.

## Controls

The right controller aims the visible weapon. The right trigger fires, the left grip aims down sights, and the sticks handle movement and snap turning. Native menus appear on a panel in front of the player and can be pointed at with the right controller.

See the complete [VR controls](CONTROLS.md).

## Media

Actual gameplay screenshots and a headset-capture video will be added before the repository is made public. Only captures from a tested release build will be used.

## Reporting a problem

Check [Known Issues](KNOWN-ISSUES.md), then [open a bug report](https://github.com/RyanCraighead/WorldAtWarVR-Releases/issues/new) with the mode, map or mission, headset, graphics card, resolution preset, and steps needed to reproduce the issue.

## Important notice

WorldAtWarVR is an independent fan-made modification. It is not affiliated with, endorsed by, or sponsored by Activision. Call of Duty and related names are trademarks of their respective owners.

WorldAtWarVR does not include Call of Duty executables or game assets. The installer presents the first-party license and installs the applicable third-party notices alongside the application.
