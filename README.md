# MiniCraft

A browser-based 2D Minecraft-inspired game. Mine blocks, build structures, survive the night, and craft items — all in a single HTML file.

## How to Play

### Controls

| Action | Keyboard | Mobile |
|--------|----------|--------|
| Move left / right | A / D or ← / → | ◀ ▶ buttons |
| Jump | W / Space / ↑ | ▲ button |
| Mine block | Hold left click | Hold ⛏ button |
| Place block | Right click | Hold 🧱 button |
| Select hotbar slot | 1–9 or scroll wheel | Tap slot |
| Next / prev slot | E / Q | — |
| Eat food | F or H | Right click food |
| Open inventory | I or ⋮ button | Tap ⋮ button |
| Close inventory | Escape or I | Tap ⋮ or press Escape |

### Inventory

- **Left-click** a slot to pick up the full stack
- **Right-click** a slot to pick up half, or place one item
- **Left-click** again to place / swap with another slot
- Works between the 27-slot inventory and the hotbar

### Crafting

Place a **Crafting Table** from your hotbar, then right-click it to open the crafting menu:

| Recipe | Cost |
|--------|------|
| 4× Planks | 1 Wood |
| 1× Crafting Table | 4 Planks |
| 1× Bed | 3 Planks |

### Survival

- **Hunger** (drumstick bar) drains over time — eat Apples or Raw Beef to restore it
- **Health** (heart bar) takes damage from falls, starvation, and mobs
- Sleep in a **Bed** to skip to morning and restore some health and hunger
- Hostile mobs spawn at night — Zombies, Skeletons, Creepers, and Endermen

### Mobs

| Mob | Behavior | Drop |
|-----|----------|------|
| Cow | Passive, wanders | Raw Beef |
| Pig | Passive, wanders | Raw Pork |
| Zombie | Chases player, melee | — |
| Skeleton | Ranged, shoots arrows | Bone |
| Creeper | Explodes near player | Gunpowder |
| Enderman | Chases player, high HP | Ender Pearl |

## Running the Game

Open `index.html` directly in a browser, or serve it over a local network to play on mobile:

```bash
cd Minicraft
python3 -m http.server 8080
```

Then open `http://<your-local-ip>:8080` on any device on the same Wi-Fi.

## Features

- Procedurally generated 2D world (220 × 80 tiles)
- Mining, placing, and crafting systems
- Inventory with click-to-move item management
- Day / night cycle with dynamic sky and star rendering
- Hunger and health systems
- Mob AI with unique behaviors per mob type
- Lumberjack mechanic — mine one log to fell the whole tree
- Full mobile touch support
- No dependencies — single HTML file
