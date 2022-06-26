# **The Comprehensive Minecraft Guide**

(Planning)

- [**The Comprehensive Minecraft Guide**](#the-comprehensive-minecraft-guide)
  - [**Basics**](#basics)
    - [**World Types**](#world-types)
    - [**Superflat Worlds - Presets**](#superflat-worlds---presets)
    - [**Superflat Worlds - Custom Presets**](#superflat-worlds---custom-presets)
    - [**Gamemodes**](#gamemodes)
    - [**World Creation**](#world-creation)
    - [**What Are Blocks?**](#what-are-blocks)
    - [**What Are Items?**](#what-are-items)
    - [**What Are Entities?**](#what-are-entities)
    - [**Crafting**](#crafting)
  - [**Minecraft In Depth**](#minecraft-in-depth)
    - [**Status Effects**](#status-effects)
    - [**Blocks In Depth**](#blocks-in-depth)
    - [**Items In Depth**](#items-in-depth)
    - [**Entities In Depth**](#entities-in-depth)
    - [**Health In Depth**](#health-in-depth)
    - [**Hunger In Depth**](#hunger-in-depth)
    - [**Armor In Depth**](#armor-in-depth)
  - [**Generation**](#generation)
    - [**What Are Biomes?**](#what-are-biomes)
    - [**Surface Biomes**](#surface-biomes)
    - [**Underground Biomes**](#underground-biomes)
    - [**Nether Biomes**](#nether-biomes)
    - [**Other Biomes**](#other-biomes)
    - [**Structures**](#structures)
    - [**Ores**](#ores)
  - [**Blocks**](#blocks)
    - [**Todo**](#todo)
  - [**Data**](#data)
    - [**What is JSON?**](#what-is-json)
    - [**Advanced JSON**](#advanced-json)
    - [**Custom Worlds**](#custom-worlds)

tutorials.zephyrsnow.xyz

---
---

## **Basics**

### **World Types**

There are 5 different normal world types in Minecraft: Java Edition, and 1 *hidden* world type, alongside a much more advanced "custom" world type.

> Default

This world type is the normal, natural generation of a minecraft world. It's the standard minecraft experience, generating all biomes and all structures. (See [Biomes](#biomes) and [Structures](#structures))

> Superflat

The default superflat generation has 1 layer of bedrock, 2 layers of dirt, and 1 final layer of grass. No biomes generate, and villages are the only structure that generates.

Superflat worlds do have customization options, though. You can use presets, or create your own. (See [Superflat Presets](#superflat-worlds---presets) and [Custom Superflat Presets](#superflat-worlds---custom-presets))

> Amplified

Amplified worlds generate extreme mountains, with vertical cliffs reaching up to the height limit. Travelling is difficult, and deaths by falling are frequent. This can be very fun if you're looking to challenge yourself, or just looking for an interesting experience! The world will generate all biomes and structures, so it's still possible to beat the game!

> Large Biomes

Large biomes generation is normal world generation, but with every biome 16 times larger. This makes generated structures much more likely to be found, but it can also make finding some rarer or biome-specific resources a huge pain.

> Single Biome

Single-biome worlds will generate using only one biome. Besides that, all (possible) structures will generate.

> Hidden World Type: Debug

The "debug" world type can only be accessed by holding down the ALT key on your keyboard while clicking through the different world types. This world type generates every single block state (See [Blocks In Depth](#blocks-in-depth)) in the game, in a massive grid. The player cannot place or break blocks.

> Custom

Customizable worlds take JSON data (See [What is JSON?](#what-is-json)), which changes how existing dimensions generate, and can also add entirely new dimensions. This is a pretty complicated process, and definitely isn't for any new players. (See [Custom Worlds](#custom-worlds))

---

### **Superflat Worlds - Presets**

Superflat worlds come with plenty of built-in presets. This video will cover each one, the layers of blocks that make them up as well as the structures that do (or don't) generate.

> Classic Flat

As stated before, the default, classic flat is 1 layer of bedrock, 2 layers of dirt, and 1 layer of grass.

> Tunnelers Dream

The tunnelers dream preset generates 1 layer of bedrock, 230 layers of stone, 5 layers of dirt, and one layer of grass. Strongholds, mineshafts, and dungeons generate, but there are no villages. Ores also generate.

> Water World

The water world preset generates 1 layer of bedrock, 64 layers of deepslate, 5 layers of stone, 5 layers of dirt, 5 layers of gravel, and 90 layers of water. Villages don't generate here either, however, ocean monuments, ocean ruins, and shipwrecks do.

> Overworld

The overworld preset generates 1 layer of bedrock, 59 layers of stone, 3 layers of dirt, and 1 layer of grass. Villages generate, alongside pillager outposts, strongholds, mineshafts, dungeons, and ruined portals.

> Snowy Kingdom

The snowy kingdom preset generates 1 layer of bedrock, 59 layers of stone, 3 layers of dirt, 1 layer of grass, and 1 layer of snow. Only villages and igloos generate here.

> Bottomless Pit

The bottomless pit preset generates nearly identically to the default preset, except the layer of bedrock is replaced with two layers of cobblestone. This means you can easily dig into the void in survival mode.

> Desert

The desert preset generates 1 layer of bedrock, 3 layers of stone, 52 layers of sandstone, and 8 layers of sand. Villages, pyramids, strongholds, mineshafts, and dungeons all spawn in this preset.

> Redstone Ready

The redstone ready preset generates 1 layer of bedrock, 3 layers of stone, and 116 layers of sandstone. No structures generate. This preset is ideal for, you guessed it, redstone building and testing.

> The Void

The void preset generates 1 layer of air - basically, nothing. The player spawns on a small stone platform, surrounded by absolutely nothing. No structures generate.

That's it for the built-in superflat presets! If you're looking to make your own presets, check out my [Custom Presets](#superflat-worlds---custom-presets) video!

---

### **Superflat Worlds - Custom Presets**

Todo

---

### **Gamemodes**

Gamemodes determine what the main gameplay will look like. There are three main gamemodes: Survival, creative, and spectator.

> Survival

In survival mode, the player has a few things on their hotbar - health, hunger, and XP. There are a few extra things that may show up on the hotbar too, these being armor and breath.

>> Health

Normally, the player has 10 hearts as their health bar. This can be increased, through the absorption status effect (See [Status Effects](status-effects)). Each heart is actually 2 points of health, as hearts are split in half. This means that the player actually has 20 points of health total. (See [Health In Depth](#health-in-depth))

>> Hunger

Hunger is also shown with 10 icons, in this case drumsticks, that represent 20 points of hunger. Different actions deplete hunger at different rates, and the hunger status effect will deplete it quickly, at different speeds depending on the level of the status effect. (See [Hunger In Depth](#hunger-in-depth))

>> XP

Todo

>> Armor

Todo

>> Breath

Todo

> Creative

Todo

> Spectator

Todo

---

### **World Creation**

Todo

---

### **What Are Blocks?**

Todo

---

### **What Are Items?**

Todo

---

### **What Are Entities?**

Todo

---

### **Crafting**

Todo

---
---

## **Minecraft In Depth**

### **Status Effects**

Todo

---

### **Blocks In Depth**

Todo

---

### **Items In Depth**

Todo

---

### **Entities In Depth**

Todo

---

### **Health In Depth**

Todo

---

### **Hunger In Depth**

Todo

---

### **Armor In Depth**

Todo

---
---

## **Generation**

### **What Are Biomes?**

Todo

---

### **Surface Biomes**

Todo

---

### **Underground Biomes**

Todo

---

### **Nether Biomes**

Todo

---

### **Other Biomes**

Todo

---

### **Structures**

Todo

---

### **Ores**

Todo

---
---

## **Blocks**

### **Todo**

Todo

---
---

## **Data**

### **What is JSON?**

Todo

---

### **Advanced JSON**

Todo

---

### **Custom Worlds**

Todo
