# Known issues

This project is still a pre-release. Zombies has received the most testing; other modes should be treated as experimental.

## Zombies

- Zombies is the primary supported mode, but not every custom setup, headset, GPU, or map state has been tested.
- If headset rendering becomes unstable, exit the game completely and retry with the **Performance** resolution preset before filing a report.

## Multiplayer

- Local/offline multiplayer is experimental. Some maps or modes remain broken or may fail to start correctly.
- Optional bots require the separately downloaded `PeZBOTWAW_005p.zip` archive.
  Leave it unextracted in Windows Downloads; WorldAtWarVR verifies and installs
  it automatically when **Automatic Bots** is enabled.
- A map or mode may start without bots if its bot support fails, even when automatic bots are enabled.
- The current launcher does not yet show a bot-installation status. If no bots
  appear, confirm the archive has the exact filename above, restart the
  launcher, and keep **Dedicated** set to **No** when creating the local game.
- Online multiplayer is not supported or tested. Do not use this build on public servers.

## Campaign

- Campaign is experimental and has not been tested from beginning to end.
- Progression may currently fail around the second mission.
- Some mission-specific prompts or scripted camera events may still require keyboard input or behave incorrectly in VR.

## Compatibility and presentation

- Only recognized, compatible game executables are accepted.
- Performance and visual clarity vary by headset resolution and GPU. The High Quality preset may be too demanding for some systems.
- A headset showing a desktop window or two-eye mirror instead of immersive stereo is a fault. Exit the game and include the launch target and exact sequence in a bug report.

If your problem is not covered here, [open a bug report](https://github.com/RyanCraighead/WorldAtWarVR-Releases/issues/new).
