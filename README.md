# ese5190_lab2b
## LED Video
![image](https://github.com/IndigoQuadratic/ese5190lab2b/blob/ff860f84c2d0287caa6c203fdff19601a3aac6cc/lab2b_led.gif)
## Proposal (tentative) : Mini Customized RPG machine based on RP2040
- ***Introduction***: With the rapid grow of virtual reality technology, especially its application in some host RPG(role play games) like *Pokemo:GO*, *SWORD ART ONLINE* and *STAR WARS*, more and more players have got an immersive experience surfing fantasy world as if they are the main chracter. But it seems always annoying when starting a new character by chaging the modeling parameters in the game, so why don't we use a more time-saving way to get started with the main character who just acts as your cyber substitute? This project demos a virtual character customization using human face recognition based on designated sensors. More comprehensive modules will be included as follows.
- ***Component List***:
  | Component         | Number      |                     Note                   |       Product Website |
  | -----------       | ----------- | -----------                                |-----------                                                           |
  | QT Py RP2040      | 1           | core microprocessor                        |https://www.adafruit.com/product/4900                                 |
  | OV7725 Image Sensor   | 1           | image sensor for image sampling        |https://www.adafruit.com/product/4478                                 |
  | 2.8" TFT Touch Shield   | 1           | capacitive touch screen              |https://learn.adafruit.com/adafruit-2-8-tft-touch-shield-v2/downloads |
  | APDS-9960         | 1           | proximity, Light, RGB, and Gesture Sensor  |https://www.adafruit.com/product/3595                                 |                
  | DuPont line       | some        | jumper wire                                |   N/A                                                                |
  | Breadboard        | 1           | platform for circuit construction          |   N/A                                                                |  
  | STEMMA QT         | 1           | connection of peripheral dvice with GPIO of RP2040   |https://www.adafruit.com/product/4209                       |
- ***Expected System Diagram***
  ![image](https://github.com/IndigoQuadratic/ese5190lab2b/blob/a8418466693c918ccbf7a03e4dedd450b8baa771/SCHEMATIC.jpg)
- ***Function description***:
  - Firstly, through the image sensor module, the user can upload their personal image into the built in μSD Card;
  - Then, a customized profile needs to be updated through the Touch sheld;
  - After doing the above steps, users can control their character through the "virtual keyboard", which operates several simple commands such as up, down, left and right via the sensors in APDS-9960;
  - The core microprocessor, QT Py RP2040, briges the "virtual keyboard" operated on personal comuputer and the "display interface", LCD on TFT sheild.
- ***Physical Circuit***
  - This part will be  updated after the lab.



  
  
