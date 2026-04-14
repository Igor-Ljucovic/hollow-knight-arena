# Hollow Knight Arena

A 2D action game inspired by Hollow Knight, featuring multiple movement abilities, spells, items, arenas, and boss combat mechanics.

---

## Features

- 9 player movement abilities including double jump, wall jump, dash, dodge, roll, and fast fall
- 3 combat spells inspired by the original Hollow Knight
- 24 collectible/equippable items (charms)
- 2 unique game modes with different gameplay mechanics
- 3 playable combat arenas
- 1 boss featuring 4 phases and 10 unique attacks
- Input buffering system for smoother and more responsive gameplay

---

## Game Modes

### Classic

Replicates the controls and mechanics of the original Hollow Knight.

- Jump, double jump, wall slide, wall jump, dash
- 3 original spells
- 12 selectable charms before boss fights

### Ultimate

Expanded version with additional movement mechanics.

- Everything from Classic mode
- Fast fall, spot dodge, air dodge, roll
- 3 original spells
- 12 additional selectable charms before boss fights

---

## Technical / Design Highlights

- Implemented input buffering for improved gameplay responsiveness  
- Added coyote-time / jump leniency mechanics to improve platforming feel  
- Reduced player hitbox size relative to sprite for fairer-feeling collisions  
- Designed modular systems for:
  - Player state management
  - Boss attack behavior
  - Hitbox detection
  - Item/charm handling
  - Input buffering

---

## What I Learned

- Working with UI/menus, animations, and physics systems
- Writing scalable, readable, and maintainable code with proper abstraction
- Planning game mechanics and systems before implementation
- Debugging and avoiding difficult-to-maintain code patterns
- Designing systems with user experience in mind
- Understanding trade-offs between readability, scalability, memory efficiency, and development speed

---

## Tech Stack

- **Engine:** Unity
- **Programming Language:** C#
- **Core Technologies:** Unity Physics, Animation System, State Management

---

## Demo

YouTube video showcasing this video game:  
https://www.youtube.com/watch?v=phzQARODG74

---

## Additional Notes

This project focused primarily on gameplay programming and technical implementation rather than visual art design.  
Existing sprites were reused for character animations and placeholder visuals.

This project was committed after development had already started, as Git version control was not used during the earliest development stages.  
As a result, version history is limited for the initial implementation.
