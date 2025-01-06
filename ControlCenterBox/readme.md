# Control Center Box - README

## Overview
This repository contains CAD files and images for the **Control Center Box** project. The Control Center Box is a customizable enclosure designed for housing electronics such as OLED displays, Ethernet modules, and LED control systems. It is suitable for 3D printing and provides modular inserts for various configurations.

The rear insert included is for a keystone where you can use anything from a CAT5/6 Ethernet insert, Barrel Jack (for DC power), HDMI etc. 

Currently it houses: 

1. Olimex [ESP32-POE-ISO IoT development board with 100Mb Ethernet, Power over Ethernet, WiFi, BLE](https://www.olimex.com/Products/IoT/ESP32/ESP32-POE-ISO/open-source-hardware)
2. DFRobot [Monochrome 0.96" 128x64 I2C/SPI OLED Display](Https://www.dfrobot.com/product-2017.html)
3. Seeed Studio [Grove - RGB LED Stick (15-WS2813 Mini)](https://www.seeedstudio.com/Grove-RGB-LED-Stick-15-WS2813-Mini-p-4270.html)
4. Seeed Studio [Grove - RGB LED (WS2813 Mini)](https://www.seeedstudio.com/Grove-RGB-LED-WS2813-Mini-p-4269.html)
5. Parallax [BME680 Environmental Sensor](https://www.parallax.com/product/bme680-environmental-sensor/)
6. Miscelaneous Normally Open (N.O) buttons ^but theses are not currently implemented yet

## Completed Build Pictures

![Complete Control Center Box - Front Right](./Images/CompletedBuild_FrontLeft.jpg)
![Complete Control Center Box - Front](./Images/CompletedBuild_FrontProfile.jpg)
![Complete Control Center Box - Rear Right](./Images/CompletedBuild_RearRight.jpg)

## Project Structure
```
3D_Printing/ControlCenterBox/
├── Files
│   ├── BaseBox.f3d
│   ├── BaseBox.step
│   ├── BaseBox.stl
│   ├── BaseLid.f3d
│   ├── BaseLid.step
│   ├── BaseLid.stl
│   ├── Base_AND_Screen.f3d
│   ├── Base_AND_Screen.step
│   ├── Base_AND_Screen.stl
│   ├── Center_Screen_LED_Insert.f3d
│   ├── Center_Screen_LED_Insert.step
│   ├── Center_Screen_LED_Insert.stl
│   ├── Left_Screen - OLED.f3d
│   ├── Left_Screen - OLED.step
│   ├── Left_Screen - OLED.stl
│   ├── Rear_Extension_Insert_Single_Keystone.f3d
│   ├── Rear_Extension_Insert_Single_Keystone.step
│   ├── Rear_Extension_Insert_Single_Keystone.stl
│   ├── Right_Screen_WLED_and_Buttons.f3d
│   ├── Right Screen_WLED_and_Buttons.step
│   ├── Right Screen_WLED_and_Buttons.stl
│   ├── Screen.f3d
│   ├── Screen.step
│   └── Screen.stl
├── Images
    ├── ControlCenterBox-BaseLid-FrontRightCorner.jpg
    ├── ControlCenterBox-BaseLid-RightRearUnderside.jpg
    ├── ControlCenterBox-BaseShell.jpg
    ├── ControlCenterBox-FrontProfile-Empty.jpg
    ├── ControlCenterBox-FrontRightCorner-Empty.jpg
    ├── ControlCenterBox-FrontRightCorner-Full.jpg
    ├── ControlCenterBox-Hero-WithBlanks.jpg
    ├── ControlCenterBox-Hero.jpg
    ├── ControlCenterBox-RearProfile.jpg
    ├── ControlCenterBox-RearRightCorner-WithEthernetInsert.jpg
    ├── ControlCenterBox-RearRightCorner.jpg
    ├── ControlCenterBox-ScreenShell.jpg
    ├── DFRobot-OLEDInsert-FrontProfile.jpg
    ├── DFRobot-OLEDInsert-SideRearProfile.jpg
    ├── Hero-Inserts.jpg
    ├── Seeed-WLEDSingleInsert-FrontProfile.jpg
    ├── Seeed-WLEDSingleInsert-SideRearProfile.jpg
    ├── Seeed-WLEDStripInsert-FrontProfile.jpg
    └── Seeed-WLEDStripInsert-SideRearProfile.jpg
```

## Description of Components

### Combo Base and Screen 

- **Base_AND_Screen.f3d**, **Base_AND_Screen.step**, **Base_AND_Screen.stl**: Start here as this is the file which combines both the base and screen into a single print. [Download Base_and_Screen Files](./Files/Base_AND_Screen.stl). ![Base_AND_Screen](./images/ControlCenterBox-FrontRightCorner-Empty.jpg)


### Base and Lid
- **BaseBox.f3d**, **BaseBox.step**, **BaseBox.stl**: Main enclosure base for holding components. [Download BaseBox Files](./Files/BaseBox.stl)
- **BaseLid.f3d**, **BaseLid.step**, **BaseLid.stl**: Lid that secures onto the base for easy access. [Download BaseLid Files](./Files/BaseLid.stl)

#### Images
- **Base Lid**: Highlights the assembled base and lid from a front-right perspective.  ![ControlCenterBox-BaseLid-FrontRightCorner](./Images/ControlCenterBox-BaseLid-FrontRightCorner.jpg)
- **Base Lid Underside**: Underside view of the base and lid assembly.  ![ControlCenterBox-BaseLid-RightRearUnderside](./Images/ControlCenterBox-BaseLid-RightRearUnderside.jpg)

### Shell
- **Base_AND_Screen.f3d**, **Base_AND_Screen.step**, **Base_AND_Screen.stl**: A modular shell designed to house screens or other inserts. [Download Shell Files](./Files/Base_AND_Screen.stl)

#### Images
- **Base Shell**: Displays the base with the screen shell attached.  ![ControlCenterBox-BaseShell](./Images/ControlCenterBox-BaseShell.jpg)
- **Screen Shell**: Standalone view of the screen shell.  ![ControlCenterBox-ScreenShell](./Images/ControlCenterBox-ScreenShell.jpg)

### Inserts
1. **Center Screen LED Insert**
   - **Center Screen LED Insert.f3d**, **Center Screen LED Insert.step**, **Center Screen LED Insert.stl**: Insert designed for a central screen LED. [Download Center LED Insert Files](./Files/Center Screen LED Insert.stl)
   - **Images**:
     - **LED Strip Front Profile.jpg**: Front view of the OLED insert.  ![View Image](./Images/Seeed-WLEDStripInsert-FrontProfile.jpg)
     - **LED Strip Rear Profile.jpg**: Side and rear view of the OLED insert.  ![View Image](./Images/Seeed-WLEDStripInsert-SideRearProfile.jpg)

2. **Left Screen - DFRobot OLED (128x64) and Buttons**
   - **Left Screen - OLED.f3d**, **Left Screen - OLED.step**, **Left Screen - OLED.stl**: Insert designed for OLED displays. [Download OLED Screen & Buttons Insert Files](./Files/Left_Screen_OLED_and_Buttons.stl) ![Left Screen OLED and Buttons - Front Profile](./Images/DFRobot-OLEDInsert-FrontProfile.jpg) ![Left Screen OLED and Buttons - Side Rear Profile](./Images/DFRobot-OLEDInsert-SideRearProfile.jpg)

3. **Rear Extension - Single Keystone**
   - **Rear_Extension_Insert_Single_Keystone.f3d**, **Rear_Extension_Insert_Single_Keystone.step**, **Rear_Extension_Insert_Single_Keystone.stl**: Insert designed for a single Keystone insert. [Download Rear Insert - Single Keystone Files](./Files/Rear_Extension_Single_Keystone.stl) ![Rear Extension Insert - Single Keystone](./Images/RearInsert-SingleKeystone-Face.jpg) ![Rear Extension Insert - Single Keystone- Rear](./Images/RearInsert-SingleKeystone-Rear.jpg)

4. **Right Screen - WLED and Buttons**
   - **Right Screen - WLED and Buttons.f3d**, **Right Screen - WLED and Buttons.step**, **Right Screen - WLED and Buttons.stl**: Insert designed for WLED modules and buttons. [Download Single WLED & Buttons Insert Files](./Files/Right_Screen_WLED_and_Buttons.stl) ![Right Screen -Single WLED and Buttons - Front Profile](./Images/Seeed-WLEDSingleInsertWithButtons-FrontProfile.jpg) ![Right Screen - Single WLED and Buttons - Side Rear](./Images/Seeed-WLEDSingleInsertWithButtons-SideRearProfile.jpg) 

### Hero Images
- **Control Center Box**: Fully assembled Control Center Box in its default configuration.  ![Control Center Box - Hero](./Images/ControlCenterBox-Hero.jpg)
- **Control Center Box - With Blanks**: Fully assembled box with blank inserts for customization.  ![Control center box with blanks](./Images/ControlCenterBox-Hero-WithBlanks.jpg)
- **Hero-Inserts.jpg**: Showcases all available inserts together.  ![Hero inserts](./Images/Hero-Inserts.jpg)

### Additional Views
- **ControlCenterBox-FrontProfile-Empty.jpg**: Front profile of the box without any inserts.  ![Control Center box front profile - Empty](./Images/ControlCenterBox-FrontProfile-Empty.jpg)
- **ControlCenterBox-FrontRightCorner-Empty.jpg**: Front-right corner view of the empty box.  ![Control Center box front right corner profile - Empty](./Images/ControlCenterBox-FrontRightCorner-Empty.jpg)
- **ControlCenterBox-FrontRightCorner-Full.jpg**: Front-right corner view of the box with inserts installed.  ![Control Center box front profile - Populated](./Images/ControlCenterBox-FrontRightCorner-Populated.jpg)
- **ControlCenterBox-RearProfile.jpg**: Rear profile of the box.  ![View Image](./Images/ControlCenterBox-RearProfile.jpg)
- **ControlCenterBox-RearRightCorner.jpg**: Rear-right corner view of the box.  ![View Image](./Images/ControlCenterBox-RearRightCorner.jpg)
- **ControlCenterBox-RearRightCorner-WithEthernetInsert.jpg**: Rear-right corner view with an Ethernet insert installed.  ![View Image](./Images/ControlCenterBox-RearRightCorner-WithEthernetInsert.jpg)

## Printing Instructions
1. **Recommended Settings**:
   - Material: PLA or PETG
   - Layer Height: 0.2mm
   - Infill: 20% (adjust based on strength requirements)
   - Supports: Required for overhangs (e.g., Keystone insert area, screen seperator bars)

2. **Assembly**:
   - Print the combined base and screen first
   - Choose and print the necessary inserts based on your hardware and a base lid as well
   - Secure inserts into the shell and mount the shell to the base.
     - The inserts are screwed into the body using m2.5x4mm screws. 

3. **Customization**:
   - Modify the CAD files to fit additional components if needed.

## Usage
- Ideal for prototyping small electronic projects.
- Modular design allows for easy customization and reconfiguration.
- Suitable for DIY home automation and display projects.

