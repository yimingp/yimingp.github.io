---
name: Simple Miner
tools: [C++, Custom Engine, Lighting, Procedural Generation, Multi-threading]
image: ../pictures/sm_demo.gif
description:  Minecraft-like game
---

# Simple Miner

***

![Gameplay](../pictures/ss_gp.gif)

***

- Duration:             2 months
- Language:             C++
- Key words:            3D, Lighting, Procedural Generation, Multi-threading
- Engine:               Custom Engine
- Time:                 May 2023 - July 2023

***

SimpleMiner is a program inspired by Minecraft, featuring an endlessly generating voxel world, utilizing multi-threading for its creation. It extensively employs Perlin noise to produce uniform, seed-based procedural worlds filled with diverse structures like trees, giant mushrooms, and caves formed by Perlin worms, as well as varying biomes influencing block types. The lighting system, modeled closely on Minecraft's, uses a heat map for accuracy. Additionally, the program has the capability to save and load player-modified chunks using a unique file format, ensuring the preservation of player alterations.

***

### Key features

1. 3D lighting using light value propogation
2. Procedural generated world using chunking method and perlin noise
3. Multi-threading chunk activation and deactivation