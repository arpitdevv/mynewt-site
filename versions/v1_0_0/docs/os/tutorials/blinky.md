## Blinky, your "Hello World!" on a Target Board
The set of Blinky tutorials show you how to create, build, and run  a "Hello World" application that blinks a LED on the various target boards that Mynewt supports. The tutorials use the same Blinky application from the [Creating Your First Project](/os/get_started/project_create) tutorial.  

### Objective

Learn how to use packages from a default application repository of Mynewt to build your first *Hello World* application (Blinky) on a target board. Once built using the *newt* tool, this application will blink a LED light on the target board.

###Available Tutorials
Tutorials are available for the following boards:

* [Blinky on an Arduino Zero](/os/tutorials/arduino_zero.md)
* [Blinky on an Arduino Primo](/os/tutorials/blinky_primo.md)
* [Blinky on an Olimex](/os/tutorials/olimex.md)
* [Blinky on a nRF52](/os/tutorials/nRF52.md)
* [Blinky on a RedBear Nano 2](/os/tutorials/rbnano2.md)
* [Blinky on a STM32F4-Discovery](/os/tutorials/blinky_stm32f4disc.md)

We also have a tutorial that shows you how to add [Console and Shell to the Blinky Application](/os/tutorials/blinky_console.md).
<br>
### Prerequisites
Ensure that you meet the following prerequisites before continuing with one of the tutorials. 

* Have Internet connectivity to fetch remote Mynewt components.
* Have a computer to build a Mynewt application and connect to the board over USB.
* Have a Micro-USB cable to connect the board and the computer.
* Install the newt tool and toolchains (See [Basic Setup](/os/get_started/get_started.md)).
* Read the Mynewt OS [Concepts](/os/get_started/vocabulary.md) section. 
* Create a project space (directory structure) and populate it with the core code repository (apache-mynewt-core) or know how to as explained in [Creating Your First Project](/os/get_started/project_create).
<br>
###Overview of Steps
These are the general steps to create, load and run the Blinky application on your board:

* Create a project.
* Define the bootloader and Blinky application targets for the board.
* Build the bootloader target.
* Build the Blinky application target and create an application image.
* Connect to the board.
* Load the bootloader onto the board.
* Load the Blinky application image onto the board.
* See the LED on your board blink.

<br>

After you try the Blinky application on your boards, checkout out other tutorials to enable additional functionality such as [remote comms](project-slinky.md) on the current board. If you have BLE (Bluetooth Low Energy) chip (e.g. nRF52) on your board, you can try turning it into an [iBeacon](ibeacon.md) or [Eddystone Beacon](eddystone.md)! 

If you see anything missing or want to send us feedback, please sign up for 
appropriate mailing lists on our [Community Page](../../community.md).
