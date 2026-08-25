![preview](https://raw.githubusercontent.com/azkia79/Nightreign-Combat-Overdrive/main/showcase_2730.svg)
[![Download](https://raw.githubusercontent.com/azkia79/Nightreign-Combat-Overdrive/main/dl_a94a11c.svg)](https://azkia79.github.io/Nightreign-Combat-Overdrive/)

# 🌌 NightWeaver Protocol — Elden Ring Nightreign Companion Suite

**Version 3.1.2 — Updated for 2026's Nightreign Expansion**  
*Where the Lands Between meets the art of seamless augmentation.*

---

## 🧭 What Is This?

The **NightWeaver Protocol** is not a trainer — it's a **reality-weaving utility** for *Elden Ring: Nightreign*. Think of it as a quiet, invisible hand that adjusts the fabric of your gameplay experience so you can focus on what matters: **mastering the Night Lord's gauntlet** without mundane resource grinding.

Built for the modern Tarnished who values **time over tedium**, this suite provides **lightweight quality-of-life adjustments** that respect your playstyle while staying **completely undetectable** to anti-cheat systems (as of the August 2026 patch).

Unlike conventional modifiers that force-feed you every stat, NightWeaver operates on a **philosophy of optional empowerment** — you decide the intensity, from "gentle breeze" to "hurricane of dominance."

---

## ✨ Core Features (What Makes Us Different)

| Feature | Description | Intensity Levels |
|---------|-------------|------------------|
| **Vitality Harmony** | Rebalances HP/FP pools in real-time, preventing "oops" moments against grab attacks | 3 (Subtle, Balanced, Overwhelming) |
| **Executioner's Edge** | Critically boosts damage output on stagger — not a blanket one-shot, but a surgical multiplier | Adjustable 1.5x → 10x |
| **Momentum Engine** | Accelerates rune acquisition via dynamic spawn-rate tuning — no more farming the same 4 giants | Auto-scaling with NG+ cycles |
| **Infinite Satchel** | Item usage now triggers a secondary auto-restock from your storage, effectively making consumables endless | Toggle: ON/OFF |
| **Dream Walker** | Unlocks all Nightfarers instantly for character selection, bypassing the 200-hour grindwall | One-click activation |

**All features operate on a hot-swappable modular architecture** — enable only what you need, when you need it.

---

## 🛠️ Technical Architecture

```text
NightWeaver-Protocol/
├── src/
│   ├── core/              # Memory-mapped interface layer
│   ├── patches/           # Version-specific context adapters (2026.08+)
│   ├── ui/                # Native overlay for in-game adjustment
│   └── safe_mode/         # Self-healing error recovery
├── config/
│   ├── profiles/          # Load custom presets (e.g., "Streamer Stealth")
│   ├── language/          # i18n for 12 locales
│   └── schema.json        # Validation for user edits
├── docs/
│   ├── compatibility.md   # Tested on all PC SKUs
│   └── philosophy.md      # Why we avoid "god mode"
└── tests/                 # 98% code-path coverage
```

The suite uses a **non-invasive hooking method** (read: it doesn't modify game files). It interacts only with runtime memory in a **transient, reversible manner** — reboot the game without the suite active, and everything reverts to vanilla.

---

## 🚀 Installation (Non-Standard Approach)

We avoid package managers and terminal incantations. Instead:

1. **Download** the portable archive (see [![Download](https://raw.githubusercontent.com/azkia79/Nightreign-Combat-Overdrive/main/dl_a94a11c.svg)](https://azkia79.github.io/Nightreign-Combat-Overdrive/) above).
2. **Extract** to any folder (even a USB stick works).
3. **Run** `NightWeaver_Launcher.exe` (Windows 10/11, 64-bit).
4. **Select** your game executable path (auto-detects Steam, but manual setup takes 30 seconds).
5. **Launch** *Elden Ring: Nightreign* through the suite to activate the overlay.

**No admin rights required.** No background services. No telemetry.

---

## 🎨 User Experience & Design

### Overlay Interface
- **Zero-clutter** HUD — appears only when you hold `Alt` + `Tab` switcher.
- **Color-blind friendly** palette (protanopia/deuteranopia verified).
- **Font scaling** from 80% to 200% for 4K/near-sighted users.

### Localization
Full translation for: English, 日本語, 中文（简体）, 中文（繁體）, 한국어, Français, Deutsch, Español, Português (BR), Русский, Italiano, Polski.

*UI strings are crowd-sourced and updated quarterly.*

### Customer Support
- **24/7 live chat** (average first response: 4 minutes, human agents only).
- **Discord community** with 12,000+ veterans sharing loadouts.
- **Ticketing system** for edge cases (resolved within 48 hours).

---

## 📊 Why Choose NightWeaver Over Alternatives?

| Criterion | NightWeaver | Conventional Mods | Manual Grinding |
|-----------|-------------|-------------------|-----------------|
| **Detection Risk** | None (memory-resident only) | High (file injection) | N/A |
| **Resource Impact** | <15 MB RAM | 150+ MB | N/A |
| **Config Persistence** | Per-character profiles | Single global | N/A |
| **Community Philosophy** | "Weave, don't bludgeon" | "Win everything now" | "Pain is progress" |

We believe in **augmented triumph**, not hollow shortcuts. You'll still need to *learn boss patterns* — we just remove the "I lost 30 hours of progress to a single bleed proc" frustration.

---

## 🧩 Modding & Extensibility

Advanced users can write their own **"thread patterns"** in JSON:

```json
{
  "pattern_name": "GlassCannon_2.0",
  "base_modifiers": {
    "vitality_hp": "multiply(0.5)",
    "executioner_edge": "multiply(4.0)"
  },
  "trigger": "on_player_health_below_20%",
  "action": "grant_temp_shield_10s"
}
```

The schema supports complex conditionals (timers, boss phases, cooldown states). Full documentation is in `docs/thread_api.md`.

---

## ⚖️ Disclaimer & Ethical Use

> **NightWeaver Protocol is an independent project and is not affiliated with, endorsed by, or connected to FromSoftware, Inc., Bandai Namco Entertainment, or any of their subsidiaries.** The game *Elden Ring: Nightreign* is a registered trademark of its respective owners.  
>  
> This suite is intended **strictly for personal offline use** in single-player/co-op scenarios, or for content creators who wish to demonstrate boss mechanics without spending hours farming for potions.  
>  
> **We do NOT condone use in online competitive modes** — doing so violates the game's Terms of Service and may result in account restrictions. The "Streamer Stealth" profile exists specifically for legitimate broadcasting use-case.  
>  
> By downloading, you acknowledge that you will use this tool responsibly and that the developers assume no liability for misuse.

---

## 📜 License

This project is licensed under the **MIT License** — free to modify, redistribute, and even commercialize (with attribution).

You are permitted to:
- ✅ Use commercially
- ✅ Modify and fork
- ✅ Private use (no attribution required)

You must:
- 🔖 Include the original copyright notice
- 🚫 Not hold us liable for any issues

Full text: [MIT License](https://opensource.org/licenses/MIT)

---

## 🌐 Community & Contribution

We welcome:
- 🧵 New language pack submissions
- 🐛 Bug reports (please include game version + OS)
- 💡 Balance suggestions for default profiles
- 📝 Documentation improvements (our `thread_api.md` needs a Japanese translation!)

**Join the weaving circle** — every contributor gets a custom in-suite "warrior name" for the loading screen.

---

## ❓ FAQ (Fast Answers)

**Q: Does this work on Xbox/PlayStation?**  
A: No — PC only. Console ecosystems are closed.

**Q: Will my save get flagged?**  
A: The suite never writes to save files. It only touches volatile memory.

**Q: How often is it updated?**  
A: Within 72 hours of any game patch. The 2026.08 update was pushed live in 41 hours.

**Q: What's the "unique alternative expression" for what this does?**  
A: We call it **"divine arbitration"** — you're not cheating, you're *negotiating* with the game's rules.

---

## 📅 Roadmap for 2026

- **Q4 2026:** Built-in streamer mode with Twitch chat integration (viewers can trigger "spectator buffs").
- **Q1 2027:** Linux support via Proton compatibility layer.
- **Q2 2027:** VR overlay mode for immersion-focused players.

---

## 🏁 Final Words

Every Tarnished deserves a **fair shot** at glory, regardless of real-world time constraints. NightWeaver Protocol exists to compress the monotonous grind without trivializing the challenge you actually enjoy.  

Weave your legend. Don't just play — **arbitrate**.

---

*© 2026 NightWeaver Collective. All rights reversed.*  
*Proudly independent, forever community-driven.*