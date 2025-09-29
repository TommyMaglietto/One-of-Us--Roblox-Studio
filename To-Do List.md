# GAME TO-DO LIST

CORE CONTENT IMPORTS

* Import Creature Rig
* Import Creature Animations
* Import Loading Screen



LOBBY

* Add Directions/Instructions in Lobby



ENVIRONMENT \& LEVEL DESIGN

* Remake Farmhouse and Cabins



PLAYER SYSTEMS

* Player Stats (health, stamina, sanity)
* Player Upgrades to Stats
* Upgrade System from Perks
* Inventory System (items, bandages, flashlight)
* Healing System (uses bandages)
* Healing Animations
* Lay Down Animation
* Spectator UI
* Random Assignment of Roles (survivor, monster, special roles)



MONSTER SYSTEMS

* Monster Stats (HP, damage, detection radius)
* Monster Movement System
* Monster Eating Player Function
* Monster Scream
* Shotgun Damage/Wound Monster
* Flashlight Interaction with Monster
* Player Transform into Monster
* Player Being Dragged Animation
* Monster Attack



COMBAT \& TOOLS

* Shotgun Animation (idle, reload, shoot)
* Shotgun Shooting Mechanic
* Shotgun Damage/Wounding



AUDIO \& FEEDBACK

* Monster Scream SFX
* Flashlight SFX/Feedback
* Healing SFX
* Task Completion SFX/UI



PROGRESSION \& META

* Monetization Features (skins, boosts, passes)
* Log of Players’ Completed Tasks



MOBILE
-add sprint button
-add jump button





DEPENDENCIES / ORDER

1. Imports
2. Core Systems (Player + Monster)
3. Tools/Combat
4. Animations
5. Monster Functions
6. Meta/Progression
7. Polish (UI, audio, spectator, environment)


   I need you to build a fully functional Skinwalker transformation system for my Roblox horror game using the assets I’ll provide. The system should allow the player to press a key (for example, “T”) to transform from their normal Robloxian character into the Skinwalker form. When transforming, the Robloxian rig should become transparent or hidden, and the Skinwalker model should appear in its place, fully visible and animated. The Skinwalker form must use the provided animations for walking, attacking, grabbing, and eating, each triggered by specific keybinds (for example, “Q” for attack, “F” for grab, “E” for eat). The user can only activate the eat ability if they have successfully grabbed a player first. Each ability should play its animation smoothly and be visible to all players in multiplayer. The system must also include a custom health system for the Skinwalker, featuring a very large health pool compared to regular players (for example, several times higher), displayed on-screen through a clear and prominent health bar UI while transformed. When reverting back to their normal Robloxian form, the health should reset to normal levels and the default UI should return. All actions, transformations, health updates, and abilities should replicate correctly across the server so every player sees them accurately. The scripts must be clean, well-commented, and organized, using RemoteEvents for client-server communication. I’ll supply the Skinwalker model, all animations, and any sound or visual effects needed — your job is to script and integrate the full transformation logic, abilities, health system, UI, and reversion process.



