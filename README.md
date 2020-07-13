# ms_releases
This contains ModularSensor releases that may be downloaded to the specified platform.

mayfly_tu_LT5_200708_1708_0.25.0firmware.hex  ~ Interfaces to LT500/SDI-12/B033(J6 data pin7), and Acculevel RS485, using RS485 wingboard. Transmits to MMW using Digi LTE cell, which has been tested using apn "VZWINTERNET"  and "hologram"     
mayfly_tu_EC01_200708_1726_0.25.0firmware.hex ~ relative "Electrical Conductivity" sensors using B032 board. Standalone recording to uSD, and uses 3.6V battery.     
mayfly_tu_id01_200418_1432.hex ~ CTD sensor interface. Transmits to MMW using Digi LTE cell, which has been tested using apn "VZWINTERNET"  and "hologram"    

to download to Mayfly :         
prog_mayfly file.hex  COMxx           
  requires tool avrdude to be on path. See https://www.nongnu.org/avrdude/   
