
# Week 07




## GPIO slides (1-35):
- analog wave is a continuous and digital wave is square wave or on/off
- GPIO stands for General-purpose input/output/both and it is a digital signal pin
- RPi has 40 GPIO pins

![Screen Shot 2022-03-09 at 2 17 06 PM](https://user-images.githubusercontent.com/70282901/157515332-b3b25126-0e26-478d-be42-96968ba27954.png)

- slide 16: connect and LED and button:


![Screen Shot 2022-03-09 at 3 18 36 PM](https://user-images.githubusercontent.com/70282901/157528123-a5866285-2803-4adb-8104-dac10ca03924.png)

![Screen Shot 2022-03-09 at 10 04 59 PM](https://user-images.githubusercontent.com/70282901/157580579-bb7bd896-f60a-4d10-82de-e2485b51f693.png)

- slide 26 and 27: turn on and off LED manually:

![Screen Shot 2022-03-09 at 3 09 26 PM](https://user-images.githubusercontent.com/70282901/157525439-6dc912b3-1408-4a02-bec4-6e0cbeb67c3d.png)

- BLink.py:


![Screen Shot 2022-03-09 at 3 12 42 PM](https://user-images.githubusercontent.com/70282901/157527796-d6ec48df-d548-44a0-ae31-373a556b3040.png)

![Screen Shot 2022-03-09 at 3 11 59 PM](https://user-images.githubusercontent.com/70282901/157527798-b596c905-06b3-45ed-b568-a4374c2c9dca.png)

![Screen Shot 2022-03-09 at 3 17 47 PM](https://user-images.githubusercontent.com/70282901/157527801-b57393ba-6e04-4040-816c-217276a6ef2a.png)

## Monk Chapter 10 - Controlling Hardware, Recipes and outcomes:

#### 10.0. Introduction
#### 10.1. Connecting an LED
1. Describe the difference between RPi.GPIO and gpiozero libraries.
- gpiozero is the new method of acessing GPIO pins
- RPi.GPIO library does not automatically set the GPIO pins to be in a safe input state
- with RPi.GPIO you must call a cleanup function before exiting
- without the clenaup fxn pins set to be outputs would remain as outputs after the program has finished
- you might accidentally short a GPIO output this way

2. Demonstrate a basic "blink" script using both RPi.GPIO and gpiozerio
- demostrated above!

#### 10.2. Leaving the GPIO Pins in a Safe State
1. Explain what is meant by "safe input state"
- this means it will not short any of the components, or the RPi and once finished use ti will reset and not retain it's state
#### 10.3. Controlling the Brightness of an LED
1. Use gpiozero to fade an LED in and out.
- shown above!
#### 10.4. Switching a High-Power DC Device Using a Transistor
#### 10.5. Switching a High-Power Device Using a Relay
- See also: Adafruit RPi 13 - Power Control 
#### 10.6. Controlling High-Voltage AC Devices
#### 10.7. Controlling Hardware with Android and Bluetooth
#### 10.8. Making a User Interface to Turn Things On and Off
#### 10.9. Making a User Interface to Control PWM Power for LEDs and Motors
#### 10.10. Changing the Color of an RGB LED
#### 10.11. Using an Analog Meter as a Display
- Do this in class


