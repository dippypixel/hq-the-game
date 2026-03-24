
LIVE INPUT DISPLAY "STICK" V2.5
should be compatible with both 4/3 && 16/9 resolutions

0) Drop the stick folder into your data folder
1) Open up your config.ini
2) data/stick/stick.const ADD TO Const SECTION
3) data/stick/stick.zss ADD TO States SECTION
4) data/stick/stick.def ADD TO Fx SECTION
5) Look at included config.ini as a example make sure if you have other assets the last one does not end with a , (comma)
6) Go to training mode stick should be active

############################################################################################################################
you can enable disable buttons in the constant folder
you can change button anims(comes with multiple colours) for both styles see examples
you can replace sprties be sure to keep the dimensions the same not to break placement of buttons
you can add constants to your char.def to have a unique stick config per char
eg

[constants]
stylej 	  = 1 ;##0- joystick capcom style 1-snk style
style 	  = 0 ;##0- button capcom style 1-snk style
styleu 	  = 1 ;## 0-underlay capcom style 1- snk style 
underlay = 1; ## background explod 0-off 1-on
plainunderlay = 1; ##semi-transparent underlay only works if underlay = 1

enjoy

Horse


