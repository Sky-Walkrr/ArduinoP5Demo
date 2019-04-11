### ArduinoP5Demo

A demo shows how P5.js interacts with Arduino, based on a pulse sensor.

---

##### How to use

0.Download and install the [P5.serialcontrol](https://github.com/vanevery/p5.serialcontrol/releases) app (which is a packaged application for running serial server on computer). When you run this program, it allows you to select the serial port for communication. You also have the option to run [p5.serialserver](https://www.npmjs.com/package/p5.serialserver) in command line, which requires node.js environment.

1.Run P5.serialcontrol.exe, connect your pulse sensor and arduino with PC, select an available port for Arduino.

2.Change the `portname` in `sketch.js` to the same as YOUR available port name.

3.Open `index.html` in browser(suggest Chrome).