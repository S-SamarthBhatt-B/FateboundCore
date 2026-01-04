# 🔮 FateboundCore

> **A consequence-driven survival core where power is dangerous, fate is permanent, and the world tells its own story.**

FateboundCore is a meta-core Minecraft plugin designed to add **meaningful progression, permanent player fates, world relics, and real risk** to survival gameplay — without replacing economy, claims, or teams.

---

## 📌 Key Features

- 🔗 Permanent **Player Fates**
- ⚔️ Powerful abilities with real **weaknesses**
- 🐉 World-level **Fate Relics** (Dragon Egg)
- ☠️ PvP-driven power transfer
- 💤 AFK & inactivity punishment
- 📢 Server-wide fate notifications
- 🧠 Anti-exploit & anti-alt protections
- 🔌 Compatible with popular plugins

---

## 🎯 Design Philosophy

> **Power must be carried.  
> Fate must be faced.  
> Hiding has consequences.**

### Core Rules
- Every power has a weakness
- Stronger fate = higher risk
- AFK and inactivity are punished
- No pay-to-win advantages
- Gameplay creates stories naturally

FateboundCore **reacts to gameplay** instead of forcing it.

---

## ⚙️ How FateboundCore Works

FateboundCore is an **event-driven meta-core**.

### It LISTENS to:
- Player deaths
- PvP kills
- Inventory actions
- AFK & login time
- World changes
- Relic ownership

### It DOES NOT:
- Replace economy plugins
- Override land-claim plugins
- Replace teams or clans
- Break vanilla survival

It applies **fate logic on top of your server**.

---

## 🔌 Compatibility

Fully compatible with:
- GriefPrevention
- WorldGuard (with region respect)
- Vault-based economies
- Teams / Clans plugins
- NPCs (Citizens)
- Menus (DeluxeMenus)
- Anticheat (Grim)

---

## 🧬 Player Fate System

Every player is bound to **ONE fate**.

### Fate Assignment
- Random on first join (configurable)
- Earned through relics or events
- Cannot be freely changed

### Fate Change Requirements
- Rare ritual
- Heavy cost
- Optional admin approval

Fates are **identity-level**, not cosmetic.

---

## 🧿 List of All Fates

---

## 🐉 Dragonbound
**(World Relic Holder – Dragon Egg)**

### How to Obtain
- Kill the current Dragonbound
- Claim the Dragon Egg from the End

### Powers
- +2 permanent max hearts
- Fire resistance near lava
- Increased damage in the End
- Intimidation aura (nearby players briefly glow)

### Weaknesses
- Server-wide visibility
- Constant PvP threat
- Cannot stay AFK
- Offline 3+ days = fate lost
- Death instantly transfers fate

---

## 🩸 Bloodbound
**(PvP Predator)**

### Powers
- Lifesteal on player kills
- Strength boost below 5 hearts
- Faster regeneration after combat

### Weaknesses
- Extra mob damage
- Golden apples disabled
- Death reduces max hearts

---

## 🌑 Voidmarked
**(High-Risk Explorer)**

### Powers
- Immune to void damage
- Short-distance teleport ability
- Reduced fall damage

### Weaknesses
- Weakness in daylight
- Mining fatigue above Y=64
- Drops additional loot on death

---

## 🔥 Ashen Soul
**(Nether-Aligned)**

### Powers
- Fire immunity
- Bonus damage in the Nether
- Faster netherite processing

### Weaknesses
- Water damage
- Slowness during rain
- Weakness effect in Overworld nights

---

## 🌿 Earthbound
**(Builder / Survivor)**

### Powers
- Bonus armor points
- Faster block breaking
- Increased crop yields

### Weaknesses
- Reduced PvP damage
- Slower combat movement
- Elytra penalties

---

## ⚖️ Oathbroken
**(Punishment Fate)**

### How to Obtain
- Team betrayal
- Combat logging
- Severe rule violations

### Powers
- None

### Weaknesses
- Increased damage taken
- Relics disabled
- Public fate mark

Removed only through redemption.

---

## 🐲 Fate Relics System

Fate Relics are **world-level artifacts**, not normal items.

### Core Rules
- Only ONE active holder
- Cannot be duplicated
- Cannot be destroyed
- Transfers only through fate rules

---

## 🐉 Dragon Egg Relic – Full Rules

### Inventory Binding
- Cannot be dropped
- Cannot be stored
- Cannot be renamed
- Cannot be destroyed
- Cannot be transferred manually

### PvP Transfer
If the holder is killed by a player:
- Egg transfers instantly
- No item drop
- No delay
- Inventory force-insert if full

---

## 💤 AFK & Inactivity System

The Dragon Egg **rejects inactive holders**.

### Offline Rule
- Offline for 3 days → Egg returns to End

### AFK Rule
- Extended AFK → Egg abandons holder
- Movement + interaction based detection
- AFK machines do NOT work

---

## 🌌 Egg Return to the End

When abandoned:
- Egg teleports to the End
- Spawn options:
  - End portal bedrock
  - Random obsidian pillar
  - Custom coordinates

### Broadcast Message
