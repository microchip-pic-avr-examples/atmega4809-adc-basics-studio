<a href="https://www.microchip.com" rel="nofollow"><img src="images/microchip.png" alt="MCHP" width="300"/></a>

# ATMEGA4809 Xplained Pro ADC basics

This is an example of how to get started with the ADC on the ATMEGA4809, this is a general example which is applicable to the whole megaAVR 0-series. This is based on the application note [AN2573](#Related-Documentation).

## Related Documentation

- [AN2573 - ADC Basics with tinyAVR 0- and 1-series, and megaAVR 0-series](https://www.microchip.com/wwwAppNotes/AppNotes.aspx?appnote=en601379)
- [ATmega4809 Device Page](https://www.microchip.com/wwwproducts/en/ATMEGA4809)

## Software Used

- [Atmel Studio 7.0.2397 or later](https://www.microchip.com/mplab/avr-support/atmel-studio-7)
- ATmega_DFP 1.4.351 or later

## Hardware Used

- [ATmega4809 Xplained Pro](https://www.microchip.com/developmenttools/ProductDetails/ATMEGA4809-XPRO)

## Setup

* Connect the ATmega4809 Xplained Pro to your computer with a micro usb cable.
* Port `PD6` is the ADC channel input, connect a cable here to interract with the ADC.

## Operation

1. Open `ADCBasicswithmegaAVR0-Series.atsln` in Atmel Studio
2. Connect the ATmega4809 Xplained Pro to your computer with a micro usb cable.
3. In your menu bar in Atmel Studio go to `Debug->Start Without Debugging` or press `CTRL + ALT + F5`
4. Open data visualizer under `Tools->Data Visualizer` to view the messages which is transmitted through UART.

As mentioned in the appnote [AN2573](#Related-Documentation) you can change the voltage level of the adc input port and the approximated value will be shown over UART through data visualizer.
## Conclusion

We here shown how to setup and get started with the ADC basics project. For more details about this example and how the ADC works please see the [AN2573](#Related-Documentation) Application Note.