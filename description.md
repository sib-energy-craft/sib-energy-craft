# Description
Mod name is Sib Energy Craft, minecraft namespace: **sib_energy_craft**.

This mod is attempt to resurrect old techno mod packs in one peace and on actual Minecraft versions.

Mod is fully open source, all sources located on [GitHub](https://github.com/orgs/sib-energy-craft/repositories),
fill free to Pull Request and issue creating if you found something bad or have an idea to improve mod.

## General definitions

* Energy - is the abstract force that makes machines work.
* Energy charge - energy has a charge, it is always positive and its accuracy is 10 digits.
* Energy consumer - game block what can receive energy.
* Energy supplier - game block what can send energy.
* Energy cable - game block what can recipe energy from any energy and send energy to all energy except direction which was energy received.
* Energy level - characteristic of energy consumers, describe max amount of energy what consumer can receive without explosion.

# Mod structure

## Core libs
<details>
    <summary>Content</summary>

* [Energy API](https://github.com/sib-energy-craft/energy-api) - basic energy API. 
Contains interface for EnergyConsumer and EnergySupplier, definition of Energy and EnergyLevels.
* [SEC Utils](https://github.com/sib-energy-craft/sec-utils) - utils methods for blocks, items, screens, entities registration.
* [SEC Network](https://github.com/sib-energy-craft/sec-network) - network extension. Add ability to send custom properties on block screens.

</details>

## Mods API
<details>
    <summary>Content</summary>

* [Tools API](https://github.com/sib-energy-craft/mod-tools-api) - tools API. Currently, contains only tree tap interface.
* [Pipes API](https://github.com/sib-energy-craft/mod-pipes-api) - pipes API. Add interfaces of item consumers and suppliers. 
Which used to build pipe transfer system.
* [Iron Table API](https://github.com/sib-energy-craft/mod-iron-craft-table-api) - API for iron table tools.
Add ability to extend functionality of iron crafting table.
* [Energy container API](https://github.com/sib-energy-craft/energy-containers-api) - lib contains definition of abstract energy container. 
Also, lib provide implementation of clean energy container.
* [Energy machines API](https://github.com/sib-energy-craft/energy-machines-api) - lib contains abstract energy machine implementation and abstract energy machine screen handler.
* [Recipes](https://github.com/sib-energy-craft/mod-recipes) - mod add new types of recipes into the game.

</details>

## Mods
<details>
    <summary>Content</summary>

* [Agronomy](https://github.com/sib-energy-craft/mod-agronomy) - mod add machine to harvest corps. 
Also add ability to collect grown up crops from blocks by additional action button (Right mouse button).
* [Backpacks](https://github.com/sib-energy-craft/mod-backpacks) - mod add simple backpacks into the game.
Now you can bring more stuff from mines. Tips: even don't try to put backpack into backpack.
* [Ores](https://github.com/sib-energy-craft/mod-ores) - mod add 2 new ores: silver and tin. 
You can mine it as well as iron or copper ore.
* [Tools](https://github.com/sib-energy-craft/mod-tools-impl) - mod add Tree tap as tool in game.
* [Recipes Impl](https://github.com/sib-energy-craft/mod-recipes-impl/tree/main/src/main) - mod add recipes into the game.
Now you can craft a diamond.
* [Rubber](https://github.com/sib-energy-craft/mod-rubber) - mod add rubber tree, rubber and vulcanized rubber into the game.
Rubber tree can be used as regular minecraft tree, for crafting gates, doors, etc.
* [Energy items](https://github.com/sib-energy-craft/mod-energy-items) - mod add items, what used into crafting recipes.
* [Metallurgy](https://github.com/sib-energy-craft/mod-metallurgy) - mod add new types of metal's products, such as plates and chasing.
This mod bring also some composite metals, such as bronze and steel.x
* [Bronze Age](https://github.com/sib-energy-craft/mod-bronze-age) - mod add new bronze tools, sword and armor. 
Needed to spend a bunch of copper that is generated in the world.
* [Pipes](https://github.com/sib-energy-craft/mod-pipes) - mod add item extractors, item filters, trash cans and of course pipes.
With this mod you can transfer, sort your items and destroy useless items.
* [Chests](https://github.com/sib-energy-craft/mod-chests) - mod add new chests with more space.
Also, mod provide ability to boost up your chest just by using improving item on it.
All chest inventory will be saved.
* [Energy Tools](https://github.com/sib-energy-craft/mod-energy-tools) - mod add energy analog of simple tools.
New tools: energy saw, energy tree tap, energy hoe, energy mining drill, energy shovel. Some of tools has advanced versions.
* [Machines](https://github.com/sib-energy-craft/mod-machines) - mod has a lot of machines, energy generators and energy transformers.
* [Energy Containers](https://github.com/sib-energy-craft/mod-energy-containers) - mod add energy containers to store excess energy for a better time. 
* [Cables](https://github.com/sib-energy-craft/mod-cables) - mod add cables, what allow to transfer energy between energy consumers and suppliers.
* [Quarry](https://github.com/sib-energy-craft/mod-quarry) - mod add drilling rig into the game, with this stuff you can automize and speed up mining.
* [Solar panels](https://github.com/sib-energy-craft/mod-solar-panels) - mod brings several solar panels - eco free energy generators.

</details>

# Status
## Development
Currently mod is in **development** phase and not completely done.

So if you find something working wrong or some balance issue or even crash, please report me on GitHub.

I will try to save back compatibility as long as I can.
## Textures
Many of the textures were created in haste, by simply playing with contrasts in Photoshop.

Ideally, you need to rework them all in the same style, if someone wants to do this, including not for free, write to me.

# Localizations

Status of localizations:

* English - 100%
* Russian - 100%

# Feedback & Bag Reports
Do it better here: [sib-energy-craft](https://github.com/sib-energy-craft/sib-energy-craft) this is main mod repository.

Or you can message me on: `sibmaks@proton.me`

# Inspired by

I create this mode by inspiration of IndustrialCraft, BuildCraft, RailCraft and a bunch of other mods.

A lot of this mods available only for old Minecraft version, such as 1.12, so I want to bring their tech spirit into modern Minecraft.
