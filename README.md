# Playervaults-Skript
[Spigot page](https://www.spigotmc.org/resources/playervaults.128507/)


A flexible, user-friendly Skript-based **player vaults system** for Minecraft servers (compatible with 1.21.4–1.21.6 and any version where Skript & SkBee work).  
**Create, manage, and secure personal vaults with custom size and permissions, directly in-game!**

---

## 💡 What Is It?

**Playervaults-Skript** is a Skript replacement for the well-loved Playervaults Plugin, letting your players store their items safely in private virtual chests ("vaults") accessed via command.  
All messages, vault names, and prompts use a small-caps unicode font for style and readability.

---

## 📦 Dependencies

- [**Skript**](https://github.com/SkriptLang/Skript)
- [**SkBee**](https://github.com/ShaneBeee/SkBee)

*Add both to your `/plugins` folder, reload your server, and you're ready!*

---

## 🚀 Features

- 🚪 **Private player vaults** w/ permissions for the number of allowed vaults per player (`playervaults.amount.X`)
- 👍 **Staff/Admin vault access** (`playervaults.admin`)
- 🧱 **Blocked item filter** (bedrock, barriers, spawners, command blocks—auto-returns blocked items to player if attempted to store)
- 📋 **Tab completion support:** Quick vault selection, player selection for admins
- 💬 **Stylish small-caps messages and titles**
- 👤 **Admin can access/inspect other players' vaults**
- 💾 **Vault auto-saving** (on close, drag, or click)
- 📝 **Easy to edit and expand** for custom server needs

---

## 🛡️ Permissions

| Permission                    | Action                                              |
|-------------------------------|-----------------------------------------------------|
| `playervaults.use`            | Access your own vaults (`/pv`)                      |
| `playervaults.amount.X`       | Allows up to X vaults (replace X with a number)     |
| `playervaults.admin`          | Access any player's vault and up to 1000 vaults     |

*Default: OPs have admin, normal players need their vault count specified.*

---

## 🕹️ Commands

```
/pv [vault_number] [player]
/playervault [vault_number] [player]
```
- `vault_number`: The vault to open (default: 1)
- `player`: (Admin only) open another player's vault

Tab completion helps pick numbers and players.

---

## ⛔ Blocked Items

By default, these items **cannot be stored** in vaults (for balance/security):
- Bedrock  
- Command Block  
- Spawner  
- Barrier  

Blocked items are sent back to the player's inventory automatically with a message.

You can easily customize blocked items by editing the relevant list at the top of the Skript.

---

## 🛠️ How To Install

1. Place `PlayerVaults.sk` in your `plugins/Skript/scripts` folder.
2. Ensure you have **Skript** and **SkBee** installed.
3. Run `/skript reload PlayerVaults` in-game or from console.
4. Set player permissions as needed (see above).

---

## ✅ Confirmed Working

Tested on **Minecraft 1.21.x** (should work on any recent version supporting Skript & SkBee).  
No resource pack or custom jars required—fully open source!

---

## 📝 Editing & Credit

- Skript by [hrmfulladvocado](https://github.com/harmfulladvocado)
- [PlayerVaults plugin resource](https://www.spigotmc.org/resources/playervaults.128507/)

---

## 📫 Support & Issues

For feedback, suggestions, or help:
- SpigotMC Resource: [PlayerVaults Skript](https://www.spigotmc.org/resources/playervaults.128507/)
- Or reach out via Spigot or Discord server if available

---
