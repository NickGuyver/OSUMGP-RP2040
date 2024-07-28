# OSUMGP-RP2040

**OSUMGP-RP2040**: **Open Source Universal Modern Game Pad - RP2040 Edition**. This project is a reference design for building a game pad utilizing the GP2040-CE firmware, specifically tailored for the RP2040 microcontroller.

## Current Status
- **Beta**: The project is currently in beta. Feedback and contributions to improve the design and functionality are appreciated.

## Features
- **Open Source**: Fully open-source design and firmware for community collaboration and customization.
- **RP2040 Microcontroller**: Leverages the powerful and versatile RP2040, the same chip used in the Raspberry Pi Pico.
- **GP2040-CE Firmware**: Compatible with the GP2040-CE firmware, providing robust support for many consoles and devices.
- **Customizable**: Easily adaptable for various game pad layouts and configurations.

## Pinout Summary
- See [GP2040-CE Usage](https://gp2040-ce.info/usage/) for reference between modes

| RP2040 Pin | Action     | PCB        |
|------------|------------|------------|
| 17         | Up         | S4         |
| 13         | Down       | S1         |
| 14         | Right      | S2         |
| 16         | Left       | S3         |
| 9          | B1         | S5         |
| 8          | B2         | S6         |
| 7          | R2         | S18        |
| 18         | L2         | S17        |
| 6          | B3         | S7         |
| 5          | B4         | S8         |
| 3          | R1         | S16        |
| 21         | L1         | S15        |
| 22         | S1         | S9         |
| 2          | S2         | S10        |
| 19         | L3         | SW3        |
| 10         | R3         | SW4        |
| 15         | A1         | S14        |
| 20         | A2         | S11        |
| 26         | LS - X     | SW3        |
| 28         | LS - Y     | SW3        |
| 27         | RS - X     | SW4        |
| 29         | RS - Y     | SW4        |


| RP2040 Pin | Function   | PCB        |
|------------|------------|------------|
| 0          | SDA        | J2         |
| 1          | SCL        | J2         |
| 11         | USB D+     | J3         |
| 12         | USB D-     | J3         |

![osumgp-rp2040_0 4b-real](https://github.com/user-attachments/assets/972e6f74-f13b-44ad-b16f-c4e3d9486174)

## Thanks
Special thanks to the [Alpakka](https://inputlabs.io/alpakka) and [GP2040-CE](https://gp2040-ce.info/) projects, as well as the many people in the community who provided help and guidance.

## License
This project is licensed under the Creative Commons Attribution 4.0 International License - see the [LICENSE](LICENSE) file for details.

