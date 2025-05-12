# Industrial+ Modpack for Minecraft Forge 1.19.2

> [!WARNING]
> Some mods are incompatible with <kbd>**OptiFine**</kbd>. Therefore, this modpack uses <kbd>**Embeddium**</kbd> and <kbd>**Oculus**</kbd> instead. To ensure proper functionality, launch Minecraft with <kbd>**Forge**</kbd> version <kbd>**1.19.2**</kbd> without <kbd>**OptiFine**</kbd>.

## Description

**`Industrial+`** is a modpack focused on expanding **`Minecraft’s`** industrial side without changing the core feel of the game. It adds systems for automation, resource processing, and engineering, giving players more ways to progress and optimize how they play.

The selection of mods is aimed at keeping things structured and approachable. Whether you're already familiar with tech mods or just getting into them, everything is arranged to make the experience smooth. Visual tweaks, performance improvements, and a few helpful additions are included to make gameplay more consistent and enjoyable.

If you're into building factories, automating production chains, or simply want more depth without breaking the vanilla atmosphere, **`Industrial+`** is made for that.

## Installation

This modpack is structured into separate <kbd>**client-side**</kbd> and <kbd>**server-side**</kbd> archives to simplify installation and prevent compatibility issues. Some mods are purely visual and should not be installed on a server, while others may cause errors. To avoid manual sorting, the necessary mods for both the client and server have been pre-sorted and can be downloaded from the [**releases**][releases].

### Client Side

If you're playing in single-player mode, you only need to install <kbd>**client-side**</kbd> mods:

