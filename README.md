# Industrial Modpack for Minecraft Forge 1.19.2

> [!WARNING]
> Some mods are incompatible with <kbd>**OptiFine**</kbd>. Therefore, this modpack uses <kbd>**Embeddium**</kbd> and <kbd>**Oculus**</kbd> instead. To ensure proper functionality, launch Minecraft with <kbd>**Forge**</kbd> version <kbd>**1.19.2**</kbd> without <kbd>**OptiFine**</kbd>.

## Installation

This modpack is structured into separate <kbd>**client-side**</kbd> and <kbd>**server-side**</kbd> archives to simplify installation and prevent compatibility issues. Some mods are purely visual and should not be installed on a server, while others may cause errors. To avoid manual sorting, the necessary mods for both the client and server have been pre-sorted and can be downloaded from the [**releases**][releases].

### Client Side

If you're playing in single-player mode, you only need to install <kbd>**client-side**</kbd> mods:

1. Make sure you have the appropriate version of Minecraft <kbd>**Forge**</kbd> installed. If <kbd>**Forge**</kbd> is not installed, download the [**installer**][forge] and select the <kbd>**Install Client**</kbd> option.
2. Download the <kbd>**client-side**</kbd> [**modpack**][releases] and extract its contents into the game directory:
   - **`Windows:`** <kbd>**%appdata%\\.minecraft\\**</kbd>
   - **`macOS:`** <kbd>**~/Library/Application Support/minecraft/**</kbd>
   - **`Linux:`** <kbd>**~/.minecraft/**</kbd>
3. Launch the Minecraft launcher, select the <kbd>**Forge**</kbd> profile, and click <kbd>**Play**</kbd>.

<kbd>**Client-side**</kbd> mods, divided into <kbd>**mods**</kbd> and <kbd>**libs**</kbd>, are located in this repository at the following path:

```
modpack
└── client-side
    ├── libs
    │   ├── lib.jar
    │   └── ...
    └── mods
        ├── mod.jar
        └── ...
```

### Server Side

If you're playing on your own server, you'll also need to install mods on the server:

1. Make sure your server has the appropriate version of Minecraft <kbd>**Forge**</kbd> installed. If <kbd>**Forge**</kbd> is not installed, download the [**installer**][forge] and select the <kbd>**Install Server**</kbd> option.
2. Download the <kbd>**server-side**</kbd> [**modpack**][releases] and extract its contents into the server's root directory, where <kbd>**server.jar**</kbd> and other files are located.
3. Start the server and check that it runs without errors and all mods load correctly.

<kbd>**Server-side**</kbd> mods, divided into <kbd>**mods**</kbd> and <kbd>**libs**</kbd>, are located in this repository at the following path:

```
modpack
└── server-side
    ├── libs
    │   ├── lib.jar
    │   └── ...
    └── mods
        ├── mod.jar
        └── ...
```

> **_Don't forget to install mods on your computer as indicated in the <kbd>[**_Client-side_**](#client-side)</kbd> installation section._**

## Tables of Modifications <kbd>**51**</kbd>

In this section, all mods included in this modpack, both <kbd>**client-side**</kbd> and <kbd>**server-side**</kbd>, are presented. The mods are organized into two tables: <kbd>**Mods**</kbd> and <kbd>**Libs**</kbd>. This provides a convenient overview of dependencies and allows for easy removal of unwanted mods and their associated libs.

Each table provides the following information:

- **`name:`** The name of the mod or lib.
- **`dependencies:`** Other mods or libs that this mod requires to function.
- **`used by:`** If it's a lib, the mods that use it are listed here.
- **`installation side:`** Indicates whether the mod is intended for the <kbd>**client-side**</kbd> or <kbd>**server-side**</kbd>.

This structure allows users to tailor the modpack to their preferences.

### Mods <kbd>**40**</kbd>

[comment]: # (For convenient reading of tables in this file, disable word wrap.)

| **name**                                                                                 | **dependencies**                                                                                                                               | **installation side** |
| ---------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------- | --------------------- |
| [**Advanced Solars Classic**][advanced-solars-classic]                                   | <kbd>[**Industrial Craft 2 Classic<br>(IC2 Classic)**][ic2-classic]</kbd>                                                                      | `client and server`   |
| [**AmbientSounds**][ambientsounds]                                                       | <kbd>[**CreativeCore**][creativecore]</kbd>                                                                                                    | `client`              |
| [**Applied Energistics 2 (AE2)**][ae2]                                                   | <kbd>_none_</kbd>                                                                                                                              | `client and server`   |
| [**Applied Energistics 2 Things<br>(AE2 Things)**][ae2-things]                           | <kbd>[**Applied Energistics 2 (AE2)**][ae2]</kbd>                                                                                              | `client and server`   |
| [**Better Third Person**][better-third-person]                                           | <kbd>_none_</kbd>                                                                                                                              | `client`              |
| [**Biomes O' Plenty**][biomes-o-plenty]                                                  | <kbd>[**TerraBlender**][terrablender]</kbd>                                                                                                    | `client and server`   |
| [**Carry On**][carry-on]                                                                 | <kbd>_none_</kbd>                                                                                                                              | `client and server`   |
| [**ChoiceTheorem's<br>Overhauled Village<br>(CTOV)**][ctov]                              | <kbd>_none_</kbd>                                                                                                                              | `client and server`   |
| [**Cosmetic Armor Reworked**][cosmetic-armor-reworked]                                   | <kbd>_none_</kbd>                                                                                                                              | `client and server`   |
| [**Embeddium**][embeddium]                                                               | <kbd>_none_</kbd>                                                                                                                              | `client`              |
| [**Embeddium Extra**][embeddium-extra]                                                   | <kbd>[**Embeddium**][embeddium]</kbd>                                                                                                          | `client`              |
| [**Embeddium Extras**][embeddium-extras]                                                 | <kbd>[**Embeddium**][embeddium]</kbd>                                                                                                          | `client`              |
| [**Farmer's Delight**][farmers-delight]                                                  | <kbd>_none_</kbd>                                                                                                                              | `client and server`   |
| [**First-person Model**][first-person-model]                                             | <kbd>[**Not Enough Animations**][not-enough-animations]</kbd>                                                                                  | `client`              |
| [**Gravisuit Classic**][gravisuit-classic]                                               | <kbd>[**Industrial Craft 2 Classic<br>(IC2 Classic)**][ic2-classic]</kbd>                                                                      | `client and server`   |
| [**HT's TreeChop**][hts-treechop]                                                        | <kbd>_none_</kbd>                                                                                                                              | `client and server`   |
| [**Industrial Craft 2 Classic<br>(IC2 Classic)**][ic2-classic]                           | <kbd>[**Curios API**][curios-api]</kbd>                                                                                                        | `client and server`   |
| [**Industrial Craft 2 Classic<br>UU-Matter<br>(IC2C UU-Matter)**][ic2-classic-uu-matter] | <kbd>[**Industrial Craft 2 Classic<br>(IC2 Classic)**][ic2-classic],<br><br>[**Just Enough Items (JEI)**][jei]</kbd>                           | `client and server`   |
| [**Inventory HUD+**][inventory-hud]                                                      | <kbd>_none_</kbd>                                                                                                                              | `client`              |
| [**Inventory Profiles Next (IPN)**][ipn]                                                 | <kbd>[**Kotlin**][kotlin], [**libIPN**][libipn]</kbd>                                                                                          | `client`              |
| [**Iron Chests**][iron-chests]                                                           | <kbd>_none_</kbd>                                                                                                                              | `client and server`   |
| [**Item Borders**][item-borders]                                                         | <kbd>[**Iceberg**][iceberg], [**Prism**][prism]</kbd>                                                                                          | `client`              |
| [**Just Enough Items (JEI)**][jei]                                                       | <kbd>_none_</kbd>                                                                                                                              | `client and server`   |
| [**Just Enough Resources (JER)**][jer]                                                   | <kbd>[**Just Enough Items (JEI)**][jei]</kbd>                                                                                                  | `client and server`   |
| [**Legendary Tooltips**][legendary-tooltips]                                             | <kbd>[**Iceberg**][iceberg], [**Prism**][prism]</kbd>                                                                                          | `client`              |
| [**Light Overlay**][light-overlay]                                                       | <kbd>[**Architectury API**][architectury-api],<br><br>[**Cloth Config API**][cloth-config-api]</kbd>                                           | `client`              |
| [**Lootr**][lootr]                                                                       | <kbd>_none_</kbd>                                                                                                                              | `client and server`   |
| [**Model Gap Fix**][model-gap-fix]                                                       | <kbd>_none_</kbd>                                                                                                                              | `client`              |
| [**Mouse Tweaks**][mouse-tweaks]                                                         | <kbd>_none_</kbd>                                                                                                                              | `client`              |
| [**Not Enough Animations**][not-enough-animations]                                       | <kbd>_none_</kbd>                                                                                                                              | `client`              |
| [**Oculus**][oculus]                                                                     | <kbd>[**Embeddium**][embeddium]</kbd>                                                                                                          | `client`              |
| [**OpenBlocks Elevator<br>(Elevatorid)**][elevatorid]                                    | <kbd>_none_</kbd>                                                                                                                              | `client and server`   |
| [**Packed Up**][packed-up]                                                               | <kbd>[**SuperMartijn642's Config Lib**][supermartijn642s-config-lib],<br><br>[**SuperMartijn642's Core Lib**][supermartijn642s-core-lib]</kbd> | `client and server`   |
| [**Serene Seasons**][serene-seasons]                                                     | <kbd>_none_</kbd>                                                                                                                              | `client and server`   |
| [**Skin Layers 3D**][skin-layers-3d]                                                     | <kbd>_none_</kbd>                                                                                                                              | `client`              |
| [**TexTrue's Embeddium Options**][textrues-embeddium-options]                            | <kbd>[**Embeddium**][embeddium]</kbd>                                                                                                          | `client`              |
| [**The One Probe**][the-one-probe]                                                       | <kbd>_none_</kbd>                                                                                                                              | `client and server`   |
| [**Towns and Towers**][towns-and-towers]                                                 | <kbd>_none_</kbd>                                                                                                                              | `client and server`   |
| [**Xaero's Minimap**][xaeros-minimap]                                                    | <kbd>_none_</kbd>                                                                                                                              | `client and server`   |
| [**Xaero's World Map**][xaeros-world-map]                                                | <kbd>_none_</kbd>                                                                                                                              | `client and server`   |

### Libs <kbd>**11**</kbd>

[comment]: # (For convenient reading of tables in this file, disable word wrap.)

| **name**                                                        | **used by**                                                                                      | **installation side** |
| --------------------------------------------------------------- | ------------------------------------------------------------------------------------------------ | --------------------- |
| [**Architectury API**][architectury-api]                        | <kbd>[**Light Overlay**][light-overlay]</kbd>                                                    | `client`              |
| [**Cloth Config API**][cloth-config-api]                        | <kbd>[**Light Overlay**][light-overlay]</kbd>                                                    | `client`              |
| [**CreativeCore**][creativecore]                                | <kbd>[**AmbientSounds**][ambientsounds]</kbd>                                                    | `client`              |
| [**Curios API**][curios-api]                                    | <kbd>[**Industrial Craft 2 Classic<br>(IC2 Classic)**][ic2-classic]</kbd>                        | `client and server`   |
| [**Iceberg**][iceberg]                                          | <kbd>[**Item Borders**][item-borders],<br><br>[**Legendary Tooltips**][legendary-tooltips]</kbd> | `client`              |
| [**Kotlin**][kotlin]                                            | <kbd>[**Inventory Profiles Next (IPN)**][ipn]</kbd>                                              | `client`              |
| [**libIPN**][libipn]                                            | <kbd>[**Inventory Profiles Next (IPN)**][ipn]</kbd>                                              | `client`              |
| [**Prism**][prism]                                              | <kbd>[**Item Borders**][item-borders],<br><br>[**Legendary Tooltips**][legendary-tooltips]</kbd> | `client`              |
| [**SuperMartijn642's Config Lib**][supermartijn642s-config-lib] | <kbd>[**Packed Up**][packed-up]</kbd>                                                            | `client and server`   |
| [**SuperMartijn642's Core Lib**][supermartijn642s-core-lib]     | <kbd>[**Packed Up**][packed-up]</kbd>                                                            | `client and server`   |
| [**TerraBlender**][terrablender]                                | <kbd>[**Biomes O' Plenty**][biomes-o-plenty]</kbd>                                               | `client and server`   |


[advanced-solars-classic]: https://www.curseforge.com/minecraft/mc-mods/advanced-solars-classic
[ambientsounds]: https://www.curseforge.com/minecraft/mc-mods/ambientsounds
[ae2]: https://www.curseforge.com/minecraft/mc-mods/applied-energistics-2
[ae2-things]: https://www.curseforge.com/minecraft/mc-mods/ae2-things-forge
[better-third-person]: https://www.curseforge.com/minecraft/mc-mods/better-third-person
[biomes-o-plenty]: https://www.curseforge.com/minecraft/mc-mods/biomes-o-plenty
[carry-on]: https://www.curseforge.com/minecraft/mc-mods/carry-on
[ctov]: https://www.curseforge.com/minecraft/mc-mods/choicetheorems-overhauled-village
[cosmetic-armor-reworked]: https://www.curseforge.com/minecraft/mc-mods/cosmetic-armor-reworked
[embeddium]: https://www.curseforge.com/minecraft/mc-mods/embeddium
[embeddium-extra]: https://www.curseforge.com/minecraft/mc-mods/rubidium-extra
[embeddium-extras]: https://www.curseforge.com/minecraft/mc-mods/magnesium-extras
[farmers-delight]: https://www.curseforge.com/minecraft/mc-mods/farmers-delight
[first-person-model]: https://www.curseforge.com/minecraft/mc-mods/first-person-model
[gravisuit-classic]: https://www.curseforge.com/minecraft/mc-mods/gravisuit-classic
[hts-treechop]: https://www.curseforge.com/minecraft/mc-mods/treechop
[ic2-classic]: https://www.curseforge.com/minecraft/mc-mods/ic2-classic
[ic2-classic-uu-matter]: https://www.curseforge.com/minecraft/mc-mods/ic2cuumatter
[inventory-hud]: https://www.curseforge.com/minecraft/mc-mods/inventory-hud-forge
[ipn]: https://www.curseforge.com/minecraft/mc-mods/inventory-profiles-next
[iron-chests]: https://www.curseforge.com/minecraft/mc-mods/iron-chests
[item-borders]: https://www.curseforge.com/minecraft/mc-mods/item-borders
[jei]: https://www.curseforge.com/minecraft/mc-mods/jei
[jer]: https://www.curseforge.com/minecraft/mc-mods/just-enough-resources-jer
[legendary-tooltips]: https://www.curseforge.com/minecraft/mc-mods/legendary-tooltips
[light-overlay]: https://www.curseforge.com/minecraft/mc-mods/light-overlay
[lootr]: https://www.curseforge.com/minecraft/mc-mods/lootr
[model-gap-fix]: https://www.curseforge.com/minecraft/mc-mods/model-gap-fix
[mouse-tweaks]: https://www.curseforge.com/minecraft/mc-mods/mouse-tweaks
[not-enough-animations]: https://www.curseforge.com/minecraft/mc-mods/not-enough-animations
[oculus]: https://www.curseforge.com/minecraft/mc-mods/oculus
[elevatorid]: https://www.curseforge.com/minecraft/mc-mods/openblocks-elevator
[packed-up]: https://www.curseforge.com/minecraft/mc-mods/packed-up-backpacks
[serene-seasons]: https://www.curseforge.com/minecraft/mc-mods/serene-seasons
[skin-layers-3d]: https://www.curseforge.com/minecraft/mc-mods/skin-layers-3d
[textrues-embeddium-options]: https://www.curseforge.com/minecraft/mc-mods/textrues-embeddium-options
[the-one-probe]: https://www.curseforge.com/minecraft/mc-mods/the-one-probe
[towns-and-towers]: https://www.curseforge.com/minecraft/mc-mods/towns-and-towers
[xaeros-minimap]: https://www.curseforge.com/minecraft/mc-mods/xaeros-minimap
[xaeros-world-map]: https://www.curseforge.com/minecraft/mc-mods/xaeros-world-map

[architectury-api]: https://www.curseforge.com/minecraft/mc-mods/architectury-api
[cloth-config-api]: https://www.curseforge.com/minecraft/mc-mods/cloth-config
[creativecore]: https://www.curseforge.com/minecraft/mc-mods/creativecore
[curios-api]: https://www.curseforge.com/minecraft/mc-mods/curios
[iceberg]: https://www.curseforge.com/minecraft/mc-mods/iceberg
[kotlin]: https://www.curseforge.com/minecraft/mc-mods/kotlin-for-forge
[libipn]: https://www.curseforge.com/minecraft/mc-mods/libipn
[prism]: https://www.curseforge.com/minecraft/mc-mods/prism-lib
[supermartijn642s-config-lib]: https://www.curseforge.com/minecraft/mc-mods/supermartijn642s-config-lib
[supermartijn642s-core-lib]: https://www.curseforge.com/minecraft/mc-mods/supermartijn642s-core-lib
[terrablender]: https://www.curseforge.com/minecraft/mc-mods/terrablender

[releases]: https://github.com/iwdath/mc-industrial-modpack-forge-1.19.2/releases
[forge]: https://files.minecraftforge.net/net/minecraftforge/forge/index_1.19.2.html