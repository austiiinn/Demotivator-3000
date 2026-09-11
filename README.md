<img width="1280" height="640" alt="git (1)" src="https://github.com/user-attachments/assets/8920b256-2ba8-4988-b824-5351134eb4bd" />



# DEMOTIVATOR 3000 🎯


## Basic Details
### Team Name: Austin Sebastian


### Team Members
- Team Lead: Austin Sebastian - Lourdes Matha College of Science and Technology

### Project Description
DEMOTIVATOR 3000 is a completely unnecessary machine that gives you a random demotivational message whenever you press a button.

A physical button connected to an Arduino triggers a dramatic electronic selection sequence, after which a retro-style LCD interface displays a random message designed to provide absolutely zero motivation.
Instead of providing motivation, productivity, or literally anything useful, it uses an Arduino, a buzzer, and a retro-style web interface to remind you that your efforts could have been better.

### The Problem (that doesn't exist)
People occasionally feel the need for motivation.
Unfortunately, there is already an excessive amount of motivational content everywhere.
Nobody has made a machine specifically designed to make you regret asking for motivation.
.
 .
#### Until now.

### The Solution (that nobody asked for)
I built the DEMOTIVATOR 3000.

Press the physical button and the Arduino starts a dramatic selection sequence using a buzzer while communicating with a web-based LCD interface.
After the sequence, the display reveals a randomly selected demotivational quote.

It serves no practical purpose.

And that's EXACTLY why it exists.

## Technical Details
### Technologies/Components Used
For Software:
- C++, HTML, CSS, Javascript
- Frameworks used: None
- Libraries used: None
- Arduino IDE, Chrome, ChatGPT

For Hardware:
- Arduino board
- Push button
- Buzzer
- Breadboard
- Jumper wires
- USB cable
- Laptop/PC

Specifications:
- Arduino digital pin 2 → Push button
- Arduino digital pin 4 → Buzzer
- Button configured using INPUT_PULLUP
- Serial communication: 9600 baud
- USB used for Arduino-to-PC communication
- Browser receives Arduino commands using Web Serial API
- HTML/CSS interface acts as the visual LCD

### Implementation
For Software:
# Installation
Install Arduino IDE

# Run
1. Open "Demotivator.html" in Google Chrome or Microsoft Edge.
2. Click **Connect Arduino**.
3. Select the Arduino's COM port.
4. Press the physical button.
5. The Arduino triggers the buzzer and sends serial commands to the webpage.
6. The webpage displays a randomly selected demotivational quote.

### Project Documentation
For Software:

# Screenshots (Add at least 3)
<img width="1365" height="767" alt="image" src="https://github.com/user-attachments/assets/e4576d90-aeee-4db1-a57b-24f5f0c834ae" />

*Title screen*

<img width="1365" height="767" alt="image" src="https://github.com/user-attachments/assets/8ff17143-ff7e-4612-affa-11ba5f976c26" />

*Example*

<img width="417" height="404" alt="image" src="https://github.com/user-attachments/assets/7d7834f0-a9de-4460-892d-18088ae63d89" />

*Arduino code*

# Diagrams
<img width="1536" height="1024" alt="ChatGPT Image Sep 12, 2026, 03_47_16 AM" src="https://github.com/user-attachments/assets/e6279afd-5b5d-41d0-802c-fc5191dbd753" />

*Workflow showing how a button press is processed by the Arduino, communicated to the webpage via USB Serial, and converted into a random demotivational message on the LCD interface.*

For Hardware:

# Schematic & Circuit
<img width="1188" height="1296" alt="Untitled Sketch_bb" src="https://github.com/user-attachments/assets/ead9c125-e639-495f-a0a5-6ecddbdb0581" />

*Circuit connections: push button → Arduino D2 + GND; buzzer → Arduino D4 + GND; Arduino → laptop via USB for power and serial communication.*

<img width="627" height="849" alt="Untitled Sketch_schem" src="https://github.com/user-attachments/assets/be55e64a-5e3c-4548-8cf4-fbd83d08a5ad" />

*Circuit connections: push button → Arduino D2 + GND; buzzer → Arduino D4 + GND; Arduino → laptop via USB for power and serial communication.*

# Build Photos
<img width="2480" height="3307" alt="IMG_20260912_042122_003" src="https://github.com/user-attachments/assets/284e66bf-4fe8-45db-a5ce-114c93fad23a" />

*Arduino, buzzer, button*

<img width="2480" height="3307" alt="IMG_20260912_042131_515" src="https://github.com/user-attachments/assets/2f7cae40-b437-4643-9a12-c0ff97791615" />

*The Arduino, button, and buzzer were connected on a breadboard, then connected to the laptop via USB and tested with the webpage.*

<img width="3307" height="2480" alt="IMG_20260912_042126_387" src="https://github.com/user-attachments/assets/15fa24a3-df42-411d-b413-bd69dd5b1fe0" />

*The final build combines the Arduino, button, and buzzer with the web-based LCD interface, creating a functional DEMOTIVATOR 3000.*

### Project Demo
# Video
https://youtube.com/watch?v=84pq9Fvrwsg&si=B48yIzzb-hB-Yr1M
*Working*

# Additional Demos
<img width="1366" height="768" alt="Recording2026-09-12041439-ezgif com-optimize" src="https://github.com/user-attachments/assets/be662c3c-f5a3-4d36-958f-787578b903b7" />




---
Made with ❤️ at TinkerHub Useless Projects 

![Static Badge](https://img.shields.io/badge/TinkerHub-24?color=%23000000&link=https%3A%2F%2Fwww.tinkerhub.org%2F)
![Static Badge](https://img.shields.io/badge/UselessProjects--26-26?link=https%3A%2F%2Ftinkerhub.org%2Fevents%2F1M8ORET9A1%2Fuseless-projects-3.0)



