# Make EAGLE 9 Sane (only need to do once!)

2019/01/19 - From the `eaglecad-things` repo (written for EAGLE 9.2.2). Copy all files in the repo to the right place (SCR and DRU directories).

## Control Panel Setup

- Run EAGLE.
- The Control Panel should open up.
- "Options" > "User Interface"
   - Make sure "Layout" has "Background: Black" (IMPORTANT!)
   - Make sure "Schematic has "Background: White"


## Schematic Setup

- "Projects" > "Examples" > "Arduino" > `Arduino_MEGA2560_ref.sch`
- Type `scr` to run a script.
- Choose `assign-hotkeys-for-schematic.scr`.
- Test the script: zoom in, then type `ctrl-f` to fit the window to the screen.
- If you can't pan and you want to:
   - Type `scr` to run a script.
   - Choose `assign-control-for-panning.scr` - now holding down the control key will pan!
- Type `scr` to run a script
- Choose `legacycolors` to make everything actually bearable.
- Save, so that your changes save.

## Layout setup

- From within the Schematic editor, type `board`.
- Type `scr` to run a script.
- Choose `assign-hotkeys-for-layout.scr`.
- Test the script: zoom in, then type `ctrl-f` to fit the window to the screen.
- If you can't pan and you want to:
   - Type `scr` to run a script.
   - Choose `assign-control-for-panning.scr` - now holding down the control key will pan!
- Type `scr` to run a script
- Choose `legacycolors` to make everything actually bearable.
- Save, so that your changes save.
