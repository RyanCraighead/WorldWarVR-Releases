# Requirements

## Required

- **Operating system:** 64-bit Windows 10 version 2004 (build 19041) or newer, or Windows 11
- **Game:** a lawfully obtained, compatible Windows installation of Call of Duty: World at War, updated to version 1.7
- **VR:** an OpenXR-compatible PC VR headset with its active OpenXR runtime
- **Input:** two tracked motion controllers for the full VR control scheme
- **Graphics:** a DirectX 11-capable VR system

The normal Steam installation is detected automatically when possible. A compatible installation in another folder can be selected with **Browse** and is validated before launch.

WorldAtWarVR does not include the game, maps, executables, or other game assets.

## Performance

VR performance varies significantly by headset resolution, GPU, and map. Start with the **Recommended** preset. Use **Performance** if the headset drops frames or the game returns to the desktop view. Use **High Quality** only when the Recommended preset is stable.

A precise minimum CPU/GPU specification has not yet been established across enough systems. Please include the headset, GPU, and chosen preset when reporting performance results.

## Optional bots

Bots are optional and intended only for local/offline multiplayer. The
installer does not include or download a bot package.

To install them, download [PeZBOT 005p for World at War](https://www.moddb.com/mods/pezbot/downloads/pezbot-005p-for-world-at-war), leave
`PeZBOTWAW_005p.zip` unextracted in the current user's Windows **Downloads**
folder, enable **Automatic Bots**, and launch Multiplayer. WorldAtWarVR checks
the archive and installs it into its own private multiplayer profile. Do not
extract the archive or install it into the Call of Duty: World at War folder.

When creating the local game, leave **Dedicated** set to **No** so the headset
player joins alongside the bots. A successful import requests nine bots. The
ZIP is no longer needed after the verified installation has been created.

## Not supported

- Online multiplayer and public servers
- Non-Windows game builds
- Modified or unrecognized game executables
- Headsets without a working PC OpenXR runtime
