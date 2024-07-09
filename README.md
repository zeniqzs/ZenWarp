# Zenaria Warp Plugin 🌐

Welcome to the Zenaria Warp Plugin, designed to enhance teleportation functionality within your Minecraft server!

## Features 🚀

- **MySQL Integration:** Store warp locations in a MySQL database for efficient management.
  
- **Customizable Messages:** Personalize messages for different warp-related events.
  
- **Simple Command Setup:** Easy-to-use commands for setting, deleting, and teleporting to warp points.

## Configuration Example 📝

### MySQL Configuration

```yaml
MySQL:
  Host: "localhost"
  Port: "3306"
  Database: "warp"
  User: "root"
  Password: "0"

Messages:
  WarpNotFound: "#FF0000Warp not found."
  WarpMoved: "#FF0000Teleportation canceled because you moved!"
  WarpAlrTeleporting: "#FF0000You are already Teleporting!"
  WarpTeleporting: "&7Teleporting in &3%seconds% &7seconds."
  WarpTeleported: "&aSuccessfully Teleported to %warp%."
```

# Plugin Information
- Author: Zeniqzs & Zenaria
- Website: https://discord.zenaria.eu
- Commands and Permissions
- /warp: Teleports the player to a predefined warp point. Requires z.warp permission.
- /delwarp: Deletes a warp point. Requires z.delwarp permission.
- /setwarp: Sets a new warp point at the player's current location. Requires z.setwarp permission.


Enjoy seamless teleportation and management of warp points with the Zenaria Warp Plugin! For more information and updates, visit https://discord.zenaria.eu.
