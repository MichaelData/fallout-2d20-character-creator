# ☢️ FALLOUT 2d20 MANAGER: ULTIMATE EDITION

```text
> SYSTEM BOOT...
> CHECKING BIOS... OK
> LOADING HOLOTAPE: "CHARACTER_MANAGER_V4.1"
> USER DETECTED: THE ARCHIVIST
> ACCESS: GRANTED

> MESSAGE:
"Greetings, Wastelander. You hold in your hands a relic of the Old World, 
repurposed for the harsh realities of the New. Whether you are a Vault Dweller 
stepping into the light for the first time, or a scarred NCR Ranger, 
this tool will document your journey.

Don't lose your head out there. And if you do... well, at least your 
inventory will be well-organized."
```

## 📝 Overview
This is a standalone, offline **HTML5 Character Creator & Manager** for the *Fallout: The Roleplaying Game* (2d20 System). It is designed to run in any modern web browser (Chrome, Firefox, Edge) without an internet connection.

It handles everything from **Character Creation** (Origins, S.P.E.C.I.A.L., Skills) to **Active Play** (Health, Radiation, Ammo tracking, Inventory).

## ✨ Features

### 1. Character Builder
*   **Full Origin Database:** Includes all major Origins (Survivor, Brotherhood, Super Mutant, Ghoul, Synth, Mister Handy, etc.) with automatic stat adjustments (e.g., Super Mutants get STR/END limits set to 12).
*   **Trait Logic:** Automatically populates the correct Traits based on your Origin (NCR, Tribal, Survivor lists).
*   **Perk Selection:** 198 perks taken straight from the Core Rulebook, Settler's Guide and Wanderer's Guide (printed page numbers shown). Multi-rank perks can be taken again for the next rank, and the level requirement rises per rank exactly as the books say (e.g. Life Giver: level 5, then 10, then 15). The dropdown marks each perk: ✖ requirements not met, ✔ MAX rank reached, ★ rare perk found in play. If you pick a perk you don't qualify for, the app warns you and lets you override it (for GM-approved exceptions).
*   **Starting Equipment:** Each origin lists its real equipment packs from the books (expand one and press "Use this pack"). "Add items from my Tag skills" adds the Core p.81 tag skill items.
*   **Skill Caps:** No skill above rank 3 before level 3, and Super Mutants and Nightkin are capped at rank 4.
*   **Skill Tagging:** Checking a "Tag" box automatically calculates your +2 Skill Rank bonus.

### 2. The Weapon Fabricator
*   **Database:** Pre-loaded with **144 weapons** taken from the weapon tables in the Core Rulebook, Settler's Guide, Wanderer's Guide and Winter of Atom, grouped by skill, with damage, effects, range, qualities and rarity exactly as printed.
*   **Customization:** Select a preset (e.g., "10mm Pistol") and modify it, or create a completely custom "Homebrew" weapon from scratch.
*   **Ammo Tracking:** Track Mag capacity vs. Ammo Pool directly on the sheet.

### 3. Manager Mode (Active Play)
*   **Health & Resistances:** Calculates Max HP, Defense, and Carry Weight based on your stats.
*   **Inventory:** Text area for general gear, caps, and armor.
*   **XP & Leveling:** Track XP and force level-ups.

### 4. Holotape Save System
*   **Save Data:** Exports your character as a `.json` file to backup your progress.
*   **Save Text:** Exports a readable `.txt` summary of your sheet.
*   **Terminal Animation:** Features a retro RobCo terminal boot-up sequence when saving.
*   **Load:** Restore your character instantly by uploading your `.json` backup.

### 5. Visual Themes
*   **Pip-Boy Mode:** High contrast Green-on-Black CRT aesthetic.
*   **Paper Mode:** Printer-friendly layout for physical sessions.

## 🚀 How to Install
1.  Download the `.html` file.
2.  **That's it.** There is no installation.
3.  Double-click the file to open it in your web browser.

## Armor, weapon mods and magazines
*   **Armor:** 170 armor, clothing, outfit and power armor pieces plus 35 robot plating parts, taken from the book tables. Single arm or leg pieces ask which side. The sheet shows Physical, Energy and Radiation DR for each of the six body locations (worn armor, mods, plus perk and origin bonuses).
*   **Armor mods:** 141 mods, added to a chosen piece; their DR changes count toward that piece. Perk requirements (for example Armorer) are checked against your perks and can be overridden.
*   **Weapon mods:** 257 mods from the Core Rulebook and the other books, attached to a weapon from your list. Their effects are shown on the sheet; damage is not changed automatically. The mod list is filtered to the mods the books allow for that weapon (about 85 weapons have a list read from the books); tick "Show every mod" to override. A second mod in the same slot asks for confirmation.
*   **Books and magazines:** all 20 publications from Core p.172-179 plus the four issues on the Winter of Atom loot table. Reading one gives you a temporary perk on the sheet. Press Use when you spend it; at your next level up the app asks whether to learn it permanently or forget it (Core p.172).

## Perk filter and override

Both perk lists (character builder and the sheet screen) have two checkboxes. "Only show perks I can take now" hides every perk you do not qualify for (SPECIAL, level, rank and robot rules). "Override: allow any perk" shows all perks and lets you add one you do not qualify for, after telling you exactly what is missing. With override off, an unqualified perk is refused and the missing requirements are listed.

## 🕹️ Controls
*   **Hover:** Hover over perks to see requirements and descriptions.
*   **Click:** Click "Tag" boxes to add tag skills.
*   **Toggle:** Use the "Toggle View" button to switch between Pip-Boy and Paper themes.
*   **Print:** Click "Save as PDF / Print" to generate a clean sheet for physical play (automatically hides the buttons and builder tools).

## ⚠️ Notes from The Archivist
*   **Super Mutants:** Remember, your Strength and Endurance bases are higher. The system handles this, but remember you cannot lower them below your racial minimum.
*   **Browser Storage:** This tool runs locally. If you close the browser without clicking "Export Save Data," your progress is lost to the radiation. **SAVE OFTEN.**

---

```text
> END OF ENTRY.
> ROBCO INDUSTRIES (TM) TERM-LINK PROTOCOL
> LOGGING OFF...
```

*Disclaimer: This is a fan-made tool. Fallout is a trademark of Bethesda Softworks LLC. This tool is not affiliated with Modiphius Entertainment or Bethesda.*

If you wish to donate you can use this link https://donate.stripe.com/9B64gz5Ee87tdBz5tO1Fe07
