# Modpacks for Minecraft Forge 1.19.2

> [!NOTE]
> In each folder of this repository dedicated to an individual modpack, you’ll find a README file that contains a detailed table of mods included in the modpack. These tables provide valuable information about each mod, including its **`name`**, **`dependencies`**, and **`installation side`**. **_I recommend reviewing these tables if you’d like to customize the modpack to your preferences._**

## Installation

Mods in these modpacks are divided into <kbd>**client-side**</kbd> and <kbd>**server-side**</kbd> for easier and faster installation. The archive with the mods can be downloaded from the [**releases**][releases].

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


[releases]: https://github.com/iwdath/mc-modpacks/releases