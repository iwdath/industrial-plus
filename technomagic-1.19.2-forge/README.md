# TechnoMagic modpack for Minecraft Forge 1.19.2

> [!WARNING]
> Some mods may conflict with <kbd>**OptiFine**</kbd>. Therefore, this modpack uses <kbd>**Embeddium**</kbd> and <kbd>**Oculus**</kbd> instead. For the modpack to work correctly, launch Minecraft on <kbd>**Forge**</kbd> version <kbd>**1.19.2**</kbd> without <kbd>**OptiFine**</kbd>.

## Installation

Mods in this modpack are divided into <kbd>**client-side**</kbd> and <kbd>**server-side**</kbd> for easier and faster installation. The archive with the mods can be downloaded from the [**releases**][releases].

### Client-side

If you're playing in single-player mode, you need to install only <kbd>**client-side**</kbd> mods, the archive with which can be downloaded from the [**releases**][releases]. The contents of the archive should be placed in the <kbd>**root**</kbd> folder of your launcher.

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

### Server-side

If you're playing on your own server, you'll also need to install mods on the server, the archive with which can be downloaded from the [**releases**][releases]. The contents of the archive should be placed in the <kbd>**root**</kbd> folder of your server.

Some mods are visual and do not require installation on the server, while others may cause errors. To save you from manually removing unnecessary <kbd>**client-side**</kbd> mods, I've done this for you and placed the archive with <kbd>**server-side**</kbd> mods in the [**release**][releases].

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

## Tables of modifications <kbd>**74**</kbd>

In this section, all mods included in this modpack, both <kbd>**client-side**</kbd> and <kbd>**server-side**</kbd>, are presented. The mods are organized into two tables: <kbd>**Mods**</kbd> and <kbd>**Libs**</kbd>. This provides a convenient overview of dependencies and allows for easy removal of unwanted mods and their associated libs.

Each table provides the following information:

- **`name:`** The name of the mod or lib.
- **`dependencies:`** Other mods or libs that this mod requires to function.
- **`used by:`** If it's a lib, the mods that use it are listed here.
- **`installation side:`** Indicates whether the mod is intended for the <kbd>**client-side**</kbd> or <kbd>**server-side**</kbd>.

This structure allows users to tailor the modpack to their preferences.

### Mods <kbd>**56**</kbd>

[comment]: # (For convenient reading of tables in this file, disable word wrap.)

