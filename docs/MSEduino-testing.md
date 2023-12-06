# MSEduino Testing

In order to test the functionality of the MSEduino, test code must be loaded onto the device. 

Programs for the Arduino are called sketches. These are created within an Integrated Development Environment (IDE) for the Arduino. The IDE allows sketches to be written and edited. The language and constructs are similar to C++. It provides functionality to convert (or compile) the human-readable code into instructions that the Arduino hardware understands (machine language). The IDE also facilitates the process of uploading compiled machine code onto the Arduino board. The IDE is available for Windows, Mac OS X and Linux based systems.

To start, Visit the official Arduino website and click on the \textsf{Getting Started} header (\url{https://arduino.cc/en/Guide/HomePage}). Follow the step-by-step instructions to install the Arduino IDE for the operating system on your laptop or home computer. Open the [Arduino IDE](https://www.arduino.cc/en/software) and configure it for the ESP32. 



Use a USB-A to USB-micro cable to connect your ESP32 to your computer. Use the **Tools→Board→esp32** menu to select the **DOIT ESP32 DEVKIT V1**. If you do not see any options for ESP32 boards, follow the instructions [here](https://randomnerdtutorials.com/installing-the-esp32-board-in-arduino-ide-windows-instructions/).

![Board configuration](docs/Config-board.png)

Once the board is selected, the Port should be set as **COMx** on Windows or **/dev/cu.usbserial-000x** on Mac.

![Port configuration](docs/Config-port.png)

Open and/or write the sketch that is to be uploaded to the microcontroller. Select **Sketch→Upload** or press the right arrow icon to build and upload the sketch.

![Program upload](docs/Upload.png)

In order to help identify the cause of hangups and errors during the build and upload processes, it is recommended that verbose output be enabled. Open the Preferences window and ensure that the **compile** and **upload** checkboxes are selected:

![Arduino IDE preferences](docs/Config-preferences.png)

#### VSCode and PlatformIO

Note that as an alternative to the Arduino IDE, this project can be developed using [VSCode](https://code.visualstudio.com) with the [PlatformIO IDE](https://platformio.org/platformio-ide) extension and the [Espressif 32 platform](https://registry.platformio.org/platforms/platformio/espressif32) installed.