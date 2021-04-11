# Blue Wizard Mod

This is an open source bluetooth controller for the Kinesis Advantage and Advantage 2 (see below) line of keyboards using the BlueMicro firmware.

Firmware can be found here. https://github.com/wizarddata/BlueMicro_BLE/tree/blue-wizard-working

For now, use the fork linked above to make any layout changes and utilize the adafruit nrf52832 BSP.

Gerbers and BOM are available if you'd like to build your own! If you're interested in purchasing an assembled mod email me at andrew.wells88@gmail.com or check out my etsy store. If you're so inclined, I can install a mod in your keyboard as well.
 
 https://www.etsy.com/shop/WizardKeyboards?ele=shop_open
 
![Image_of_Rev0](https://github.com/wizarddata/Blue-Wizard-Mod/blob/master/Pictures/20200911_090510.jpg)

You will need some additional hardware to make your board functional. Links are provided below for guidance:

1) Latching/Toggle/Rocker panel mount switch for power, or bridge J14 pins for always on. 

 https://www.sparkfun.com/products/11138

2) USB-C panel mount extension.
 
 https://www.amazon.com/dp/B08169ZB5C/ref=cm_sw_r_cp_api_glt_fabc_G1MT1V5PB9B76P2SWG2N?_encoding=UTF8&psc=1
 https://www.sparkfun.com/products/15455  
 
3) Momentary panel mount switch for reset (optional, reset switch is onboard).

 https://www.sparkfun.com/products/11995

4) LiPo battery.

 https://www.sparkfun.com/products/13855
 

***Advantage 2 Troubleshooting***  
Some keyboards experience intermittent joined activations on function keys. Installing a jumper wire from the negative battery connection to the ground pin of the 3.3v regulator can help resolve this issue. The necessary wire is pictured here:  
https://github.com/wizarddata/Blue-Wizard-Mod/blob/master/Pictures/Advantage_2_Wire.jpg  
Some users have reported F1 simultateously triggering F2. A 10k resistor between the pins pictured here will resolve this.  
https://github.com/wizarddata/Blue-Wizard-Mod/blob/master/Pictures/pull%20up%201.jpg  
https://github.com/wizarddata/Blue-Wizard-Mod/blob/master/Pictures/pull%20up%202.jpg
