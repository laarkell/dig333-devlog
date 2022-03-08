## Week 2

### Context

We had two readings this week, the first was an article in the MIT Review by Sanjay Sarma and was titled, The Internet of Things: Roadmap to a Connected World. This article talks about the internet of things, which is the term used for a network of objects embedded in an electronic system that optimizes data collection. Sarma emphasizes that the internet of things is going to affect every aspect of life and that if it’s not regulated that till lead to weakness. He suggests the creation of procedures, standards to control and lists three primary concerns to focus on. I understand that lack of encryption can lead to hacking and data stealing but I am unsure what data will be breached by the objects that are described in the article. For example, he talked about teslas and google cars being examples. But what data will be leaked form these and why is it detrimental? The second reading was titled, The Internet of Things has a dirty little secret: it's not really yours. This article talks about "The internet of shit" which is a twitter account that is all about devices that are being connected to the internet. The author talks about how the internet devices just lead to more problems, often break more easily or need updating more often, and are more complicated. Here is a quote from the author that talks about his view on these devices, "The lure of these devices when presented against the backdrop of old, offline devices is obvious: they could change your whole life and in some ways for me, they have, but the headaches are only beginning, and selling them as life-changers without commitment is irresponsible, and there’s no transparency about how they could change in the future." One question I have for this author is as follows, is there a future where the internet connected devices are beneficial to us? And how will we know when this is, or which ones are? If not, how can we avoid letting everything become internet connected?


### Platt Experiments 1-5

#### 1. Taste the power
Notes:     
- Current is related to the load or the resistance
- Didn't taste much!

Takeaway:
- Positive voltage runs from the positive to the negative battery terminal and negative flows the other way.

Question:
- Are you an insulator or a conductor?

#### 2. Lets abuse a battery
![Screen Shot 2022-02-08 at 8 21 54 PM](https://user-images.githubusercontent.com/70282901/153103799-0ff97fc4-e60d-4067-8c76-9b6bfee938a9.png)

Takeaway:
- Never touch the positive and negative ends of a battery together or it will smoke and smell.

Question:
- If you smell something smokey, what is the first thing you should disconnect in your circuit?

#### 3. Your first circuit
![Screen Shot 2022-02-08 at 8 10 33 PM](https://user-images.githubusercontent.com/70282901/153102695-da3e90d4-37b2-4649-a600-d7722783eebe.png)

Notes:        
- It does not matter what order you put the pieces in
- Resistors have a color code that allows you to determine their resistance
- Multimeter can measure voltage, current, and resistance
- Resistor is used to block some voltage from the LED

Takeaway:
- Diodes or LEDs have to face the right direction in order to work properly.

Question:
- What do the colors on a resistor mean?

#### 4. Varying the voltage

Notes:       
- Potentiometers allow you to vary the voltage
- Turning the knob on the potentiometer changes the resistance
- Doesn't matter if you put the pot before or after the LED
- Ohm's Law: V=IR
-  Amount of voltage changes the brightness of the LED, more the brighter, but not too much!

Takeaway:
- You can ignore the resitance of the wires when doing ohm's law calculations

Question:
- If you want to combine batteries how do you connect them? Which terminal to which terminal?

#### 5. Lets make a battery!
- Didn't have any lemons so I didnt make it but it was interesting to read!
- When zinc reacts chemically with an acid, like lemon juice, it makes free electrons and conducts electricity
- Bottled lemon juice works just as well as fresh lemons

### Monk Chapter 1 - Setup and Management

#### Recipes and outcomes:
##### 1.1 Selecting a Model of Raspberry Pi
1. Explain some uses for different Raspberry Pis (Nano, Zero, V3, V4): 
- Zero is good for a single purpose and projects that require a tiny size, like a web camera, smart home device, can run the Apache server software, no ethernet, no SATA ports, doesn’t have an in-built GPIO header with it
- V3 is good for projects that only demand passive cooling, 
- V4 is good for machine learning, watching videos, build a robot, an educational tool for students and teachers, has quad-core 64-bit processor coupled with 4 GB RAM
2. List common features of a RPi 3 or 4 Model B:
- 1.5-GHz, quad-core processor with 8/4/2 GB RAM
- USB 3.0 and 2.0 ports
- ethernet port
- micro-HDMI connectors
- three to four times faster than any previous Raspberry Pi
##### 1.3 Enclosing a Raspberry Pi
1. Explain why you need an enclosure:
- case can act as a heat sink
- protects the sensors and chips that are exposed on the pi
- elimianted static electricity from affecting it 
##### 1.4 Selecting a Power Supply
1. Recall the standard operating voltage of a RPi: **5V**
3. Describe the safe operating current (A) of a RPi: **2A**
4. Describe the potential downsides of using too little current or too much
- Could harm the Pi if you use too much, and if you don't use enough it might not run properly
##### 1.5 Selecting an Operating System 
- [x] Recall there are custom operating systems for media centers, retro gaming, etc.
##### 1.7 Installing an Operating System Without NOOBS
1. Explain why it is best to avoid NOOBS, Pi Bakery, and other "pre installed" SD cards and non-RPI Foundation options:
-  if you want to use a nonstandard operating system or if you want the disk image to be on something other than an SD card like USB drive
2. Demonstrate how to install Raspberry Pi OS using Raspberry Pi Imager:
- download imager, insert SD card, Open imager, configure settings and export iOS to SD card
##### 1.12 Using a Composite Video Monitor/TV 
1. Describe the two video out signals on a RPi:
- HDMI, better quality, 
- composite video from the audio jack,
##### 1.14. Maximizing Performance
1. Describe the pros and cons of "overclocking":
- con: could make it overheat, draws more current
- pro: runs faster, increases performance
3. Demonstrate how to configure your RPI with sudo raspi-config:
- ![Screen Shot 2022-03-07 at 9 16 53 PM](https://user-images.githubusercontent.com/70282901/157152982-c7acee94-82d4-4bed-9a38-d0771fd59e52.png)
##### 1.15. Changing Your Password
- [x] Use raspi-config to change your password
![Screen Shot 2022-03-07 at 9 17 18 PM](https://user-images.githubusercontent.com/70282901/157153026-a448ed86-512f-43b6-9332-b5380f279dc1.png)
##### 1.16. Shutting Down Your Raspberry Pi
1. Explain what sudo is and why you would use it: stands for super user do, and is like the administrative power and it is used to perform important administrative tasks like shutting down
2. Demonstrate how to reboot from the command line:
![Screen Shot 2022-03-07 at 9 20 29 PM](https://user-images.githubusercontent.com/70282901/157153405-2df4bdba-a157-4ffe-8259-8af94f1bfba3.png)
4. Explain why you shouldn't pull the power plug on the (any) computer:
- pulling out could lead to file corruption, risk data loss, could damage computer
##### 1.17. Installing the Raspberry Pi Camera Module
*Just skim this section.*
1. Explain how to install and enable the Pi Camera:
- ribbon cable attaches to a special connector
- use the Raspberry Pi Configuration tool or raspi-config on terminal to configure camera module 
- command to take pictures is: $ raspistill -o image1.jpg

- [x] View the help menu for raspistill
- [x] Use raspistill to take a picture via the CLI
##### 1.18. Using Bluetooth
*Just skim this section*

