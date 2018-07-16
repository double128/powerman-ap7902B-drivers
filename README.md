Slightly modified 8-port APC AP7900B drivers that allow the 16-port AP7902B to properly function on the CM71xx (and other devices that use powerman, assumedly). Without these drivers, the CM will only pick up 8 of the 16 ports on the device.

*powerstrips.xml* is appended to `/etc/config/powerstrips.xml`. *apc7902b.dev* is added to `/etc/config/powerman`. 
