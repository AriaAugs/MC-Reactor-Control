# About

This program manages a single reactor from BigReactors using ComputerCraft. While nowhere near as fancy as the other scripts that use GUIs and automatically optimize control rods, this script is still efficient and works well. Simply attach an advanced computer to your reacor's computer port, run `pastebin get Hm4tGphD startup`, edit control variables as needed, then reboot the computer.

# Control Parameters

The program has 3 different variables that you can edit. The variable names, types, and descriptions are as follows:

| Name | Type | Default | Description |
| --- | --- | --- | --- |
| debug_info | boolean | false | If set to true, the program will display info about the reactor every 10 seconds. The information contains the raw energy stored, the percentage energy stored with respect to the shut-off amount, and the current control rod insertion. |
| shutOff | float | 0.50 | Once the reactor's energy storage is this filled to this percentage, the reactor control rods will be completely inserted, effectively shutting off the reactor. |
| minInsertion | int | 0 | This is the minimum allowed control rod insertion. At 0% energy capacity, the reactor's fuel rods will be inserted by this amount. |
