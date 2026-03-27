# Lucky Lino — Far West Runner

A 2D side-scrolling runner game built with **raylib** in C++.

**Author:** WABERI FARAH WABERI | **Class:** L2 Engineering — 2025/2026

---

## Gameplay

Dodge incoming axes (Laevas) and collect watermelons to boost your score. The game speeds up over time. A shield power-up activates every 30 points to protect you from one hit.

## Controls

| Key | Action |
|-----|--------|
| `ENTER` | Start game |
| `SPACE` / `W` | Jump |
| `S` | Duck |
| `Q` | Music off |
| `E` | Music on |

---

## Compilation

Requires [raylib](https://www.raylib.com) installed on your system.

**Linux/macOS**
```bash
g++ main.cpp -o glino -lraylib -lm
```

**Windows (MinGW)**
```bash
g++ main.cpp -o glino.exe -lraylib -lopengl32 -lgdi32 -lwinmm
```

---

## File Structure

```
Glino/
├── main.cpp
├── highscore.txt          # Auto-generated on first run
├── Sounds/
│   ├── jump.wav
│   ├── pickupCoin.wav
│   ├── gameover.wav
│   └── Pixel Kings.wav
└── textures/
    ├── Back.png
    ├── montain.png
    ├── birds.png
    ├── treesBack.png
    ├── treesFront.png
    ├── dino.png
    ├── Laeva.png
    └── Yellow Watermelon2.png
```

> ⚠️ The `Sounds/` and `textures/` folders must be in the same directory as the executable.
