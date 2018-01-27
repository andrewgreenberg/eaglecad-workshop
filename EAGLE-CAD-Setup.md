# Configuring EAGLE 8 to be slightly sane (only need to do once!)

2018/01/26 - From the `eaglecad-things` repo (written for EAGLE 8.6.0). Copy all files in the repo to the right place (SCR and DRU directories).

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


## Library Setup

- From within the Schematic editor, type `use`
- Select all Libraries by typing Ctrl-A.
- Choose 'Remove' (don't worry, isn't deleting anything, and you don't want all that junk).
- Choose "Available" tab.
- Expand the `Name` column so you can see the whole name.
- Click on "Author" to sort the libraries by Author.
- Select ALL of the SparkFun libraries and choose "Use".
- Select AdaFruit libraries and choose "Use"
- Under "EAGLE PCB", select the following vaguely useful libraries:
   - atmel
   - crystal
   - diode
   - frames
   - holes
   - led
   - pinhead
   - rcl
   - supply1
   - supply2
   - testpad
   - transistor
- Choose "Use"
- Note that there are lots of other libraries; feel free to browse!
- Close the Library window.


## Layout setup

- From within the Schematic editor, type `board`.
- Type `scr` to run a script.
- Choose `assign-hotkeys-for-layout.scr`.
- Test the script: zoom in, then type `ctrl-f` to fit the window to the screen.
- If you can't pan and you want to:
   - Type `scr` to run a script.
   - Choose `assign-control-for-panning.scr` - now holding down the control key will pan!


