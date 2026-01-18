# esp32-wikipedia-summarizer
This IoT project showcases how a Esp32 communicates with the internet thru its built in wifi, first the user auto connects to the internet via putting the correct credentials in the code and then the user types in a topic or thing and wikapedia gives a summerizied text of it (NOTE: error 404 will show up if for certin searches)

# Set-up guide

*equipment needed:*


  -Esp32-WROOM(2.5ghz built-in antenna)
  
  -breadbored (optinal but recomended)
  
  -jumper wires/normal wires (jumper wires preferably M-M or F-M)
  
  -5v/3.3v battery pack
  
  -cutted USB-C cable (only need + and -)
  
  -switch
  
  -ST7789 TFT screen (2.8inches 240 by 320px)
  
  -joystick moudule(with sw)
  
  -A 2.5ghz wifi source (for this project i used my laptops built-in 2.5ghz hotspot but you can use the 2.5ghz dual band wifi from your routor)

*wiring guide:*

Esp32 pin----------------screen pin

gnd-------------------------gnd

3.3v--------------------------vcc

3.3v---------------------------BL

D18                        SCK/SCL

D23                        MOSI/SDA

D17                        RST

D16                        DC

D5                         CS











  


