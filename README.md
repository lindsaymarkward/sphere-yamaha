# sphere-yamaha
Ninja Sphere driver (Go) for controlling Yamaha Audio Video Receivers (AVRs)

Allowing control of one zone at a time from the sphereamid and phone app

  - power (on/off) 
  - volume
  
Use the configuration (in Labs or http://ninjasphere.local) to:
 
  - create and rename an AVR
  - control power
  - set input
  - set zone (set input/power for selected zone)
  
Installation
------------

Copy both package.json and the binary (from the release) into `/data/sphere/user-autostart/drivers/sphere-yamaha` (create the directory as needed) and run `nservice sphere-yamaha start` on (or restart) the sphereamid.

Known Issues
------------

The driver doesn't yet find Yamaha AVRs using SSDP
