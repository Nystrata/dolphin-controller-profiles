# Dolphin Controller Profiles
A community collection of controller profiles for [Dolphin Emulator](https://dolphin-emu.org/)

## Contributing
File/Folder Structure
```
<GCPad or Wiimote>/<Game ID> - <Game Title>/<GCPad or Wiimote> - <Game Title> - <Input Backend> - <Profile Name>
```
- `<GCPad or Wiimote>`: Whether the profile is for an emulated GameCube controller or emulated Wii Remote (and accessories).
- `<Game ID>`: Non-region-specific 3-character Game ID for the game   
  (If the full Game ID for *Metroid Prime 3: Corruption* for the Wii is `RM3E01`, the non-region-specific Game ID is the first three characters: `RM3`)
- `<Game Title`>: The full title of the game, as allowed by standard file name convention
- `<Input Backend>`: The input protocol for the controller device  
  (e.g.: `SDL`, `DInput`, `XInput`, `WGInput`, `DSU`, etc.)
- `<Profile Name>`: Descripe the profile  
  (e.g.: "Nyss Switch Pro Gyro Aiming")

Example file path:
```
Wiimote/R3M - Metroid Prime Trilogy/Wiimote - Metroid Prime Trilogy - SDL - Nyss Switch Pro Gyro Aiming.ini
```