| **name**                                                                                 | **dependencies**                                                                                                                               | **installation side** |
| ---------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------- | --------------------- |
| [**Advanced Solars Classic**][advanced-solars-classic]                                   | <kbd>[**Industrial Craft 2 Classic<br>(IC2 Classic)**][ic2-classic]</kbd>                                                                      | `client and server`   |
| [**Alex's Mobs**][alexs-mobs]                                                            | <kbd>[**Citadel**][citadel]</kbd>                                                                                                              | `client and server`   |
| [**AmbientSounds**][ambientsounds]                                                       | <kbd>[**CreativeCore**][creativecore]</kbd>                                                                                                    | `client`              |
| [**Apotheosis**][apotheosis]                                                             | <kbd>[**Patchouli**][patchouli], [**Placebo**][placebo]</kbd>                                                                                  | `client and server`   |
| [**Applied Energistics 2 (AE2)**][ae2]                                                   | <kbd>_none_</kbd>                                                                                                                              | `client and server`   |
| [**Applied Energistics 2 Things<br>(AE2 Things)**][ae2-things]                           | <kbd>[**Applied Energistics 2 (AE2)**][ae2]</kbd>                                                                                              | `client and server`   |
| [**Better Combat**][better-combat]                                                       | <kbd>[**Cloth Config API**][cloth-config-api],<br><br>[**playerAnimator**][playeranimator]</kbd>                                               | `client and server`   |
| [**Better Third Person**][better-third-person]                                           | <kbd>_none_</kbd>                                                                                                                              | `client`              |
| [**Biomes O' Plenty**][biomes-o-plenty]                                                  | <kbd>[**TerraBlender**][terrablender]</kbd>                                                                                                    | `client and server`   |
| [**Bushier Flowers**][bushier-flowers]                                                   | <kbd>_none_</kbd>                                                                                                                              | `client and server`   |
| [**Carry On**][carry-on]                                                                 | <kbd>_none_</kbd>                                                                                                                              | `client and server`   |
| [**ChoiceTheorem's<br>Overhauled Village<br>(CTOV)**][ctov]                              | <kbd>_none_</kbd>                                                                                                                              | `client and server`   |
| [**Cosmetic Armor Reworked**][cosmetic-armor-reworked]                                   | <kbd>_none_</kbd>                                                                                                                              | `client and server`   |
| [**Embeddium**][embeddium]                                                               | <kbd>_none_</kbd>                                                                                                                              | `client`              |
| [**Embeddium Extra**][embeddium-extra]                                                   | <kbd>[**Embeddium**][embeddium]</kbd>                                                                                                          | `client`              |
| [**Embeddium Extras**][embeddium-extras]                                                 | <kbd>[**Embeddium**][embeddium]</kbd>                                                                                                          | `client`              |
| [**Epic Knights: Shields,<br>Armor and Weapons<br>(Epic Knights)**][epic-knights]        | <kbd>[**Architectury API**][architectury-api],<br><br>[**Cloth Config API**][cloth-config-api]</kbd>                                           | `client and server`   |
| [**Farmer's Delight**][farmers-delight]                                                  | <kbd>_none_</kbd>                                                                                                                              | `client and server`   |
| [**First-person Model**][first-person-model]                                             | <kbd>[**Not Enough Animations**][not-enough-animations]</kbd>                                                                                  | `client`              |
| [**Gravisuit Classic**][gravisuit-classic]                                               | <kbd>[**Industrial Craft 2 Classic<br>(IC2 Classic)**][ic2-classic]</kbd>                                                                      | `client and server`   |
| [**Guard Villagers**][guard-villagers]                                                   | <kbd>_none_</kbd>                                                                                                                              | `client and server`   |
| [**HT's TreeChop**][hts-treechop]                                                        | <kbd>_none_</kbd>                                                                                                                              | `client and server`   |
| [**Ice and Fire: Dragons<br>(Ice and Fire)**][ice-and-fire]                              | <kbd>[**Citadel**][citadel]</kbd>                                                                                                              | `client and server`   |
| [**Industrial Craft 2 Classic<br>(IC2 Classic)**][ic2-classic]                           | <kbd>[**Curios API**][curios-api]</kbd>                                                                                                        | `client and server`   |
| [**Industrial Craft 2 Classic<br>UU-Matter<br>(IC2C UU-Matter)**][ic2-classic-uu-matter] | <kbd>[**Industrial Craft 2 Classic<br>(IC2 Classic)**][ic2-classic],<br><br>[**Just Enough Items (JEI)**][jei]</kbd>                           | `client and server`   |
| [**Inventory HUD+**][inventory-hud]                                                      | <kbd>_none_</kbd>                                                                                                                              | `client`              |
| [**Inventory Profiles Next (IPN)**][ipn]                                                 | <kbd>[**Kotlin**][kotlin], [**libIPN**][libipn]</kbd>                                                                                          | `client`              |
| [**Iron Chests**][iron-chests]                                                           | <kbd>_none_</kbd>                                                                                                                              | `client and server`   |
| [**Iron's Spells 'n Spellbooks<br>(Iron's Spellbooks)**][irons-spellbooks]               | <kbd>[**Caelus API**][caelus-api], [**Curios API**][curios-api],<br><br>[**GeckoLib**][geckolib], [**playerAnimator**][playeranimator]</kbd>   | `client and server`   |
| [**Item Borders**][item-borders]                                                         | <kbd>[**Iceberg**][iceberg], [**Prism**][prism]</kbd>                                                                                          | `client`              |
| [**ItemPhysic Full**][itemphysic-full]                                                   | <kbd>[**CreativeCore**][creativecore]</kbd>                                                                                                    | `client and server`   |
| [**Just Enough Items (JEI)**][jei]                                                       | <kbd>_none_</kbd>                                                                                                                              | `client and server`   |
| [**Just Enough Resources (JER)**][jer]                                                   | <kbd>[**Just Enough Items (JEI)**][jei]</kbd>                                                                                                  | `client and server`   |
| [**Legendary Tooltips**][legendary-tooltips]                                             | <kbd>[**Iceberg**][iceberg], [**Prism**][prism]</kbd>                                                                                          | `client`              |
| [**Light Overlay**][light-overlay]                                                       | <kbd>[**Architectury API**][architectury-api],<br><br>[**Cloth Config API**][cloth-config-api]</kbd>                                           | `client`              |
| [**Lootr**][lootr]                                                                       | <kbd>_none_</kbd>                                                                                                                              | `client and server`   |
| [**Model Gap Fix**][model-gap-fix]                                                       | <kbd>_none_</kbd>                                                                                                                              | `client`              |
| [**Mouse Tweaks**][mouse-tweaks]                                                         | <kbd>_none_</kbd>                                                                                                                              | `client`              |
| [**MrCrayfish's Furniture Mod<br>(CFM)**][cfm]                                           | <kbd>_none_</kbd>                                                                                                                              | `client and server`   |
| [**Not Enough Animations**][not-enough-animations]                                       | <kbd>_none_</kbd>                                                                                                                              | `client`              |
| [**Oculus**][oculus]                                                                     | <kbd>[**Embeddium**][embeddium]</kbd>                                                                                                          | `client`              |
| [**OpenBlocks Elevator<br>(Elevatorid)**][elevatorid]                                    | <kbd>_none_</kbd>                                                                                                                              | `client and server`   |
| [**Packed Up**][packed-up]                                                               | <kbd>[**SuperMartijn642's Config Lib**][supermartijn642s-config-lib],<br><br>[**SuperMartijn642's Core Lib**][supermartijn642s-core-lib]</kbd> | `client and server`   |
| [**Serene Seasons**][serene-seasons]                                                     | <kbd>_none_</kbd>                                                                                                                              | `client and server`   |
| [**Simply Swords**][simply-swords]                                                       | <kbd>[**Architectury API**][architectury-api],<br><br>[**Cloth Config API**][cloth-config-api]</kbd>                                           | `client and server`   |
| [**Skin Layers 3D**][skin-layers-3d]                                                     | <kbd>_none_</kbd>                                                                                                                              | `client`              |
| [**Spells & Shields**][spells-shields]                                                   | <kbd>_none_</kbd>                                                                                                                              | `client and server`   |
| [**TexTrue's Embeddium Options**][textrues-embeddium-options]                            | <kbd>[**Embeddium**][embeddium]</kbd>                                                                                                          | `client`              |
| [**The One Probe**][the-one-probe]                                                       | <kbd>_none_</kbd>                                                                                                                              | `client and server`   |
| [**The Twilight Forest**][the-twilight-forest]                                           | <kbd>_none_</kbd>                                                                                                                              | `client and server`   |
| [**Towns and Towers**][towns-and-towers]                                                 | <kbd>_none_</kbd>                                                                                                                              | `client and server`   |
| [**Vampirism**][vampirism]                                                               | <kbd>_none_</kbd>                                                                                                                              | `client and server`   |
| [**Werewolves**][werewolves]                                                             | <kbd>[**Vampirism**][vampirism]</kbd>                                                                                                          | `client and server`   |
| [**Xaero's Minimap**][xaeros-minimap]                                                    | <kbd>_none_</kbd>                                                                                                                              | `client and server`   |
| [**Xaero's World Map**][xaeros-world-map]                                                | <kbd>_none_</kbd>                                                                                                                              | `client and server`   |
| [**YDM's Weapon Master**][ydms-weapon-master]                                            | <kbd>_none_</kbd>                                                                                                                              | `client and server`   |

### Libs <kbd>**18**</kbd>

[comment]: # (For convenient reading of tables in this file, disable word wrap.)

| **name**                                                            | **used by**                                                                                                                                                                                                                   | **installation side** |
| ------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------- |
| [**Architectury API**][architectury-api]                            | <kbd>[**Epic Knights: Shields,<br>Armor and Weapons<br>(Epic Knights)**][epic-knights],<br><br>[**Light Overlay**][light-overlay],<br><br>[**Simply Swords**][simply-swords]</kbd>                                            | `client and server`   |
| [**Caelus API**][caelus-api]                                        | <kbd>[**Iron's Spells 'n Spellbooks<br>(Iron's Spellbooks)**][irons-spellbooks]</kbd>                                                                                                                                         | `client and server`   |
| [**Citadel**][citadel]                                              | <kbd>[**Alex's Mobs**][alexs-mobs],<br><br>[**Ice and Fire: Dragons<br>(Ice and Fire)**][ice-and-fire]</kbd>                                                                                                                  | `client and server`   |
| [**Cloth Config API**][cloth-config-api]                            | <kbd>[**Better Combat**][better-combat],<br><br>[**Epic Knights: Shields,<br>Armor and Weapons<br>(Epic Knights)**][epic-knights],<br><br>[**Light Overlay**][light-overlay],<br><br>[**Simply Swords**][simply-swords]</kbd> | `client and server`   |
| [**CreativeCore**][creativecore]                                    | <kbd>[**AmbientSounds**][ambientsounds],<br><br>[**ItemPhysic Full**][itemphysic-full]</kbd>                                                                                                                                  | `client and server`   |
| [**Curios API**][curios-api]                                        | <kbd>[**Industrial Craft 2 Classic<br>(IC2 Classic)**][ic2-classic],<br><br>[**Iron's Spells 'n Spellbooks<br>(Iron's Spellbooks)**][irons-spellbooks]</kbd>                                                                  | `client and server`   |
| [**GeckoLib**][geckolib]                                            | <kbd>[**Iron's Spells 'n Spellbooks<br>(Iron's Spellbooks)**][irons-spellbooks]</kbd>                                                                                                                                         | `client and server`   |
| [**Guide-API Village and Pillage<br>(Guide-API-VP)**][guide-api-vp] | <kbd>[**Vampirism**][vampirism],<br><br>[**Werewolves**][werewolves]</kbd>                                                                                                                                                    | `client and server`   |
| [**Iceberg**][iceberg]                                              | <kbd>[**Item Borders**][item-borders],<br><br>[**Legendary Tooltips**][legendary-tooltips]</kbd>                                                                                                                              | `client`              |
| [**Kotlin**][kotlin]                                                | <kbd>[**Inventory Profiles Next (IPN)**][ipn]</kbd>                                                                                                                                                                           | `client`              |
| [**libIPN**][libipn]                                                | <kbd>[**Inventory Profiles Next (IPN)**][ipn]</kbd>                                                                                                                                                                           | `client`              |
| [**Patchouli**][patchouli]                                          | <kbd>[**Apotheosis**][apotheosis]</kbd>                                                                                                                                                                                       | `client and server`   |
| [**Placebo**][placebo]                                              | <kbd>[**Apotheosis**][apotheosis]</kbd>                                                                                                                                                                                       | `client and server`   |
| [**playerAnimator**][playeranimator]                                | <kbd>[**Better Combat**][better-combat],<br><br>[**Iron's Spells 'n Spellbooks<br>(Iron's Spellbooks)**][irons-spellbooks]</kbd>                                                                                              | `client and server`   |
| [**Prism**][prism]                                                  | <kbd>[**Item Borders**][item-borders],<br><br>[**Legendary Tooltips**][legendary-tooltips]</kbd>                                                                                                                              | `client`              |
| [**SuperMartijn642's Config Lib**][supermartijn642s-config-lib]     | <kbd>[**Packed Up**][packed-up]</kbd>                                                                                                                                                                                         | `client and server`   |
| [**SuperMartijn642's Core Lib**][supermartijn642s-core-lib]         | <kbd>[**Packed Up**][packed-up]</kbd>                                                                                                                                                                                         | `client and server`   |
| [**TerraBlender**][terrablender]                                    | <kbd>[**Biomes O' Plenty**][biomes-o-plenty]</kbd>                                                                                                                                                                            | `client and server`   |


[advanced-solars-classic]: https://www.curseforge.com/minecraft/mc-mods/advanced-solars-classic
[alexs-mobs]: https://www.curseforge.com/minecraft/mc-mods/alexs-mobs
[ambientsounds]: https://www.curseforge.com/minecraft/mc-mods/ambientsounds
[apotheosis]: https://www.curseforge.com/minecraft/mc-mods/apotheosis
[ae2]: https://www.curseforge.com/minecraft/mc-mods/applied-energistics-2
[ae2-things]: https://www.curseforge.com/minecraft/mc-mods/ae2-things-forge
[better-combat]: https://www.curseforge.com/minecraft/mc-mods/better-combat-by-daedelus
[better-third-person]: https://www.curseforge.com/minecraft/mc-mods/better-third-person
[biomes-o-plenty]: https://www.curseforge.com/minecraft/mc-mods/biomes-o-plenty
[bushier-flowers]: https://www.curseforge.com/minecraft/mc-mods/bushier-flowers
[carry-on]: https://www.curseforge.com/minecraft/mc-mods/carry-on
[ctov]: https://www.curseforge.com/minecraft/mc-mods/choicetheorems-overhauled-village
[cosmetic-armor-reworked]: https://www.curseforge.com/minecraft/mc-mods/cosmetic-armor-reworked
[embeddium]: https://www.curseforge.com/minecraft/mc-mods/embeddium
[embeddium-extra]: https://www.curseforge.com/minecraft/mc-mods/rubidium-extra
[embeddium-extras]: https://www.curseforge.com/minecraft/mc-mods/magnesium-extras
[epic-knights]: https://www.curseforge.com/minecraft/mc-mods/epic-knights-armor-and-weapons
[farmers-delight]: https://www.curseforge.com/minecraft/mc-mods/farmers-delight
[first-person-model]: https://www.curseforge.com/minecraft/mc-mods/first-person-model
[gravisuit-classic]: https://www.curseforge.com/minecraft/mc-mods/gravisuit-classic
[guard-villagers]: https://www.curseforge.com/minecraft/mc-mods/guard-villagers
[hts-treechop]: https://www.curseforge.com/minecraft/mc-mods/treechop
[ice-and-fire]: https://www.curseforge.com/minecraft/mc-mods/ice-and-fire-dragons
[ic2-classic]: https://www.curseforge.com/minecraft/mc-mods/ic2-classic
[ic2-classic-uu-matter]: https://www.curseforge.com/minecraft/mc-mods/ic2cuumatter
[inventory-hud]: https://www.curseforge.com/minecraft/mc-mods/inventory-hud-forge
[ipn]: https://www.curseforge.com/minecraft/mc-mods/inventory-profiles-next
[iron-chests]: https://www.curseforge.com/minecraft/mc-mods/iron-chests
[irons-spellbooks]: https://www.curseforge.com/minecraft/mc-mods/irons-spells-n-spellbooks
[item-borders]: https://www.curseforge.com/minecraft/mc-mods/item-borders
[itemphysic-full]: https://www.curseforge.com/minecraft/mc-mods/itemphysic
[jei]: https://www.curseforge.com/minecraft/mc-mods/jei
[jer]: https://www.curseforge.com/minecraft/mc-mods/just-enough-resources-jer
[legendary-tooltips]: https://www.curseforge.com/minecraft/mc-mods/legendary-tooltips
[light-overlay]: https://www.curseforge.com/minecraft/mc-mods/light-overlay
[lootr]: https://www.curseforge.com/minecraft/mc-mods/lootr
[model-gap-fix]: https://www.curseforge.com/minecraft/mc-mods/model-gap-fix
[mouse-tweaks]: https://www.curseforge.com/minecraft/mc-mods/mouse-tweaks
[cfm]: https://www.curseforge.com/minecraft/mc-mods/mrcrayfish-furniture-mod
[not-enough-animations]: https://www.curseforge.com/minecraft/mc-mods/not-enough-animations
[oculus]: https://www.curseforge.com/minecraft/mc-mods/oculus
[elevatorid]: https://www.curseforge.com/minecraft/mc-mods/openblocks-elevator
[packed-up]: https://www.curseforge.com/minecraft/mc-mods/packed-up-backpacks
[serene-seasons]: https://www.curseforge.com/minecraft/mc-mods/serene-seasons
[simply-swords]: https://www.curseforge.com/minecraft/mc-mods/simply-swords
[skin-layers-3d]: https://www.curseforge.com/minecraft/mc-mods/skin-layers-3d
[spells-shields]: https://www.curseforge.com/minecraft/mc-mods/spells-shields
[textrues-embeddium-options]: https://www.curseforge.com/minecraft/mc-mods/textrues-embeddium-options
[the-one-probe]: https://www.curseforge.com/minecraft/mc-mods/the-one-probe
[the-twilight-forest]: https://www.curseforge.com/minecraft/mc-mods/the-twilight-forest
[towns-and-towers]: https://www.curseforge.com/minecraft/mc-mods/towns-and-towers
[vampirism]: https://www.curseforge.com/minecraft/mc-mods/vampirism-become-a-vampire
[werewolves]: https://www.curseforge.com/minecraft/mc-mods/werewolves-become-a-beast
[xaeros-minimap]: https://www.curseforge.com/minecraft/mc-mods/xaeros-minimap
[xaeros-world-map]: https://www.curseforge.com/minecraft/mc-mods/xaeros-world-map
[ydms-weapon-master]: https://www.curseforge.com/minecraft/mc-mods/ydms-weapon-master

[architectury-api]: https://www.curseforge.com/minecraft/mc-mods/architectury-api
[caelus-api]: https://www.curseforge.com/minecraft/mc-mods/caelus
[citadel]: https://www.curseforge.com/minecraft/mc-mods/citadel
[cloth-config-api]: https://www.curseforge.com/minecraft/mc-mods/cloth-config
[creativecore]: https://www.curseforge.com/minecraft/mc-mods/creativecore
[curios-api]: https://www.curseforge.com/minecraft/mc-mods/curios
[geckolib]: https://www.curseforge.com/minecraft/mc-mods/geckolib
[guide-api-vp]: https://www.curseforge.com/minecraft/mc-mods/guide-api-village-and-pillage
[iceberg]: https://www.curseforge.com/minecraft/mc-mods/iceberg
[kotlin]: https://www.curseforge.com/minecraft/mc-mods/kotlin-for-forge
[libipn]: https://www.curseforge.com/minecraft/mc-mods/libipn
[patchouli]: https://www.curseforge.com/minecraft/mc-mods/patchouli
[placebo]: https://www.curseforge.com/minecraft/mc-mods/placebo
[playeranimator]: https://www.curseforge.com/minecraft/mc-mods/playeranimator
[prism]: https://www.curseforge.com/minecraft/mc-mods/prism-lib
[supermartijn642s-config-lib]: https://www.curseforge.com/minecraft/mc-mods/supermartijn642s-config-lib
[supermartijn642s-core-lib]: https://www.curseforge.com/minecraft/mc-mods/supermartijn642s-core-lib
[terrablender]: https://www.curseforge.com/minecraft/mc-mods/terrablender

[releases]: https://github.com/iwdath/mc-modpacks/releases