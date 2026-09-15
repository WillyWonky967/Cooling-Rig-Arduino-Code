# Cooling-Rig-Arduino-Code
This is the code that is used to program the arduino to read and write data to the SD card in the cooling rig.

Every time before you save data, make sure to change the name of the file in every line that says "myFile = sd.open("sensortest.csv", FILE_WRITE);" from sensortest.csv to a different name each time, so you don't override previous data files. 

