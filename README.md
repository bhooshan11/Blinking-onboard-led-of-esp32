# TASK 1: Blinking onboard led of Esp-32

<p> Esp-32 is a wifi module. It is the successor of the popular Esp8266 wifi module. The processor used in esp-32 is ESP-WROOM-32, It is a 32 bit microprocessor.</p>

## Specifications
* Upto 18 12-bit Analog to Digital converters.
* Two 8-bit Digital to Analog converters.
* 10 capacitive touch switch sensors.
* Four SPI channels.
* Two I2C interfaces.
* Two I2S interfaces (for digital audio).
* Three UARTs for communications.
* Upto 8 channels of IR remote control.
* Upto 16 channels of LED PWM (pulse width modulation).
* An integrated Hall-effect sensor.
* An ultra-low-power analog preamp.
* An internal low-dropout regulator.

## Image of Esp-32.
![this is an image](add the image)

### Setting up arduino ide for esp32.
* Download and install arduino ide from the [official website](https://www.arduino.cc/en/Main/Software ).
* After installing, open IDE and go to **Files -> Prefrences** and open preference window and check for **Additional Boards Manager URL's**.
* If the box already has another URL then paste the below URL by seperating another URL using comma otherwise paste the below URL into this box.

    https://dl.espressif.com/dl/package_esp32_index.json
 * Press OK.
 * Now go to **Tools-> Board-> Board Manager** and search for ESP32 and press install.
    After this close the window of board manager.
 
 
 Now your arduino IDE is ready to work with esp32.
 
 In this task we are blinking the built-in led of ESP32. In ESP32 the internal led is connected to pin no 2. First connect the esp32 to your computer using micro-usb cable.
 * Go to **Tools-> Board** and select **ESP32 Dev Module**.
 * Go to **Tools-> Port** and select the appropriate port.
 * Write the code for blinking of built-in led 
     
     Code:(https://github.com/bhooshan11/Blinking-onboard-led-of-esp32/blob/main/task1.ino)
 * Compile and upload the code.
 
 
 ### WORKING 
 (https://drive.google.com/file/d/1nfnOAKrabgT8GNB9jvQBjM82S_1OH-5J/view?usp=sharing)
 
 
 ### ERRORS
 * While uploading the code to ESP32 it shows fatal error. To solve this problem press and hold boot button in ESP32 while uploading.
 
 ### Refrences.
 https://iotdesignpro.com/projects/getting-started-with-esp32-program-it-using-arduino-ide-blinking-led
