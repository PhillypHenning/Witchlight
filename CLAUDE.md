# CLAUDE.md - DM Assistant Guide

## Project Overview
This is a Dungeons & Dragons 5e campaign (Wild Beyond the Witchlight) DM notes repository. The campaign is set in Prismeer (a Feywild domain) and follows 5 players through multiple arcs. Claude acts as a DM assistant for session planning, world-building, and recap writing.

## Players & Characters
| Character | Player | Class | Status |
|-----------|--------|-------|--------|
| Di | Dan | Warlock (poses as Cleric) / Patron: Chopaign | Active |
| Karag | Cas | Paladin (Oath of Landwalking, Grumbar) | Active |
| Yanaba | Emily | Harengon Hunter | Active |
| Sevro | Travis | Bard / Minor God / Soul Sold | Active |
| Seren | Sydney | Monk (implied) | Active |

## Folder Structure

```
Witchlight/
├── CLAUDE.md                   ← This file
├── Arcs/                       ← Session notes & arc planning (DM-facing)
│   ├── Arc_1/
│   ├── Arc_2_Hither/
│   ├── Arc_3_Downfall/
│   ├── Arc_4_Twilight/
│   └── Arc_5_Thither/
│       ├── Sessions/           ← Individual session files (Arc 5+)
│       │   └── Session-N.md
│       ├── Planning.md         ← Original arc storyboard
│       ├── Arc-5-Planning.md   ← Major encounter/location index
│       └── [Supporting files] ← Encounters, items, NPCs specific to arc
├── Players/                    ← Character sheets and event history
│   └── [Character-Player].md
├── Worlds/                     ← World-building (location-focused, persistent)
│   ├── General/
│   │   ├── Factions/
│   │   ├── Locations/
│   │   └── NPCs/
│   └── Prismeer/
│       ├── Hither/
│       ├── Thither/            ← Current arc location
│       │   ├── Locations/
│       │   └── NPCs/
│       ├── Twilight_Court/
│       └── Yon/
├── Game/                       ← Player-facing materials
│   └── Player-Package/
└── creatures/                  ← Stat blocks

```

## Linking Convention
- Arc session files link TO Worlds files (one-way)
- Worlds files do NOT link back to Arc files
- Use relative markdown links: `[Name](../relative/path.md)`
- Arc 5 sessions live in `Arcs/Arc_5_Thither/Sessions/`

## Session Template
When creating a new session file, use this format:

```markdown
# Arc-N, Session-N

# Planning

## Recap
[2-3 paragraph recap of previous session events, written for the players — second person, in-world, narrative tone]

## Cut-Scene (Optional)
[Only include when DM explicitly provides one. Leave section out otherwise.]

## Beats
1. **Location or Scene**
   a. Sub-beat or detail
      - Additional note

## Future Events
[Beats that are planned but not yet scheduled for this session]
1. **Upcoming event** ([link](path/to/file.md))
   a. Detail

## Reminders
1. **Category**
   a. Detail
   b. Detail

## NPCs
- **Name** (Role) — Key traits, current status, what players need to know

## Outstanding Quests
1. **Quest name** — deadline/urgency
   a. Detail

---

# Game Notes
[To be filled during/after session — transcript notes, unexpected events, rulings made]
```

## Key Active Mechanics (Arc 5 - Casino)

### Sinner's Weight (Wisdom Save DC 12 per hour in casino)
- Stack 1: Disadvantage on Insight
- Stack 2: Disadvantage on Wisdom saves
- Stack 3: -1 to Wisdom skill checks
- Stack 4: Compulsion to gamble (DC 15 Wisdom to leave)
- Stack 5: Charmed by Velisara or Caldrien
- Removal: Leave 8h = -1 stack; Lesser Restoration = -2; Greater Restoration = all

### Casino Currency
- 1 ability score point = 10 starvens
- Must maintain positive scores

### Di's Contracts
- Signed TWO contracts (Velisara + Caldrien, coordinated) for Chopaign's eye color
- Deadline: 2 months or owe 100 starvens
- Yanaba witnessed the Velisara deal while hidden

## Key Plot Threads (Arc 5)
1. **Di's double contract** - Velisara & Caldrien work together
2. **Karag's Dream** - Three paths: Fury / Stillness / Throne (multiclass decision)
3. **Witchlight Staff** - Find 7 in ~6 days; 3 in casino (Tilly found, Grimble + Marlon missing)
4. **Maurnu** - Will arrange Hagspawn Sons meeting (Tempest, Creak, and 3rd)
5. **Never Leave Spa Quest** - Casino owners want competition eliminated; reward includes Polymorph potion
6. **4-Way Ambush** - After casino: frog knight vs Sevro, kidnappers vs Yanaba, spirits vs Karag
7. **Yanaba's birth parents** - Imprisoned in Cinder Hold Prison under Skabatha
8. **White Bliss drug** - Will be offered to Sevro by escort (Con save DC 15 for addiction)

## World Files of Note
- [Starved-Goblin-Casino.md](Worlds/Prismeer/Thither/Locations/Starved-Goblin-Casino.md)
- [Casino-Owners.md](Worlds/Prismeer/Thither/NPCs/Casino-Owners.md)
- [Cinder-Hold-Prison.md](Worlds/Prismeer/Thither/Locations/Cinder-Hold-Prison.md)
- [Never-Leave-Spa.md](Worlds/Prismeer/Thither/Locations/Never-Leave-Spa.md)
- [4-Way-Ambush.md](Arcs/Arc_5_Thither/4-Way-Ambush.md)
- [Karags-Dream.md](Arcs/Arc_5_Thither/Karags-Dream.md)
