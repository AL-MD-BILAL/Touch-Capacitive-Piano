# Touch Capacitive Piano

The Touch Capacitive Piano basically uses human capacitance in the finger to play different frequencies of tone via touch.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Requirements](#requirements)
- [Hardware Requirements](#hardware-requirements)
- [Circuit Diagram](#circuit-diagram)
- [Usage](#usage)


## Prerequisities

Before you begin, ensure you have met the following requirements
- Arduino IDE 
```
# Use the below link to install Arduino IDE
https://www.arduino.cc/en/software
```

## Installation

Type or copy the below code in your terminal to pull the repo files to your computer 

```bash
# Clone the repository
git clone https://github.com/AL-MD-BILAL/Touch-Capacitive-Piano.git

# Change directory to the transposition directory
cd Touch-Capacitive-Piano
```

## Requirements

The required libraries for working of the code are 
```
- CapacitiveSensor.h

 # This pitches.h is already in the repo so it does not require installation from Library Manager
- pitches.h             

Note : All of the above mentional libraries should be installed inside Arduino IDE via Library Manager (Sketch > Include Library > Manage Libraries) or in the form of zip files.
```

## Hardware Requirements

The Hardware required for working of the code include
```
- Arduino Board (UNO, Mega. or any series)
- Metal Keys
- 5V Buzzer
- 10k Resistor
- NPN Transistor
- Breadboard
- Jumper Wires
```

## Circuit Diagram
![Circuit Diagram](https://hackster.imgix.net/uploads/attachments/1523482/arduino_piano_1_4LME68rzCs.png)


## Usage

To use the project follow the steps given below

```
1. Install Arduino IDE as per the prerequisite
2. Install the required libraries
3. Connect the hardware components using the above circuit diagram
4. Either Download the code and make the required changes as stated inside the code with the help or comments or copy paste the code in your Arduino IDE and make required changes
5. Compile and upload the code to Arduino using USB cable
6. Check the output via the buzzer
```
