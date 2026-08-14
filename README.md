# Awesome Retro Gaming

> Curated tools, operating systems, and resources for playing and preserving classic games — on dedicated hardware, old laptops, or modern computers.

## Contents

- [Frontends & Emulation Operating Systems](#frontends--emulation-operating-systems)
- [Emulators](#emulators)
	- [PlayStation](#playstation)
	- [Nintendo](#nintendo)
	- [Sega](#sega)
	- [Arcade, DOS & Handheld](#arcade-dos--handheld)
	- [Multi-System Emulators](#multi-system-emulators)
	- [Other Consoles](#other-consoles)
- [Playing PC & Console Games on Linux](#playing-pc--console-games-on-linux)
- [ROM & Library Management](#rom--library-management)
- [Shaders & CRT Effects](#shaders--crt-effects)
- [Controllers & Input](#controllers--input)
- [Handhelds & Hardware](#handhelds--hardware)
- [Preservation & ROMsets](#preservation--romsets)
- [Communities](#communities)
- [Guides & Articles](#guides--articles)
- [Related Awesome Lists](#related-awesome-lists)

## Frontends & Emulation Operating Systems

- [Batocera](https://batocera.org) - Linux-based retro gaming OS that boots into a polished console interface with support for dozens of classic systems. Runs from a USB stick without touching the host computer.
- [RetroArch](https://www.retroarch.com) - Cross-platform frontend for the Libretro API, combining hundreds of emulator cores under one interface.
- [RetroBat](https://www.retrobat.org) - Windows-focused emulation frontend built around RetroArch and EmulationStation, an alternative to Batocera for machines that must keep Windows.
- [EmulationStation Desktop Edition](https://es-de.org) - A frontend that organizes emulators and games into a browsable, console-like library.
- [Recalbox](https://www.recalbox.com) - Emulation operating system for Raspberry Pi and x86 that boots into a friendly, console-style interface.
- [Lakka](https://lakka.tv) - Lightweight Linux distribution that turns a PC or single-board computer into a full RetroArch-based emulation console.
- [LaunchBox](https://www.launchbox-app.com) - Windows frontend that organizes emulators, ROMs, and game art into a browsable library, with Big Box as its full-screen mode.
- [Pegasus](https://pegasus-frontend.org) - Open-source, cross-platform emulator frontend with a themeable, game-focused interface.
- [OpenEmu](https://openemu.org) - macOS frontend that bundles dozens of emulators behind one clean, console-style interface.

## Emulators

### PlayStation

- [PCSX2](https://pcsx2.net) - The leading PlayStation 2 emulator, with a hardware renderer and wide game compatibility.
- [DuckStation](https://www.duckstation.org) - Fast, accurate PlayStation 1 emulator with modern enhancements like save states and upscaling.
- [ePSXe](https://www.epsxe.com) - Long-running PlayStation 1 emulator with high compatibility and plugin-based audio and video.
- [PPSSPP](https://www.ppsspp.org) - Fast and portable PlayStation Portable emulator that also runs on Android and other mobile platforms.
- [RPCS3](https://rpcs3.net) - The most advanced PlayStation 3 emulator; demanding on hardware but steadily improving.

### Nintendo

- [Dolphin](https://dolphin-emu.org) - Mature emulator for GameCube and Wii games with strong performance and online play support.
- [Cemu](https://cemu.info) - Wii U emulator with impressive game compatibility and native Vulkan support.
- [Snes9x](https://www.snes9x.com) - Classic Super Nintendo emulator known for broad game compatibility.
- [mGBA](https://mgba.io) - Fast Game Boy, Game Boy Color, and Game Boy Advance emulator focused on accuracy.
- [MelonDS](https://melonds.kuribo64.net) - Active Nintendo DS emulator with online play and homebrew support.
- [Mupen64Plus](https://mupen64plus.org) - Open-source Nintendo 64 emulator available as a plugin core for RetroArch.
- [Ryujinx](https://ryujinx.app) - Experimental Nintendo Switch emulator that steadily improves game compatibility.
- [bsnes](https://github.com/bsnes-emu/bsnes) - Cycle-accurate Super Nintendo emulator built for maximum hardware accuracy.

### Sega

- [Flycast](https://github.com/flyinghead/flycast) - Dreamcast and Naomi emulator with high compatibility and modern rendering options.

### Arcade, DOS & Handheld

- [MAME](https://www.mamedev.org) - The classic arcade machine emulator, preserving thousands of coin-op games.
- [FinalBurn Neo](https://github.com/finalburnneo/FBNeo) - Arcade emulator focused on CPS-1, CPS-2, and Neo Geo titles, distributed as RetroArch cores.
- [ScummVM](https://www.scummvm.org) - Recreates the engines of classic point-and-click adventure games.
- [DOSBox](https://www.dosbox.com) - Runs classic MS-DOS games and applications on modern operating systems.

### Multi-System Emulators

- [Mednafen](https://mednafen.github.io) - Multi-system emulator covering NES, SNES, PS1, Saturn, and more with accurate cores.
- [ares](https://ares-emu.net) - Multi-system emulator from former bsnes and higan developers with a focus on accuracy.

### Other Consoles

- [xemu](https://xemu.app) - Original Xbox emulator with growing compatibility and hardware emulation focus.

## Playing PC & Console Games on Linux

- [Proton](https://github.com/valveSoftware/proton) - Valve's compatibility layer that lets Windows games run on Linux via Steam, including many retro and indie titles.
- [Wine](https://www.winehq.org) - The long-running open-source compatibility layer for running Windows applications on Linux and macOS.
- [Lutris](https://lutris.net) - Game manager that wires up Wine, Proton, and emulators with per-game install scripts.
- [DXVK](https://github.com/doitsujin/dxvk) - Direct3D 9/10/11 to Vulkan translation layer, used by Proton and Wine to run DirectX games on Linux.
- [ProtonDB](https://www.protondb.com) - Crowdsourced compatibility reports telling you whether a Windows game runs under Proton.
- [Bottles](https://usebottles.com) - Desktop app that manages Wine prefixes and installs Windows games and software on Linux with minimal fuss.
- [Heroic Games Launcher](https://heroicgameslauncher.com) - Open-source launcher for Epic and GOG libraries that works with Wine, Proton, and cloud saves.
- [Winetricks](https://winetricks.org) - Script-driven helper for installing Wine components such as DirectX runtimes into prefixes.

## ROM & Library Management

- [RomM](https://romm.app) - Self-hosted web library that scans, organizes, and serves your ROM collection to browsers and emulator clients.
- [Steam ROM Manager](https://github.com/SteamGridDB/steam-rom-manager) - Scans emulated games and adds them to your Steam library with artwork for launching in Big Picture.
- [Skraper](https://www.skraper.net) - Downloads box art, videos, and metadata for your ROM collection across supported systems.
- [ScreenScraper](https://screenscraper.fr) - Community database of game metadata and media used by frontends to fill in library artwork.

## Shaders & CRT Effects

- [RetroArch Shader System](https://docs.libretro.com/technical/shaders/) - Built-in GPU shader pipeline that adds scanlines, curvature, and CRT emulation to any core.
- [CRT Royale & shader collections](https://github.com/libretro/glsl-shaders) - The libretro shader repository, home of the high-end CRT Royale and many other CRT filters.

## Controllers & Input

- [8BitDo](https://8bitdo.com) - Controller maker with Bluetooth and 2.4 GHz gamepads, many styled after classic retro pads.
- [Brook Gaming](https://brookgaming.com) - Arcade sticks and console adapters that let retro and modern controllers work across consoles and PCs.
- [Retro-Bit](https://retro-bit.com) - Licensed controller reproductions and accessories for classic consoles.
- [Hyperkin](https://www.hyperkin.com) - Retro console and accessory manufacturer known for controller reproductions and HDMI adapters.

## Handhelds & Hardware

- [Retroid Pocket](https://www.goretroid.com) - Line of Android-based retro handhelds with a built-in emulator-friendly launcher.
- [Steam Deck](https://steamdeck.com) - Valve's handheld PC that runs the full Steam library, including emulators, in the palm of your hands.

## Preservation & ROMsets

- [Redump](https://redump.org) - Database project cataloging optical disc dumps from PS1, PS2, Dreamcast, and more for preservation.
- [No-Intro](https://no-intro.org) - Community that maintains complete, verified ROM sets with no intro screen or modifications.
- [Vimm's Lair](https://vimm.net) - Long-running site hosting emulators and console game ROMs with a simple download model.
- [Romhacking.net](https://romhacking.net) - Archive of fan translations and ROM hacks for classic games.

## Communities

- [RetroAchievements](https://retroachievements.org) - Achievement system that adds challenges to thousands of classic games across emulators.
- [Libretro Forums](https://forums.libretro.com) - Discussion forum for RetroArch and the libretro core ecosystem.
- [r/RetroPie](https://www.reddit.com/r/RetroPie/) - Community around building Raspberry Pi emulation consoles with RetroPie.
- [r/SBCGaming](https://www.reddit.com/r/SBCGaming/) - Discussion of emulation handhelds and single-board computer gaming setups.

## Guides & Articles

- [Batocera Documentation](https://wiki.batocera.org) - Official setup, configuration, and hardware guidance for Batocera.
- [RetroBat vs Batocera (2026)](https://arcadesystems.co.uk/blog/post/retrobat-vs-batocera) - Comparison of the two popular emulation frontends and which hardware each suits.
- [Best Emulator Frontend 2026](https://arcadesystems.co.uk/blog/post/best-emulator-frontend-2026) - Honest comparison of retro gaming frontends for different setups.
- [D7VK brings Direct3D gaming to Linux](https://www.gamingonlinux.com/2026/04/d7vk-version-1-7-brings-even-more-retro-direct3d-gaming-to-linux/) - Covers translation layers that run older DirectX-era Windows games on Linux.
- [RetroPie Documentation](https://retropie.org.uk/docs/) - Official setup and configuration guides for RetroPie on Raspberry Pi.
- [RetroArch Documentation](https://docs.libretro.com) - Official docs covering cores, shaders, and configuration.
- [RetroRGB](https://www.retrorgb.com) - News and deep-dive articles on retro video output, scalers, and connecting retro consoles to modern displays.

## Related Awesome Lists

- [Awesome Game Development](https://github.com/ellisonleao/magictools#readme) - Tools and resources for making games, including emulation-adjacent tooling.
- [Awesome Node.js](https://github.com/sindresorhus/awesome-nodejs#readme)
- [Awesome Self Hosted](https://github.com/awesome-selfhosted/awesome-selfhosted#readme)
- [Awesome Mac](https://github.com/jaywcjlove/awesome-mac#readme)
- [Awesome Rust](https://github.com/rust-unofficial/awesome-rust#readme)

## License

[CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/)

This list is released to the public domain under CC0, so you are free to reuse it without restriction.
