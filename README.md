# v0.0.1 Alpha - Early Preview
DawnAurora Player Animations Bedrock Add-On

## Project Overview
DawnAurora Player Animations is a player animation overhaul add-on for Minecraft Bedrock Edition.
This add-on redesigns nearly all native player animations. Every held item includes custom 3D visual models.
Core animation systems are fully functional and stable for regular gameplay.

> This build is marked as Alpha for conservative iteration.
> The main animation features are ready to test, while several extra animation features remain in active development.

## ✅ Completed Animations
All core player animations are finished and work correctly:
- Movement animations: walk, run, jump, fall, idle
- Combat animations: attack, block, hit reaction
- First-person hand animations
All items have custom 3D models.

## 🚧 Planned / In-Development Animations
These animations are still being developed and will be added in future alpha releases:
1. Sleeping animation
2. Stretch animation (after waking up)
3. Two-hand flourish animation

## 🐛 Known Issues
1. **Partial model clipping**
In certain animation poses, player bones may clip slightly through the player’s own body, armor or held items. This only appears under specific animation states and does not crash the game.

2. **First-person arm swing amplitude needs polishing**
The swing range of first-person hand animations is not fully refined. Some hand movements may look too subtle or stiff. Further adjustment of rotation values is required.

3. **Minor animation transition jitter in rare cases**
When switching quickly between certain states (for example: jump to land, run to stop), animation transitions may have tiny jitter or frame skip in rare scenarios. This does not affect the core gameplay.

> These are cosmetic-only issues. No critical game-breaking bugs exist in this alpha version.

## 📥 Installation Guide
1. Download the `.mcaddon` file attached below.
2. Open the `.mcaddon` file with Minecraft Bedrock Edition.
3. Create or open your target world.
4. In world settings, enable both the **Resource Pack (RP)** and **Behavior Pack (BP)**.
5. Enter your world to test the animations.

## 📝 Feedback & Bug Report
If you discover new bugs or have animation improvement ideas, please open an issue on this GitHub repository.
When submitting reports, please include:
- Your Minecraft Bedrock version
- Detailed steps to reproduce the bug
- Screenshots or video clips if available

## 📜 License
Apache License 2.0
Author: DawnAurora0221 (Zheng Ruiyang)
