# Terratonizer

A fork of [Tectonic](https://github.com/Apollounknowndev/tectonic) by Apollo, customized for the **Titans of The Void: Ascension** modpack.

## What is Terratonizer?

Terratonizer is a terrain generation mod for Minecraft 1.20.1 (Forge) based on Tectonic. It modifies the world generation to create more dramatic and varied terrain.

## Custom Changes

- **Taller build height**: Y=-144 to Y=720 (864 blocks total) via the `increased_height` option
- **Natural mountain peaks**: Mountain-top taper raised toward the build limit so peaks come to jagged points instead of flat sliced tops
- **Sharper mountains**: Increased jaggedness and vertical scaling for more dramatic peaks
- **Deep dry caverns**: Stronger cave-layer noise for larger chambers, open cheese caves, and rock pillar columns (3× more common)
- **Less flooding**: Aquifer flooding dampened for dry caves with occasional water pools
- **Lava moved deep**: Lava aquifers now only generate below Y=-135
- **Fixed terrain generation**: Corrected depth gradient and biome placement

## Requirements

- Minecraft 1.20.1
- Forge
- Lithostitched (library dependency)

## Installation

Place the `terratonizer-forge-1.20.1-2.4.5.jar` file in your Minecraft `mods` folder.

## Credits

- Original mod: [Tectonic](https://github.com/Apollounknowndev/tectonic) by Apollo
- Fork created for: **Titans of The Void: Ascension** modpack
