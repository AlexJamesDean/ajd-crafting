# [Buy AJD Crafting on Tebex](https://alexjamesdean.tebex.io/)

# AJD Crafting · Full-Suite QBCore Crafting Framework

AJD Crafting replaces every duct-taped crafting script with a cinematic, progression-driven experience. Modular benches, XP tiers, blueprint gating, and anti-dupe server logic turn every workshop, cartel lab, or mechanic bay into endgame content for your QBCore RP server.

> **TL;DR:** If you need a crafting system that handles legal jobs, black-market labs, and weapon assembly in one optimized resource, AJD Crafting is the answer.

![Visitors](https://komarev.com/ghpvc/?username=AlexJamesDean&repo=ajd-crafting&color=blue)
---

## Flagship Highlights

- **Multi-Bench Ecosystem** – Configure unlimited PolyZone or static benches (mechanic, weapon, weed, meth, coke, LSD, ecstasy, civilian, gang, etc.) with unique recipes, cooldowns, and visual styling.
- **XP + Mastery Progression** – Customizable XP curves per craft keep grinders busy for weeks; hook levels into perks, payouts, or unlocks.
- **Blueprint & Reputation Gates** – Gate recipes behind items, jobs, gangs, citizen IDs, or global events to pace your economy.
- **Vue-Powered UI** – A clean responsive interface with sortable categories, recipe detail modals, queue timers, and failure odds.
- **Server-First Validation** – Anti-spam cooldowns, webhook logging, and oxmysql/Discord audit trails protect your economy from dupes.
- **qb-target Native** – Plug-and-play target exports with built-in interaction distance, icon sets, and permission checks.
- **Craft Queue Logic** – Server-tracked queue with cancelation, reruns, and inventory re-checks to keep desync at zero.

---

## Feature Deep Dive

| Pillar | Details |
| --- | --- |
| **Economy Control** | Per-recipe failure rates, craft times, and ingredient costs let you tune scarcity for every item class. |
| **Dynamic Availability** | Toggle benches, recipes, or entire categories through config, command, or event for live RP events. |
| **Role-Aware Recipes** | Restrict crafts by job, grade, gang, citizen ID, item possession, or custom boolean checks. |
| **Progression Hooks** | Expose XP and stat exports to HUDs, leaderboards, battle passes, or Discord bots. |
| **Security Layer** | Inventory snapshots, webhook alerts, and server throttling stop macros, while cooldowns eliminate spam. |
| **Developer Tooling** | Built-in debug toggles, logging verbosity controls, and hot reload helpers accelerate iteration. |

---

## Built for Every Use Case

- **Mechanic shops** crafting upgrades, repair kits, tuning parts.
- **Illegal labs** for weed strains, coke bricks, meth batches, LSD tabs, ecstasy pills.
- **Weapon fabrication** of parts, attachments, ammo, and custom firearms.
- **Civilian crafting** of survival items, furniture, farming gear, or event props.
- **Gang hideouts** with gated blueprints, daily limits, and turf-specific recipes.

---

## Performance & Stability

- **0.01 ms average resmon** thanks to smart bench spawning and distance-based despawn.
- **Fully synced queue** to prevent item duplication even during city restarts.
- **OxMySQL backbone** ensures consistent saves and migrations across updates.

---

## Included With Purchase

1. Full source client/server code with detailed config comments (no escrow walls).
2. 1,000+ lines of plug-and-play config covering every bench, recipe, and XP tier.
3. Vue-based UI files (`ui/index.html`, `app.js`, `styles.css`, `vue.js`) ready for branding.
4. SQL schema + migration helpers for quick database onboarding.
5. Discord webhook templates for audit logging and staff alerts.
6. Lifetime updates for the current major version plus priority hotfixes.

---

## AJD Crafting vs. Generic Craft Scripts

- **Progression system** (XP, levels, unlocking) vs. flat check marks.
- **Multi-bench orchestration** vs. single table spam.
- **Target + PolyZone support** vs. line-of-sight text prompts.
- **Server-authoritative queues** vs. client timers prone to desync.
- **Integrated logging + anti-abuse** vs. blind trust in client events.

---

## Installation Flow

1. Purchase via the **Buy AJD Crafting on Tebex** button at the top.
2. Download instantly from your Tebex account email/dashboard.
3. Drop `ajd-crafting` into your resources folder and `ensure ajd-crafting` in `server.cfg`.
4. Import the provided SQL schema and adjust `config.lua` to match your economy.
5. Use the included debug commands to verify benches, XP, and logging.

---

## FAQ

**What frameworks are supported?**  
AJD Crafting is engineered for QBCore. Custom frameworks can integrate via exports; ESX is not supported.

**Does it support multiple inventories (qb-inventory, lj-inventory, qs-inventory)?**  
Yes—callbacks abstract inventory logic so you can map them to whichever QBCore-compatible inventory you run.

**Can I make custom minigames or timed skill checks?**  
Absolutely. Tie your minigame results into the craft success callback or failureChance modifiers for high-stakes recipes.

**How do I add new benches or recipes?**  
Everything lives in `config.lua`. Duplicate a bench block, set coordinates, model, color, and drop in recipes with level, ingredients, and timing.

**Will it break during oxmysql upgrades?**  
No. The resource ships with up-to-date oxmysql usage and is actively maintained as dependencies evolve.

---

## Need More Info?

- Want a guided demo? Reach out to AJTheDev on Discord after purchase.
- Need custom bench art, skill checks, or framework bridges? Enterprise support packages are available.
- Looking to bundle AJD Crafting with AJD Scavenge, AJD StreetSelling, and AJD Crafting? Ask about the full framework deals on the store page.

---

## SEO Keywords (meta)

FiveM crafting system, QBCore crafting script, AJD Crafting, qb-target crafting benches, weapon crafting FiveM, drug lab crafting, Vue crafting UI, oxmysql crafting resource, Tebex FiveM crafting, AJTheDev scripts

---

> ⚠️ This repository is intentionally code-free. It exists solely for SEO/indexing and to direct you to the official AJD Crafting release on Tebex. Purchase via the button at the top to access the full source.

I fix the bugs other devs gaslight you about.
AI tools, FiveM systems, automation pipelines.
Build it, break it, resurrect it: 👉 https://AJThe.Dev
