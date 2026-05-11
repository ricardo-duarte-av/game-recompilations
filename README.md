# game-recompilations
Just a list of game recompilations i've bumped into

## Super Nintendo Entertainment System (SNES)

| Game | Repo | Targets | Notes |
|------|------|---------|-------|
| The Legend of Zelda: A Link to the Past | [snesrev/zelda3](https://github.com/snesrev/zelda3) | Windows, macOS, Linux, Switch | Reverse-engineered C reimplementation (~70-80kLOC). Requires a US ROM (`zelda3.sfc`) for asset extraction only. Supports 16:9/16:10, pixel shaders, MSU audio, and higher-quality world map. |

## Nintendo Entertainment System (NES)

| Game | Repo | Targets | Notes |
|------|------|---------|-------|
| Super Mario Bros. Remastered | [JHDev2006/Super-Mario-Bros.-Remastered-Public](https://github.com/JHDev2006/Super-Mario-Bros.-Remastered-Public) | Windows, Linux, macOS (unofficial) | Ground-up remake in Godot 4.6. Covers SMB1, Lost Levels, SMB Special, and All Night Nippon SMB. Requires an original SMB1 NES ROM. Includes new levels, characters, resource packs, and a level editor. |

## Nintendo 64

| Game | Repo | Targets | Notes |
|------|------|---------|-------|
| The Legend of Zelda: Ocarina of Time | [HarbourMasters/Shipwright](https://github.com/HarbourMasters/Shipwright) | Windows, macOS, Linux, Switch | Built on libultraship. Requires a legally obtained OoT ROM. Supports DX11, OpenGL, and Metal. Custom assets via `.otr` archives. |
| The Legend of Zelda: Majora's Mask | [HarbourMasters/2ship2harkinian](https://github.com/HarbourMasters/2ship2harkinian) | Windows, macOS, Linux | Built on libultraship. Requires a legally obtained MM ROM. Supports DX11, OpenGL, and Metal. Custom assets via `.o2r`/`.otr` mod files. |
| Super Mario 64 | [VDavid003/sm64-port-android](https://github.com/VDavid003/sm64-port-android) | Android | Port based on the n64decomp/sm64 decompilation. Requires a legally obtained SM64 ROM (US/JP/EU `.z64`). Can be compiled on-device via Termux or on PC. |
| Super Mario 64 | [HarbourMasters/Ghostship](https://github.com/HarbourMasters/Ghostship) | Windows, macOS, Linux, Switch | Built on libultraship (same family as Shipwright/2Ship). Requires US or JP ROM. Supports DX11, OpenGL, and Metal. Custom assets via `.o2r`/`.otr` mods. |
| Paperboy | [marijnvdwerf/paperboy-n64](https://github.com/marijnvdwerf/paperboy-n64) | — | Work-in-progress decompilation. Requires a legally obtained NTSC ROM as `baserom.z64`. Builds matching NTSC ROM and fake PAL variant. |
| Bomberman 64 | [RevoSucks/BM64Recomp](https://github.com/RevoSucks/BM64Recomp) | Windows, Linux, Steam Deck | Static recompilation via N64Recomp (no decompilation needed). Rendered with RT64 (requires D3D12, Vulkan, or Metal). US ROM only. Supports mods, widescreen, high framerate, and ultrawide. |
| Mario Kart 64 | [HarbourMasters/SpaghettiKart](https://github.com/HarbourMasters/SpaghettiKart) | Windows, macOS, Linux, Switch | Built on libultraship (same family as Shipwright/Ghostship). US ROM only. Supports DX11, OpenGL, and Metal. Custom assets via `.o2r` mods (`.otr` not supported). |
| Star Fox 64 | [HarbourMasters/Starship](https://github.com/HarbourMasters/Starship) | Windows, macOS, Linux, Switch | Built on libultraship. US 1.0/1.1 ROM required. Supports EU/JP voice language replacement. DX11, OpenGL, and Metal. Custom assets via `.o2r`/`.otr` mods. |

## Game Boy Color

| Game | Repo | Targets | Notes |
|------|------|---------|-------|
| The Legend of Zelda: Link's Awakening DX HD | [BigheadSMZ/Zelda-LA-DX-HD-Updated](https://github.com/BigheadSMZ/Zelda-LA-DX-HD-Updated) | Windows, Linux, Android | Fork of an anonymous MonoGame-based HD PC port. Requires assets from the original v1.0.0 itch.io release. Supports DX11 and OpenGL. Includes mod support (graphics, music, SFX, dialogue). |

## Game Boy Advance

| Game | Repo | Targets | Notes |
|------|------|---------|-------|
| The Legend of Zelda: The Minish Cap | [999sian/tmc](https://github.com/999sian/tmc) | Windows, macOS, Linux | Native PC port built on SDL3 with a software PPU renderer. Requires a legally obtained GBA ROM (USA/EU). Pre-built releases available. WIP. |

## Nintendo GameCube / Wii

| Game | Repo | Targets | Notes |
|------|------|---------|-------|
| The Legend of Zelda: Twilight Princess | [TwilitRealm/dusk](https://github.com/TwilitRealm/dusk) | Windows, macOS, Linux, iOS, Android | Reverse-engineered reimplementation. Requires D3D12, Vulkan, or Metal GPU. Supports GCN USA/EUR ISOs (user-provided). |

## Xbox 360

| Game | Repo | Targets | Notes |
|------|------|---------|-------|
| Sonic Unleashed | [hedge-dev/UnleashedRecomp](https://github.com/hedge-dev/UnleashedRecomp) | Windows, Linux | Static recompilation of the X360 version via XenonRecomp (PowerPC → C++) and XenosRecomp (Xenos shaders → HLSL). Requires D3D12 or Vulkan 1.2. Supports high res, ultrawide, high framerate, and mods. Requires legally obtained X360 game files. |
| Dragon Ball Z Budokai HD | [WistfulHopes/DBZ1](https://github.com/WistfulHopes/DBZ1) | PC (native) | Static recompilation of the Xbox 360 version via ReXGlue SDK (PowerPC → C++). Very early stage (v0.0.2, 2 commits). Requires original game assets. |

## PC / Mobile (Sega Retro Engine)

| Game | Repo | Targets | Notes |
|------|------|---------|-------|
| Sonic 1 & Sonic 2 (2013) | [RSDKModding/RSDKv4-Decompilation](https://github.com/RSDKModding/RSDKv4-Decompilation) | Windows, Linux, Android | Complete decompilation of Retro Engine v4. Requires assets from the official Sonic Origins release (Steam/Epic/eShop/mobile). Includes mod loader, Sonic 2 online multiplayer, and dev menu. Unofficial forks for PS Vita, Switch, 3DS, and WASM. |

## Tools

| Name | Repo | Notes |
|------|------|-------|
| N64Recomp Launcher | [SirDiabo/N64RecompLauncher](https://github.com/SirDiabo/N64RecompLauncher) | .NET 9 GUI launcher that auto-downloads and updates N64 recompiled games from GitHub releases. Configurable via `games.json`. Windows. |

## Mods & Texture Packs

| Game | Link | For | Notes |
|------|------|-----|-------|
| The Legend of Zelda: Twilight Princess 4K Texture Pack | [henrikomagnifico.com](https://www.henrikomagnifico.com/zelda-twilight-princess-4k) | [Dusk](https://github.com/TwilitRealm/dusk) | Fan-made upscaled textures (4K/1080p). 1.8K+ textures, ~80% game coverage. Separate downloads for Dusk/Courage Reborn and Dolphin. No game files included. |
| SM64 Reloaded | [evilgames.eu](https://evilgames.eu/texture-packs/sm64-reloaded.htm) | [Ghostship](https://github.com/HarbourMasters/Ghostship) + emulators | 100% complete HD/4K texture pack by GhostlyDark (v2.6.0). Supports Ghostship (`.o2r`), N64 emulators (GLideN64/mupen64plus/PJ64), Dolphin, and rt64. |
| Ship of Harkinian Mods | [gamebanana.com](https://gamebanana.com/mods/games/16121) | [Shipwright](https://github.com/HarbourMasters/Shipwright) | GameBanana mod hub for the OoT PC port. Community-submitted mods of all kinds. |
| Starship Mods | [gamebanana.com](https://gamebanana.com/mods/games/21612) | [Starship](https://github.com/HarbourMasters/Starship) | GameBanana mod hub for the Star Fox 64 PC port. Community-submitted mods of all kinds. |
