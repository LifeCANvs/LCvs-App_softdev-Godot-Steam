# GodotSteam Multiplayer Peer for GodotEngine
An open-source and fully functional Steamworks SDK / API module and plug-in for the Godot Game Engine (version 4.x) mixed with the multiplayer peer for Godot's high-level networking. It allows you to use Godot's RPC and `MultiplayerSynchronizer`/`MultiplayerSpawner` nodes. For the Windows, Linux, and Mac platforms.

Additional Flavors
---
Pre-Compiles | Plug-ins | Server | Examples/Demos
--- | --- | --- | ---
[Godot 2.x](https://github.com/CoaguCo-Industries/GodotSteam/tree/godot2)| [GDNative](https://github.com/CoaguCo-Industries/GodotSteam/tree/gdnative) | [Server 3.x](https://github.com/CoaguCo-Industries/GodotSteam-Server/tree/godot3) | [Godot 3.x](https://github.com/CoaguCo-Industries/GodotSteam-Example-Project/tree/godot3)
[Godot 3.x](https://github.com/CoaguCo-Industries/GodotSteam/tree/godot3) | [GDExtension](https://github.com/CoaguCo-Industries/GodotSteam/tree/gdextension) | [Server 4.x](https://github.com/CoaguCo-Industries/GodotSteam-Server/tree/godot4) |  [Godot 4.x](https://github.com/CoaguCo-Industries/GodotSteam-Example-Project/tree/godot4)
[Godot 4.x](https://github.com/CoaguCo-Industries/GodotSteam/tree/godot4) | --- | [GDNative](https://github.com/CoaguCo-Industries/GodotSteam-Server/tree/gdnative) | [Server 3.x](https://github.com/CoaguCo-Industries/GodotSteam-Example-Project/tree/server3)
[Multiplayer Peer](https://github.com/CoaguCo-Industries/GodotSteam/tree/multiplayer-peer) | --- | [GDExtension](https://github.com/CoaguCo-Industries/GodotSteam-Server/tree/gdextension) | [Server 4.x](https://github.com/CoaguCo-Industries/GodotSteam-Example-Project/tree/server4)

Documentation
---
[Documentation is available here](https://godotsteam.com/). You can also check out the Search Help section inside Godot Engine after compiling it with GodotSteam.

Feel free to chat with us about GodotSteam on the [CoaguCo Discord server](https://discord.gg/SJRSq6K).

Current Build
---
You can [download pre-compiled versions _(currently v4.6-mp)_ of this repo here](https://github.com/CoaguCo-Industries/GodotSteam/releases).

**Version 4.7 Changes**
- Added: in-editor docs, ***thanks to grossqx***

[You can read more change-logs here](https://godotsteam.com/changelog/multiplayer_peer/).

Compatibility
---
While rare, sometimes Steamworks SDK updates will break compatilibity with older GodotSteam versions. Any compatability breaks are noted below. Newer API files (dll, so, dylib) _should_ still work for older versions.

Steamworks SDK Version | GodotSteam Version
---|---
1.59 or newer | 4.6 or newer
1.58a or older | 4.5.4 or older

Known Issues
---
- Steam overlay will not work when running your game from the editor if you are using Forward+ as the renderer.  It does work with Compatibility though.  Your exported project will work perfectly fine in the Steam client, however.
- **Using MinGW causes crashes.** I strongly recommend you **do not use MinGW** to compile at this time.

"Quick" How-To
---
For complete instructions on how to build the GodotSteam Multiplayer Peer, [please refer to our documentation's 'How-To Multiplayer Peer' section.](https://godotsteam.com/howto/multiplayer_peer/) It will have the most up-to-date information.

Alternatively, you can just [download the pre-compiled versions in our Releases section](https://github.com/CoaguCo-Industries/GodotSteam/releases) and skip compiling it yourself!

Donate
---
Pull-requests are the best way to help the project out but you can also donate through [Github Sponsors](https://github.com/sponsors/Gramps)!

License
---
MIT license