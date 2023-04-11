# ECE_492_Capstone_stuff
A Repo for all things related to our capstone

# gpredict_bat.bat
Batchfile to run hamlib to connect gpredict to serial port (need to edit with com#)<br />
This batch file should be put where the rotctld.exe file is at Program Files\hamlib\bin and it needs to be run with command prompt in administrator mode.

# Arduino IDE
Make sure you add the RAMBo board by going into preferences and adding this additional board manager url:
https://raw.githubusercontent.com/ultimachine/ArduinoAddons/master/package_ultimachine_index.json

# Hamlib and Gpredict
You can download hamlib from https://sourceforge.net/projects/hamlib/ and Gpredict from https://sourceforge.net/projects/gpredict/ <br />
In Gpredict, go to preferences and change your ground station, and then go to interfaces and add a rotator. Give the rotator a name, the host should be localhost and the port should be 4533. Set the max azimuth to 240 degrees.
