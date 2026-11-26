# fiesta end

This is the `world_the_end` folder from FiestaSMP, the Minecraft server at fiestamc.neocities.org. Snapshot date: 2026-11-26. It contains the End only; the matching Overworld and Nether are not included here.

## download

Open [Releases](https://github.com/open-fiestasmp/world-the-end/releases), choose `snapshot-2026-11-26-8`, and download **Source code (zip)**. Extract it. The folder with `level.dat` at its top level is the Paper End world folder. Rename it `world_the_end`; keep the files inside it, including `DIM1`.

## use it on a Paper server

1. Stop the server and back up your current world folders.
2. Put `world_the_end` beside your `world` and `world_nether` folders.
3. Use a compatible Overworld and the same Minecraft/Paper version. This release does not include the matching FiestaSMP Overworld, so it is not a complete server restore.
4. Start the server and check the console before players join.

For a normal Paper layout, the folders are `world`, `world_nether` and `world_the_end`, with `level-name=world` in `server.properties`. If you use custom names or a world manager, follow its config.

## use it in single-player

1. Back up an Overworld save that uses a compatible Java version.
2. Copy only `DIM1` from this archive into that save's root, beside `level.dat` and `region`. The target path should be `saves/YourWorld/DIM1`.
3. Keep the Overworld's `level.dat`; don't replace it with this folder's copy.

`DIM1/.world-tier/access` contains server access-time markers. Minecraft does not need them to load the End.

This is a community backup of FiestaSMP at fiestamc.neocities.org. We are not affiliated with Mojang or Microsoft, and this archive does not include or grant a Minecraft license.

Backed up and uploaded using Fiesta tools by `gautam652`.
