# eaglecad-things

## Setting Up EAGLE 8 for the first time

- In the Control Panel
   - Go to "Options" and choose "User Interface".
   - Make sure "Layout" has "Background: Black"
   - Make sure "Schematic has "Background: White"
- Make a new project
- Make a new schematic.

## EAGLE Schematic Setup (only need to do once for schematic)

- Use the 'scr' command to run `assign-hotkeys-for-schematic.scr`.
- If you can't pan: use the `scr` command to run `assign-control-for-panning.scr`.
- Type `use` to open the Library Manager.
- In the "In Use" tab, select all and hit "Remove". You don't want all that junk.
- Click on the "Available" tab.
- Organize the library list by "Author".
- Select all of the SparkFun and AdaFruit libraries. Seeed too if you want.
- Select the following useful EAGLE libraries:
    - atmel
    - frames
    - pinhead
    - rcl
    - supply1
    - supply2
    - testpad
    
## New Schematic Setup (Do everytime you start a new schematic

- Switch grid to 0.5 x 2: `grid 0.5 2 on`
- Control+1 to set the right layers.
- Add a frame (usually start with 11 x 17, make it smaller later if you want, place on origin.
- Add all the things.
- Run `ERC` before you make the board.
- Make the board!

## EAGLE Layout Setup (only need to do this once for layout)

- Use the 'scr' command to run `assign-hotkeys-for-layout.scr`.
- If you can't pan: use the `scr` command to run `assign-control-for-panning.scr`.


## Mew Layout Setup (Do everytime you start a new layup)

- Type `drc` and click "Load" and load in your DRC file (.DRU file) (e.g., `osh-park-2-layers-design-rules.dru`).
- Type `grid mm` then `grid 0.1 on`, or `grid 0.5 on` if you like a courser grid.

