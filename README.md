# Lab 1

## Objectives

This lab will serve to introduce students to soldering techniques for printed circuit boards (PCBs) and wire-to-wire connections. By the end of the lab each student should:

1. Be able to identify a number of common electronic components
2. Be able to solder components to through-hole PCBs
3. Be able to solder simple surface-mount components to a PCB
4. Be able to solder wires to one another and insulate joint with heat shrink tubing
5. Know how to obtain code from GitHub
6. Be able to upload code to an ESP32-based Arduino microcontroller
7. Have a working Arduino-compatible microcontroller
8. Have a number of other components ready to be used for subsequent lab exercises

## Description

[Arduino](https://www.arduino.cc) started as an open-source microcontroller originally designed with the goal of making it simple for artists and other nontechnical individuals to build interactive objects. It is easy to program and intuitive to connect to external devices such as motors, lights, switches and other sensors. The right balance of capability and cost, bolstered by a growing open-source hardware movement, has allowed the device to become widely adopted. Today, the Arduino family of microcontrollers are employed in a wide range of applications, including art installations, mobile robotics, machine control, home automation and entertainment systems. Programming is performed using the cross-platform Arduino IDE, which runs on Windows, Mac OS X and Linux based systems.

The MSEduino that you will build in this lab is a custom Arduino-compatible board developed specifically for MSE 2202. It uses an ESP32 microcontroller and is supported by the Arduino IDE. The ESP32 operates on an input voltage of 3.3 V. A voltage regulator on the MSEduino board converts a 5 VDC input supplied to the USB port to 3.3 VDC for use by the microcontroller. Both 3.3 V and 5 V are available on the board to power peripheral devices. The ESP32 used by the MSEduino has two 32-bit cores running at up to 240 MHz, 4 MB of Flash memory, 512 kB of SRAM, 448 kB of ROM, 25 general-purpose input/output (GPIO) lines, two 10 channel A/D converters, and many built-in peripherals, including Bluetooth LE, WiFi, a real-time clock, and hardware security. It is a very powerful and capable device.

In addition to the MSEduino, this lab will prepare a number of other components that will be used in this and future lab exercises. These include an MX1508 dual DC motor driver, DC gearmotors with integrated encoders, an IR detector, and an IR LED.

### Equipment

For this lab, you will have to purchase an MSE 2202 Lab Kit. This kit contains a custom-designed Arduino-compatible ESP32-based microcontroller board, a variety of components required to populate this board, a modular solderless breadboard for prototyping purposes, a USB cable for interfacing the microcontroller with a desktop or laptop computer, a variety of other electronic components, and the parts required to build the MSEbot in Labs 3 and 4. The MSEduino features a number of connectors and components to facilitate the development of mechatronic devices and robots. The lab kit will be used throughout MSE 2202.

In addition to the components contained in the Lab Kit, the following equipment is available in ACEB 3435 for the purpose of conducting this laboratory:

* Safety glasses
* Weller WES51 soldering station
* 63/37 tin/lead rosin core solder
* Panavise with circuit board holder
* Flush cutters
* Needle-nose pliers
* Wire strippers
* Heat gun
* Solder sucker (if necessary)
* Agilent Technologies U3401A multimeter
* Rigol MSO1074 4 Channel 70 MHz oscilloscope
* USB-A male to USB-A female cable
* PC with Arduino IDE

## Prelab Preparation

1. Purchase the MSE 2202 Lab Kit from the [Engineering Stores online store](https://estore.eng.uwo.ca). Bring your printed or electronic receipt to the lab.
2. Review [Soldering is Easy](https://mightyohm.com/files/soldercomic/FullSolderComic_EN.pdf).

## Exercises

This lab consists of the following exercises. Follow the associated link for full instructions for each exercise.

1. [MSEduino Assembly](docs/MSEduino-assembly.md)
2. [MX1508 DC Motor Driver Assembly](docs/MX1508-assembly.md)
3. [DC Motor Wiring](docs/DC-motor-wiring.md)
4. [IR Detector Assembly](docs/IR-detector-assembly.md)
5. [IR LED Assembly](docs/IR-LED-assembly.md)
6. [MSEduino Testing](docs/MSEduino-testing.md)

## Evaluation

| Task | Maximum Marks |
| :----------- | :-------------: |
| MSEduino build | **40** |
| MX1508 build | **5** |
| DC motor wiring | **10** |
| IR receiver build | **5** |
| IR LED build | **5** |
| MSEduino operational | **25** |
| Build quality | **10** |
| Total Marks | **100** |
