# espbasic_modified

see below of the page ... address of interesting examples in arduino 

For compile i used Arduino 1.8.9 with aditional board manager : http://arduino.esp8266.com/stable/package_esp8266com_index.json

![alt text](https://github.com/costycnc/espbasic_modified/blob/master/board.jpg)

with esp8285 settings 

![alt text](https://github.com/costycnc/espbasic_modified/blob/master/settings.jpg)


I create classes.h with declared of all functions because appear uknown

Example code open close led
              
'''        

Button "open" [setthepin] 

Button "close" [resetthepin] 

Wait 
 
[setthepin] 

Po 0 1 

Wait 
 
[resetthepin] 

Po 0 0 

Wait 
             
'''        


 

![alt text](https://github.com/costycnc/espbasic_modified/blob/master/button.jpg)

![alt text](https://github.com/costycnc/espbasic_modified/blob/master/telefon.jpg)


led conected a pin 0 (i used esp8285 module)

![alt text](https://github.com/costycnc/espbasic_modified/blob/master/led.jpg)

![alt text](https://github.com/costycnc/espbasic_modified/blob/master/led1.jpg)

![alt text](https://github.com/costycnc/espbasic_modified/blob/master/open.jpg)

de inspirat:

'in arduino File Examples esp8266wifi wifiaccesspoint  solo come si conette per entrare con 192.168.4.1 (senza router)

'File Examples esp8266wifi wifimanualwebserver come mandare tutta risposta 

client.print(F("HTTP/1.1 200 OK\r\nContent-Type: text/html\r\n\r\n<!DOCTYPE HTML>\r\n<html>\r\nGPIO is now "));
  
'  File Examples esp8266wifi wifiscan  print all network found
  
  Arduino core for ESP8266 WiFi chip https://github.com/esp8266/Arduino
  
  language reference https://docs.google.com/document/d/1NMZvnnjZ5XNzkykINgYS_Ql6mQ3nJEAzYudbmScdiIg/pub

esp basic first release https://github.com/esp8266/Basic/commits/master?after=e05b67c5268d73694d7d35063f6d9ffe268948a9+185

i modified first espbasic release from here https://github.com/esp8266/Basic/tree/3877dd952e2aac2c07d24c36e9f1752b6b6fe74d because is easy to understand the principle!

esp tool https://github.com/igrr/esptool-ck/blob/master/README.md 

