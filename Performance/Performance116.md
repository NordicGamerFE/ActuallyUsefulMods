# Performance Mods

A list of performance-enhancing mods for 1.16.x forge/fabric versions.

[![Home](https://i.imgur.com/zGuelkW.png)](/README.md)

## Fabric 1.16.X

| Name | Known Incompatibilities | Description | Author | Performance Improvement | [Label](/README.md/#labels) |
| --- | :---: | :---: | :---: | :---: | :---: |
| [Alternate Current](https://www.curseforge.com/minecraft/mc-mods/alternate-current) | Unknown | Alternate Current is an efficient and non-locational redstone dust implementation. | SpaceWalkerRS | Server | None |
| [Angerable Patch](https://www.curseforge.com/minecraft/mc-mods/angerable-patch) | Unknown | Fixes MC-192362 / MC-189565, which causes drastically large log file sizes and lag | Draylar | Client | None |
| [Better Beds](https://www.curseforge.com/minecraft/mc-mods/better-beds) | Unknown | Removes the Block Entity Renderer from the bed and replaces it with the default minecraft model renderer. | Motschen | Client | None |
| [Better Biome Blend](https://www.curseforge.com/minecraft/mc-mods/better-biome-blend) | Sodium | Better Biome Blend is a mod  which accelerates the biome color blending algorithm. | FionaTheMortal | Client | None |
| [C2ME](https://github.com/YatopiaMC/C2ME-fabric/releases)| Tic-Tacs, + | A Fabric mod designed to improve the chunk performance of Minecraft. | ishland | Server | Alpha (5) |
| [Canvas](https://www.curseforge.com/minecraft/mc-mods/canvas-renderer) | Sodium | Advanced Rendering Engine for Fabric | grondag | Client | Alpha (1) |
| [Chunky](https://www.curseforge.com/minecraft/mc-mods/chunky-pregenerator) | Unknown | Pre-generates chunks, quickly and efficiently. | pop4959 | Both | Configuration Needed (7) |
| [Cull Leaves](https://www.curseforge.com/minecraft/mc-mods/cull-leaves) | Unknown | Adds culling to leaf blocks, providing a huge performance boost over vanilla. | Motschen | Client | None |
| [DashLoader](https://www.curseforge.com/minecraft/mc-mods/dashloader) | Hydrogen, Enhanced Block Entities | This mod launches minecraft faster by caching all of the content on first launch and then loading that cache on the next one | alphaqu | Client | Incompatible (4) |
| [Dimensional Threading](https://github.com/WearBlackAllDay/DimensionalThreading/releases)| Unknown | Minecraft mod which optimizes the processing of multiple Dimensions, by assigning them independent threads | WearBlackAllDay | Server | None |
| [Dynamic FPS](https://modrinth.com/mod/dynamic-fps) | Unknown | Automatically reduces rendering speed when minecraft is not focused (to 1 FPS) or hidden (no renders at all). | juliand665 | Client | None |
| [Enhanced Block Entities](https://modrinth.com/mod/ebe) | Sodium[⁴](/README.md#-some-of-the-mods-that-have-sodium-as-an-incompatibility-might-work-if-you-use-indium), DashLoader | EBE is a mod which aims to increase the performance of block entity rendering, as well as offer customizability via resource packs. | FoundationGames | Client | None |
| [Entity Distance](https://modrinth.com/mod/entity-distance) | Unknown | Allows the user to adjust the (client) distance at which different entities render | capnkork | Client | None |
| [Entity Culling](https://www.curseforge.com/minecraft/mc-mods/entityculling) | None | EntityCulling using async path-tracing to skip rendering Tiles/Entities that are not visible | tr9zw | Client | None |
| [Fabric Chunk Pregenerator](https://www.curseforge.com/minecraft/mc-mods/fastanim) | Unknown | Fabric Chunk Pregenerator is a fabric mod that allows you to pregenerate chunks for your server or for singleplayer while running fabric. | SuperCoder79 | Both | Configuration Needed (7) |
| [FastBench](https://www.curseforge.com/minecraft/mc-mods/fastbench-for-fabric) | None | This is a mod aimed at improving performance of all crafting-related functions. | tfarecnim | Server | None |
| [FastChest](https://www.curseforge.com/minecraft/mc-mods/fastchest) | Unknown | This mod helps by removing dynamic models from chests and making them render as static chunk geometry. | fake_domi | Client | None |
| [FastFurnace](https://www.curseforge.com/minecraft/mc-mods/fast-furnace-for-fabric) | Recipe Cache | Similar to FastWorkbench, it caches the last recipe used, and checks this recipe first before re-scanning the entire registry | tfarecnim | Server | None |
| [Fat Experience Orbs](https://www.curseforge.com/minecraft/mc-mods/fat-experience-orbs) | Unknown | This mod makes it so that nearby experience orbs merge together | NinjaPhenix | Server | None |
| [FerriteCore](https://www.curseforge.com/minecraft/mc-mods/ferritecore-fabric) | Unknown | This mod reduces the memory usage of Minecraft in a few different ways | malte0811 | Both | None |
| [Hopper Optimizations](https://github.com/2No2Name/hopperOptimizations) | Unknown | A mod that optimizes hoppers and their interactions with entities and inventories | 2No2Name | Server | None |
| [Hydrogen](https://modrinth.com/mod/hydrogen) | DashLoader | Reduces the memory usage of the game in more modded scenarios | CaffeineMC | Client | Alpha (1) |
| [Krypton](https://www.curseforge.com/minecraft/mc-mods/krypton) | Unknown | Krypton is a Minecraft mod designed for the Fabric mod loader that implements a suite of optimizations focused on the Minecraft networking stack | astei | Both | Alpha (1) |
| [Ksyxis](https://www.curseforge.com/minecraft/mc-mods/ksyxis) | Unknown | Speeds up your world loading by not loading nearby chunks every time. | VidTu | Both | Reverse Features (1) |
| [LazyDFU](https://www.curseforge.com/minecraft/mc-mods/lazydfu) | None | LazyDFU is an optimization mod that makes the initialization of DataFixerUpper "lazy" | astei | Both | None |
| [Let Me Despawn](https://www.curseforge.com/minecraft/mc-mods/let-me-despawn) | Unknown | Helps with lag caused by accidental persistent mobs. | frikinjay1 | Server | Reverse features (7) |
| [Lithium](https://www.curseforge.com/minecraft/mc-mods/lithium) | None | Lithium is a general-purpose optimization mod for Minecraft which works to improve a number of systems without changing any behavior | CaffeineMC | Server | None |
| [MCMT-Fabric](https://github.com/himekifee/MCMTFabric) | Carpet, Dimensional Threading | This is a mod, that attempts to multithread minecraft's tick execution. | himekifee | Server | Corruption (1) |
| [Mipmaplevel and Language Fix](https://modrinth.com/mod/mipmaplevelandlanguagefix) | Unknown | Makes changing Mipmaplevels and Language faster, by instead of doing a full reload, only reloading the respective part of the game. | KingContaria | Client | None |
| [Observable](https://modrinth.com/mod/observable) | Unknown | Shows what's lagging your world/server by profiling (tile) entities. | tasgon | Server | None |
| [Overworld Two](https://www.curseforge.com/minecraft/mc-mods/overworld-two) | Unknown | Optimization mod that generates overworld and nether terrain much faster than vanilla minecraft at the cost of breaking parity. | gegy1000, SuperCoder79 | Server | None |
| [Phosphor](https://www.curseforge.com/minecraft/mc-mods/phosphor) | Starlight | Phosphor is a Minecraft mod which works to optimize one of game's most inefficient areas, the lighting engine | CaffeineMC | Both | None |
| [Recipe Cache](https://www.curseforge.com/minecraft/mc-mods/recipe-cache) | FastFurnace, FastBench (?) | Caches recipe lookup for crafting and furnaces to lessen server lag caused by crafting stacks of items and large amounts of furnaces ticking | biom4st3r1 | Server | None |
| [Resolution Control+](https://github.com/UltimateBoomer/Resolution-Control/releases) | Unknown | ResolutionControl+ allows you to change Minecraft's render resolution separately from the HUD elements. | Ultimate Boomer | Client | Buggy (4) |
| [Smoke Suppresion](https://www.curseforge.com/minecraft/mc-mods/smoke-suppression) | Unknown | This is to prevent client-side lag and general annoyance when using large numbers of campfires in farms. | supersaiyansubtlety | Client | None |
| [Smooth Boot](https://www.curseforge.com/minecraft/mc-mods/smooth-boot) | Unknown | Optimize Minecraft loading performance to be smoother on low end systems and scale better on high end systems | UltimateBoomer | Both | None |
| [Sodium](https://www.curseforge.com/minecraft/mc-mods/sodium) | Mods that utilize of the FRAPI[⁴](/README.md#-some-of-the-mods-that-have-sodium-as-an-incompatibility-might-work-if-you-use-indium) | Sodium is a free and open-source rendering engine replacement for the Minecraft client that greatly improves frame rates, reduces micro-stutter, and fixes graphical issues in Minecraft | CaffeineMC | Client | None |
| [Starlight](https://github.com/PaperMC/Starlight/releases) | Phosphor | Fabric mod for completely rewriting the vanilla light engine. | Spottedleaf (PaperMC) | Both | None |
| [Tic-Tacs](https://github.com/Gegy/tic-tacs/releases) | C2ME | Tic-TACS is an experimental reimplementation of Minecraft's chunk loading engine | gegy | Server | Alpha (3) |
| [VanillaFix](https://github.com/DimensionalDevelopment/VanillaFix/releases) | Unknown | Bug fixes and optimizations for Minecraft | BoogieMonster1O1 (Dimensional Development) | Both | None |

## Forge 1.16.X

| Name | Known Incompatibilities | Description | Author | Performance Improvement | [Label](/README.md/#labels) |
| --- | :---: | :---: | :---: | :---: | :---: |
| [AI Improvements](https://www.curseforge.com/minecraft/mc-mods/ai-improvements)[⁵](/README.md#-ai-improvements-newer-versions-114-dont-have-as-much-impact-as-the-older-versions-have-since-in-newer-versions-of-minecraft-a-lot-of-fixes-to-the-ai-are-implemented-sources-curseforge-page-faq-dev) | None | Simplified AI modification mod focused on performance and low-level modifications to AIs in the game | QueenOfMissiles | Server | None |
| [APTweaks](https://www.curseforge.com/minecraft/mc-mods/adaptive-performance-tweaks) | Dynamic View (View Distance Feature), Clumps | Adaptive Performance Tweaks is a Minecraft Forge Mod which automatically adjust specific settings on the server and client side to allow a balanced TPS/FPS. | Kaworru | Server | None |
| [Better Biome Blend](https://www.curseforge.com/minecraft/mc-mods/better-biome-blend) | None | Better Biome Blend is a mod  which accelerates the biome color blending algorithm. | FionaTheMortal | Client | None |
| [Better Fps - Render Distance](https://www.curseforge.com/minecraft/mc-mods/better-fps-render-distance) | Unknown | Better FPS Render Distance is a mod which adds a few performance improvements to increase fps. | someaddon | Client | None |
| [C2ME](https://github.com/YatopiaMC/C2ME-forge/releases) | Unknown | A Forge mod designed to improve the chunk performance of Minecraft. | YatopiaMC | Server | Alpha (1) |
| [Chunk-Pregenerator](https://www.curseforge.com/minecraft/mc-mods/chunkpregenerator) | Unknown | Chunk Pregenerator is a tool that allows you to generate your World more efficiently, by Preemptively generating the chunks. It is a Server-side tool that has some optional client features if wanted. | Speiger | Both | Configuration Needed (7) |
| [Chunky](https://www.curseforge.com/minecraft/mc-mods/chunky-pregenerator-forge) | Unknown | Pre-generates chunks, quickly and efficiently. | pop4959 | Both | Configuration Needed (7) |
| [Clumps](https://www.curseforge.com/minecraft/mc-mods/clumps) | APTweaks, MCMT | Clumps groups XP orbs together into a single entity to reduce lag when there are many in a small area | jaredlll08 | Both | None |
| [DataFixerSlayer](https://www.curseforge.com/minecraft/mc-mods/datafixerslayer)[³](/README.md#-do-not-blame-me-if-you-didnt-read-this-notice-if-you-try-to-load-a-older-world-in-a-newer-instance-of-the-game-and-you-have-one-of-these-mods-installed-bad-things-will-happen-uninstall-the-mod-first) | Any other mod that also removes DFU | DataFixerSlayer prevents the DataFixerUpper (DFU) system from loading | Vazkii | Both | None |
| [Does It Tick?](https://www.curseforge.com/minecraft/mc-mods/does-it-tick) | Unknown | performance enhancing mod that limits entity ticking outside view distance | TeamDeusVult | Server | None |
| [DrawerFPS](https://www.curseforge.com/minecraft/mc-mods/drawerfps) | Unknown | Simple, efficient mod which lets you configure at which range Storage Drawers do render items to improve fps. | someaddon | Client | None |
| [Dynamic View](https://www.curseforge.com/minecraft/mc-mods/dynamic-view) | APTweaks | This is a small/light serverside utility mod to help balancing lag (TPS) and chunk view/load distance. | someaddon | Server | None |
| [Entity Culling](https://www.curseforge.com/minecraft/mc-mods/entityculling) | None | EntityCulling using async path-tracing to skip rendering Tiles/Entities that are not visible | tr9zw | Client | None |
| [Entity Collision FPS Fix](https://www.curseforge.com/minecraft/mc-mods/entity-collision-fps-fix) | Unknown | Client Side mod that optimizes entity's on the render thread. | CorgiTaco | Client | None |
| [FastFurnace minus Replacement](https://www.curseforge.com/minecraft/mc-mods/fastfurnace-minus-replacement) | None | Similar to FastWorkbench, it caches the last recipe used, and checks this recipe first before re-scanning the entire registry. | tfarecnim | Server | None |
| [FastSuite](https://www.curseforge.com/minecraft/mc-mods/fastsuite) | Unknown | FastSuite is a mod about improving recipe performance, it improves upon all mods that use the JSON recipe system, rather than just a specific subset of recipes | Shadows_of_Fire | Server | None |
| [FastWorkbench minus Replacement](https://www.curseforge.com/minecraft/mc-mods/fastworkbench-minus-replacement) | None | This is a mod aimed at improving performance of all crafting-related functions. | tfarecnim | Server | None |
| [FerriteCore](https://www.curseforge.com/minecraft/mc-mods/ferritecore) | Unknown | This mod reduces the memory usage of Minecraft in a few different ways | malte0811 | Both | None |
| [Get It Together, Drops!](https://www.curseforge.com/minecraft/mc-mods/get-it-together-drops) | Unknown | This mod adds two configuration options to control how dropped items combine on the ground. This can significantly improve performance in areas with lots of dropped items | bl4ckscor3 | Server | None |
| [Krypton Reforged](https://www.curseforge.com/minecraft/mc-mods/krypton-reforged) | Unknown | Krypton Reforged is a Forge port of Krypton a Minecraft mod designed for the Fabric mod loader that implements a suite of optimizations focused on the Minecraft networking stack | TeamDeusVult | Both | Alpha (1) |
| [Ksyxis](https://www.curseforge.com/minecraft/mc-mods/ksyxis) | Unknown | Speeds up your world loading by not loading nearby chunks every time. | VidTu | Both | Reverse Features (1) |
| [LazyDFU](https://www.curseforge.com/minecraft/mc-mods/lazy-dfu-forge) | Mods that remove the DFU | LazyDFU is an optimization mod that makes the initialization of DataFixerUpper "lazy" | Corgi_Taco | Both | None |
| [Let Me Despawn](https://www.curseforge.com/minecraft/mc-mods/let-me-despawn) | Unknown | Helps with lag caused by accidental persistent mobs. | frikinjay1 | Server | Reverse features (7) |
| [Log Begone](https://www.curseforge.com/minecraft/mc-mods/log-begone) | Unknown | Log Begone is a fork of [Shut Up Console by Bravarly](https://www.curseforge.com/minecraft/mc-mods/shut-up-console) that simply allows you to remove annoying logs. Can also help with performance if there is a lot of log spam | AzureDoomC | Server | Configuration Needed (7) |
| [MCMT](https://hatebin.com/swopimmvaw) | Immersive Portals, Performant, Clumps, ***+++*** | This is a mod, that *attempts* to multithread minecraft's tick execution. | jediminer543 | Server | Corruption (1) |
| [Magnesium/Rubidium Extras](https://www.curseforge.com/minecraft/mc-mods/magnesium-extras) | Rubidium Toolkit | Pairing this with Rubidium is highly recommended. Fixes many issues and is compatible with almost everything. | TeamDeusVult | Client | None |
| [Observable](https://modrinth.com/mod/observable) | Unknown | Shows what's lagging your world/server by profiling (tile) entities. | tasgon | Server | None |
| [Out of Sight](https://www.curseforge.com/minecraft/mc-mods/out-of-sight) | Unknown | Out of Sight simply stops modded tile entities from rendering if they are further than 24 blocks away | Corosus | Client | Reverse Features (1) |
| [Overworld Two](https://www.curseforge.com/minecraft/mc-mods/overworld-two-forge) | Unknown | Optimization mod that generates overworld and nether terrain much faster than vanilla minecraft at the cost of breaking parity. | Corgi_Taco, gegy1000, SuperCoder79 | Server | None |
| [Performant](https://www.curseforge.com/minecraft/mc-mods/performant) | Phosphophyllite, Resourceful Bees, + | Lightweight mod project which hugely improves performance and blocklag. | someaddon | Server | Incompatible (2) |
| [RoadRunner](https://www.curseforge.com/minecraft/mc-mods/roadrunner) | Performant | RoadRunner is an unofficial fork of the popular performance-enhancing Fabric mod Lithium by jellysquid3 for the Forge mod loader. | MaxNeedsSnacks | Server | None |
| [Rubidium](https://www.curseforge.com/minecraft/mc-mods/rubidium) | Magnesium | Another unofficial fork of Sodium to Forge. Pairs well with [Oculus](https://www.curseforge.com/minecraft/mc-mods/oculus) so a user can have Sodium's performance improvements with shaders. | Asek3 | Client | None |
| [Rubidium Toolkit](https://www.curseforge.com/minecraft/mc-mods/rubidium-toolkit) | Magnesium/Rubidium Dynamic Lights, Magnesium/Rubidium Extras | Replaces Magnesium/Rubidium Dynamic Lights and Magnesium/Rubidium Extras | TexTrue | Client | Alpha (7) |
| [Saturn](https://www.curseforge.com/minecraft/mc-mods/saturn) | Unknown | Saturn is a free and open-source performance mod for Minecraft Forge designed to optimize Minecraft's memoy usage | AbdElAziz333 | Both | None |
| [Smooth Boot](https://www.curseforge.com/minecraft/mc-mods/smooth-boot-forge) | Unknown | Optimize Minecraft loading performance to be smoother on low end systems and scale better on high end systems | UltimateBoomer | Both | None |
| [Spawner Bug Fix](https://www.curseforge.com/minecraft/mc-mods/spawner-fix) | Unknown | This addresses a bug which causes lag in mods that create custom spawners. | Lupicus | Client | None |
| [Starlight](https://github.com/PaperMC/Starlight/releases) | Create, Sulfuric | Mod for completely rewriting the vanilla light engine. | Spottedleaf (PaperMC) | Both | None |
| [Starlight x Create](https://www.curseforge.com/minecraft/mc-mods/starlight-x-create) | Sulfuric | Mod for completely rewriting the vanilla light engine. | Spottedleaf(PaperMC), Create Patch by: AeiouEnigma, Curseforge Upload and 1.16 Maintained by SirOMGitsYOU | Both | None |
| [Radon](https://www.curseforge.com/minecraft/mc-mods/radon) | Starlight | Radon is an Unofficial Port of CaffeineMC's "Phosphor," made to work with Forge Mod Loader | Asek3 | Both | None |

[![Home](https://i.imgur.com/zGuelkW.png)](/README.md)
