# espbasic_modified
esp basic first release https://github.com/esp8266/Basic/commits/master?after=e05b67c5268d73694d7d35063f6d9ffe268948a9+185

i modified first bascom release from here https://github.com/esp8266/Basic/tree/3877dd952e2aac2c07d24c36e9f1752b6b6fe74d because is easy to understand the principle!

For compile i used Arduino 1.8.9 with aditional board manager : http://arduino.esp8266.com/stable/package_esp8266com_index.json

![alt text](https://github.com/costycnc/espbasic_modified/blob/master/board.jpg)

with esp8285 settings 
![alt text](https://github.com/costycnc/espbasic_modified/blob/master/settings.jpg)


I create classes.h with declared of all functions because appear uknown

Example code open close led

Button "open" [setthepin] 
Button "close" [resetthepin] 
Wait 
 
[setthepin] 
Po 0 1 
Wait 
 
[resetthepin] 
Po 0 0 
Wait 

led conected a D0 (i used esp8285 module)
 
