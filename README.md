[<img src="https://raw.githubusercontent.com/sh969/integrated-aq-sensor/master/.images/logo.png">](http://open-seneca.org)

Here you find the open-source files and assembly instructions on the 2021 integrated open-seneca air quality sensor.

We are a citizen science project, please feel free to get in touch!

You can visit us here: http://open-seneca.org

BETA: SEN55 support (includes VOC and NOX measurements). Sensor casing requires adaptation. Edit 07/22.

UPDATE 06/23: Longitude issue has now been fixed. Flash new .elf file to upgrade.

## Repository structure

| Directory | Contents |
|-----------|----------|
| [Assembly](Assembly/) | Step-by-step assembly instructions ([PDF](Assembly/Assembly%20instructions%20-%20fully%20assembled%20sensor.pdf), [tutorial with photos](Assembly/README.md)) |
| [Firmware](Firmware/) | Source code, pre-compiled hex files, and [flashing instructions](Firmware/README.md) |
| [Hardware](Hardware/) | Bill of Materials ([full sensor](Hardware/BOM/BOM%20Full%20sensor.xlsx), [PCB only](Hardware/BOM/BOM%20PCB.xlsx)) and [PCB Gerber files](Hardware/PCB/gerber.zip) |

## Known missing files & information

The following items are not yet included in this repository:

- **Sticker design file** - The colourful sticker applied to the display side of the sensor
- **Enclosure/box design** - CAD files for the sensor box (with our custom cutout for the SPS30)
- **Component sourcing links** - Several AliExpress links are outdated and no longer valid. In particular:
  - **GPS antenna** - The specific model we used is not documented (was listed as "custom")
  - **Enclosure/box** - No current purchasing link
  - **Screws & spacers** - The BOMs reference metal M3 screws/spacers, but we later switched to **nylon** ones to avoid short circuits on the PCB. Updated sourcing links for the correct nylon hardware are needed.

If you have sourcing suggestions or can contribute any of the above, please open an issue or pull request!

## Apps

Download the sensor logging app for iPhone and Android:

[<img width="200" src="https://raw.githubusercontent.com/sh969/integrated-aq-sensor/master/.images/apple.png">](https://apps.apple.com/gb/app/open-seneca/id1557645819?fbclid=IwAR2OlgHsh-e7t_3RmL6pHDrDfW7VRLy2B10hRCUW2dqcQbhn8BgqbDvHhck)
[<img width="200" src="https://raw.githubusercontent.com/sh969/integrated-aq-sensor/master/.images/google.png">](http://app.open-seneca.org/android/v1.2.1.apk)

![alt text](https://raw.githubusercontent.com/sh969/integrated-aq-sensor/master/.images/sensor.jpg)
