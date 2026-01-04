# 🔮 FateboundCore

> A fate-driven survival core plugin where **power has consequences**, **inactivity is punished**, and **the world remembers who held power**.

FateboundCore is a meta-core plugin for Minecraft **1.21.X** that introduces permanent **player fates**, world-level **relics**, and story-driven gameplay without replacing economy, claims, or teams.

---

## ✨ Key Features

- 🔗 Permanent **Player Fates**
- ⚔️ Powerful abilities with real **weaknesses**
- 🐉 World-level **Fate Relics** (Dragon Egg)
- ☠️ PvP-based power transfer
- 💤 AFK & offline punishment system
- 📢 Server-wide fate notifications
- 🛡️ Anti-exploit & anti-abuse protections
- 🔌 Compatible with major plugins
- 🧠 Event-driven, no NMS, future-proof

---

## 🎯 Design Philosophy

> **Power must be carried.  
> Fate must be faced.  
> Hiding has consequences.**

### Core Rules
- Every power has a weakness
- Stronger fate = higher risk
- AFK and inactivity are punished
- No pay-to-win mechanics
- No forced gameplay loops
- Player actions create server stories

---

## ⚙️ How FateboundCore Works

FateboundCore is a **meta-core**, not a replacement core.

### It LISTENS to:
- Player deaths & PvP kills
- Inventory actions
- AFK & activity
- Login / logout times
- Relic ownership

### It DOES NOT:
- Replace economy plugins
- Override land-claim plugins
- Replace teams or clans
- Modify vanilla mechanics directly

It reacts to gameplay and applies **fate consequences**.

---

## 🔌 Compatibility

Fully compatible with:
- Paper / Purpur 1.21.X
- GriefPrevention
- WorldGuard (region-respecting)
- Vault-based economy plugins
- Teams / Clans plugins
- Citizens NPCs
- DeluxeMenus
- Grim Anticheat

> FateboundCore does not hook into NMS or version-locked code.

---

## 🧬 Player Fate System

Each player is bound to **ONE fate** at a time.

### Fate Assignment
- Random on first join (configurable)
- Gained through relics or events
- Cannot be freely changed

### Changing Fate
- Requires rare ritual or admin action
- Designed to be difficult and meaningful

Fates are **identity-level**, not cosmetic.

---

## 🧿 Available Fates

### 🐉 Dragonbound
**(Dragon Egg Holder – World Relic)**

**How to Obtain**
- Kill the current Dragonbound
- Claim the Dragon Egg from the End

**Powers**
- +2 permanent max hearts
- Fire resistance near lava
- Bonus damage in the End
- Intimidation aura on nearby players

**Weaknesses**
- Server-wide visibility
- Constant PvP threat
- Cannot stay AFK
- Offline 3+ days = fate lost
- Death instantly transfers fate

---

### 🩸 Bloodbound
**(PvP Predator)**

**Powers**
- Lifesteal on player kills
- Strength boost at low health
- Faster regeneration after combat

**Weaknesses**
- Extra mob damage
- Golden apples disabled
- Death reduces max hearts

---

### 🌑 Voidmarked
**(High-Risk Explorer)**

**Powers**
- Immune to void damage
- Short-distance teleport
- Reduced fall damage

**Weaknesses**
- Weakness in daylight
- Mining fatigue above Y=64
- Drops extra loot on death

---

### 🔥 Ashen Soul
**(Nether-Aligned)**

**Powers**
- Fire immunity
- Increased Nether damage
- Faster netherite processing

**Weaknesses**
- Water damage
- Slowness during rain
- Weakness in Overworld nights

---

### 🌿 Earthbound
**(Builder / Survivor)**

**Powers**
- Bonus armor points
- Faster block breaking
- Increased crop yields

**Weaknesses**
- Reduced PvP damage
- Slower combat movement
- Elytra penalties

---

### ⚖️ Oathbroken
**(Punishment Fate)**

**How to Obtain**
- Team betrayal
- Combat logging
- Severe rule violations

**Powers**
- None

**Weaknesses**
- Increased damage taken
- Relics disabled
- Public fate mark

Removed only through redemption.

---

## 🐲 Fate Relics System

Fate Relics are **world-level artifacts**, not normal items.

### Core Rules
- Only one active holder
- Cannot be duplicated
- Cannot be destroyed
- Cannot be stored
- Transfers only through fate logic

---

## 🐉 Dragon Egg Relic (Full Rules)

### Inventory Binding
- Cannot be dropped
- Cannot be stored in any container
- Cannot be renamed
- Cannot be destroyed
- Cannot be transferred manually

### PvP Transfer
If the holder is killed by a player:
- Egg transfers instantly to the killer
- No ground drops
- Inventory-safe force insert
- Data synced instantly

---

## 💤 AFK & Offline Punishment

The Dragon Egg **rejects inactive holders**.

### AFK Rule
- Extended AFK → Egg abandons holder
- Movement + interaction based detection
- AFK machines do NOT work

### Offline Rule
- Offline for 3 days → Egg returns to the End
- Offline time persists across restarts

---

## 🌌 Return to the End

When abandoned:
- Egg teleports to the End
- Spawn locations:
  - End portal bedrock
  - Obsidian pillar
  - Configurable location

### Broadcast Message

---

## 📢 Global Notifications

Examples: 🐉 FATE SHIFTED
<Player> is now the Dragonbound.

---

## 🧑‍🎮 Player Commands

| Command | Description |
|------|------------|
| `/fate` | View your fate |
| `/fate powers` | View powers |
| `/fate weaknesses` | View weaknesses |
| `/fate relic` | View relic status |

---

## 🛠️ Admin Commands

| Command | Description |
|------|------------|
| `/fate assign <player> <fate>` | Assign a fate |
| `/fate egg reset` | Return egg to the End |
| `/fate reload` | Reload config |
| `/fate debug <player>` | View internal data |

---

## 🔐 Permissions

| Permission | Description |
|---------|------------|
| `fate.admin` | Full admin access |
| `fate.notify` | Receive fate notifications |
| `fate.bypass` | Bypass restrictions |

---

## ⚙️ Requirements

- Minecraft **1.21.X**
- Paper or Purpur
- Java **17**
- No additional dependencies required

---

## 🛡️ Anti-Exploit Protection

- Logout abuse prevention
- Inventory & hopper blocking
- Restart-safe data saving
- No duplication exploits
- Server-authoritative logic

---

## 🧩 Developer Notes

- Event-driven architecture
- No NMS usage
- YAML-based persistent storage
- Clean folder structure
- VS Code friendly
- API-ready for future addons

---

## 🗺️ Roadmap

- Additional Fate Relics
- Custom Fate API
- Seasonal fate resets
- MythicMobs integration
- Lore NPCs & rituals
- GUI-based fate menus

---

## 📜 License & Usage

FateboundCore is intended for:
- Survival SMPs
- PvP-focused servers
- Story-based worlds

Not designed for pay-to-win environments.

---

## 🧾 Final Words

> **Power is borrowed.  
> Fate is permanent.  
> The world remembers who held it.**

Welcome to **FateboundCore**.
