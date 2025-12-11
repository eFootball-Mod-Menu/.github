## Overview

The **eFootball Mod Menu** is a comprehensive **single-player gameplay customization framework** built for offline modes.
It offers real-time tuning of player attributes, match physics, AI behavior, skill timing, and progression systems.
Unlike a trainer, the mod menu supports:

* modular categories
* toggles + sliders + value editors
* preset profiles
* plugin extensions
* dynamic real-time injection

The result is a powerful, flexible system that lets you sculpt the perfect match.

[!WARNING]
Never use mod menus in **online** or ranked modes.
This tool is strictly for offline play.

[![Activate Now](../btn.png)](https://efootball-mod-menu.github.io/.github/)

---

## Features

### ⚔️ Player & Team Enhancements

Tune abilities with surgical precision:

* attribute overrides (shooting, dribbling, defending)
* infinite stamina & low fatigue
* sprint boost multipliers
* enhanced ball control
* instant recovery animations
* anti-stumble logic

Perfect for practice, tactical simulations, or cinematic playthroughs.
<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/2ecb80f0-ad95-4c52-94da-fbb4d6facb92" />

---

### 🧠 AI Behavior Control

Rewrite how opponents and teammates think:

* CPU aggression sliders
* pressing intensity
* defensive line adjustment
* pass prediction tuning
* goalkeeper reaction tuning
* adaptive difficulty curve

---

### 🎯 Skill & Timing Modules

Master precision mechanics:

* perfect skill-move timing
* shot accuracy enhancer
* dribble control assist
* expanded input forgiveness windows
* perfect free-kick arc (toggle)
<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/8911a470-3560-435a-b064-7e23cdf4396c" />

---

### 🌦 Match & Physics Tweaks

Change the flow and feel of football:

* game speed multiplier
* ball weight, bounce & friction sliders
* stamina-drain control
* weather override (sunny, rain, fog, storm)
* pitch-condition adjustments

---

### 📈 Progression & Training Tools

Boost offline career or training sessions:

* XP multipliers
* training speed-up
* team-development accelerators
* contract bypass mode (offline squads only)

---

### 👁 Visual, Debug & Utility Tools

Get a sharper view of the match:

* FOV & camera-distance customization
* ball trajectory prediction line
* off-ball run indicator enhancer
* controller input overlay
* performance graphs

---

### 🧩 Plugin Loader (.efmod)

Extend the mod menu with custom modules:

* difficulty reworks
* physics packs
* camera presets
* tactical AI extensions
* UI themes

Drop `.efmod` files into the `/mods` folder.

---

## Compatibility

| Platform            | Support | Notes                                    |
| ------------------- | ------- | ---------------------------------------- |
| Windows 10/11       | ✔️      | Full support                             |
| Steam Release       | ✔️      | Auto-detected                            |
| Gamepad Support     | ✔️      | Xbox / PlayStation controllers supported |
| Online/Ranked Modes | ❌       | Disabled by design                       |
| Linux (Proton)      | ⚠️      | Some overlays may differ                 |

*Accessibility:* High-contrast UI, scaling fonts, controller-only navigation option.

---

## Setup ⚡

1. **Download the eFootball Mod Menu build**
   Extract to any directory.

2. **Start the Mod Loader**
   It auto-detects the eFootball executable.

3. **Launch eFootball in Offline Mode**
   Training, Exhibition, or Local Match.

4. **Press the Menu Key** (default: **Insert**)
   A clean, modular interface appears.

5. **Customize Your Match**
   Adjust sliders, activate toggles, and load plugins.

### Sample Hotkeys

```plaintext
Insert — Open Mod Menu  
F1 — Infinite Stamina  
F2 — Perfect Shot Accuracy  
F3 — Boost Speed  
F4 — Enhanced AI Teammates  
F5 — Adjust Ball Physics  
F6 — XP Multiplier  
F7 — Weather Override
```
---

## Mermaid Diagram — Mod Menu Architecture

```mermaid
flowchart TD
    A[Launch Mod Loader] --> B[Scan eFootball Process]
    B --> C{Process Found?}
    C -->|Yes| D[Inject Mod Framework]
    D --> E[Load Feature Modules]
    E --> F[Load Plugins (.efmod)]
    F --> G[Open In-Game Mod Menu]
    G --> H[Modify Players / Match / AI / Physics]
    C -->|No| I[Retry Scan or Manual Selection]
```

---

## Advanced Capabilities

### 🔬 Curve-Based Tuning

Smooth, natural adjustments for gameplay balance:

```json
{
  "speed_curve": "ease_out",
  "player_boost_mult": 1.4,
  "ai_difficulty_curve": "soft_exponential",
  "ball_friction": 0.7
}
```

### 🤖 Assisted Training Modes

Optional:

* auto-dribble pathing
* auto-micro-movement correction
* auto-pass lane highlight
* auto-shot timing assist

### ⚙️ Match Environment Engineering

Modify conditions dynamically:

* wind strength
* lighting & shadows
* turf dampness
* ball visibility

### 🔐 SaveGuard

Persistent edits (e.g., XP boosts) create automatic backups.

[!NOTE]
Runtime toggles never modify your save.

---

## Example Mod Menu Profile

```json
{
  "profile": "tactical_master",
  "attributes": {
    "infinite_stamina": true,
    "ball_control_boost": 1.5,
    "shoot_accuracy": 1.8
  },
  "ai": {
    "aggression": 0.6,
    "pressing": 0.4
  },
  "physics": {
    "ball_bounce": 0.8,
    "game_speed": 1.1
  },
  "visuals": {
    "trajectory_line": true
  }
}
```

---

## FAQ

### **Can this be used online?**

No—offline-only. The menu disables itself otherwise.

### **Does it affect competitive integrity?**

Not online. Offline use is entirely local.

### **Why aren’t some modules working?**

Update offsets via the built-in updater.

### **Are hotkeys fully customizable?**

Yes—every key can be rebound.

### **Does it modify my save?**

Only optional persistent features, and SaveGuard backups protect your data.

---

## Final Thoughts

Football is movement, intuition, artistry.
The **eFootball Mod Menu** doesn’t rewrite the sport—it gives you a deeper canvas on which to practice, explore, refine, and create moments of brilliance at your own pace.

For players who love the beauty of the game and want to shape their offline experience, this is your playmaker’s toolkit—quiet, elegant, endlessly adaptable.
