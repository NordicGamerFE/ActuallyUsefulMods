# Performance Mods

A list of performance-enhancing mods for 1.19.x forge/fabric versions.

[![Home](https://i.imgur.com/zGuelkW.png)](/README.md)

## Fabric 1.19.X

| Name | Known Incompatibilities | Description | Author | Performance Improvement | [Label](/README.md#labels) |
| --- | :---: | :---: | :---: | :---: | :---: |
| [Alternate Current](https://modrinth.com/mod/alternate-current) | Unknown | Alternate Current is an efficient and non-locational redstone dust implementation. | Space Walker | Server | None |
| [Better Beds](https://www.curseforge.com/minecraft/mc-mods/better-beds) | Unknown | Removes the Block Entity Renderer from the bed and replaces it with the default minecraft model renderer. | Motschen | Client | None |
| [C2ME](https://modrinth.com/mod/c2me-fabric) | Unknown | A Fabric mod designed to improve the chunk performance of Minecraft. | ishland | Both | Alpha (1) |
| [Chunky](https://www.curseforge.com/minecraft/mc-mods/chunky-pregenerator) | Unknown | Pre-generates chunks, quickly and efficiently. | pop4959 | Both | Configuration Needed (7) |
| [Clumps](https://www.curseforge.com/minecraft/mc-mods/clumps) | Unknown | Clumps groups XP orbs together into a single entity to reduce lag when there are many in a small area. | jaredlll08 | Server | None |
| [Cull Leaves](https://www.curseforge.com/minecraft/mc-mods/cull-leaves) | Unknown | Adds culling to leaf blocks, providing a huge performance boost over vanilla. | Motschen | Client | None |
| [Cull Less Leaves](https://www.curseforge.com/minecraft/mc-mods/cull-less-leaves) | Unknown | Cull Less Leaves is an improved version of Cull Leaves. | XanderIsDev | Client | None |
| [DashLoader](https://www.curseforge.com/minecraft/mc-mods/dashloader) | Unknown | This mod launches minecraft faster by caching all of the content on first launch and then loading that cache on the next one | alphaqu | Client | Incompatible (2) |
| [Dynamic FPS](https://modrinth.com/mod/dynamic-fps) | Unknown | Automatically reduces rendering speed when minecraft is not focused (to 1 FPS) or hidden (no renders at all). | juliand665 | Client | None |
| [Entity Culling](https://www.curseforge.com/minecraft/mc-mods/entityculling) | Unknown | EntityCulling using async path-tracing to skip rendering Tiles/Entities that are not visible. | tr9zw | Client | None |
| [Entity Collision FPS Fix](https://modrinth.com/mod/entity-collision-fps-fix) | Unknown | Client Side mod that optimizes entity's on the render thread. | CorgiTaco | Client | None |
| [Exordium](https://modrinth.com/mod/exordium) | Unknown | Render the GUI and screens at a lower framerate to speed up what's really important: the worldrendering. | tr7zw | Client | None |
| [Fabric Chunk Pregenerator](https://www.curseforge.com/minecraft/mc-mods/chunk-pregenerator-fabric) | Unknown | Fabric Chunk Pregenerator is a fabric mod that allows you to pregenerate chunks for your server or for singleplayer while running fabric. | SuperCoder79 | Both | Configuration Needed (7) |
| [FastAnim](https://www.curseforge.com/minecraft/mc-mods/fastanim) | Unknown | FastAnim is a mod that improves the animation speed of entities. | lunadedogs | Client | None |
| [Fastload](https://www.curseforge.com/minecraft/mc-mods/fastload) | ForceCloseLoadingScreen | Fastload, is a simple mod that reduces world loading time. This serves as an alternative to ksyxis, which uses an unsafe method of cutting down time. | overloadedwithmods | Both | None |
| [FerriteCore](https://www.curseforge.com/minecraft/mc-mods/ferritecore-fabric) | Unknown | This mod reduces the memory usage of Minecraft in a few different ways | malte0811 | Both | None |
| [ForgetMeChunk](https://modrinth.com/mod/forgetmechunk) | Unknown | Fixes the large lag spikes you sometimes get when crossing a chunk border | BreadLoaf | Client | Unstable (7) |
| [Krypton](https://www.curseforge.com/minecraft/mc-mods/krypton) | Unknown | Krypton is a Minecraft mod designed for the Fabric mod loader that implements a suite of optimizations focused on the Minecraft networking stack. | astei | Both | None |
| [LazyDFU](https://www.curseforge.com/minecraft/mc-mods/lazydfu) | Unknown | LazyDFU is an optimization mod that makes the initialization of DataFixerUpper "lazy" | tr9zw | Both | None |
| [Let Me Despawn](https://www.curseforge.com/minecraft/mc-mods/let-me-despawn) | Unknown | Helps with lag caused by accidental persistent mobs. | frikinjay1 | Server | Reverse features (7) |
| [Lithium](https://www.curseforge.com/minecraft/mc-mods/lithium) | Unknown | Lithium is a general-purpose optimization mod for Minecraft which works to improve a number of systems without changing any behavior | jellysquid3_ | Server | None |
| [Log Begone](https://www.curseforge.com/minecraft/mc-mods/log-begone) | Unknown | Log Begone is a fork of [Shut Up Console by Bravarly](https://www.curseforge.com/minecraft/mc-mods/shut-up-console) that simply allows you to remove annoying logs. Can also help with performance if there is a lot of log spam | AzureDoomC | Server | Configuration Needed (7) |
| [MemoryLeakFix](https://www.curseforge.com/minecraft/mc-mods/memoryleakfix) | Unknown | A mod that fixes multiple memory leaks in minecraft. Both server-side & client-side. | FX_PR0CESS | Both | None |
| [Mipmaplevel and Language Fix](https://modrinth.com/mod/mipmaplevelandlanguagefix) | Unknown | Makes changing Mipmaplevels and Language faster, by instead of doing a full reload, only reloading the respective part of the game. | KingContaria | Client | None |
| [More Culling](https://www.curseforge.com/minecraft/mc-mods/moreculling) | See [MoreCulling#6](https://github.com/fxmorin/MoreCulling/issues/6) | changes how blockstate culling is handled in order to improve performance | FX_PR0CESS | Client | None |
| [Particle Blocker](https://modrinth.com/mod/particles) | Unknown | Adds a GUI to pick and choose particles to not render. | Declipsonator | Client | None |
| [Phosphor](https://www.curseforge.com/minecraft/mc-mods/phosphor) | Starlight | Phosphor is a Minecraft mod which works to optimize one of game's most inefficient areas, the lighting engine | CaffeineMC | Both | None |
| [Simply No Shading](https://www.curseforge.com/minecraft/mc-mods/simply-no-shading) | Unknown | This mod mimics OptiFine's Internal Shader with Old Lighting OFF by default. Benefits are less lag as this mod is not a shader, stability, and compatibility with other mods. | StartsMercury | Client | None |
| [Sodium](https://www.curseforge.com/minecraft/mc-mods/sodium) | Mods that utilize of the FRAPI[⁴](https://github.com/NordicGamerFE/usefulmods/tree/main#-some-of-the-mods-that-have-sodium-as-an-incompatibility-might-work-if-you-use-indium) | Sodium is a free and open-source rendering engine replacement for the Minecraft client that greatly improves frame rates, reduces micro-stutter, and fixes graphical issues in Minecraft. | jellysquid3_ | Client | None |
| [ServerCore](https://modrinth.com/mod/servercore) | Unknown | A fabric mod that aims to optimize & add multiplayer features to the minecraft server. | Wesley1808 | Server | None |
| [Smooth Boot](https://www.curseforge.com/minecraft/mc-mods/smooth-boot) | Unknown | Optimize Minecraft loading performance to be smoother on low end systems and scale better on high end systems. | UltimateBoomer | Both | None |
| [Starlight](https://www.curseforge.com/minecraft/mc-mods/starlight) | Unknown | Fabric mod for completely rewriting the vanilla light engine. | Spottedstar | Both | None |
| [Very Many Players](https://modrinth.com/mod/vmp-fabric) | Unknown | Very Many Players, or VMP for short, is a Fabric mod designed to improve general server performance at high playercount without sacrificing vanilla functionality or behavior. | ishland | Server | None |
| [Vulkan Renderer](https://www.curseforge.com/minecraft/mc-mods/vulkanmod) | Sodium | a fabric mod that rewrites Minecraft OpenGL renderer to use Vulkan API. | x_collateral | Client | Incompatible(6) |

## Forge 1.19.X

| Name | Known Incompatibilities | Description | Author | Performance Improvement | [Label](/README.md#labels) |
| --- | :---: | :---: | :---: | :---: | :---: |
| [Canary](https://www.curseforge.com/minecraft/mc-mods/canary) | Unknown | Canary is a general-purpose optimization mod and unofficial fork of the Fabric mod Lithium for Minecraft which works to improve a number of systems (game physics, mob AI, block ticking, etc) without changing any behavior. | AbdElAziz333 | Both | None |
| [Chunk-Pregenerator](https://www.curseforge.com/minecraft/mc-mods/chunkpregenerator) | Unknown | Chunk Pregenerator is a tool that allows you to generate your World more efficiently, by Preemptively generating the chunks. It is a Server-side tool that has some optional client features if wanted. | Speiger | Both | Configuration Needed (7) |
| [Chunky](https://www.curseforge.com/minecraft/mc-mods/chunky-pregenerator-forge) | Unknown | Pre-generates chunks, quickly and efficiently. | pop4959 | Both | Configuration Needed (7) |
| [Clumps](https://www.curseforge.com/minecraft/mc-mods/clumps) | Unknown | Clumps groups XP orbs together into a single entity to reduce lag when there are many in a small area. | jaredlll08 | Server | None |
| [Entity Culling](https://www.curseforge.com/minecraft/mc-mods/entityculling) | Unknown | EntityCulling using async path-tracing to skip rendering Tiles/Entities that are not visible. | tr9zw | Client | None |
| [Entity Collision FPS Fix](https://modrinth.com/mod/entity-collision-fps-fix) | Unknown | Client Side mod that optimizes entity's on the render thread. | CorgiTaco | Client | None |
| [Fastload](https://www.curseforge.com/minecraft/mc-mods/fastload) | Ksysix | Fastload, is a simple mod that reduces world loading time. This serves as an alternative to ksyxis, which uses an unsafe method of cutting down time. | overloadedwithmods | Both | None |
| [FerriteCore](https://www.curseforge.com/minecraft/mc-mods/ferritecore) | Unknown | This mod reduces the memory usage of Minecraft in a few different ways | malte0811 | Both | None |
| [It Shall Not Tick (ISNT)](https://www.curseforge.com/minecraft/mc-mods/it-shall-not-tick) | Unknown | It Shall Not Tick (ISNT) is a performance enhancing mod that limits entity ticking to within a configurable range of players. | Gaz_ | Both | None |
| [LazyDFU](https://www.curseforge.com/minecraft/mc-mods/lazy-dfu-forge) | Mods that remove the DFU | LazyDFU is an optimization mod that makes the initialization of DataFixerUpper "lazy" | Corgi_Taco | Both | None |
| [Let Me Despawn](https://www.curseforge.com/minecraft/mc-mods/let-me-despawn) | Unknown | Helps with lag caused by accidental persistent mobs. | frikinjay1 | Server | Reverse features (7) |
| [Log Begone](https://www.curseforge.com/minecraft/mc-mods/log-begone) | Unknown | Log Begone is a fork of [Shut Up Console by Bravarly](https://www.curseforge.com/minecraft/mc-mods/shut-up-console) that simply allows you to remove annoying logs. Can also help with performance if there is a lot of log spam | AzureDoomC | Server | Configuration Needed (7) |
| [Krypton Reforged](https://www.curseforge.com/minecraft/mc-mods/krypton-reforged) | Unknown | Krypton Reforged is a Minecraft mod that implements a suite of optimizations focused on the Minecraft networking stack. | TeamDeusVult | Both | None |
| [Pluto](https://www.curseforge.com/minecraft/mc-mods/pluto) | Unknown | Pluto is a networking stack optimization mod and unofficial fork of the Fabric mod Krypton for Minecraft, this mod aims to optimize the network stack of the game in order to provide better network performance. | AbdElAziz333 | Both | None |
| [Radon](https://www.curseforge.com/minecraft/mc-mods/radon) | Unknown | Radon is an Unofficial Fork of CaffeineMC's "Phosphor", made to work with Forge Mod Loader. | Asek3 | Both | None |
| [Rubidium](https://www.curseforge.com/minecraft/mc-mods/rubidium) | Optifine | Rubidium is an Unofficial Fork of CaffeineMC's "Sodium", made to work with Forge Mod Loader. | Asek3 | Client | None |
| [Saturn](https://www.curseforge.com/minecraft/mc-mods/saturn) | Unknown | Saturn is a free and open-source performance mod for Minecraft Forge designed to optimize Minecraft's memoy usage | AbdElAziz333 | Both | None |
| [Starlight](https://www.curseforge.com/minecraft/mc-mods/starlight-forge) | Unknown | Forge mod for rewriting the light engine to fix lighting performance and lighting errors | SpottedLeaf (PaperMC) | Server | None |
| [Smooth Boot (Reloaded)](https://www.curseforge.com/minecraft/mc-mods/smooth-boot-reloaded) | Unknown | Smooth Boot - Optimize Minecraft loading performance to be smoother on low end systems and scale better on high end systems. | AbdElAziz333 | Client | None |

[![Home](https://i.imgur.com/zGuelkW.png)](/README.md)
