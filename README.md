# ese5190-LAB2B-proposal
Team members: Katrina Ji, Yuchen Wang

---
# LED Demo
---
## Components
- LEDs
- BreadBoard
- Jump Wires
- Stemma Qt to male headers cable
- 330 Ohm Resistor
- Adfruit 2040 Microcontroller 

---
## GIF Demo

![IMG_9560](https://user-images.githubusercontent.com/105755054/197127548-be8c2474-be12-4744-9a43-4de7041ed1a0.GIF)

---
## Circuit Diagram 
![Screen Shot 2022-10-21 at 01 55 27](https://user-images.githubusercontent.com/105755054/197122977-882c0ded-c0b9-4f89-a97a-13723dabf946.png)

---
# Lab 2B Proposal
---
## Outline
Since the goal of the lab is to practice using I2C communication, our team would like to make a project around this topic. We would like to stcik with I2C and preserve “daisy-chain-ability” with other I2C sensors. Thus, we are using two RP2040s. The second on our daughter board as a second microcontroller to handle I2C.

We would like to make a LED-array design with a switch to control it. The inital LEDs will present a pumpkin pattern. When toggling the switch, the pattern will change and a ghoastface will appear. If possible, we want to toggle the switch again, and both the ghoastface and pumpkin pattern will be lit. 

---
## Why we design that?
Since Halloween is coming up recently, we thought the this proposal will be in line with the festive atmosphere. This topic also fits the requirement to use I2C communication.

---
## Compenents (Need Discussion)
- Several yellow/orange LEDs for the pumpkin
- Several red LEDs for the ghostface
- Several 330 Ohm Resistor
- 2* RP2040
- I2C port expander
- BreadBoard
- Jump Wires
- Stemma Qt to male headers cable
- LED screen (if possible)

---
## Question
- What are the advantages of I2C？
- How can we communiate will multiple LEDs?
- What is the maximum number of ports I2C can communicate with?
- Can we change this protocol and use the remaining two pins to control the flashing of the LEDs?
- Is it possible to use a LED screen?

