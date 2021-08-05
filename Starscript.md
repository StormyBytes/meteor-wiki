# Starscript
[Starscript](https://github.com/MeteorDevelopment/starscript) is the formatting language currently used in Discord Presence.  
Full syntax can be found [here](https://github.com/MeteorDevelopment/starscript/wiki).

## Variables
A list of standard variables can be found [here](https://github.com/MeteorDevelopment/starscript/wiki#standard-variables).

### General
- `version`: Meteor version.
- `mc_version`: Minecraft version.
- `fps`: Current FPS.

### Player
- `player`: Username.
- `player.health`: Player's health.
- `player.hunger`: Player's hunger.
- `player.speed`: Speed in blocks per second.
- `player.pos`: Player's position formatted as `X: 0 Y: 0 Z: 0`.
- `player.pos.x`: Player's X position.
- `player.pos.y`: Player's Y position.
- `player.pos.z`: Player's Z position.
- `player.yaw`: Player's yaw rotation.
- `player.pitch`: Player's pitch rotation.
- `player.hand`: The name of the player’s main held item.
- `player.offhand`: The name of the player’s offhand held item.

### Server
- `server`: Server name.
- `server.tps`: Server's TPS.
- `server.time`: Server's time formatted as `16:00`.
- `server.difficulty`: Server's difficulty.
- `server.player_count`: Server's player count.
