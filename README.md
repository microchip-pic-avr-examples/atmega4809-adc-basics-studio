<a href="https://www.microchip.com" rel="nofollow"><img src="images/microchip.png" alt="MCHP" width="300"/></a>

# ATMEGA4809 Xplained Pro ADC basics

This is an example of how to get started with the ADC on the ATMEGA4809, this is a general example which is applicable to the whole megaAVR 0-series.

## Related Documentation

- [AN2573 - ADC Basics with tinyAVR 0- and 1-series, and megaAVR 0-series](https://www.microchip.com/wwwAppNotes/AppNotes.aspx?appnote=en601379)
- [ATmega4809 Family Product Page](https://www.microchip.com/design-centers/8-bit/avr-mcus/device-selection/atmega4809)

## Software Used

- [Atmel Studio 7.0 or newer](https://www.microchip.com/mplab/avr-support/atmel-studio-7)
- ATmega_DFP 1.4.351 or newer

## Hardware Used

- ATmega4809 Xplained Pro [(ATMEGA4809-XPRO)](https://www.microchip.com/developmenttools/ProductDetails/ATMEGA4809-XPRO)

## Setup

1. Open `ADCBasicswithmegaAVR0-Series.atsln` in Atmel Studio
2. Connect the ATmega4809 Xplained Pro to your computer with a micro usb cable.
3. In your menu bar in Atmel Studio go to `Debug->Start Without Debugging` or press `CTRL + ALT + F5`
4. Open data visualizer under `Tools->Data Visualizer` to view the messages which is transmitted through UART.

## Operation

As mentioned in the appnote [AN2573](#Related-Documentation) you can change the voltage level of the adc input port and the approximated value will be shown over UART through data visualizer.
## Summary

We here shown how to setup and get started with the ADC basics project. For more details about this example and how the ADC works please see the [AN2573](#Related-Documentation) Application Note.