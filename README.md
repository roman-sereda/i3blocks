![alt tag](https://raw.githubusercontent.com/roman-sereda/i3blocks/55107125c890256b49f7bb29bbf50d32b5c6e786/screenshot/screenshot.png)


## Scripts
###CMUS
Instances: color, icon, max, mode

You can use three modes:
- `ti` - only title
- `ti_ar`- title with artist(if artist doesn't exists - only title)
- `ti_al` - title with album(if album doesn't exists - only title)
- `ti_al_ar` - title with artist & album

`max` - max string size

###CMUS CONTROLLS
I dont find anyway to create one file with three buttons, so instead we have three
script files in `cmus_controllers` folder.

####CMUS_NEXT
Instances: color, icon

####CMUS_PREVIOUS
Instances: color, icon

####CMUS_PLAY
Instances: color, icon_play, icon_pause


###KEYBOARD
Instances: color, icon, path

To use this, you need:
- to clone [xkblayout-state repository](https://github.com/nonpop/xkblayout-state).
- Make
- Add path to this repository to the path instance
`/home/username/xkblayout-state/`

###MEMORY
