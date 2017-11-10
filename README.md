# PYTHON-PROJECT
WEATHER MONITORING SYSTEM
Components required
-------------------

1. Raspberry pi zero W
2. 8 GB memory card
3. USB Data cable
4. DHT11 Sensor
5. Rain sensor
6. Jumper wires

Software's required
-------------------

1. Putty
2. VNC viewer
3. Etcher
4. Advanced IP Scanner

Setup
-----

1.  Download Raspberrian OS from https://www.raspberrypi.org/downloads/raspbian/ .
2.  Flash Raspbian OS to memory card using Etcher.
3.  Insert the SD card into Raspberry pi zero W.
4.  Connect to the PC using USB Data cable.
5.  Open Advanced IP Scanner and scan for raspberrypi.
6.  Copy IP Address and paste in as Hostname in putty on open window.
7.  Log in with username: 'pi' and password: 'raspberry' (Default).
8.  Install all the required libraries using command 'sudo apt-get libraryname.py'.
9.  Create new file using command 'sudo nano filename.py'.
10. Type the code in the new file.
11. Save the file with command 'ctrl+x' then 'Y' then 'Enter'.
12. Run the code using command 'sudo python filename.py'.
13. Enjoy.

Connection 
----------

1. Solder 2x20 male header pins into the Raspberrypi zero.
2. Connect the Rain sensor
   VCC to pin 3
   GND to pin 39
   DO  to pin 31
3. Connect the DHT11 sensor
   VCC to pin 1
   GND to pin 9
   DATA to pin 11
