# Nsumo hardware
This repository contains the schematic and PCB design of Nsumo, a mini-class Sumobot (500g 10x10cm),
created in KiCad, and manufactured by JLCPCB. It's a 2-layer PCB with microcontroller MSP430G2553IPW28,
regulators 3.3V (AMS1117-3.3) and 5V (MP2359), two motor drivers TB6612FNG, IR receiver TSP382, and
circuit protection (RS3E075AT).

<img src="/imgs/schematic.png">

<img src="/imgs/pcb.png">

<img src="/imgs/nsumo.jpg">

## Setup
Import the project into KiCad >6.0 and make sure you have the "default global symbol library table"
and the "default footprint library" available. KiCad should find the 3Dmodels and symbols under _libs/_
automatically. You must manually import the footprints under _libs/footprints/_ (select "file/add library"
from the menu in the footprint editor and add them to the project).
