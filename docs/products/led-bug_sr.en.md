# LED-BUG SR LED Controller

![SR](/images/product/sr.png){ width="600" }

The **LED-BUG SR** is a light controller with the ESP32 as its core processor. It includes onboard dual-level conversion, an I2S digital microphone, and a MAX485 chip, capable of driving addressable programmable RGB light strips at voltages of 5V, 12V, and 24V (requires switching the power source). It comes pre-installed with WLED firmware, enabling music synchronization and the driving of DMX512 light strips, wall washers, and more. Additionally, it provides GPIO pins and offers two 3.3V and two 5V power outputs for easy connection to various sensors and actuators. This makes it not only a powerful ESP32 light project development board but also a versatile platform for custom programming development using Arduino IDE and Platform IO.

- It serves both as a light controller and a development board for lighting projects.

## Features

- Pre-installed with WLED firmware ([https://kno.wled.ge/](https://kno.wled.ge/))
- Onboard level conversion chip supports driving 5V, 12V, 24V programmable strips
- Onboard DC-DC step-down converter, enabling 5V or 12V/24V power supply (switching required)
- Dual light strip signal outputs, compatible with single and dual signal line programmable strips
- Supports a wide range of addressable programmable light strips such as WS281X, SK6812, TM1814
- Features MAX485 chip for DMX512 protocol support, including wall washers
- Onboard digital microphone for sound collection and music synchronization features
- Supports automatic firmware uploading
- Utilizes ESP32, compatible with Arduino, TouchDesigner, Platform IO for custom programming
- Supports Lightpack project for ambient lighting ([https://github.com/psieg/Lightpack](https://github.com/psieg/Lightpack))
- Supports LedFX for music visualization ([https://www.ledfx.app/](https://www.ledfx.app/))

## Technical Specifications

| Specification | Detail |
|---------------|--------|
| Main Controller | ESP32-WROOM-32E/4M |
| Music Rhythm | Built-in digital silicon microphone |
| Operating Voltage | 5V/12V/24V (switchable) |
| Maximum Load Current | 3A |
| Applicable Light Strips | Single or dual signal line programmable RGB strips/DMX512 strips |
| Operating Temperature | -40°C to 85°C |
| Recommended Number of LEDs | 500 to 800 per channel |

Light and shadow artistry, seamlessly integrating sound and light.

## Onboard resources

![SR1](/images/product/eng/sr_intro_1.png){ width="800" }
![SR2](/images/product/eng/sr_intro_2.png){ width="800" }
![SR3](/images/product/eng/sr_intro_3.png){ width="800" }