[![MCHP](images/microchip.png)](https://www.microchip.com)

# Getting Started with Timer/Counter Type D (TCD) Examples (MPLAB® X)

This repository contains examples of MCC-generated source code for Timer/Counter Type D (TCD), as described in the [TB3212-Getting Started with Timer/Counter Type D (TCD)](https://ww1.microchip.com/downloads/en/Appnotes/TB3212-Getting-Started-with-TCD-DS90003212.pdf) document from Microchip. The repository contains two MPLAB® X projects inside:

* [<strong>Generating Complementary Driving Signals:</strong>](Generating_complementary_driving_signals) This use case shows how to configure the TCD to generate complementary driving signals of 50 kHz frequency and with 100 ns dead time (for more details, see [<strong>Generating Complementary Driving Signals</strong>](Generating_complementary_driving_signals)).
* [<strong>Controlling Synchronous Signals Using Input Events:</strong>](Controlling_synchronous_signals_using_input_events) This use case shows how to configure the TCD to generate four signals with 10 kHz frequency that can be stopped when a fault signal is detected until it goes away (for more details, see [<strong>Controlling Synchronous Signals Using Input Events</strong>](Controlling_synchronous_signals_using_input_events)).

## Related Documentation
More details and code examples on the AVR128DA48 can be found at the following links:
- [TB3212-Getting Started with Timer/Counter Type D (TCD)](https://ww1.microchip.com/downloads/en/Appnotes/TB3212-Getting-Started-with-TCD-DS90003212.pdf)
- [AVR128DA48 Product Page](https://www.microchip.com/wwwproducts/en/AVR128DA48)
- [AVR128DA48 Code Examples on GitHub](https://github.com/microchip-pic-avr-examples?q=avr128da48)
- [AVR128DA48 Project Examples in START](https://start.atmel.com/#examples/AVR128DA48CuriosityNano)


## Software Used
- MPLAB® X IDE 5.40 or newer [(microchip.com/mplab/mplab-x-ide)](http://www.microchip.com/mplab/mplab-x-ide)
- MPLAB® XC8 2.30 or a newer compiler [(microchip.com/mplab/compilers)](http://www.microchip.com/mplab/compilers)
- MPLAB® Code Configurator (MCC) 4.0.1 or newer [(microchip.com/mplab/mplab-code-configurator)](https://www.microchip.com/mplab/mplab-code-configurator)
- MPLAB® Code Configurator (MCC) Device Libraries 8-bit AVR® MCUs 2.5.0 or newer [(microchip.com/mplab/mplab-code-configurator)](https://www.microchip.com/mplab/mplab-code-configurator)
- AVR-Dx 1.4.75 or newer Device Pack


## Hardware Used
- AVR128DA48 Curiosity Nano [(DM164151)](https://www.microchip.com/Developmenttools/ProductDetails/DM164151)
