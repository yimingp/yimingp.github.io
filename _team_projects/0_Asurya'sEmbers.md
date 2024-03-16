---
name: Asurya's Embers
tools: [Unreal 5.3, C++, FPS, Action, Steam, Epic Game Store]
image: ../pictures/sunslayer_thumbnail.png
description: Asurya's Embers is a bow-and-arrow game where you play as Dhawa the guardian of the village and trying to defeat the Sun God to save the village.
---

# Asurya's Embers

***

<div class="section Trailer"></div>

{% include elements/video.html path="../videos/sunslayer_trailer.mp4" %}

***

<div style="text-align: center;">
    <p><a href="https://store.steampowered.com/app/2491710/Asuryas_Embers/">Steam Store Page</a></p>
</div>

***

- Duration:             6 months
- Team size:            22 (7 programmers)
- Platform:             Steam, Epic Game Store
- Engine:               Unreal 5.3
- Time:                 June 2023 - Decemeber 2023

***

<div class="section Overview"></div>

Asurya's Embers is a bow-and-arrow game where you play as Dhawa the guardian of the village and trying to defeat the Sun God to save the village. On the way to the sun god, the player will need hide in the shadow and avoid damage from the sun, defeat enemies, and solve puzzles. This game features two boss fights, and three types of enemies, four types of arrows, parkour system, fully animated mordern first person shooter combat system, diagetic UI, save/load game system, and aim assist system. 

***

### Roles and Responsibility

1. Boss fight system for the dragon including: pathing, animation, AI, UI
2. Bow-and-arrow implementation such as camera management, animation FSM, input system, player movement
3. Audio system implementation using Unreal Metasound for footsteps, environment sound, and character voicelines
4. System architecture 
5. Store SDK relevant things like pushing builds to store, achievements, and overlays for Steam and Epic Game Store
6. UI Implementation and bug fixing
7. Level small puzzle implementations

***

<div class="section Dragon"></div>

![AE Dragon](../pictures/ae_dragon.gif)

1. Made with blueprint
2. 3 stages of boss fight that use different beahviour patterns
3. Created triggers and splines for boss designer to use in the editor
4. Used control rig and animation blueprint for animation
5. Used niagara to bring particle effects assets to dragon
6. Used behaivour tree for AI 

***

<div class="section UI"></div>

{% include elements/video.html path="../videos/ae_ui.mp4" %}

1. Implementing UI components from design
2. Solve input can not be recieved bug in UMG
3. Solve focus issues with UMG
4. Help build responsive UI icons to different controls scheme (keyboard/controller)

***

<div class="section AI"></div>

- Implementing Dragon Boss AI with behaviour tree
- Build architecture of Enemy class
- Finialize enemy classes APIs
![AE Enemy Base](../pictures/ae_enemy_base.png)

***

<div class="section Player Control"></div>

![AE Player AnimBP](../pictures/ae_player_anim_bp.webp)

- Help building the state machine for player control

{% include elements/video.html path="../videos/ae_valut.mp4" %}

- Set up initial tech design of the valuting system

***

<div class="section Photo"></div>

### The Team

![Seafeud Programmers](../pictures/sunslayer_family.webp)