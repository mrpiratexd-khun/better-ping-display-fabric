# DISCLAIMER
This project was forked from Vladmacrica's Better Ping Display Fabric Mod. It will be updated by me.

Here is the official source code of this mod: https://github.com/vladmarica/better-ping-display-fabric


# Better Ping Display Remake

[![](https://img.shields.io/curseforge/dt/1644760?style=for-the-badge&logo=curseforge&label=Downloads&color=rgb(241%2C%20100%2C%2054))](https://www.curseforge.com/minecraft/mc-mods/better-ping-display-remake) [![](https://img.shields.io/modrinth/dt/better-ping-display-remake?style=for-the-badge&logo=modrinth&logoColor=rgb(27%2C%20217%2C%20106)&label=Downloads&color=rgb(27%2C%20217%2C%20106))](https://modrinth.com/mod/better-ping-display-remake)

A [Fabric](https://fabricmc.net/) mod for Minecraft to display each player's ping in the player list as a number.

**Newly Added Features,**  
1.Player Head Skin For Tab List Menu  
2.Custom Fonts for Only Tab List Menu  
3.User Pirority   
4.Custom Tag \[BPD+\] and \[NEO+\]

![image](https://media.forgecdn.net/attachments/description/1644760/description_c87f2f52-e1b6-42ae-aa66-11f40f40cf30.png)

This is a client-side mod. The server doesn't need to have it installed. It works even when playing on vanilla servers.

## Configuration

This mod's config file is `betterpingdisplay.json`. It contains the following options:

| &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<br>&nbsp; &nbsp; &nbsp;Option&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;&nbsp; |Default Value |Description                                                                                                      |
| ------------------------------------------------------------------------------------------------------------------------------------------ |------------- |---------------------------------------------------------------------------------------------------------------- |
| <code>autoColorPingText</code>                                                                                                             |<code>true</code> |Whether to color a player's ping based on their latency.                                                         |
| <code>renderPingBars</code>                                                                                                                |<code>false</code> |Whether to also draw the default Minecraft ping bars                                                             |
| <code>pingTextColor</code>                                                                                                                 |<code>#A0A0A0</code> |The ping text color to use. Only works whens <code>autoColorPingText</code> is false                             |
| <code>pingTextFormatString</code>                                                                                                          |<code>%dms</code> |The format string for ping text. Must include a <code>%d</code>, which will be replaced dynamically by the actual ping value. |
| <code>showPlayersHead</code>                                                                                                               |<code>true</code> |Show player skin heads next to names in the tab list.                                                            |
| <code>tabFont</code>                                                                                                                       |<code>default</code> |Choose a custom font for player names and ping text in the tab list.                                             |
| <code>prioritizeSelfInTabList</code>                                                                                                       |<code>true</code> |Always shows your own name at the top of the tab list, regardless of your rank or tag.                           |
| <code>showSelfPrefix</code>                                                                                                                |<code>false</code> |Shows a client-side-only custom tag provide by this mod in front of your own name in the tab list.               |

>   As of mod version **<span>Dappled_Forest</span>****.1.6.0**, a GUI configuration screen is available if you have [Mod Menu](https://modrinth.com/mod/modmenu) and [YACL](https://modrinth.com/mod/yacl) installed. These are optional dependencies and this mod will continue to work normally without them installed.

![image](https://media.forgecdn.net/attachments/description/1644760/description_786bca32-bf8f-41f0-b0cd-99fc465f5b68.png)

## Supported Minecraft Versions

 \* **1.15.x**  \* **1.16.x**  \* **1.17.x**  \* **1.18.x**  \* **1.19.x**  \* **1.20.x**  \* **1.21.x**  \* **26.2.x  \*26.3.x**

## Requirements

 \* [Fabric](https://fabricmc.net/)
