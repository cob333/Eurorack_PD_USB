# Eurorack PD USB Power Supply

This is a USB-C PD powered Eurorack power supply module inspired by "Powerline". It provides **+12 V, -12 V, and +5 V** rails, with additional short-circuit protection and reverse-voltage protection.

Check the original Powerline design at:

**https://github.com/Andreas-Dorfner/Powerline-USB-C**

## Hardware Preview

| Front | Back |
| --- | --- |
| ![Eurorack PD USB front side](images/Eurorack_PD_USB_Front.jpg) | ![Eurorack PD USB back side](images/Eurorack_PD_USB_Back.jpg) |

## Overview

This module is designed to power a Eurorack system from a USB-C Power Delivery source. It negotiates a **20 V PD 3.0 input profile** and converts it into the three standard Eurorack rails.

## Electrical Specifications

| Item | Specification |
| --- | --- |
| Input connector | USB-C |
| Input protocol | USB Power Delivery 3.0 |
| Input voltage profile | 20 V |
| Output rails | +12 V, -12 V, +5 V |
| Estimated output current | +12 V / 1.5 A, -12 V / 1 A, +5 V / 800 mA |

![Test result](images/Test.jpg)

## Disclaimer

Build, test, and use it at your own risk, and always validate the supply before connecting any modules.

## License

This project is licensed under the [MIT License](LICENSE).
