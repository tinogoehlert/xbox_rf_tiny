xbox360_rf_tiny
===============

attiny45/85 sketch for controlling the Xbox 360 RF Unit.  


###burning the Sketch
  
avrdude:

```
avrdude -v -pattiny45 -cstk500v2 -Pusb -Uflash:w:xbox_rf_tiny.hex:i
```

or use the Arduino IDE with the Attiny bundle of your choice.  
For example: http://hlt.media.mit.edu/?p=1695  
  
The code was tested on an Attiny45 running with 1 Mhz.  
i didn't changed the Fusebits, so it should work out of the shelf.
  
Good luck! ;)
