# LINE Things Starter for M5Stack

## Requirements
* [Moddable SDK](https://github.com/Moddable-OpenSource/moddable)
* [M5Stack or M5StickC](http://m5stack.com/)
* USB Type-C to USB Cable

## Installation
See [the official Getting-Started document of Moddable](https://github.com/Moddable-OpenSource/moddable/blob/public/documentation/Moddable%20SDK%20-%20Getting%20Started.md). Follow ESP32 section of your OS(MacOS, Windows or Linux).

## Setup & Upload
1. Connect the **M5Stack** board via USB Type-C cable to your computer
2. Go to this directory on terminal
3. Type below to upload

for M5Stack
```sh
$ mcconfig -d -m -p esp32/m5stack
```

or for M5StickC
```sh
$ env ESPBAUD=1500000 DEBUGGER_SPEED=1500000 mcconfig -v -d -m -p esp32/m5stick_c -r 270
```
