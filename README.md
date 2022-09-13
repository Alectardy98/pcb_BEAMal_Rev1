# FXTal Rev. 2 
    A Drop In Replacement PCB For The IBM Model F XT
                                            
![FXTal Rev2 Top](https://user-images.githubusercontent.com/61422584/179572550-0d33e4d3-237b-4558-9665-d15da1065a68.png)
![FXTal Rev2 Bottom](https://user-images.githubusercontent.com/61422584/179572566-d7b1beae-03b3-488a-b2fd-5e3fa2ef4441.png)


All Supported Layouts can be seen [HERE](http://www.keyboard-layout-editor.com/#/gists/daab9567d1fe4691fd52719a6adab8b0)

xwhatsit/QMK atmega32u4 pcb for the IBM Model F XT and IBM Bigfoot

This version has been tested and has shown to function properly, THIS IS A SMALL PRODUCTION OF 5 UNITS, NEVER TO BE SOLD AGAIN
- The firmware can be found in the firmware folder
- All files for production though JLCPCB can be found in the JLCPCB folder
- This pcb requires an xwhatsit to function, see [purdeaandrei's open source files](https://github.com/purdeaandrei/SMDModelFController)
- Test Points are currently on the pcb, when building make sure to cover the bottom test points with eletrical tape to prevent a short
- The origonal backplate will need to be modified to remove the right PCB mounting peg, to prevent interfearance
- The barrel Plate will need to be modified, a scan of the required holes are provided in folder meta, to help with the task

The PCB thickness should be 0.6mm or 0.08mm. This is thin enough to allow the board to flex into shape.
- 0.8mm tested and working

Standard glossy soldermask is probably the best choice. JLCPCB has had issues with wear on their black soldermask before. They have changed the formula, but a standard green/red/blue/yellow/purple/white/etc. glossy solder mask is probaby the safest bet for keyswitch wear resistance. Higher wear resistance might also be achieved by coating the front of the capacitive pads in silkscreen, as silkscreen is an extra layer of epoxy. I am unsure how this will affect keyfeel or actuation, however.

For connecting the board to an xwhatsit or other controller, I would recommend [3M 8132/06 100](https://www.digikey.com/en/products/detail/3m/8132-06-100/7809902), which has the correct pitch to connect this pcb to an xwhatsit



Capacitive pad footprints have been taken dvjs project the mtf-capacitive Other mesurements have been taken by NeonKight and myself from an origonal IBM F XT. The key matrix of the PCB is custom, made by myself guided by dvjs and purdeaandrei.

Released without warranty, use at your own risk.  
PRs & feedback welcome!

| Authors | 

Alectardy98

| Special Thanks |

djvs - for generial and overall help.   
NeonKnight - for mesurments and reversenginering.   
purdeaandrei - for writing the QMK firmware to work with xwhatsit.   
