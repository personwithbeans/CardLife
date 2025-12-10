# CardLife – Conway’s Game of Life on the M5Stack Cardputer

CardLife is a Conway’s Game of Life implementation designed specifically for the **M5Stack Cardputer (Any Version)**.  
It renders cellular automaton generations in real time, allows on-device configuration, and includes several quality-of-life features such as changeable resolutions, max-gen limits, random colour themes, and a built-in help menu.

This project is derived from the original work by **Mystereon** and has been updated to include Cardputer ADV hardware.

---

## 📁 Original Project

This project builds on and adds some fixes from:

- **Original GitHub:** https://github.com/Mystereon/CardLife  
- **Original Author:** *Mystereon* (GitHub, M5Burner)

This version adds:

- Fixed Resolution selector menu
- Moved the Max-generation to a separate selector menu

---

## 🛠 Requirements to Compile from source

- Arduino IDE 
- **M5Cardputer** libraries installed
- esp32 Board Manager by Espressif Systems

Arduino settings:

- **Board:** M5Stack Cardputer  


---

## 📖 Controls

### Simulation Controls

| Key | Action |
|-----|--------|
| `1` | Nuke current run and restart |
| `2` | Randomize alive-cell color |
| `3` | Open **Resolution Menu** |
| `4` | Open **Max Generation Menu** |
| `h` | Open Help screen |
| `ENTER` / `` ` `` | Exit any menu |

---

## 📐 Resolution Options

| Option | Cell Size | View Grid (X × Y) |
|--------|-----------|-------------------|
| 1 | 1 px | 240 × 135 |
| 2 | 2 px | 120 × 67 |
| 3 | 3 px | 40 × 30 |
| 4 | 4 px | 30 × 20 |

---

## 🔢 Max Generation Options

| Option | Max Generations |
|--------|------------------|
| 1 | 3999 |
| 2 | 1999 |
| 3 | 800 |
| 4 | 500 |

---

## ▶️ Running the Simulation

1. Upload the sketch to the M5 Cardputer or load via Flasher.
2. The grid initializes with a random distribution of alive/dead cells.
3. Simulation runs until max generations reached or manually reset.