1. Ensure the correct version of `Minecraft` <kbd>**Forge**</kbd> is installed. If not, download the [**installer**][forge], run it, and select the <kbd>**Install Client**</kbd> option.
2. Download the <kbd>**client-side**</kbd> [**modpack**][releases] and extract it to your game directory:
   - **`Windows:`** <kbd>**%appdata%\\.minecraft\\**</kbd>
   - **`macOS:`** <kbd>**~/Library/Application Support/minecraft/**</kbd>
   - **`Linux:`** <kbd>**~/.minecraft/**</kbd>
3. Open the `Minecraft` launcher, select the <kbd>**Forge**</kbd> profile, and click <kbd>**Play**</kbd>.

<kbd>**Client-side**</kbd> mods, divided into <kbd>**mods**</kbd> and <kbd>**libs**</kbd>, are located in this repository at the following path:

```swift
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

If you're running your own server, you also need to install <kbd>**server-side**</kbd> mods:

1. Ensure the correct version of `Minecraft` <kbd>**Forge**</kbd> is installed on your server. If not, download the [**installer**][forge], run it, and select the <kbd>**Install Server**</kbd> option.
2. Download the <kbd>**server-side**</kbd> [**modpack**][releases] and extract it to the server's root directory, where <kbd>**server.jar**</kbd> and other core files are located.
3. Start the server and make sure it runs without errors and all mods load correctly.

<kbd>**Server-side**</kbd> mods, divided into <kbd>**mods**</kbd> and <kbd>**libs**</kbd>, are located in this repository at the following path:

```swift
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

## Tables of Components <kbd>**166 + 14**</kbd>

This section presents all components included in this modpack: <kbd>**141 [mods](#mods-141)**</kbd>, <kbd>**25 [libs](#libs-25)**</kbd>, and <kbd>**14 [resource packs](#resource-packs-14)**</kbd>. The components are organized into three tables for better clarity and easier customization.

Each table provides the following information:

- **`name:`** The name of the <kbd>**mod**</kbd>, <kbd>**lib**</kbd>, or <kbd>**resource pack**</kbd>.
- **`dependencies:`** Other components required for proper functionality (if applicable).
- **`used by:`** If it's a <kbd>**lib**</kbd>, this column lists the <kbd>**mods**</kbd> that depend on it.
- **`installation side:`** Indicates if the component is for <kbd>**client-side**</kbd>, <kbd>**server-side**</kbd>, or both.

This structure helps users tailor the modpack to their needs by clearly showing dependencies and letting them skip components they don’t need.

### Mods <kbd>**141**</kbd>

<!-- To properly display the tables, disable word wrap in your editor -->
| **name**                                                                                   | **dependencies**                                                                                                                                     | **installation side** |
| ------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------- |
| [**A Good Place**][a-good-place]                                                           | <kbd>_none_</kbd>                                                                                                                                    | `client`              |
| [**Additional Placements**][additional-placements]                                         | <kbd>_none_</kbd>                                                                                                                                    | `client and server`   |
| [**Advanced Solars Classic**][advanced-solars-classic]                                     | <kbd>[**Industrial Craft 2 Classic<br>(IC2 Classic)**][ic2-classic]</kbd>                                                                            | `client and server`   |
| [**Advancement Plaques**][advancement-plaques]                                             | <kbd>[**Iceberg**][iceberg]</kbd>                                                                                                                    | `client and server`   |
| [**Alex's Caves**][alexs-caves]                                                            | <kbd>[**Citadel**][citadel]</kbd>                                                                                                                    | `client and server`   |
| [**Alex's Mobs**][alexs-mobs]                                                              | <kbd>[**Citadel**][citadel]</kbd>                                                                                                                    | `client and server`   |
| [**AmbientSounds**][ambientsounds]                                                         | <kbd>[**CreativeCore**][creativecore]</kbd>                                                                                                          | `client`              |
| [**AppleSkin**][appleskin]                                                                 | <kbd>_none_</kbd>                                                                                                                                    | `client and server`   |
| [**Applied Energistics 2 (AE2)**][ae2]                                                     | <kbd>_none_</kbd>                                                                                                                                    | `client and server`   |
| [**Applied Energistics 2 Things<br>(AE2 Things)**][ae2-things]                             | <kbd>[**Applied Energistics 2 (AE2)**][ae2]</kbd>                                                                                                    | `client and server`   |
| [**Auditory**][auditory]                                                                   | <kbd>_none_</kbd>                                                                                                                                    | `client and server`   |
| [**Berry Good**][berry-good]                                                               | <kbd>[**Blueprint**][blueprint]</kbd>                                                                                                                | `client and server`   |
| [**Better Advancements**][better-advancements]                                             | <kbd>_none_</kbd>                                                                                                                                    | `client`              |
| [**Better Combat**][better-combat]                                                         | <kbd>[**Cloth Config API**][cloth-config-api]</kbd><br><kbd>[**playerAnimator**][playeranimator]</kbd>                                               | `client and server`   |
| [**Better FPS - Render Distance**][better-fps-render-distance]                             | <kbd>[**Cupboard**][cupboard]</kbd>                                                                                                                  | `client`              |
| [**Better Safe Bed**][better-safe-bed]                                                     | <kbd>_none_</kbd>                                                                                                                                    | `client and server`   |
| [**Better Statistics Screen (BSS)**][bss]                                                  | <kbd>_none_</kbd>                                                                                                                                    | `client and server`   |
| [**Better Third Person**][better-third-person]                                             | <kbd>_none_</kbd>                                                                                                                                    | `client`              |
| [**BetterF3**][betterf3]                                                                   | <kbd>[**Cloth Config API**][cloth-config-api]</kbd>                                                                                                  | `client`              |
| [**Biomes O' Plenty**][biomes-o-plenty]                                                    | <kbd>[**TerraBlender**][terrablender]</kbd>                                                                                                          | `client and server`   |
| [**Boat Item View**][boat-item-view]                                                       | <kbd>_none_</kbd>                                                                                                                                    | `client`              |
| [**Build Guide**][build-guide]                                                             | <kbd>_none_</kbd>                                                                                                                                    | `client`              |
| [**Bushier Flowers**][bushier-flowers]                                                     | <kbd>_none_</kbd>                                                                                                                                    | `client and server`   |
| [**CameraOverhaul**][cameraoverhaul]                                                       | <kbd>[**Cloth Config API**][cloth-config-api]</kbd>                                                                                                  | `client`              |
| [**Carry On**][carry-on]                                                                   | <kbd>_none_</kbd>                                                                                                                                    | `client and server`   |
| [**Catalogue**][catalogue]                                                                 | <kbd>_none_</kbd>                                                                                                                                    | `client`              |
| [**Chat Heads**][chat-heads]                                                               | <kbd>[**Cloth Config API**][cloth-config-api]</kbd>                                                                                                  | `client`              |
| [**Cherished Worlds**][cherished-worlds]                                                   | <kbd>_none_</kbd>                                                                                                                                    | `client`              |
| [**Chest Search Bar**][chest-search-bar]                                                   | <kbd>_none_</kbd>                                                                                                                                    | `client`              |
| [**ChoiceTheorem's Overhauled<br>Village (CTOV)**][ctov]                                   | <kbd>_none_</kbd>                                                                                                                                    | `client and server`   |
| [**Configured**][configured]                                                               | <kbd>_none_</kbd>                                                                                                                                    | `client`              |
| [**Controlling**][controlling]                                                             | <kbd>_none_</kbd>                                                                                                                                    | `client`              |
| [**Corpse**][corpse]                                                                       | <kbd>_none_</kbd>                                                                                                                                    | `client and server`   |
| [**Cosmetic Armor Reworked**][cosmetic-armor-reworked]                                     | <kbd>_none_</kbd>                                                                                                                                    | `client and server`   |
| [**Curious Lanterns**][curious-lanterns]                                                   | <kbd>[**Radiant Gear**][radiant-gear]</kbd> <kbd>[**Curios API**][curios-api]</kbd>                                                                  | `client and server`   |
| [**Dark Mode Everywhere**][dark-mode-everywhere]                                           | <kbd>_none_</kbd>                                                                                                                                    | `client`              |
| [**Debugify**][debugify]                                                                   | <kbd>[**Cloth Config API**][cloth-config-api]</kbd>                                                                                                  | `client and server`   |
| [**Deeper and Darker**][deeper-and-darker]                                                 | <kbd>_none_</kbd>                                                                                                                                    | `client and server`   |
| [**Dont Clear Chat History**][dont-clear-chat-history]                                     | <kbd>_none_</kbd>                                                                                                                                    | `client`              |
| [**Dynamic Music Updated**][dynamic-music-updated]                                         | <kbd>[**Architectury API**][architectury-api]</kbd><br><kbd>[**Cloth Config API**][cloth-config-api]</kbd>                                           | `client`              |
| [**Easy Anvils**][easy-anvils]                                                             | <kbd>[**Puzzles Lib**][puzzles-lib]</kbd>                                                                                                            | `client and server`   |
| [**Easy Magic**][easy-magic]                                                               | <kbd>[**Puzzles Lib**][puzzles-lib]</kbd>                                                                                                            | `client and server`   |
| [**Eating Animation**][eating-animation]                                                   | <kbd>_none_</kbd>                                                                                                                                    | `client`              |
| [**Effective**][effective]                                                                 | <kbd>_none_</kbd>                                                                                                                                    | `client`              |
| [**Embeddium**][embeddium]                                                                 | <kbd>_none_</kbd>                                                                                                                                    | `client`              |
| [**Embeddium Dynamic Lights**][embeddium-dynamic-lights]                                   | <kbd>[**Embeddium**][embeddium]</kbd>                                                                                                                | `client`              |
| [**Embeddium Extra**][embeddium-extra]                                                     | <kbd>[**Embeddium**][embeddium]</kbd>                                                                                                                | `client`              |
| [**Embeddium Extras**][embeddium-extras]                                                   | <kbd>[**Embeddium**][embeddium]</kbd>                                                                                                                | `client`              |
| [**Entity Culling**][entity-culling]                                                       | <kbd>_none_</kbd>                                                                                                                                    | `client`              |
| [**Extra Sounds Next**][extra-sounds-next]                                                 | <kbd>_none_</kbd>                                                                                                                                    | `client`              |
| [**Farmer's Delight**][farmers-delight]                                                    | <kbd>_none_</kbd>                                                                                                                                    | `client and server`   |
| [**Fast IP Ping**][fast-ip-ping]                                                           | <kbd>_none_</kbd>                                                                                                                                    | `client`              |
| [**FastBoot**][fastboot]                                                                   | <kbd>_none_</kbd>                                                                                                                                    | `client`              |
| [**FastQuit**][fastquit]                                                                   | <kbd>_none_</kbd>                                                                                                                                    | `client`              |
| [**FerriteCore**][ferritecore]                                                             | <kbd>_none_</kbd>                                                                                                                                    | `client and server`   |
| [**First-person Model**][first-person-model]                                               | <kbd>[**Not Enough Animations**][not-enough-animations]</kbd>                                                                                        | `client`              |
| [**Footprint Particle**][footprint-particle]                                               | <kbd>[**Architectury API**][architectury-api]</kbd><br><kbd>[**Cloth Config API**][cloth-config-api]</kbd>                                           | `client and server`   |
| [**Forgematica**][forgematica]                                                             | <kbd>[**MaFgLib**][mafglib]</kbd>                                                                                                                    | `client`              |
| [**Forgery**][forgery]                                                                     | <kbd>_none_</kbd>                                                                                                                                    | `client and server`   |
| [**ForgetMeChunk**][forgetmechunk]                                                         | <kbd>_none_</kbd>                                                                                                                                    | `client`              |
| [**FPS Reducer**][fps-reducer]                                                             | <kbd>_none_</kbd>                                                                                                                                    | `client`              |
| [**GPU Memory Leak Fix**][gpu-memory-leak-fix]                                             | <kbd>_none_</kbd>                                                                                                                                    | `client`              |
| [**Gravisuit Classic**][gravisuit-classic]                                                 | <kbd>[**Industrial Craft 2 Classic<br>(IC2 Classic)**][ic2-classic]</kbd>                                                                            | `client and server`   |
| [**Held Item Tooltips**][held-item-tooltips]                                               | <kbd>[**Puzzles Lib**][puzzles-lib]</kbd>                                                                                                            | `client`              |
| [**HT's TreeChop**][hts-treechop]                                                          | <kbd>_none_</kbd>                                                                                                                                    | `client and server`   |
| [**ImmediatelyFast**][immediatelyfast]                                                     | <kbd>_none_</kbd>                                                                                                                                    | `client`              |
| [**Industrial Craft 2 Classic<br>(IC2 Classic)**][ic2-classic]                             | <kbd>[**Curios API**][curios-api]</kbd>                                                                                                              | `client and server`   |
| [**Industrial Craft 2 Classic:<br>Jade Addon (IC2C: Jade Addon)**][ic2-classic-jade-addon] | <kbd>[**Industrial Craft 2 Classic<br>(IC2 Classic)**][ic2-classic]</kbd><br><kbd>[**Jade**][jade]</kbd>                                             | `client and server`   |
| [**Industrial Craft 2 Classic<br>UU-Matter (IC2C UU-Matter)**][ic2-classic-uu-matter]      | <kbd>[**Industrial Craft 2 Classic<br>(IC2 Classic)**][ic2-classic]</kbd><br><kbd>[**Just Enough Items (JEI)**][jei]</kbd>                           | `client and server`   |
| [**Inventory HUD+**][inventory-hud]                                                        | <kbd>_none_</kbd>                                                                                                                                    | `client`              |
| [**Inventory Profiles Next (IPN)**][ipn]                                                   | <kbd>[**Kotlin**][kotlin]</kbd> <kbd>[**libIPN**][libipn]</kbd>                                                                                      | `client`              |
| [**Iron Chests**][iron-chests]                                                             | <kbd>_none_</kbd>                                                                                                                                    | `client and server`   |
| [**Item Borders**][item-borders]                                                           | <kbd>[**Iceberg**][iceberg]</kbd> <kbd>[**Prism**][prism]</kbd>                                                                                      | `client`              |
| [**Item Highlighter**][item-highlighter]                                                   | <kbd>_none_</kbd>                                                                                                                                    | `client`              |
| [**Jade**][jade]                                                                           | <kbd>_none_</kbd>                                                                                                                                    | `client and server`   |
| [**Jade Addons**][jade-addons]                                                             | <kbd>[**Jade**][jade]</kbd>                                                                                                                          | `client and server`   |
| [**Just Enough Items (JEI)**][jei]                                                         | <kbd>_none_</kbd>                                                                                                                                    | `client and server`   |
| [**Just Enough Resources (JER)**][jer]                                                     | <kbd>[**Just Enough Items (JEI)**][jei]</kbd>                                                                                                        | `client and server`   |
| [**Krypton**][krypton]                                                                     | <kbd>_none_</kbd>                                                                                                                                    | `client and server`   |
| [**Lazy DataFixerUpper (LazyDFU)**][lazydfu]                                               | <kbd>_none_</kbd>                                                                                                                                    | `client`              |
| [**Light Overlay**][light-overlay]                                                         | <kbd>[**Architectury API**][architectury-api]</kbd><br><kbd>[**Cloth Config API**][cloth-config-api]</kbd>                                           | `client`              |
| [**Lootr**][lootr]                                                                         | <kbd>_none_</kbd>                                                                                                                                    | `client and server`   |
| [**Memory Leak Fix**][memory-leak-fix]                                                     | <kbd>_none_</kbd>                                                                                                                                    | `client and server`   |
| [**Model Gap Fix**][model-gap-fix]                                                         | <kbd>_none_</kbd>                                                                                                                                    | `client`              |
| [**ModernFix**][modernfix]                                                                 | <kbd>_none_</kbd>                                                                                                                                    | `client and server`   |
| [**More Chat History**][more-chat-history]                                                 | <kbd>_none_</kbd>                                                                                                                                    | `client`              |
| [**More Mob Variants**][more-mob-variants]                                                 | <kbd>_none_</kbd>                                                                                                                                    | `client and server`   |
| [**Mouse Tweaks**][mouse-tweaks]                                                           | <kbd>_none_</kbd>                                                                                                                                    | `client`              |
| [**Neapolitan**][neapolitan]                                                               | <kbd>[**Blueprint**][blueprint]</kbd>                                                                                                                | `client and server`   |
| [**Neko's Enchanted Books**][nekos-enchanted-books]                                        | <kbd>_none_</kbd>                                                                                                                                    | `client`              |
| [**No Chat Reports**][no-chat-reports]                                                     | <kbd>_none_</kbd>                                                                                                                                    | `client`              |
| [**Not Enough Animations**][not-enough-animations]                                         | <kbd>_none_</kbd>                                                                                                                                    | `client`              |
| [**Not Enough Recipe Book (NERB)**][nerb]                                                  | <kbd>_none_</kbd>                                                                                                                                    | `client and server`   |
| [**Obscure Tooltips**][obscure-tooltips]                                                   | <kbd>[**Obscure API**][obscure-api]</kbd>                                                                                                            | `client`              |
| [**Oculus**][oculus]                                                                       | <kbd>[**Embeddium**][embeddium]</kbd>                                                                                                                | `client`              |
| [**Oh The Biomes You'll Go (BYG)**][byg]                                                   | <kbd>[**CorgiLib**][corgilib]</kbd> <kbd>[**GeckoLib**][geckolib]</kbd><br><kbd>[**TerraBlender**][terrablender]</kbd>                               | `client and server`   |
| [**OpenBlocks Elevator (Elevatorid)**][elevatorid]                                         | <kbd>_none_</kbd>                                                                                                                                    | `client and server`   |
| [**Packed Up**][packed-up]                                                                 | <kbd>[**SuperMartijn642's Config Lib**][supermartijn642s-config-lib]</kbd><br><kbd>[**SuperMartijn642's Core Lib**][supermartijn642s-core-lib]</kbd> | `client and server`   |
| [**Packet Fixer**][packet-fixer]                                                           | <kbd>_none_</kbd>                                                                                                                                    | `client and server`   |
| [**Plasmo Voice (PV)**][pv]                                                                | <kbd>_none_</kbd>                                                                                                                                    | `client and server`   |
| [**Polymorph**][polymorph]                                                                 | <kbd>_none_</kbd>                                                                                                                                    | `client and server`   |
| [**Presence Footsteps**][presence-footsteps]                                               | <kbd>_none_</kbd>                                                                                                                                    | `client`              |
| [**PV Addon Groups**][pv-addon-groups]                                                     | <kbd>[**Plasmo Voice (PV)**][pv]</kbd>                                                                                                               | `client and server`   |
| [**PV Addon Sculk**][pv-addon-sculk]                                                       | <kbd>[**Plasmo Voice (PV)**][pv]</kbd>                                                                                                               | `client and server`   |
| [**PV Addon Sound Physics**][pv-addon-sound-physics]                                       | <kbd>[**Plasmo Voice (PV)**][pv]</kbd>                                                                                                               | `client`              |
| [**Quark**][quark]                                                                         | <kbd>[**AutoRegLib**][autoreglib]</kbd>                                                                                                              | `client and server`   |
| [**Radiant Gear**][radiant-gear]                                                           | <kbd>[**Curios API**][curios-api]</kbd>                                                                                                              | `client and server`   |
| [**Realm RPG: Fallen Adventurers**][realm-rpg-fallen-adventurers]                          | <kbd>_none_</kbd>                                                                                                                                    | `client and server`   |
| [**Remove Reloading Screen (RRlS)**][rrls]                                                 | <kbd>[**Cloth Config API**][cloth-config-api]</kbd>                                                                                                  | `client`              |
| [**Remove Terralith Intro Message**][remove-terralith-intro-message]                       | <kbd>[**Terralith**][terralith]</kbd>                                                                                                                | `client`              |
| [**Screenshot to Clipboard**][screenshot-to-clipboard]                                     | <kbd>_none_</kbd>                                                                                                                                    | `client`              |
| [**Screenshot Viewer**][screenshot-viewer]                                                 | <kbd>_none_</kbd>                                                                                                                                    | `client`              |
| [**Seamless Loading Screen**][seamless-loading-screen]                                     | <kbd>_none_</kbd>                                                                                                                                    | `client`              |
| [**Serene Seasons**][serene-seasons]                                                       | <kbd>_none_</kbd>                                                                                                                                    | `client and server`   |
| [**Simply Light**][simply-light]                                                           | <kbd>_none_</kbd>                                                                                                                                    | `client and server`   |
| [**Skin Layers 3D**][skin-layers-3d]                                                       | <kbd>_none_</kbd>                                                                                                                                    | `client`              |
| [**Smooth Swapping**][smooth-swapping]                                                     | <kbd>_none_</kbd>                                                                                                                                    | `client`              |
| [**Sound Physics Remastered**][sound-physics-remastered]                                   | <kbd>_none_</kbd>                                                                                                                                    | `client`              |
| [**Starlight**][starlight]                                                                 | <kbd>_none_</kbd>                                                                                                                                    | `client and server`   |
| [**Structory**][structory]                                                                 | <kbd>_none_</kbd>                                                                                                                                    | `client and server`   |
| [**Terralith**][terralith]                                                                 | <kbd>_none_</kbd>                                                                                                                                    | `client and server`   |
| [**TexTrue's Embeddium Options**][textrues-embeddium-options]                              | <kbd>[**Embeddium**][embeddium]</kbd>                                                                                                                | `client`              |
| [**Tiny Item Animations (TIA)**][tia]                                                      | <kbd>_none_</kbd>                                                                                                                                    | `client`              |
| [**Towns and Towers**][towns-and-towers]                                                   | <kbd>_none_</kbd>                                                                                                                                    | `client and server`   |
| [**Visual Workbench**][visual-workbench]                                                   | <kbd>[**Puzzles Lib**][puzzles-lib]</kbd>                                                                                                            | `client and server`   |
| [**Wall-Jump TXF**][wall-jump-txf]                                                         | <kbd>_none_</kbd>                                                                                                                                    | `client and server`   |
| [**What Are They Up To (WATUT)**][watut]                                                   | <kbd>[**CoroUtil**][coroutil]</kbd>                                                                                                                  | `client and server`   |
| [**World Play Time**][world-play-time]                                                     | <kbd>_none_</kbd>                                                                                                                                    | `client`              |
| [**Xaero's Minimap**][xaeros-minimap]                                                      | <kbd>_none_</kbd>                                                                                                                                    | `client and server`   |
| [**Xaero's World Map**][xaeros-world-map]                                                  | <kbd>_none_</kbd>                                                                                                                                    | `client and server`   |
| [**YUNG's Better Desert Temples**][yungs-better-desert-temples]                            | <kbd>[**YUNG's API**][yungs-api]</kbd>                                                                                                               | `client and server`   |
| [**YUNG's Better Dungeons**][yungs-better-dungeons]                                        | <kbd>[**YUNG's API**][yungs-api]</kbd>                                                                                                               | `client and server`   |
| [**YUNG's Better End Island**][yungs-better-end-island]                                    | <kbd>[**YUNG's API**][yungs-api]</kbd>                                                                                                               | `client and server`   |
| [**YUNG's Better Jungle Temples**][yungs-better-jungle-temples]                            | <kbd>[**YUNG's API**][yungs-api]</kbd>                                                                                                               | `client and server`   |
| [**YUNG's Better Mineshafts**][yungs-better-mineshafts]                                    | <kbd>[**YUNG's API**][yungs-api]</kbd>                                                                                                               | `client and server`   |
| [**YUNG's Better Nether Fortresses**][yungs-better-nether-fortresses]                      | <kbd>[**YUNG's API**][yungs-api]</kbd>                                                                                                               | `client and server`   |
| [**YUNG's Better Ocean Monuments**][yungs-better-ocean-monuments]                          | <kbd>[**YUNG's API**][yungs-api]</kbd>                                                                                                               | `client and server`   |
| [**YUNG's Better Strongholds**][yungs-better-strongholds]                                  | <kbd>[**YUNG's API**][yungs-api]</kbd>                                                                                                               | `client and server`   |
| [**YUNG's Better Witch Huts**][yungs-better-witch-huts]                                    | <kbd>[**YUNG's API**][yungs-api]</kbd>                                                                                                               | `client and server`   |
| [**YUNG's Bridges**][yungs-bridges]                                                        | <kbd>[**YUNG's API**][yungs-api]</kbd>                                                                                                               | `client and server`   |
| [**YUNG's Extras**][yungs-extras]                                                          | <kbd>[**YUNG's API**][yungs-api]</kbd>                                                                                                               | `client and server`   |

### Libs <kbd>**25**</kbd>

<!-- To properly display the tables, disable word wrap in your editor -->
| **name**                                                        | **used by**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | **installation side** |
| --------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------- |
| [**Architectury API**][architectury-api]                        | <kbd>[**Dynamic Music Updated**][dynamic-music-updated]</kbd><br><kbd>[**Footprint Particle**][footprint-particle]</kbd> <kbd>[**Light Overlay**][light-overlay]</kbd>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | `client and server`   |
| [**AutoRegLib**][autoreglib]                                    | <kbd>[**Quark**][quark]</kbd>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | `client and server`   |
| [**Blueprint**][blueprint]                                      | <kbd>[**Berry Good**][berry-good]</kbd> <kbd>[**Neapolitan**][neapolitan]</kbd>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | `client and server`   |
| [**Citadel**][citadel]                                          | <kbd>[**Alex's Caves**][alexs-caves]</kbd> <kbd>[**Alex's Mobs**][alexs-mobs]</kbd>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | `client and server`   |
| [**Cloth Config API**][cloth-config-api]                        | <kbd>[**Better Combat**][better-combat]</kbd> <kbd>[**BetterF3**][betterf3]</kbd><br><kbd>[**CameraOverhaul**][cameraoverhaul]</kbd> <kbd>[**Chat Heads**][chat-heads]</kbd><br><kbd>[**Debugify**][debugify]</kbd> <kbd>[**Dynamic Music Updated**][dynamic-music-updated]</kbd><br><kbd>[**Footprint Particle**][footprint-particle]</kbd> <kbd>[**Light Overlay**][light-overlay]</kbd><br><kbd>[**Remove Reloading Screen (RRlS)**][rrls]</kbd>                                                                                                                                                                                                                                                                                                                                     | `client and server`   |
| [**CorgiLib**][corgilib]                                        | <kbd>[**Oh The Biomes You'll Go (BYG)**][byg]</kbd>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | `client and server`   |
| [**CoroUtil**][coroutil]                                        | <kbd>[**What Are They Up To (WATUT)**][watut]</kbd>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | `client and server`   |
| [**CreativeCore**][creativecore]                                | <kbd>[**AmbientSounds**][ambientsounds]</kbd>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | `client`              |
| [**Cupboard**][cupboard]                                        | <kbd>[**Better FPS - Render Distance**][better-fps-render-distance]</kbd>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | `client`              |
| [**Curios API**][curios-api]                                    | <kbd>[**Curious Lanterns**][curious-lanterns]</kbd><br><kbd>[**Industrial Craft 2 Classic<br>(IC2 Classic)**][ic2-classic]</kbd><br><kbd>[**Radiant Gear**][radiant-gear]</kbd>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | `client and server`   |
| [**Entity Model Features (EMF)**][emf]                          | <kbd>[**Fresh Moves**][fresh-moves]</kbd>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | `client`              |
| [**Entity Texture Features (ETF)**][etf]                        | <kbd>[**Fresh Moves**][fresh-moves]</kbd>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | `client`              |
| [**GeckoLib**][geckolib]                                        | <kbd>[**Oh The Biomes You'll Go (BYG)**][byg]</kbd>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | `client and server`   |
| [**Iceberg**][iceberg]                                          | <kbd>[**Advancement Plaques**][advancement-plaques]</kbd> <kbd>[**Item Borders**][item-borders]</kbd>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | `client and server`   |
| [**Kotlin**][kotlin]                                            | <kbd>[**Inventory Profiles Next (IPN)**][ipn]</kbd>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | `client`              |
| [**libIPN**][libipn]                                            | <kbd>[**Inventory Profiles Next (IPN)**][ipn]</kbd>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | `client`              |
| [**MaFgLib**][mafglib]                                          | <kbd>[**Forgematica**][forgematica]</kbd>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | `client`              |
| [**Obscure API**][obscure-api]                                  | <kbd>[**Obscure Tooltips**][obscure-tooltips]</kbd>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | `client and server`   |
| [**playerAnimator**][playeranimator]                            | <kbd>[**Better Combat**][better-combat]</kbd>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | `client and server`   |
| [**Prism**][prism]                                              | <kbd>[**Item Borders**][item-borders]</kbd>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | `client`              |
| [**Puzzles Lib**][puzzles-lib]                                  | <kbd>[**Easy Anvils**][easy-anvils]</kbd> <kbd>[**Easy Magic**][easy-magic]</kbd><br><kbd>[**Held Item Tooltips**][held-item-tooltips]</kbd><br><kbd>[**Visual Workbench**][visual-workbench]</kbd>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | `client and server`   |
| [**SuperMartijn642's Config Lib**][supermartijn642s-config-lib] | <kbd>[**Packed Up**][packed-up]</kbd>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | `client and server`   |
| [**SuperMartijn642's Core Lib**][supermartijn642s-core-lib]     | <kbd>[**Packed Up**][packed-up]</kbd>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | `client and server`   |
| [**TerraBlender**][terrablender]                                | <kbd>[**Biomes O' Plenty**][biomes-o-plenty]</kbd><br><kbd>[**Oh The Biomes You'll Go (BYG)**][byg]</kbd>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | `client and server`   |
| [**YUNG's API**][yungs-api]                                     | <kbd>[**YUNG's Better Desert Temples**][yungs-better-desert-temples]</kbd><br><kbd>[**YUNG's Better Dungeons**][yungs-better-dungeons]</kbd><br><kbd>[**YUNG's Better End Island**][yungs-better-end-island]</kbd><br><kbd>[**YUNG's Better Jungle Temples**][yungs-better-jungle-temples]</kbd><br><kbd>[**YUNG's Better Mineshafts**][yungs-better-mineshafts]</kbd><br><kbd>[**YUNG's Better Nether Fortresses**][yungs-better-nether-fortresses]</kbd><br><kbd>[**YUNG's Better Ocean Monuments**][yungs-better-ocean-monuments]</kbd><br><kbd>[**YUNG's Better Strongholds**][yungs-better-strongholds]</kbd><br><kbd>[**YUNG's Better Witch Huts**][yungs-better-witch-huts]</kbd><br><kbd>[**YUNG's Bridges**][yungs-bridges]</kbd> <kbd>[**YUNG's Extras**][yungs-extras]</kbd> | `client and server`   |

### Resource Packs <kbd>**14**</kbd>

<!-- To properly display the tables, disable word wrap in your editor -->
| **name**                                                 | **dependencies**                                                                                         |
| -------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- |
| [**(VT) Lower Shield**][vt]                              | <kbd>_none_</kbd>                                                                                        |
| [**(VT) Shorter Grass**][vt]                             | <kbd>_none_</kbd>                                                                                        |
| [**(VT) Smaller Crosshair**][vt]                         | <kbd>_none_</kbd>                                                                                        |
| [**(VT) Unobtrusive Rain**][vt]                          | <kbd>_none_</kbd>                                                                                        |
| [**(VT) Unobtrusive Snow**][vt]                          | <kbd>_none_</kbd>                                                                                        |
| [**(VT) Variated Bookshelves**][vt]                      | <kbd>_none_</kbd>                                                                                        |
| [**(VT) Variated Bricks**][vt]                           | <kbd>_none_</kbd>                                                                                        |
| [**(VT) Variated Dirt**][vt]                             | <kbd>_none_</kbd>                                                                                        |
| [**Fancy Crops**][fancy-crops]                           | <kbd>_none_</kbd>                                                                                        |
| [**Fresh Moves**][fresh-moves]                           | <kbd>[**Entity Model Features (EMF)**][emf]</kbd><br><kbd>[**Entity Texture Features (ETF)**][etf]</kbd> |
| [**Ore Variants**][ore-variants]                         | <kbd>_none_</kbd>                                                                                        |
| [**Simple Grass Flowers**][simple-grass-flowers]         | <kbd>_none_</kbd>                                                                                        |
| [**Simple Lower Grass Sides**][simple-lower-grass-sides] | <kbd>_none_</kbd>                                                                                        |
| [**Spring Flowers**][spring-flowers]                     | <kbd>_none_</kbd>                                                                                        |

<!-- Links to mods used in the modpack -->
[a-good-place]: https://www.curseforge.com/minecraft/mc-mods/a-good-place
[additional-placements]: https://www.curseforge.com/minecraft/mc-mods/additional-placements
[advanced-solars-classic]: https://www.curseforge.com/minecraft/mc-mods/advanced-solars-classic
[advancement-plaques]: https://www.curseforge.com/minecraft/mc-mods/advancement-plaques
[alexs-caves]: https://www.curseforge.com/minecraft/mc-mods/alexs-caves
[alexs-mobs]: https://www.curseforge.com/minecraft/mc-mods/alexs-mobs
[ambientsounds]: https://www.curseforge.com/minecraft/mc-mods/ambientsounds
[appleskin]: https://www.curseforge.com/minecraft/mc-mods/appleskin
[ae2]: https://www.curseforge.com/minecraft/mc-mods/applied-energistics-2
[ae2-things]: https://www.curseforge.com/minecraft/mc-mods/ae2-things-forge
[auditory]: https://www.curseforge.com/minecraft/mc-mods/auditory
[berry-good]: https://www.curseforge.com/minecraft/mc-mods/berry-good
[better-advancements]: https://www.curseforge.com/minecraft/mc-mods/better-advancements
[better-combat]: https://www.curseforge.com/minecraft/mc-mods/better-combat-by-daedelus
[better-fps-render-distance]: https://www.curseforge.com/minecraft/mc-mods/better-fps-render-distance
[better-safe-bed]: https://www.curseforge.com/minecraft/mc-mods/better-safe-bed
[bss]: https://www.curseforge.com/minecraft/mc-mods/better-stats
[better-third-person]: https://www.curseforge.com/minecraft/mc-mods/better-third-person
[betterf3]: https://www.curseforge.com/minecraft/mc-mods/betterf3
[biomes-o-plenty]: https://www.curseforge.com/minecraft/mc-mods/biomes-o-plenty
[boat-item-view]: https://www.curseforge.com/minecraft/mc-mods/boat-item-view-forge
[build-guide]: https://www.curseforge.com/minecraft/mc-mods/build-guide
[bushier-flowers]: https://www.curseforge.com/minecraft/mc-mods/bushier-flowers
[cameraoverhaul]: https://www.curseforge.com/minecraft/mc-mods/cameraoverhaul
[carry-on]: https://www.curseforge.com/minecraft/mc-mods/carry-on
[catalogue]: https://www.curseforge.com/minecraft/mc-mods/catalogue
[chat-heads]: https://www.curseforge.com/minecraft/mc-mods/chat-heads
[cherished-worlds]: https://www.curseforge.com/minecraft/mc-mods/cherished-worlds
[chest-search-bar]: https://www.curseforge.com/minecraft/mc-mods/chest-search-bar
[ctov]: https://www.curseforge.com/minecraft/mc-mods/choicetheorems-overhauled-village
[configured]: https://www.curseforge.com/minecraft/mc-mods/configured
[controlling]: https://www.curseforge.com/minecraft/mc-mods/controlling
[corpse]: https://www.curseforge.com/minecraft/mc-mods/corpse
[cosmetic-armor-reworked]: https://www.curseforge.com/minecraft/mc-mods/cosmetic-armor-reworked
[curious-lanterns]: https://www.curseforge.com/minecraft/mc-mods/curious-lanterns
[dark-mode-everywhere]: https://www.curseforge.com/minecraft/mc-mods/dark-mode-everywhere
[debugify]: https://www.curseforge.com/minecraft/mc-mods/debugify-reforged
[deeper-and-darker]: https://www.curseforge.com/minecraft/mc-mods/deeperdarker
[dont-clear-chat-history]: https://www.curseforge.com/minecraft/mc-mods/dont-clear-chat-history
[dynamic-music-updated]: https://www.curseforge.com/minecraft/mc-mods/dynamic-music-updated
[easy-anvils]: https://www.curseforge.com/minecraft/mc-mods/easy-anvils
[easy-magic]: https://www.curseforge.com/minecraft/mc-mods/easy-magic
[eating-animation]: https://www.curseforge.com/minecraft/mc-mods/eating-animation-forge
[effective]: https://www.curseforge.com/minecraft/mc-mods/effective-forge
[embeddium]: https://www.curseforge.com/minecraft/mc-mods/embeddium
[embeddium-dynamic-lights]: https://www.curseforge.com/minecraft/mc-mods/dynamiclights-reforged
[embeddium-extra]: https://www.curseforge.com/minecraft/mc-mods/rubidium-extra
[embeddium-extras]: https://www.curseforge.com/minecraft/mc-mods/magnesium-extras
[entity-culling]: https://www.curseforge.com/minecraft/mc-mods/entityculling
[extra-sounds-next]: https://www.curseforge.com/minecraft/mc-mods/extrasounds-forge
[farmers-delight]: https://www.curseforge.com/minecraft/mc-mods/farmers-delight
[fast-ip-ping]: https://www.curseforge.com/minecraft/mc-mods/fast-ip-ping
[fastboot]: https://www.curseforge.com/minecraft/mc-mods/fastboot
[fastquit]: https://www.curseforge.com/minecraft/mc-mods/fastquit-forge
[ferritecore]: https://www.curseforge.com/minecraft/mc-mods/ferritecore
[first-person-model]: https://www.curseforge.com/minecraft/mc-mods/first-person-model
[footprint-particle]: https://www.curseforge.com/minecraft/mc-mods/footprintparticle
[forgematica]: https://www.curseforge.com/minecraft/mc-mods/forgematica
[forgery]: https://www.curseforge.com/minecraft/mc-mods/forgery
[forgetmechunk]: https://www.curseforge.com/minecraft/mc-mods/forgetmechunk-forge
[fps-reducer]: https://www.curseforge.com/minecraft/mc-mods/fps-reducer
[gpu-memory-leak-fix]: https://www.curseforge.com/minecraft/mc-mods/fix-gpu-memory-leak
[gravisuit-classic]: https://www.curseforge.com/minecraft/mc-mods/gravisuit-classic
[held-item-tooltips]: https://www.curseforge.com/minecraft/mc-mods/held-item-tooltips
[hts-treechop]: https://www.curseforge.com/minecraft/mc-mods/treechop
[immediatelyfast]: https://www.curseforge.com/minecraft/mc-mods/immediatelyfast
[ic2-classic]: https://www.curseforge.com/minecraft/mc-mods/ic2-classic
[ic2-classic-jade-addon]: https://www.curseforge.com/minecraft/mc-mods/jade-addons-ic2classic
[ic2-classic-uu-matter]: https://www.curseforge.com/minecraft/mc-mods/ic2cuumatter
[inventory-hud]: https://www.curseforge.com/minecraft/mc-mods/inventory-hud-forge
[ipn]: https://www.curseforge.com/minecraft/mc-mods/inventory-profiles-next
[iron-chests]: https://www.curseforge.com/minecraft/mc-mods/iron-chests
[item-borders]: https://www.curseforge.com/minecraft/mc-mods/item-borders
[item-highlighter]: https://www.curseforge.com/minecraft/mc-mods/item-highlighter
[jade]: https://www.curseforge.com/minecraft/mc-mods/jade
[jade-addons]: https://www.curseforge.com/minecraft/mc-mods/jade-addons
[jei]: https://www.curseforge.com/minecraft/mc-mods/jei
[jer]: https://www.curseforge.com/minecraft/mc-mods/just-enough-resources-jer
[krypton]: https://www.curseforge.com/minecraft/mc-mods/krypton-reforged
[lazydfu]: https://www.curseforge.com/minecraft/mc-mods/lazy-dfu-forge
[light-overlay]: https://www.curseforge.com/minecraft/mc-mods/light-overlay
[lootr]: https://www.curseforge.com/minecraft/mc-mods/lootr
[memory-leak-fix]: https://www.curseforge.com/minecraft/mc-mods/memoryleakfix
[model-gap-fix]: https://www.curseforge.com/minecraft/mc-mods/model-gap-fix
[modernfix]: https://www.curseforge.com/minecraft/mc-mods/modernfix
[more-chat-history]: https://modrinth.com/mod/morechathistory-reforged
[more-mob-variants]: https://www.curseforge.com/minecraft/mc-mods/more-mob-variants
[mouse-tweaks]: https://www.curseforge.com/minecraft/mc-mods/mouse-tweaks
[neapolitan]: https://www.curseforge.com/minecraft/mc-mods/neapolitan
[nekos-enchanted-books]: https://www.curseforge.com/minecraft/mc-mods/nekos-enchanted-books
[no-chat-reports]: https://www.curseforge.com/minecraft/mc-mods/no-chat-reports
[not-enough-animations]: https://www.curseforge.com/minecraft/mc-mods/not-enough-animations
[nerb]: https://www.curseforge.com/minecraft/mc-mods/notenoughrecipebook
[obscure-tooltips]: https://www.curseforge.com/minecraft/mc-mods/obscure-tooltips
[oculus]: https://www.curseforge.com/minecraft/mc-mods/oculus
[byg]: https://www.curseforge.com/minecraft/mc-mods/oh-the-biomes-youll-go
[elevatorid]: https://www.curseforge.com/minecraft/mc-mods/openblocks-elevator
[packed-up]: https://www.curseforge.com/minecraft/mc-mods/packed-up-backpacks
[packet-fixer]: https://www.curseforge.com/minecraft/mc-mods/packet-fixer
[pv]: https://modrinth.com/plugin/plasmo-voice
[polymorph]: https://www.curseforge.com/minecraft/mc-mods/polymorph
[presence-footsteps]: https://www.curseforge.com/minecraft/mc-mods/presence-footsteps-forge
[pv-addon-groups]: https://modrinth.com/plugin/pv-addon-groups
[pv-addon-sculk]: https://modrinth.com/plugin/pv-addon-sculk
[pv-addon-sound-physics]: https://modrinth.com/mod/pv-addon-soundphysics
[quark]: https://www.curseforge.com/minecraft/mc-mods/quark
[radiant-gear]: https://www.curseforge.com/minecraft/mc-mods/radiant-gear
[realm-rpg-fallen-adventurers]: https://www.curseforge.com/minecraft/mc-mods/realm-rpg-fallen-adventurers
[rrls]: https://www.curseforge.com/minecraft/mc-mods/rrls
[remove-terralith-intro-message]: https://modrinth.com/datapack/remove-terralith-intro-message
[screenshot-to-clipboard]: https://www.curseforge.com/minecraft/mc-mods/screenshot-to-clipboard
[screenshot-viewer]: https://www.curseforge.com/minecraft/mc-mods/screenshot-viewer
[seamless-loading-screen]: https://www.curseforge.com/minecraft/mc-mods/seamless-loading-screen-forge
[serene-seasons]: https://www.curseforge.com/minecraft/mc-mods/serene-seasons
[simply-light]: https://www.curseforge.com/minecraft/mc-mods/simply-light
[skin-layers-3d]: https://www.curseforge.com/minecraft/mc-mods/skin-layers-3d
[smooth-swapping]: https://www.curseforge.com/minecraft/mc-mods/smooth-swapping
[sound-physics-remastered]: https://www.curseforge.com/minecraft/mc-mods/sound-physics-remastered
[starlight]: https://www.curseforge.com/minecraft/mc-mods/starlight-forge
[structory]: https://www.curseforge.com/minecraft/mc-mods/structory
[terralith]: https://www.curseforge.com/minecraft/mc-mods/terralith
[textrues-embeddium-options]: https://www.curseforge.com/minecraft/mc-mods/textrues-embeddium-options
[tia]: https://modrinth.com/mod/tiny-item-animations
[towns-and-towers]: https://www.curseforge.com/minecraft/mc-mods/towns-and-towers
[visual-workbench]: https://www.curseforge.com/minecraft/mc-mods/visual-workbench
[wall-jump-txf]: https://www.curseforge.com/minecraft/mc-mods/wall-jump-txf
[watut]: https://www.curseforge.com/minecraft/mc-mods/what-are-they-up-to
[world-play-time]: https://www.curseforge.com/minecraft/mc-mods/world-play-time
[xaeros-minimap]: https://www.curseforge.com/minecraft/mc-mods/xaeros-minimap
[xaeros-world-map]: https://www.curseforge.com/minecraft/mc-mods/xaeros-world-map
[yungs-better-desert-temples]: https://www.curseforge.com/minecraft/mc-mods/yungs-better-desert-temples
[yungs-better-dungeons]: https://www.curseforge.com/minecraft/mc-mods/yungs-better-dungeons
[yungs-better-end-island]: https://www.curseforge.com/minecraft/mc-mods/yungs-better-end-island
[yungs-better-jungle-temples]: https://www.curseforge.com/minecraft/mc-mods/yungs-better-jungle-temples
[yungs-better-mineshafts]: https://www.curseforge.com/minecraft/mc-mods/yungs-better-mineshafts-forge
[yungs-better-nether-fortresses]: https://www.curseforge.com/minecraft/mc-mods/yungs-better-nether-fortresses
[yungs-better-ocean-monuments]: https://www.curseforge.com/minecraft/mc-mods/yungs-better-ocean-monuments
[yungs-better-strongholds]: https://www.curseforge.com/minecraft/mc-mods/yungs-better-strongholds
[yungs-better-witch-huts]: https://www.curseforge.com/minecraft/mc-mods/yungs-better-witch-huts
[yungs-bridges]: https://www.curseforge.com/minecraft/mc-mods/yungs-bridges
[yungs-extras]: https://www.curseforge.com/minecraft/mc-mods/yungs-extras

<!-- Links to libs required for the mods -->
[architectury-api]: https://www.curseforge.com/minecraft/mc-mods/architectury-api
[autoreglib]: https://www.curseforge.com/minecraft/mc-mods/autoreglib
[blueprint]: https://www.curseforge.com/minecraft/mc-mods/blueprint
[citadel]: https://www.curseforge.com/minecraft/mc-mods/citadel
[cloth-config-api]: https://www.curseforge.com/minecraft/mc-mods/cloth-config
[corgilib]: https://www.curseforge.com/minecraft/mc-mods/corgilib
[coroutil]: https://www.curseforge.com/minecraft/mc-mods/coroutil
[creativecore]: https://www.curseforge.com/minecraft/mc-mods/creativecore
[cupboard]: https://www.curseforge.com/minecraft/mc-mods/cupboard
[curios-api]: https://www.curseforge.com/minecraft/mc-mods/curios
[emf]: https://www.curseforge.com/minecraft/mc-mods/entity-model-features
[etf]: https://www.curseforge.com/minecraft/mc-mods/entity-texture-features-fabric
[geckolib]: https://www.curseforge.com/minecraft/mc-mods/geckolib
[iceberg]: https://www.curseforge.com/minecraft/mc-mods/iceberg
[kotlin]: https://www.curseforge.com/minecraft/mc-mods/kotlin-for-forge
[libipn]: https://www.curseforge.com/minecraft/mc-mods/libipn
[mafglib]: https://www.curseforge.com/minecraft/mc-mods/mafglib
[obscure-api]: https://www.curseforge.com/minecraft/mc-mods/obscure-api
[playeranimator]: https://www.curseforge.com/minecraft/mc-mods/playeranimator
[prism]: https://www.curseforge.com/minecraft/mc-mods/prism-lib
[puzzles-lib]: https://www.curseforge.com/minecraft/mc-mods/puzzles-lib
[supermartijn642s-config-lib]: https://www.curseforge.com/minecraft/mc-mods/supermartijn642s-config-lib
[supermartijn642s-core-lib]: https://www.curseforge.com/minecraft/mc-mods/supermartijn642s-core-lib
[terrablender]: https://www.curseforge.com/minecraft/mc-mods/terrablender
[yungs-api]: https://www.curseforge.com/minecraft/mc-mods/yungs-api

<!-- Links to resource packs included in the modpack -->
[vt]: https://vanillatweaks.net/picker/resource-packs/
[fancy-crops]: https://www.curseforge.com/minecraft/texture-packs/fancy-crops
[fresh-moves]: https://www.curseforge.com/minecraft/texture-packs/fresh-moves
[ore-variants]: https://www.curseforge.com/minecraft/texture-packs/ore-variants
[simple-grass-flowers]: https://www.curseforge.com/minecraft/texture-packs/simple-grass-flowers
[simple-lower-grass-sides]: https://www.curseforge.com/minecraft/texture-packs/simple-lower-grass-sides
[spring-flowers]: https://www.curseforge.com/minecraft/texture-packs/spring-flowers

<!-- General links for installation and Forge -->
[releases]: https://github.com/iwdath/industrial-plus-modpack-forge-mc1.19.2/releases
[forge]: https://files.minecraftforge.net/net/minecraftforge/forge/index_1.19.2.html
