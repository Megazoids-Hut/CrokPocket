# CrokPocket

<img width="1842" height="1260" alt="main1" src="https://github.com/user-attachments/assets/4000c8d9-de82-4ac7-8eda-237685f31fbb" />\
\
CrokPocket is an ESP32-S3 based DIY retro gaming handheld running Retro-Go

I wanted the CrokPocket project files accessable on GitHub. The project is posted on the following sites, which will have full build instructions :  
https://www.hackster.io/megazoid/crokpocket-a0ff83  
https://www.instructables.com/CrokPocket

> YouTube short Demo/Build video : [https://www.youtube.com/watch?v=JDaKIfVzHpw](https://www.youtube.com/watch?v=JDaKIfVzHpw)
________________________________________________________________  
  
# Supplies

<img width="1376" height="902" alt="stuff1" src="https://github.com/user-attachments/assets/0238c3aa-a885-400d-9c49-d3193f4bb2eb" />
  
### Parts
1 x 2 inch TFT LCD Display - 240x320 - ST7789 [AliExpress](https://vi.aliexpress.com/item/1005008082410720.html)  
1 x 602550 Polymer Lithium Battery [AliExpress](https://vi.aliexpress.com/item/1005006898814536.html)  
1 x ESP32-S3 N16R8 [AliExpress](https://vi.aliexpress.com/item/1005008168727665.html)  
1 x Ghxamp Mini Speaker 8Ohm 1W - 34.8mm*11.2mm*6.0mm [AliExpress](https://vi.aliexpress.com/item/33035261832.html)  
10 x Buttons - hanxia HX TS5220A 160gf [LCSC](https://lcsc.com/product-detail/Tactile-Switches_hanxia-HX-TS5220A-160gf_C5340185.html)  
1 x Slide Switch - Shenzhen Kinghelm Elec KH-SS12F23-G6 [LCSC](https://lcsc.com/product-detail/Slide-Switches_Shenzhen-Kinghelm-Elec-KH-SS12F23-G6_C5274466.html)  
1 x 3.5mm Stereo Audio Jack Socket [AliExpress](https://vi.aliexpress.com/item/4001057731020.html)  
1 x G-Switch Card Slot MicroSD - GT-TF003-H0185-01 [LCSC](https://lcsc.com/product-detail/SD-Card-Memory-Card-Connector_G-Switch-GT-TF003-H0185-01_C5155563.html)  
1 x MOLEX PicoBlade(MX 1.25) - Mfr. Part #532610271 [LCSC](https://lcsc.com/product-detail/Wire-To-Board-Connector_MOLEX-532610271_C177225.html)  
1 x Female USB Connector 16pin [LCSC](https://lcsc.com/product-detail/USB-Connectors_SHOU-HAN-TYPE-C-16PIN-2MD-073_C2765186.html)  
1 x TP4056 [LCSC](https://lcsc.com/product-detail/Battery-Management_UMW-Youtai-Semiconductor-Co-Ltd-TP4056_C725790.html)  
1 x NS4168 [LCSC](https://lcsc.com/product-detail/Audio-Amplifiers_Shenzhen-Nsiway-Tech-NS4168_C910588.html)  
1 x CH340C [LCSC](https://lcsc.com/product-detail/USB-Converters_WCH-Jiangsu-Qin-Heng-CH340C_C84681.html)  
1 x 700mA Voltage Regulator - XC6210B332MR-G [LCSC](https://lcsc.com/product-detail/Voltage-Regulators-Linear-Low-Drop-Out-LDO-Regulators_Torex-Semicon-XC6210B332MR-G_C47719.html)  
1 x Transistor package - UMH3N [LCSC](https://lcsc.com/product-detail/Digital-Transistors_Jiangsu-Changjing-Electronics-Technology-Co-Ltd-UMH3N_C62892.html)  
1 x NPN Transistor - S8050 (J3Y) [LCSC](https://lcsc.com/product-detail/Bipolar-BJT_Guangdong-Hottech-S8050_C181158.html)  
2 x Buttons - GT-TC029B-H025-L1N [LCSC](https://lcsc.com/product-detail/Tactile-Switches_G-Switch-GT-TC029B-H025-L1N_C843669.html)  
3 x 0603 LEDs 3 Colours [AliExpress](https://vi.aliexpress.com/item/1005005431944057.html)  
2 x Schottky Diode [LCSC](https://lcsc.com/product-detail/Schottky-Diodes_Guangdong-Hottech-SS14L_C190475.html)  
5 x 0805 Capacitors 10uF [LCSC](https://lcsc.com/product-detail/Multilayer-Ceramic-Capacitors-MLCC-SMD-SMT_Samsung-Electro-Mechanics-CL21B106KPQNNNE_C32635.html)  
5 x 0603 Capacitors 100nF [LCSC](https://lcsc.com/product-detail/Multilayer-Ceramic-Capacitors-MLCC-SMD-SMT_YAGEO-CC0603KRX7R9BB104_C14663.html)  
1 x 0603 Capacitor 1uF [LCSC](https://lcsc.com/product-detail/Multilayer-Ceramic-Capacitors-MLCC-SMD-SMT_Samsung-Electro-Mechanics-CL10B105KA8NNNC_C29936.html)  
20 x 0603 SMD Resistors (See Schematic & PCB) [AliExpress](https://vi.aliexpress.com/item/1005006301580629.html?gatewayAdapt=glo2vnm)  
4 x M2 x 16mm Flat Head Hex Socket Screws [Amazon](https://www.amazon.co.uk/FandWay-Countersunk-Machine-Washers-Assortment/dp/B0B7JLDV6V/?th=1)  
1 x Silicone Rubber Sheet Thickness 0.5 [AliExpress](https://vi.aliexpress.com/item/1005006921978058.html)  
1 x Clear Grass Trimmer Line [Amazon](https://www.amazon.co.uk/Oregon-69-482-CL-Round-Strimmer-Trimmers/dp/B07SQKP6B3/)  
1 x Micro SD card 32gb [Amazon](https://www.amazon.com/dp/B0C1Y87VT3?th=1)  

### Hand Tools & Equipment  

Soldering iron + Solder Wire 40/60 + Solder Flux + Isopropyl  
A Hot Plate and 3d printer  
Watch Makers Loupe or other Magnification  
Kapton tape + Hot Glue + Sand Paper + Double Sided Tape  

The custom PCB can be ordered from a PCB fabrication manufacturer Like JLBPCB : [Gerber File Zip](https://github.com/Megazoids-Hut/CrokPocket/tree/main/gerber) (Use default PCB board settings. 1.6mm thickness etc. Just upload the gerber zip and order)
  
________________________________________________________________  
  
# Story

CrokPocket is the second in my series of handheld gaming devices that share a similar form factor. It's powered by an ESP32-S3 and runs Retro-Go firmware. This emulation software package supports NES, Game Boy, GBC, Master System, Game Gear, Doom, and other games. SNES and Genesis are also supported, but performance is poor. More information on Retro-Go can be found on its [GitHub repository](https://github.com/ducalex/retro-go)

This is a hobbyist DIY retro gaming handheld and does not compete with the hundreds of retro gaming handhelds flooding out of China. CrokPocket has similar performance to the iconic ESP32-based Odroid Go.

As with PicoPocket, review the bill of materials and instructions before diving in. There are a few "I'm not sure I can do this" micro-soldering moments (e.g. the 16-pin USB port). You will need a hot plate and advanced skills. I made it for myself only, and I don't do tech support. 

<b>Licensing</b>: My PCB files and STLs are released under The [Unlicense](https://unlicense.org/). Everything else retains the licenses assigned by their creators. I take no responsibility for anything.  
