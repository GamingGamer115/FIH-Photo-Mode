# FIH-Photo-Mode

| Keybinds | Feature |
| :--- | :--- |
| F1 | Take a screenshot (a Save As window asks where to save it) |
| F2 | Hide or show the HUD |
| F3 | Freeze or resume time (single-player only) |
| F4 | Turn post-processing off or on |
| F5 | Toggle the game’s built-in clean-capture camera mode |
| F6 | Show or hide the keybind menu |
| Home | Free camera on/off |
| PageUp / PageDown | Hold to widen / narrow the field of view |
| End | Give the field of view back to the game |
| \ | Rule-of-thirds composition grid |

Free camera controls: W/A/S/D to move, Space and Ctrl to go up and down, Shift for fast, Alt for slow, mouse to look, mouse wheel to change FOV.

Free camera. Your player’s movement is blocked while it’s on, so your flippy doesn’t move around.
Field of view control. Override the FOV from 10° to 120°, with one key to return control to the game.
Freeze time. is blocked automatically when other players are in your session, so it can’t desync you.
Composition grid and a shutter flash. Neither appears in the saved image, and neither does the menu.
On-screen menu with every keybind and its ON/OFF status. You can move it to any corner, resize it and change its opacity.

Put PhotoMode.dll in BepInEx\plugins

Run the game once and a settings file is created at BepInEx\config\local.fih.photomode.cfg. There you can rebind every key and change the menu corner, size, opacity, free camera speed, FOV limits and screenshot resolution.

Save As on every screenshot, or turn the prompt off and save straight to BepInEx\screenshots

Everything runs on your own computer. Nothing is sent to other players.
The effects reset automatically when the game changes scenes.
