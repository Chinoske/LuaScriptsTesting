# LuaScriptsTesting

Lua scripts for WoW private servers using Eluna Engine.

## Scripts

- **WorldChat** - Global chat with faction icons & special roles
- **Pocket Portal** - Teleportation system with 140+ locations + GM Island
- **NPC Guardian** - Anti-cheat system with dramatic enforcement & GM tools
- **Scarlet Enclave** - Complete Death Knight starting zone experience
- **NPC AI System** - Intelligent NPCs with machine learning & personalized progression advice

## Features
- Database integration
- GM commands & cooldowns
- Anti-spam protection
- Real-time config
- Machine learning & AI
- Player progression analysis

## Installation
1. Copy to `lua_scripts/` folder
2. Run SQL files if needed  
3. Restart or `.reload eluna`
4. For NPC AI: `.npc init` after first load

Compatible with TrinityCore/AzerothCore 3.3.5a

---

## 🗡️ Scarlet Enclave - Death Knight Starting Zone

Complete Lua reimplementation of the Death Knight starting experience with full Spanish localization support.

### Features
- **All Death Knight quests** from Acherus to Light's Hope Chapel
- **Complete cinematics** - Eye of Acherus, Koltira Breakout, Light of Dawn
- **Advanced Combat AI** for all NPCs with proper spell rotations
- **Dynamic event system** with phase management and cleanup
- **Spanish localization** (esES/esMX) for complete immersion
- **Optimized performance** with proper memory management

---

## 🤖 NPC AI System - Intelligent NPC Interactions

Revolutionary AI system that transforms NPCs into intelligent companions that remember players and provide personalized advice.

### Features
- **5 Distinct Personalities** - Friendly, Grumpy, Wise, Mysterious, Scholar
- **Complete Player Memory** - Remembers everything about each player
- **Machine Learning** - Learns from interactions and improves over time
- **Smart Suggestions** - Recommends dungeons, zones, equipment upgrades
- **Progression Analysis** - Analyzes player trends and provides adaptive advice
- **Real-time Database** - 8 tables storing interaction data for learning

### Player Commands
```
.npc reputation        - View your reputation with NPCs
.progression all       - Complete progression analysis
.progression dungeons  - Dungeon recommendations
.progression equipment - Equipment analysis
.feedback [1-10]      - Rate NPC interactions
```

### GM Commands
```
.npc stats            - System statistics
.npc init             - Initialize database (first time only)
.npc reset [all]      - Reset player data
```

### Example Interaction
```
Player approaches NPC...

Friendly NPC: "¡Hola Juan! Por cierto... tienes 3 puntos de talento 
               sin asignar. Para tu nivel, Gnomeregan sería perfecta - 
               ideal para tu nivel y tiene armadura de malla perfecta 
               para tu clase."
```
