# ms_releases
This contains ModularSensor releases that may be downloaded to the specified platform.
to download to Mayfly :

On Windows open a cmd window and step to where the file is
 attach USB cable on host, plugin to USB on Mayflay, not what COM it is

$prog_mayfly <file.hex> COMxx

See https://github.com/neilh10/ModularSensors/releases

eg https://github.com/neilh10/ModularSensors/releases/tag/v0.34.1-abe

https://github.com/neilh10/ModularSensors/releases/tag/v0.25.0.release1_200906

mayfly0.25.0_200825_tt_tu_yyy.hex      
- Added build names, and rotating POST log file, DBGYYMM.log . Soak tested.   
https://github.com/neilh10/ModularSensors/releases/tag/v0.25.0.release1_200825    
see 2020 Aug  https://github.com/neilh10/ModularSensors/wiki/2a-Release-Notes    

mayfly0.25.0_200812_tt_tu_yyy.hex - guarenteed data delivery.   

mayfly_tu_NAME_200708_1708_0.25.0firmware.hex    
- LT5  ~ Interfaces to LT500/SDI-12/B033(J6 data pin7), and Acculevel RS485, using RS485 wingboard. Transmits to MMW using Digi LTE cell, which has been tested using apn "VZWINTERNET"  and "hologram"       
- EC01_200708_1726_0.25.0firmware.hex ~ relative "Electrical Conductivity" sensors using B032 board. Standalone recording to uSD, and 3.6V battery.      


mayfly_tu_id01_200418_1432.hex ~ CTD sensor interface. Transmits to MMW using Digi LTE cell, which has been tested using apn "VZWINTERNET"  and "hologram"    

to download to Mayfly :         
prog_mayfly file.hex  COMxx           
  requires tool avrdude to be on path. See https://www.nongnu.org/avrdude/   
