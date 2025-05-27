
### **STILL W.I.P. IM NOT RESPONSIBLE FOR ANY PROBLEM YOU MIGHT HAVE AND POSSIBLE DAMAGE TO THE VEHICLE.**
### **I AM A COMPSCI GRADUATE, NOT AN ELETRICAL ENGINEER, THERE MIGHT BE SOME ERRORS IN MY IMPLEMENTATION.**

## Speeduino v0.4.X adapter for OBD1 vehicles

This repo is dedicated for an adapter to Honda OBD1 (civic MA/MB and probably MC // british made Civic. maybe also PNP for japan made ones like eg/ek with adapter) PnP connector to interface with speeduino 0.4.X.
This project was made in altium designer, might one day put it in kicad but i dont really have the skills in kicad yet for it. in a bit i will upload the Gerber files.

- In this PCB, its used the "OBD1" 64pin connector PN:174518-7.
- There will be wideband connector pins, and place for a wideband controller, where you will be able to use the stock O2 sensor OR the wideband.

## The pin names will be based on this schema.
![schematic_ma_mb_mc_ civic](https://github.com/user-attachments/assets/2b6a3030-c109-47f1-861a-2c1b5663e9d2)

## the board will look like this:
![image](https://github.com/user-attachments/assets/a9731034-c55a-4e95-91d3-ba7a5337a097)

### 27/5 : Tested and working-ish
The car seemed to start just fime, altough i forgot to add ground for sensors, in which, i made it using a cable as a jumper. all is good.
Sorry for bad quality picture.

I think its a good place to add that you need a "JDM" style VR conditioner. official designs using max992 chip isnt really suited for this aplication.

![image](https://github.com/user-attachments/assets/73624382-c65b-4450-93af-459a8ca3eb67)


you can find the connector for cheap on aliexpress (many places its discontinued)
https://pt.aliexpress.com/item/1005006126524106.html?spm=a2g0o.order_list.order_list_main.5.65a3caa4wb4JMO&gatewayAdapt=glo2bra
** UPDATE: THIS CONNECTOR ALTOUGHT HAS A DIFERENT P/N IS AN EXACT FIT. **
# link to my website:
# https://goncaloferraz.vercel.app/home
