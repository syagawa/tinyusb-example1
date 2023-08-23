# net example1

## install libraries

1. Start Arduino
2. Sketch -> Include Library -> Manage Libraries
3. search M5Stack and install M5Stack
4. search tinyusb and install ESP32TinyUSB and  Adafruit_TinyUSB_Arduino
5. select board M5Stack-ATOMS3


## M5Stack AtomS3U uploading memo

* Arduino settings
    board: M5Stack-ATOMS3 - M5Stack
    port SerialPort(USB)


* If I have sketches that use storage, do I need to remove the disk from my PC? (For Windows, right-click the disk on the desktop)

* Also, do I have to press and hold the reset button on the S3U when writing?

## refs

https://www.seeedstudio.com/blog/2020/04/30/tinyusb-stack-on-seeeduino-xiao/
https://lang-ship.com/blog/work/m5stack-atoms3-2/



## examples

* ezdata
    * https://github.com/m5stack/M5AtomS3/tree/main/examples/Advanced/EzData
    * how to get token => click refresh token http://docs.m5stack.com/en/arduino/iotservice/ezdata
    * require libraries: ArduinoJson
