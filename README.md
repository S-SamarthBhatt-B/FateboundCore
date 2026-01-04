# 🔮 FateboundCore

> A story-driven survival core plugin built on **permanent consequences, powerful fates, and world-level relics**.

FateboundCore transforms a normal survival server into a living world where **power has responsibility**, **death has meaning**, and **players create the story**.

---

## 📌 What is FateboundCore?

**FateboundCore** is a meta-core plugin that introduces:

- Permanent **Player Fates**
- Powerful but dangerous **Powers**
- Real, unavoidable **Weaknesses**
- World-level **Fate Relics** (e.g. Dragon Egg)
- Anti-AFK and anti-hiding mechanics
- Natural PvP without forced rules

It does **NOT** replace:
- Economy
- Claims
- Teams
- Vanilla survival

It **reacts to events** and applies fate logic.

---

## 🧠 Core Philosophy

> Power is temporary.  
> Fate is permanent.

### Design Rules
- Every power has a weakness
- Stronger fate = higher risk
- AFK and inactivity are punished
- No pay-to-win mechanics
- Server stories emerge naturally

---

## ⚙️ How FateboundCore Works

FateboundCore listens to:
- Player deaths
- PvP kills
- Inventory actions
- AFK & inactivity
- Relic ownership
- World transitions

It applies fate logic **without overriding other plugins**.

Compatible with:
- GriefPrevention
- Teams / Clans
- Vault-based economy
- NPCs, menus, crates, anticheat

---

## 🔗 Player Fate System

Each player is bound to **ONE fate at a time**.

### Fate Assignment
- Random on first join  
- Gained through relics or events  
- Cannot be easily changed  

Changing fate requires:
- Rare ritual
- High cost
- Or admin permission

---

## 🧬 List of All Fates

---

### 🐉 Dragonbound
*(Dragon Egg Holder)*

**How to Obtain**
- Kill the current Dragonbound
- Retrieve the Dragon Egg from the End

**Powers**
- +2 permanent max hearts
- Fire resistance near lava
- Bonus damage in the End
- Intimidation aura on nearby players

**Weaknesses**
- Always revealed server-wide
- Cannot stay AFK
- Offline 3+ days = fate lost
- Death instantly transfers fate

---

### 🩸 Bloodbound
*(PvP Predator)*

**Powers**
- Lifesteal on player kills
- Strength boost at low health
- Faster post-combat regeneration

**Weaknesses**
- Extra mob damage
- Cannot use golden apples
- Death reduces max hearts

---

### 🌑 Voidmarked
*(Risk Taker)*

**Powers**
- No void damage
- Short-distance teleport
- Reduced fall damage

**Weaknesses**
- Weak in daylight
- Mining fatigue above Y=64
- Drops extra loot on death

---

### 🔥 Ashen Soul
*(Nether-Aligned)*

**Powers**
- Fire immunity
- Increased Nether damage
- Faster netherite crafting

**Weaknesses**
- Takes damage in water
- Slowness during rain
- Weakness in Overworld nights

---

### 🌿 Earthbound
*(Builder / Survivor)*

**Powers**
- Extra armor points
- Faster block breaking
- Increased crop yields

**Weaknesses**
- Reduced PvP damage
- Slower combat movement
- Elytra penalties

---

### ⚖️ Oathbroken
*(Punishment Fate)*

**How to Obtain**
- Team betrayal
- Combat logging
- Severe rule violations

**Powers**
- None

**Weaknesses**
- Increased damage taken
- Cannot use relics
- Public mark in chat

Removed only via redemption.

---

## 🐲 Fate Relics System

Relics are **world-level artifacts**, not normal items.

### Available Relics
- Dragon Egg (active)
- Nether Star (planned)
- Beacon Heart (planned)
- Ancient Totem (planned)

Only **one player** can bind to a relic at a time.

---

## 🐉 Dragon Egg Relic (Full Rules)

### Binding Rules
- Cannot be dropped
- Cannot be stored
- Cannot be renamed
- Cannot be destroyed
- Cannot be transferred manually

### PvP Transfer
If the holder is killed by a player:
- Egg transfers instantly to killer
- No drops
- No delay
- Inventory force-insert if full

---

## 💤 AFK & Inactivity System

The Dragon Egg rejects inactive holders.

### Offline
- Offline for 3 days → Egg returns to End

### AFK
- AFK too long → Egg abandons holder
- Movement-based detection (AFK machines don’t work)

---

## 🌌 Return to the End

When abandoned:
- Egg teleports to the End
- Spawn locations:
  - End portal bedrock
  - Random obsidian pillar
  - Custom altar

Broadcast message:
