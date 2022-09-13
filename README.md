# BEAMAL Rev. 1 
    A Custom Replacment PCB and case, using the IBM 6580 Displaywriter System as a base
                                            
![BEAMal Rev1_Top](https://user-images.githubusercontent.com/61422584/189928543-537204ac-b27b-4bec-93df-06f02b2ea461.png)
![BEAMal Rev1_Bottom](https://user-images.githubusercontent.com/61422584/189928587-36792f6f-f6df-4fae-aa94-edf01e585f31.png)

All Supported Layouts can be seen [HERE](http://www.keyboard-layout-editor.com/#/gists/b96d65da63be744e5e54532b00e9445a)

xwhatsit/QMK atmega32u4 pcb for the IBM Model F XT and IBM Bigfoot

This version has NOT YET been tested, THIS IS A SMALL PRODUCTION OF 5 UNITS, NEVER TO BE SOLD AGAIN
- The firmware can be found in the firmware folder
- All files for production though JLCPCB can be found in the JLCPCB folder
- This pcb requires an xwhatsit to function, see [purdeaandrei's open source files](https://github.com/purdeaandrei/SMDModelFController)
- Note, even though this is a beamspring pcb, it will use a model F xWhatsit replacment controller
- Test Points are currently on the pcb, when building make sure to cover the bottom test points with eletrical tape to prevent a short
- The barrel Plate will need to be modified, A replacment barrel plate file will be provided with the custom case files

The PCB thickness should be 0.6mm or 0.08mm. This is thin enough to allow the board to flex into shape.
- 0.8mm tested and working

Standard glossy soldermask is probably the best choice. JLCPCB has had issues with wear on their black soldermask before. They have changed the formula, but a standard green/red/blue/yellow/purple/white/etc. glossy solder mask is probaby the safest bet for keyswitch wear resistance. Higher wear resistance might also be achieved by coating the front of the capacitive pads in silkscreen, as silkscreen is an extra layer of epoxy. I am unsure how this will affect keyfeel or actuation, however.

For connecting the board to an xwhatsit or other controller, I would recommend [3M 8132/06 100](https://www.digikey.com/en/products/detail/3m/8132-06-100/7809902), which has the correct pitch to connect this pcb to an xwhatsit

Capacitive pad footprints have been created spificly for this project, as the White whale beamspring has an off axis footprint aligment. In order to stay true to the origional desigen philosphy, that change has been made here also. Thank you to  All mesurements have beeen take from an origonal IBM Displaywrighter system (BAE). The key matrix of the PCB is custom, made by myself, guided purdeaandrei.

Released without warranty, use at your own risk.  
PRs & feedback welcome!

| Authors | 

Alectardy98

| Special Thanks |
   
purdeaandrei - For many things, this project would not have happened without him.
