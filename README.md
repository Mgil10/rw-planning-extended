# Planning Extended

This mod adds learning XP for stonecutting again, as well as bulk recipes, cutting three chunks at once.

## Features

### Implemented

- Draw colored designations, such as walls, doors, objects and floors
- Optionally skip (don't overwrite) already placed plan designations
- Use different shapes, e.g. rectangle, area, cross
- Load / Save plan blueprints, quickly select last loaded plans
- Cut / Copy / Paste your plans
- Undo / Redo your planned actions
- Show / Hide your planning designations (incl. global shortcut)
- Change plan texture sets and opacity for each plan type individually
- Convert your plan from vanilla Rimworld or MorePlanning mod

### Coming soon

- Add more shapes, such as lines, grids and circles
- Add shape options, e.g. inner grid margin, rotate cross, ...
- Improved grabbing position while pasting

### Planned

- Toolbox
- Text overlay to describe areas
- Display wall designations according to surrounding walls

## Shapes

- Lines (Rotation, Width)
  - Line
  - Cross
- Rectangle
  - Open (Rotation, Width)
  - Grid (Rotation, Number of Segments)
  - Area (Rotation)
- Circle
  - Open Ellipse (Width)
  - Filled Ellipse
- Fixed
  - Max Room-Size
  - Sun-Lamp
  - Orbital-Trade-Station

## Shortcuts
- Q, E: Rotation
- Z, X: Flip, Width, Number of Segments
- V: Change Shape-Variant
- Ctrl: Color-Picker
- Alt: Skip / Replace
- Shift: Square

## FAQ

Can this mod be safely added and removed at any time?

> This mod can be added at any time. By removing this mod you will get a one-time error message and lose all your planning designations. Other than that, you should be fine.

I feel this mod is missing something or could be improved!
> Feel free to make any suggestions on [GitHub](https://github.com/Scherub/rw-planning-extended/). If you feel confident, you're more than welcome to branch the code and create a pull request for a newly implemented feature.


I really want this mod available in my native language!
> Unfortunately, I'll have to rely on the community here. So if you would like to support the project, feel free to translate this file (link coming soon).

Why does my performance decrease when I paint lots of planning designations?
> The problem is, that the designations aren't rendered in a batched call. When I add about 20.000 designations and fully zoom out (using Camera+), my FPS takes a slight hit. You will encounter the same problem, when using the MorePlanning mod or vanilla paint-tool (for floors or buildings/structures) and add that many designations.

## Installation

* Go to the [Steam Workshop page](https://steamcommunity.com/sharedfiles/filedetails/?id=2877392159) and subscribe to the mod.