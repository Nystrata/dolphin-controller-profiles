# Dolphin Controller Profiles
A community collection of controller profiles for [Dolphin Emulator](https://dolphin-emu.org/)

## Contributing
File/Folder Structure
```
<GCPad or Wiimote>/<Game ID> - <Game Title>/<GCPad or Wiimote> - <Game Title> - <Input Backend> - <Profile Name>.ini
```
| Field | Description |
|-------|------------|
| `<GCPad or Wiimote>` | Whether the profile is for an emulated GameCube controller or emulated Wii Remote and accessories. |
| `<Game ID>` | Non-region-specific 3-character Game ID for the game. (If the full Game ID for *Metroid Prime 3: Corruption* for the Wii is `RM3E01`, the non-region-specific Game ID is the first three characters: `RM3`.) |
| `<Game Title>` | The full title of the game, as allowed by standard file name convention. (e.g.: "Metroid Prime 3: Corruption") |
| `<Input Interface>` | The input interface for the controller device (e.g.: `SDL`, `DInput`, `XInput`, `WGInput`, `DSU`, etc.). |
| `<Profile Name>` | Describe the profile (e.g.: "Nyss Switch Pro Gyro Aiming"). |


Example file path:
```
Wiimote/R3M - Metroid Prime Trilogy/Wiimote - Metroid Prime Trilogy - SDL - Nyss Switch Pro Gyro Aiming.ini
```

Your profile INI should have comments that describe:
- The name of your profile
- The version of Dolphin Emulator you tested this on
- Which controllers it was intended for
- The purpose of the profile
- A list of input mappings for in-game actions.

See [this profile](https://github.com/Nystrata/dolphin-controller-profiles/blob/main/Wiimote/RM3%20-%20Metroid%20Prime%203%20%3ACorruption/Wiimote%20-%20Metroid%20Prime%203%3A%20Corruption%20-%20SDL%20-%20Nyss%20Switch%20Pro%20Gyro%20Aiming.ini) for an example.
