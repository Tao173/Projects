## 0. About using SPI + I2C multi display (software mode).   
 - [WIKI SPI](https://en.wikipedia.org/wiki/Serial_Peripheral_Interface).  
 -  Step by step [instructions for E-Paper Display](https://github.com/arendst/Tasmota/discussions/11850).  
 - Tasmota [commands](https://tasmota.github.io/docs/Commands/#displays) for controlling displays.  
 - Tasmota [examples](https://tasmota.github.io/docs/Displays/#rule-examples-for-scripting-examples-see-scripting-docs) for displaying information on the display.  
 - You can display the same information on all displays at once or display information individually on each display.

## Other projects where multi display is used::
 - Tasmota [SPI multi display (hardware mode)](https://github.com/arendst/Tasmota/discussions/13161).  
 - Tasmota [I2C multi display (hardware mode)](https://github.com/arendst/Tasmota/discussions/13166).  
 - Tasmota [SPI+I2C multi display (software mode)](https://github.com/arendst/Tasmota/discussions/13222).  
 - [Multiple displays on the I2C bus](https://www.youtube.com/watch?v=E9FTQyBYwAE).  
 - [8 Multiplexed OLED /w ESP32 and U8g2](https://www.youtube.com/watch?v=aMgIxXwtHbw).  
 - [SPI OLED multiple displays with an Arduino](https://youtu.be/YCkFFtVEEG4).  

## 1. SPI + I2C multi display.
![](https://raw.githubusercontent.com/TrDA-hab/Projects/master/SPI%20%2B%20I2S%20multi%20display/4181.jpg)  
![](https://raw.githubusercontent.com/TrDA-hab/Projects/master/SPI%20%2B%20I2S%20multi%20display/4182.jpg)   
![](https://raw.githubusercontent.com/TrDA-hab/Projects/master/SPI%20%2B%20I2S%20multi%20display/4183.jpg)    
![](https://raw.githubusercontent.com/TrDA-hab/Projects/master/SPI%20%2B%20I2S%20multi%20display/20210925_203145.jpg)   

#### Video of the display`s work:   
https://youtu.be/DtdU9AR7CBk   

## 2. How to use it.  
 - very soon !!! 

ESP32 GPIO|Component|SPI display|SPI display|
:-:|:-:|:-:|:-:
21|I2C SDA 1|SDA|-
22|I2C SCL 2|SCL|-
13|SSPI MOSI|-|DIN
18|SSPI SCLK|-|CKL
05|EPaper29 CS|-|CS

**Best regards,   
TrDA.**