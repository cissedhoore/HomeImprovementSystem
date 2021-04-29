# Home Improvement System
## Description
This is a hobby project with the primary aim of learning new things. The goal is to create a domotica system that can interact with a home enviroment by creating many different "nodes" that interact with each other. An example of this would be to control a "light source node" using a "wireless remote node". An other option is to control all the nodes with a central mobile application.

Things I want to learn in this project:
Hardware Design, PCB design, Electronics, Microcontrollers, ...

## Vision
### Possible nodes:
**Input**
- Temperature Sensing Node
- Romote Controller Node
- Solar Panel Node

**Output**
- LCD Screen Node
- Music Node (Audio Amplifier)
- Motor Node (to control blinds or locks for example)

**Other**
- Central Processing Node
- Battery Charging Node
- Signal Repeater Node


##   Progress
### Step 1: creating a Basic Node
This node can then be used to demonstrate how the system works and as a template to create the other nodes. The node needs to be able to communicate in a wireless way and should posses some simple inputs and outputs (like buttons and LED's for example). The node also needs to be programmable and has to have good powersource.

Link to hardware: https://easyeda.com/cissedhoore/home-system

**Components:**
- ATMEGA32u4 microcontroller
- nRF24L rf-module
- 3v3 LDO
- micro USB port

**Version 1**  
Problems:   
Some components were to small to be soldered by hand.   
USB connection to the ATMEGA doesn't work.  

**Version 2**  
Usage of the velleman nRF24L module.  
Cleaner USB connections.  



