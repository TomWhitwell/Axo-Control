# Control board for Axoloti 

This is an unnoficial knob board for the [Axoloti Core board](http://www.axoloti.com/).  It is not authorised or approved by Axoloti. 

Quick demo video: https://www.instagram.com/p/BAqbNhdjmaf/   
Another demo video: https://www.youtube.com/watch?v=lhx-O6MQIug  

## BOM  
1 x PS2/3 analogue joystick, available from [Sparkfun](https://www.sparkfun.com/products/9032) or [Cool Components](https://www.coolcomponents.co.uk/thumb-joystick.html)  

6 x 10k Potentiometers
- 9mm vertical pots 
- Linear taper, any value from 5k to 50k should be fine
- D Shaft (or whatever is suitable for your knobs)
- Try: Bourns PTV09A-4020F-B103 or Alps RK09K1130C79
- Or Alpha 9mm from [Thonk](https://www.thonk.co.uk/shop/alpha-9mm-pots/) 
- NB: If you can't find the Joystick, there is a space for a 7th pot underneath

3 x 12mm square tactile switches
- Multicomp MCDTS2-4R is the right switch, but it seems to be a fairly standard layout 
- The board also has space for standard little 6mm tactile switches
- You can get keycaps for the Omron 12mm switches:Black: KTSC-21K, White: KTSC-21I, Yellow: KTSC-21Y, Red: KTSC-21R. (

4 x 1k Resistors for LEDs (use higher values - 5k to 10k if you have ultrabright LEDs) 

4 x 3mm LEDs

4 x 11mm M3 Hex Standoffs to connect the control board to the main Axoloti Core PCB

*NB: Ignore these headers: The way the board has come out, it's impossible to solder them in, and the board is perfectly strong without them.*  2 x 2 pin Female Header 571-215297-2 to mount on the back of the Control board to provide support by connecting to pins on the X3 and X4 headers. There is no electrical connection here. 

1 x 40 pin Female Header to mount on the Axoloti core 

1 x 40 pin Male Header to mount on the Control board

## STATUS 
January 2016: Board built, works well. OSHPark project here: https://oshpark.com/shared_projects/XJm2ysZW  
Video here: https://www.instagram.com/p/BAqbNhdjmaf/   
December 2015: Design completed for Rev1 board, prototypes ordered from OSH Park. Design, BOM, Layout NOT VERIFIED. 

## LICENSE 
This project is Open Hardware  
All hardware and software design in this project is Creative Commons licensed by Tom Whitwell: CC-BY-SA: Attribution / ShareAlike.  
If you use any work in this project, you should credit me, and you must republish any changes you make under the same license.  
This license does permit commercial use of these designs, but consider getting in touch before selling anything.  
This license does not include or imply any connection to the Axoloti project by Johannes Taelman.   
