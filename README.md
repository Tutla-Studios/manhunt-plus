<div align="center">
  <img src="https://raw.githubusercontent.com/Yezun-hikari/Yezun-hikari/main/oneko_thinking.png" width="128" />
  <h1>🧭 Manhunt+</h1>
</div>

**Manhunt+** is a powerful Minecraft manhunt plugin featuring compass tracking across dimensions, twists, and full control over the hunt!

---

## 📑 Table of Contents

- [Features & Usage](#-features--usage)
- [Commands](#-commands)
  - [Basic Setup & Commands](#-basic-setup--commands)
  - [Extras](#-extras)
  - [Settings](#-settings)
  - [Custom Twist Creator](#-custom-twist-creator)
  - [LootPool Commands](#-lootpool-commands)
- [Default Twists](#-default-twists)
- [Configuration](#-configuration)
- [Coming Soon](#-coming-soon)
- [Support, Tracking & More](#-support-tracking--more)
- [Other Tutla Studio Projects](#-other-tutla-studio-projects)

---

## ⚙️ Features & Usage

- ⚡ Easy and fast setup
- 🧭 Compass tracking across all dimensions (points toward portals)
- 🌀 Enrich the game with twists
- 🛠️ Create your own twists *(coming soon!)*

---

## 🕹️ Commands

<div align="center">
  <img src="https://raw.githubusercontent.com/Yezun-hikari/Yezun-hikari/main/oneko_hungry_smol.gif" />
</div>

### 🧍 Basic Setup & Commands

| ⚙️ Category | 💻 Command                             | 📖 Description                                                       | 🔑 Permission |
|------------|----------------------------------------|----------------------------------------------------------------------|--------------|
| 🧍 Setup | `/manhunt speedrunner add <player>`    | Add a speedrunner                                                    | `permission.node` |
| 🧍 Setup | `/manhunt speedrunner remove <player>` | Remove a speedrunner                                                 | `permission.node` |
| 🧍 Setup | `/manhunt hunter add <player>`         | Add a hunter                                                         | `permission.node` |
| 🧍 Setup | `/manhunt hunter remove <player>`      | Remove a hunter                                                      | `permission.node` |
| 🚀 Game | `/manhunt start`                       | Start the manhunt                                                    | `permission.node` |
| 🛑 Game | `/manhunt stop`                        | Stop the manhunt                                                     | `permission.node` |
| 📋 Info | `/manhunt list`                        | List all hunters & speedrunners                                      | `permission.node` |
| 📋 Info | `/manhunt donate`                      | [Donate](https://donatr.ee/tutlamc?utm_source=copy&utm_medium=share) | `permission.node` |
| 🧭 Tracking | `/compass <player:speedrunner>`        | Track a speedrunner                                                  | *None* |

### 🧪 Extras

| 💻 Command | 📖 Description | 🔑 Permission |
|-----------|----------------|--------------|
| `/manhunt prepare` | Waits for a speedrunner to hit a hunter to start | `permission.node` |
| `/surround <speedrunner>` | Surrounds the speedrunner with all hunters | `permission.node` |

### ⚙️ Settings

| 💻 Command | 📖 Description | 🔑 Permission |
|-----------|----------------|--------------|
| `/manhunt countdown <minutes>` | Set a max time limit ⏱️ (**0 to disable**) | `permission.node` |
| `/manhunt twist <twist>` | Apply a twist (default: `DEFAULT`) | `permission.node` |
| `/manhunt help` | Open the help menu 📖 | `permission.node` |

### 🌀 Custom Twist Creator

| 💻 Command | 📖 Description | 🔑 Permission |
|-----------|----------------|--------------|
| `/twist create <name:one_word>` | Create a new twist | `permission.node` |
| `/twist help` | Show help for twist commands | `permission.node` |
| `/twist list` | List all twists | `permission.node` |
| `/twist effect <twist_name> <effect>` | Set twist output action | `permission.node` |
| `/twist trigger <twist_name> <trigger>` | Set twist trigger | `permission.node` |
| `/twist triggerentity <entity>` | Set trigger entity | `permission.node` |
| `/twist triggerblock <block>` | Set trigger block | `permission.node` |
| `/twist appliesto <group>` | Set who can trigger the twist | `permission.node` |
| `/twist lootpool <twist_name> <lootpool_name>` | Assign a lootpool | `permission.node` |
| `/twist description <twist_name> <description>` | Set twist description | `permission.node` |

### 📦 LootPool Commands

| 💻 Command | 📖 Description | 🔑 Permission |
|-----------|----------------|--------------|
| `/lootpool create <name:one_word>` | Create a new lootpool | `permission.node` |
| `/lootpool pool add <item> <number> <weight>` | Add item to pool | `permission.node` |
| `/lootpool pool remove <index>` | Remove item by index | `permission.node` |
| `/lootpool pool list` | List pool items | `permission.node` |
| `/lootpool tier create <name>` | Start a new lootpool tier | `permission.node` |
| `/lootpool tier cancel` | Cancel tier creation | `permission.node` |
| `/lootpool tier complete` | Finish and save tier | `permission.node` |
| `/lootpool tier add <item>` | Add item to current tier | `permission.node` |
| `/lootpool tier remove <index>` | Remove item from tier | `permission.node` |
| `/lootpool delete <name>` | Delete a lootpool | `permission.node` |
| `/lootpool difficultymultiplier <decimal>` | Set difficulty multiplier | `permission.node` |
| `/lootpool complete` | Complete lootpool | `permission.node` |
| `/lootpool list` | List all lootpools | `permission.node` |
| `/lootpool cancel` | Cancel lootpool creation | `permission.node` |
| `/lootpool help` | Show help for lootpool commands | `permission.node` |

---

## 🌀 Default Twists
- `DEFAULT` – Standard manhunt rules
- `PIG_OP_LOOT` – Pigs drop OP loot (only for the speedrunner 🐷💎)
- **More twists coming soon! 🔧**

---

## 🛠️ Configuration

🗂️ Navigate to your server folder → `plugins/ManhuntPlus/config.yml`

- Calibration
    - `auto-calibration`: Enable/Disable auto compass calibration
    - `auto-calibration-interval` - Set the interval on which the compass updates. Recommended to increase this if used on larger servers or even completely disable it, restart server to apply changes
- Broadcasting
    - `broadcast-time`: true
    - `broadcast-time-every` - Broadcast time interval(in seconds)
- `surround-radius: DECIMAL` – Distance between speedrunner and hunters when using `/surround`. Default: `3`
- `name-tracking-compass`: Name the compass to which player its tracking

---

## 🚧 Coming Soon

<div align="center">
  <img src="https://raw.githubusercontent.com/Yezun-hikari/Yezun-hikari/main/oneko_sleep.gif" />
</div>

- 🌀 Many more twists
- 📊 Leaderboards?
- 🛠️ More customizability
- Chest loot twists

---

## 💬 Support, Tracking & More

- 💬 Join our [**Discord**](https://discord.tutla.net) for sneak peeks & community support
- ⭐ Star us on [**GitHub**](https://github.com/TutlaMC/manhunt-plus)
- 🌐 Visit our [**Website**](https://tutla.net) for updates
- 💙 Contribute by [**donating**](https://donatr.ee/tutlamc?utm_source=copy&utm_medium=share)

Think we’re missing something? **Contribute on [GitHub](https://github.com/TutlaMC/manhunt-plus)**

---

## 🧪 Other Tutla Studio Projects

- ⚔️ [**PvP+**](https://modrinth.com/plugin/pvp+plugin) – A Comprehensive PvP Plugin for Paper servers
- 🛡️ [**LeaveBind!**](https://modrinth.com/mod/leavebind) – Leave the server with a click of a button
- 🧾 [**Leave This, GoBack!**](https://modrinth.com/mod/leave-this-go-back) – Pressing on a slot twice returns you back to the previous slot. Useful for attribute swapping / quick tool swapping / mace pvp 
