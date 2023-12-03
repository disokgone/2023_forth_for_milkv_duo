# 2023_forth_for_milkv_duo
a forth program for milkv duo

This program is modified from --- (ESPForth AIBOT) https://github.com/flagxor/espforth

some forth commands were not modified (such as "P0"), may cause Segmentation fault..

the blue led can be turned on by:
   1  25  pin
   
the blue led can be turned off by:
   0  25  pin

to quit program:
   bye

to change GPIO pin mode by:
   (mode) (GPIO_pin_number) pinmode
   (mode: 0=not set,  2=input mode,  4=output mode, 8=Interrupt mode)

... more data please take a reference to : https://github.com/wiringX/wiringX/blob/master/src/wiringx.h

Great thanks to Brad Nelson (flagxor) and CH Ting...
