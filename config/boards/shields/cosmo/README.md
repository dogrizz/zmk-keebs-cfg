# Cosmo keyboard
It's 3x6 + 3 split keyboard with 34mm trackball.

Generated using: https://ryanis.cool/cosmos/

Intended for use with nice!nano and ZMK.

For trackball sensor use PWM 3610. 
Matching breakout can for sensor can be found here: https://github.com/siderakb/pmw3610-pcb

Instead of handwiing consider single key boards: https://github.com/kissetfall/su120-keyboard/releases/tag/gerber

Firmware based on [corne](https://github.com/zmkfirmware/zmk/tree/main/app/boards/shields/corne).

BOM:
- 2 nice!nano
- 42 switches + keycaps
- 3 1/8" diameter ceramic ball bearings (Si3N4/Zr02)
- 1 PWM 3610 sensor
- 1 34mm ball
- 42 1N4148 Diodes (if using single key boards consider smd)
- 18 M3 x 6mm flat head screws
- 2 M3 x 10 mm flat head screws for attaching mcu holder
- 20 M3 screw inserts
- \>= 9 rubber or silicone feet
- printed parts from [parts](parts/) directory
Optional:
- Li-Po battery
- on/off switch
- reset switch
