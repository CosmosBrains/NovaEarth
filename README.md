## About

NovaEarth is a early foreshadow of the dreams of space explorstion, where every day, perhaps from the cockpit of a spaceship, we will look down on a competely new alien world and ask questions about it.

In NovaEarth, everyday, a new planet is generated, with unique terrain and character. Some might have rings, others have storms.

This program is (very) inspired by [Terranova](https://www.fourmilab.ch/terranova/) by John Walker, I highly recommend checking it out.

By the way, you can click/tap on the screen to generate a random planet.

I'm not entirely finished with the program, so I *might* add updates.

## How It Works

The program uses [FastNoiseLite](https://github.com/Auburn/FastNoiseLite) by Jordan Peck to generate the surface using perlin noise.

Perin noise is very good for realistic surfaces, since its random (enough) and rough.

The seed used for the daily random planet generation is based on "[YEAR][MONTH][DAY]". The values are joined (NOT ADDED!) and converted to numbers.

Everything else is simple variable handling and math.

I used Gamemaker as the underlying game engine (and therefore GML as the language)

All other assets and code (tilesets for example) were created by me.
