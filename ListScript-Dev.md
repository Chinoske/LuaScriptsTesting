# LuaScriptsTesting

Lua scripts for WoW private servers using Eluna Engine.

## Scripts

- **WorldChat** - Global chat with faction icons & special roles
- **Pocket Portal** - Teleportation system with 140+ locations + GM Island
- **NPC Guardian** - Anti-cheat system with dramatic enforcement & GM tools
- **Scarlet Enclave** - Complete Death Knight starting zone experience
- **NPC AI System** - Intelligent NPCs with machine learning & personalized progression advice
- **Killing Streak System** - Advanced PvP tracking with achievements, sounds & leaderboards

## Features

### Killing Streak System Highlights:
- 🎖️ **15+ Milestones**: From First Blood to Beyond Godlike (30+ kills)
- 🔊 **Custom Sound Pack**: Unique audio feedback for each achievement
- 📊 **Interactive NPC**: Combat Master with personal stats and server rankings
- 🏆 **Dynamic Leaderboards**: Top 10 by current streak, best streak, and total kills
- ⚙️ **WorldConfig Integration**: Fully configurable via worldserver.conf
- 📈 **Player Analytics**: Streak history, multi-kill tracking, and zone bonuses

### Core Features:
- Database integration (SQL stats/logging)
- GM commands & testing tools
- Real-time configuration reloading
- Zone/level restrictions
- Anti-farm protections
- Multi-language support

## Installation

1. Copy to `lua_scripts/` folder
2. Import SQL files:
   - `killingstreak_npc_system.sql` (NPC and database structure)
   - `sounds_entries.sql` (custom sound pack)
3. Add MPQ with sounds to client `Data/` folder
4. Restart server or `.reload eluna`
5. For NPC: Automatically spawns in capital cities

**Configuration:**  
Edit `worldserver.conf`:
```ini
[KillingStreak]
Enable = 1
Sounds.Enable = 1
Announcements.Screen = 1
Announcements.Chat = 1
FirstBlood.Global = 1
