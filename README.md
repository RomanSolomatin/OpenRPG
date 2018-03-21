# OpenRPG
#### Welcome! In this repository you will find a great powerful, well commented and structured API that will be the learning base to build your own RPG game!

## Inventory System
  - Has common functions like Add, Remove, Drop, Split, Swap, Drag & Drop, etc). 
  - Supports different types of items (consumable, equipment, material, quest, miscellaneous) and you can add your custom ones!
  - Very easy to add and modify items via DataTable. 
  - Each item can execute custom logic when used, just overriding an event in its class.
  
## Equipment System
  - Support for multi-slots, i have added 8 examples (helmet, armor, weapon, shield, boots, earrings, belt, ring) to show how to use your custom ones!
  - Each item has custom stat values that applies to the player when they are equipped (see Stats System for more info).
  - Every property is editable via DataTable.
  
## HotKeyBar System
  - Dynamically generated with the keys that you want!
  - Supports inventory items and skills (when Skill System implemented).
  - Enabled or disabled in your game just changing a boolean.

## Stats system
  - Allows you to have different bars (comes with health, mana and exp as examples) with custom behavior like regen/drain, etc.
  - Comes with 19 stat examples (resistances, strenghts, movement and attack speed, etc).
  - You can add your custom function logic when an stat is changed. 

**Every system has Save/Load functionality in a .sav file located in external folder just pressing a key during gameplay!**

Future systems to be implemented:

- Quest system
- Dialogue system
- Combat system
- Minimap system
- Ability system
- Crafting system
- Multipurpose NPC system

Thank you so much to [UnrealGaimeDev](https://www.youtube.com/channel/UCRnPBe1tJpXA0lccx_U1mww), i started programming in UE4 due to his amazing youtube tutorials :D
