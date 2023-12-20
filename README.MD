# About

This repository is dedicated to providing comprehensive guidance for integrating Arduino/ESP32 boards with MATLAB/Simulink.
<br> What is possible:

- Develop your logic in Simulink and upload to arduino.
- Use build-in Support Package for Arduino Blocks.
- Use custom blocks with S-Functions Blocks.
- Use any Arduino's library (with S-Function).
- Use all Simulink Blocks/Simulate/Stateflow.
- Use any Arduino Board / ESP32.

_Note:</br>This is not a Library, is just a Repository with some advices regarding Simulink and Arduino/ESP32 integration._

## Software Requirements

- MATLAB Version 9.13 (R2022b) - [MathWorks](https://www.mathworks.com/)
- Simulink R2022b 10.6 (R2022b) - [MathWorks](https://www.mathworks.com/)
- MATLAB Support Package for Arduino Hardware (version 22.2.2) - [MathWorks](https://www.mathworks.com/hardware-support/arduino-matlab.html)
- Simulink Support Package for Arduino Hardware (version 22.2.4) - [MathWorks](https://www.mathworks.com/hardware-support/arduino-simulink.html)

## How to Use

For detailed instructions on setting up your environment and configuring your hardware, please refer to the [How to Use](./how_to_use) section. This section provides step-by-step guides on software requirements, installation processes, board configuration, and deployment tips.

## Examples

- [**Blink Example**](./example_blink): A basic example using build-in Arduino blocks.
- [**RGB LED Control**](./example_rgb): An example using S-Functions and Stateflow.
- [**HTTP Request**](./example_HTTPrequest): Use of ESP32 to make HTTP Requests.
- [**MQTT**](./example_mqtt): An example to connect to a MQTT broker.
- [**DHT11**](./example_dht): An example to connect to DHT11 sensor.
- [**Alexa**](./example_alexa): An example to connect to Amazon Alexa.

---

_Please, if you can make some contribution, let me know or make a PR._
