# Yoda Yeet

Replace Yeet (squashed man in red suit) to Yoda in Horde mode.


## How to install
1. Create the directory `.../MORDHAUEditor/Mordhau/Mods/YodaYeet`.
2. Move to the directory and open the command prompt.
3. Write `git clone https://github.com/ColdSpirit0/MordhauMod-YodaYeet.git .`


## Config example

```ini
[/Script/Mordhau.MordhauGameSession]
Mods=3755001 ; https://mod.io/g/mordhau/m/yoda-yeet

[/Script/Mordhau.MordhauGameMode]
SpawnServerActorsOnMapLoad=/YodaYeet/YodaYeetInit.YodaYeetInit_C
```