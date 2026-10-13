# Sandrock Companion

The full suite for **My Time at Sandrock**: teleport to your quest objective or any point on the map, start or finish any quest, give yourself any item, then gold and currencies, stats and cheat modes, and every NPC relationship. A BepInEx plugin hosts the control panel; the desktop app sets it all up in one click.

> **Single-player only.** The multiplayer client's launch integrity check rejects the mod; don't install it there.

## What it does
- **Teleport**: one click to your current quest objective, to named locations (fast-travel points, ruins, the Moisture Farm and more), or to any point on the game's own map (dungeons, shops, NPCs, fishing spots), at real in-game coordinates.
- **Quests**: your active quests with Submit and Finish, and every named quest in the game, grouped Main Story / Side Quests in game order, with Start and Finish. Back up your save before forcing a quest.
- **Items**: the game's whole item list laid out as its crafting graph; give any item at any grade, 1, 10 or any number at a time.
- **Gold and currencies**: set or add to any of them.
- **Stats and cheat modes**: god mode, infinite stamina, infinite endurance, freeze time of day, a move-speed multiplier; set HP, stamina and endurance directly.
- **Relationships**: every NPC, grouped Townsfolk / Animals & Pets / Story & Minor, with a 💞 filter for romanceable residents, sorted A–Z or by relationship; +25, +100 or any amount, or max them all.
- The item, place, quest and NPC lists load instantly from bundled data, even before the game is running; live values come from the running game.

## Install
**Easy (recommended):** download **`Sandrock-Companion-1.2.0-setup.exe`** from the [latest release](../../releases/latest), run it, and on the **Setup** tab click **Install / Update**. It finds the game and installs BepInEx and the plugin. Then launch My Time at Sandrock in single-player; the app connects on its own.

**Manual:** download `sandrock-companion-v1.2.0.zip` from the [latest release](../../releases/latest), install **BepInEx 5.4.x (x64)** ([for My Time at Sandrock](https://www.nexusmods.com/mytimeatsandrock/mods/129)), extract the `SandrockTrainer` folder into `<game>\BepInEx\plugins\`, launch single-player, and open **http://localhost:17600** in any browser.

**Updating from 1.1.0 or earlier:** the plugin folder keeps its name, so Install / Update (or the zip) replaces the plugin in place. The desktop app installs under its new name, so Windows may still list the old app under Settings → Apps; uninstall it there.

Also on Nexus Mods: [Sandrock Companion](https://www.nexusmods.com/mytimeatsandrock/mods/173).

## Compatibility
Built against Steam build **18623106**. A game update may require a rebuilt plugin.

## License / credits
Original mod code; uses the game's API through BepInEx. Not affiliated with Pathea Games.
