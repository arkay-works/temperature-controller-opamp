# Analog Temperature Controller using Op-Amp & LM35

## Overview
This project implements a temperature-controlled system using an LM35 temperature sensor and an op-amp comparator. When the temperature crosses a set threshold, a load (fan or LED) is activated.

## Tools & Components
- LM35 Temperature Sensor (simulated as voltage source)
- Op-Amp Comparator (LTspice)
- Arduino Uno (for digital implementation)
- STM32 (optional extension)

## LTspice Simulation
The comparator output goes high when the LM35 voltage exceeds the reference voltage, turning ON a simulated fan (LED).
- Vtemp = 0.1V/°C
- Vref = 0.35V → 35°C threshold

## Arduino Version
Reads LM35 analog value. If temperature > 35°C, fan is turned ON via digital pin.

## Learning Outcomes
- Analog comparator design
- Op-amp simulation in LTspice
- Embedded sensor reading and threshold logic

## Circuit Diagram
![Circuit](images/waveform.png)

## Author
Your Name - [LinkedIn](https://linkedin.com/in/yourprofile)
