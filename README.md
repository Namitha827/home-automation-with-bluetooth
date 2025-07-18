# home-automation-with-bluetooth

*COMPANY*: CODETECH IT SOLUTIONS

*NAME*: NAMITHA.J.B

*INTERN ID*: CT04DZ84

*DOMAIN*: EMBEDDED SYSTEMS 

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTHOSH

**The Bluetooth-controlled home automation system is a simple yet efficient project designed to automate electrical appliances using an Arduino and a Bluetooth module. This project aims to modernize the traditional switching system by allowing wireless control of devices such as lights, fans, or other appliances through a smartphone or Bluetooth-enabled device. The system is particularly useful for smart home setups where comfort, convenience, and remote access are essential.

The primary components used in this project include an Arduino UNO, an HC-05 Bluetooth module, a relay module, and LEDs (to simulate home appliances). In a physical build, the relays would be connected to real devices like lights or fans, while in simulation (using Tinkercad), LEDs are used to represent those devices for testing purposes. The HC-05 module enables wireless communication between the user’s smartphone and the Arduino through Bluetooth serial communication. The smartphone sends commands such as "1" or "0" through a Bluetooth terminal app, which the Arduino reads via its serial port.

The system works as follows: when the user sends a command from their smartphone using a Bluetooth terminal app, the HC-05 module receives it and transmits it to the Arduino UNO through serial communication. The Arduino reads the input using the Serial.read() function. Depending on the input, it will turn the connected relay (or LED) ON or OFF. For example, if the user sends “1”, the Arduino will set the relay pin to HIGH, activating the device; if “0” is received, the pin is set to LOW, deactivating it.

In the Tinkercad simulation, since the HC-05 module is not available, we use the Serial Monitor to simulate Bluetooth input. Users can manually type “1” or “0” in the Serial Monitor to turn the LED ON or OFF. This simulates the exact functionality of Bluetooth control without requiring physical hardware. The circuit consists of an LED connected to digital pin 7 through a 220-ohm resistor, and the program listens for serial input to control the LED's state.

This project provides a great introduction to IoT (Internet of Things) and home automation technologies. It demonstrates how microcontrollers like Arduino can be integrated with wireless modules to build practical, real-world systems. It also teaches serial communication, relay control, and how mobile phones can interact with embedded systems.
Overall, the Bluetooth-controlled home automation system is a compact, affordable, and scalable solution for controlling household devices wirelessly. It lays the foundation for more advanced smart home applications such as voice control, remote monitoring, or Wi-Fi-based automation. With real hardware, this system can be expanded to include multiple devices, security systems, or even integrate with home assistants. In conclusion, this project successfully blends basic electronics with wireless communication to bring automation into everyday life.
