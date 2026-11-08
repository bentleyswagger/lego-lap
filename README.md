# Lego Lap

A simple Lego car racing game that runs in a web browser. Built by Jeremy and Bentley.

Race a Lego car around a brick-studded track, dodge the loose bricks, and try to beat your best time.

## How to play

Open `index.html` in any web browser. There is nothing to install.

| Key | What it does |
|-----|--------------|
| Arrow keys or WASD | Drive (gas, brake, steer) |
| Left / Right | Choose a track or car on the menus |
| Space or Enter | Pick, start the race, or choose from the finish menu |
| R | Put the car back on the start line |
| C | Change your car |
| T | Change the track |
| M | Sound on / off |

A race is 3 laps. Hitting a loose brick slows you down and scatters the bricks. The grass slows you down too.

## Where to make changes

Everything is in the one `index.html` file, with plain JavaScript. Look for these near the top of the code:

- `CONFIG`: how the game feels (speed, turning, brick slowdown, number of laps)
- `THEME`: the colors of the baseplate, road, and bricks
- `CARS`: the cars (colors, shape, and the minifigure driver). Add a new car here!
- `TRACKS`: the tracks. A new track is a list of points that the code smooths into a loop.

## Ideas for later

- Best time saved for each track
- More cars and more tracks
- A new theme (space, city, castle)
- Power-ups, boost pads, or a ghost car of your best lap
