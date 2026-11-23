# Reshade-PS4

> ReShade post-processing effects for PS4 — powered by GoldHEN plugins.

**Original author:** toweliee (with assistance from Claude)
**Revised & published by:** MordecaiOG

---
---

## What's New in 1.5

### Unreal Engine 4 Hooks

###  New effects
| Effect |
|--------|
| **Anti-aliasing (DLAA)** |
| **AgX tonemap** |
| **Adaptive sharpen (CAS)** |
| **Deband** | Light & Lens |
| **Auto exposure** |
| **LUT (.cube)** |

**Using LUTs:** drop a `.cube` file (16/32/64 sized) at `/data/GoldHEN/postfx/luts/lut.cube`
and raise the **LUT** slider on the Colour page. A cinematic starter LUT is included in the release.

---
## ✅ Tested Firmware

| TESTED Firmware |
|----------|
| 12.00 |
| 13.02 |
| 14.00 |
| 14.02 |

---

## 🎮 Known Working Titles

| Title ID | Game |
|----------|------|
| CUSA15633 | CarX |
| CUSA01830 | Assetto Corsa |
| CUSA20488 | Ride 4 |
| CUSA12398 | The Forest |
| CUSA00419 | GTA V |
| CUSA08519 | Red Dead Redemption 2 |
| CUSA00265 | Minecraft |
| CUSA16596 | Cyberpunk 2077 |
| CUSA04294 | Watch Dogs 2 |
| CUSA09958 | MudRunner |
| CUSA17425 | SnowRunner |
| CUSA07668 | Insurgency: Sandstorm |
| CUSA06877 | MX vs ATV All Out |

---

## 📦 Installation

1. Download **GoldHEN.zip** from the [latest release](https://github.com/MordecaiOG/Reshade-Ps4/releases/tag/reshade_ps4).

2. Copy files to your PS4:

   | File | Destination |
   |------|-------------|
   | `postfx.prx` | `/data/GoldHEN/Plugins/` |
   | `postfx_icon.png` | `/data/GoldHEN/` |

3. Add your Title ID(s) to `/data/GoldHEN/Plugins.ini`:

   ```ini
   [CUSA00419]
   /data/GoldHEN/plugins/postfx.prx

   [CUSA00265]
   /data/GoldHEN/plugins/postfx.prx
   ```

---

## 🎛️ Controls

| Input | Action |
|-------|--------|
| R3 + D-pad Down | Open Menu |
| R1 / L1 | Change Pages |

On first load, you'll receive an in-game notification confirming the plugin is active.

---

## 💾 Presets

Your saved presets are stored at:

```
/data/GoldHEN/PostFx/
```

Presets are portable — share them with friends or the community freely.

---

## ⚠️ Notice

If you use **third-party multiplayer plugins**, make sure `postfx.prx` is listed **after** them in your `Plugins.ini`.


---

## 📸 Screenshots

![Screenshot 1](image.png)
![Screenshot 2](image2.png)
![Screenshot 3](image3.png)
![Screenshot 4](image4.png)
![Screenshot 5](image5.png)
![Screenshot 6](image6.png)
