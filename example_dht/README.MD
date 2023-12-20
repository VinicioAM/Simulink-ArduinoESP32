# About

This example use Arduino and build-in LED to blink, by choosing the time on/off on Simulink.
<br> What is covered:

- Integration between Arduino and Stateflow;
- Use of build-in Arduino Libraries in Simulink.

# Requeriments

### Software

- MATLAB Version 9.13 (R022b)
- Simulink R2022b 10.6 (R022b)
- MATLAB Support Package for Arduino Hardware (version 22.2.2)
- Simulink Support Package for Arduino Hardware (version 22.2.4)
  <br> Maybe work with newer versions.

### Hardware

- x1 - Arduino Uno
- x1 - DHT11 Sensor

### Connections

<img src="./imgs/circuit.png"   />

# Files:

- <b>main.slx:</b> Model with the main model/logic of the example.

# Blocks

<img src="./imgs/01.png"   />

- <b>Serial_Communication: </b> This block Enables the Serial Communication. If the communication is ok, enable the DHT11.
- <b>DHT11: </b> After get the OK from previous block, enable messages with Temperature and Humidity in Serial Port.

# How to use

- Check [How to Use Section](../how_to_use/) and make all initial config.
- Open main.slx.
- Hardware > Build, Deploy & Start.
