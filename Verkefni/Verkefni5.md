### Verkefni 5 - Samskipti (10%) _drög_


Búðu til í **private** Github Repository vefsíðu (Verkefni 5) í Wiki sem inniheldur eftirfarandi:

- Svör við spurningum.
- Tengla á myndbönd af verklegum verkefnum (með nafn og dagsetningu á myndbandi).
- Tengla á kóðaskrár sem þú notar í verklegum verkefnum.

---

#### 5.1 SPI (1.5%)
Lestu [BASICS OF THE SPI COMMUNICATION PROTOCOL](https://www.circuitbasics.com/basics-of-the-spi-communication-protocol) og svaraðu eftirfarandi spurningum:
   
   1. Hvað er átt við með samstilltum (e. synchronous) samskiptastaðli?
   1. Hvað er master-slave samband, útskýrðu útfrá; MISO, MOSI, SCLK og CS/SS? 
   1. Hverjir eru helstu kostir og ókostir við SPI?
   
---

#### 5.2 UART (1.5%)
Lestu [BASICS OF UART COMMUNICATION](https://www.circuitbasics.com/basics-uart-communication/) og svaraðu eftirfarandi spurningum:
 
   1. UART notast við baud rate útskýrðu nánar tilgang þess.
   1. Hvað er packet (START BIT, DATA FRAME, PARITY, STOP BITS) í UART?
   1. Hvernig er UART frábrugðið SPI? 
 
---

#### 5.3 Inter-Integrated Circuit (I2C) (1.5%)
Lestu [I2C](https://www.circuitbasics.com/basics-of-the-i2c-communication-protocol/) og svaraðu eftirfarandi spurningum:

   1. I2C notar message og address, hvað er það og hvernig virkar það?
   1. Hvað er hægt að senda mikið af gögnum (bits) í einu?
   1. Hver er helsti munurinn á SPI og I2C? 

---

#### 5.4 I2C með tvo Arduino (3%)
Skoðaðu [I2C Communications](https://dronebotworkshop.com/i2c-arduino-arduino/) og settu upp síðari tilraunina **Remote Demo** (með breytiviðnámi og led) verklega (eða með TinkerCad).

Útskýrðu hvað eftirfarandi kóði gerir:

   1. `Wire.beginTransmission(ADDRESS);` Hvaða ADDRESS eru ekki í boði?
   1. `Wire.onReceive(receiveEvent);` og `Wire.onRequest(requestEvent);` 
   1. `Wire.requestFrom(SLAVE_ADDR, ANSWERSIZE);`

---

#### 5.5 MPU-6050 (2.5%)
Skoðaðu eftirfarandi: [Build a Digital Level with MPU-6050 and Arduino](https://dronebotworkshop.com/mpu-6050-level/). <br>
Útskýrðu alla pinna (e. pinouts) á MPU-6050. Fylgdu eftir fyrri tilrauninni (að 19:36 mín í myndbandi) til að prófa MPU-6050. 
<br>
Fylgdu svo eftir tutorial [MPU6050 and 3D Simulation With Processing](https://www.instructables.com/id/Arduino-MPU6050-GY521-6-Axis-Accelerometer-Gyro-3D/) og settu upp verklega.

---

#### Námsmat og skil
Gefið er heilt fyrir fullnægjandi lausnir og svör, hálft ef ábótavant eða svör vanta. <br>
Skilaðu á Innu vefslóð á lokaða (e. private) Github geymslu.

---

<!--

#### 5.1 UART
Kynntu þér UART [BASICS OF UART COMMUNICATION](https://www.circuitbasics.com/basics-uart-communication/) og [UART](https://www.allaboutcircuits.com/technical-articles/back-to-basics-the-universal-asynchronous-receiver-transmitter-uart/). Fylgdu eftirfarandi tutorial: [HOW TO SET UP UART COMMUNICATION ON THE ARDUINO](https://www.circuitbasics.com/how-to-set-up-uart-communication-for-arduino/) og settu upp á Breadboard.
   

#### 5.2 Serial Peripheral Interface (SPI)
1. Fylgdu eftirfarandi tutorial: [Communication between two Arduino Boards](https://circuitdigest.com/microcontroller-projects/arduino-spi-communication-tutorial) og settu upp á Breadboard. Sjá einnig [How do you use SPI on an Arduino?](https://arduino.stackexchange.com/questions/16348/how-do-you-use-spi-on-an-arduino)


**SPI:**

- [BASICS OF THE SPI COMMUNICATION PROTOCOL](https://www.circuitbasics.com/basics-of-the-spi-communication-protocol)
- [SPI](https://www.allaboutcircuits.com/technical-articles/spi-serial-peripheral-interface/)
- [Arduino og SPI](https://learn.sparkfun.com/tutorials/serial-peripheral-interface-spi/all) 
- [SPI safnið fyrir Arduino](https://www.arduino.cc/en/reference/SPI)

-->
