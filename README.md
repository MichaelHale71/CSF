# CSF
Python Code for CSF flow model experiment.
Thanks to flohwie for the MCP3201 rpi code
https://github.com/flohwie/raspi-MCP3201

Instructions for use: -

requires pigpio library see : http://abyz.me.uk/rpi/pigpio/download.html


1 in the terminal enter

  sudo pigpiod
  
2 to run the program enter
  
  python MCP3201Photometer.py
  
  you will be prompted for a file name and sampling frequency in Hertz
  
3  Data will be recorded while 3.3v is suppied to pin 17 (Broadcom Numbering)

4 Ctrl + C to exit
  
