## Optional - Build mock thermostat with ESP32

In this optional section, we will walk through configuring an ESP32 as follows:

* Red and blue LED used to indicate that thermostat is in HEAT or COOL mode, respectively

* White LED to indicate that the device is successfully connected to your AWS IoT Core cloud backend

* DHT11 temp/humidity sensor from which the device will take readings and send to AWS IoT

* A push-botton to allow the user to physically change the thermostat between HEAT, COOL, and OFF

We will flash the ESP32 with [Mongoose OS](https://mongoose-os.com/), an open-source IoT operating system. Mongoose OS (MOS) supports C/C++ and Javascript. We will be using the Javascript version in this demo.  

### Wire up your ESP32

The instructions and images below assume you are using the exact same ESP32 dev board that I listed above. If you are not, the pin numbers and locations may be different for your board's manufacturer, so be sure to reference their pinout diagram. 

1. Here's an overview and pseudo-schematic: 

    Board and schematic: 

    <img src="./../images/board_and_schematic.jpg" border="1" style="border-color: black;transform:rotate(90deg);">

    Up-close (1): 
    <img src="./../images/circuit-1.jpg" border="1" style="border-color: black">

    Up-close (2): 
    <img src="./../images/circuit-2.jpg" border="1" style="border-color: black;">

    Pinout (this is specific to my ESP32 manufacturer): 
    <img src="./../images/pinout.jpg" border="1" style="border-color: black;transform:rotate(90deg);">

### Flash ESP32 with thermostat skill

1. TODO: add instructions to create/generate device certs for your IoT thing and download locally. 

2. TODO: add instructions to flash ESP32 with contents of the /esp32 directory. 

3. TODO: add instructions to copy certs to ESP32 (if not already part of the flash)

4. TODO: add instructions to configure WIFI for the ESP32

5. After a few moments, verify that your ESP32 is connected to AWS either via the white LED or via the messages in the MOS console.