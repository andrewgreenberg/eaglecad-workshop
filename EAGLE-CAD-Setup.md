# Make EAGLE Sane (only need to do once!)

## File Setup

- Download and install the latest version of EAGLE.
- Run it once. From the control panel, open an example schematic and layout.
- Download this repo and copy all files to the right place (SCRs to EAGLE/Scripts and DRUs to EAGLE/cam directories).

## Control Panel Setup

- Run EAGLE.
- The Control Panel should open up.
- Make your color choices sane.
   - Control Panel > "Options" > "User Interface"
      - Make sure "Layout" has "Background: Black" (IMPORTANT!)
      - Make sure "Schematic has "Background: White"
- Stop reseting to default literally every time you run EAGLE
   - Control Panel > "Open" > "Scripts" > "eagle.scr"
   - Comment out `SCRIPT default-eagle.scr`

## Schematic Setup

- "Projects" > "Examples" > "Arduino" > `Arduino_MEGA2560_ref.sch`
- Type `scr` to run a script.
- Choose `assign-hotkeys-for-schematic.scr`.
- Test the script: zoom in, then type `ctrl-f` to fit the window to the screen.
- If you can't pan and you want to:
   - Type `scr` to run a script.
   - Choose `assign-control-for-panning.scr` - now holding down the control key will pan!
- Save, so that your changes save.

## Layout setup

- From within the Schematic editor, click on the board button (or type `board`).
- Type `scr` to run a script.
- Choose `assign-hotkeys-for-layout.scr`.
- Test the script: zoom in, then type `ctrl-f` to fit the window to the screen.
- If you can't pan and you want to:
   - Type `scr` to run a script.
   - Choose `assign-control-for-panning.scr` - now holding down the control key will pan!
- Save, so that your changes save.
