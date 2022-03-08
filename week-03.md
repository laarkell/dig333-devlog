## Week 3

### Context

The critical engineering manifesto lists out 10 ideals of what a critical engineer should do or be like. It was written by the Critical Engineering working group. All of the ideals are about going beyond what the machine shows and the obvious parts and advises you to dig deeper. One point that specifically stuck out to me was number 7, "The Critical Engineer observes the space between the production and consumption of technology. Acting rapidly to changes in this space, the Critical Engineer serves to expose moments of imbalance and deception." This one stuck out to me because technology is extremely controlled and driven by money and capitalism and it is important to be aware of this and work to counter it's effect on quality. The next piece we read was an Artist profile on Julian Oliver written by Jason Huff. Julian Oliver was one of the writers of the engineering manifesto. He talks about how engineering is one of the most transformative languages and that it is important to pay attention to the bigger picture as well as the small details. The article also outline a couple more projects Oliver contributed to as well as some questions that address his background and interests. One of the questions that I would ask Oliver is, do you determine what projects you are going to work on based on the company or based on the benefit of the goal? The movie we had to watch this week was called Love and Power and is the first part of  the series All Watched over by the Machines of Loving Grace. This episode talks about the idea that computers can create a ne world and how this idea came to be due to a series of events. Some of the reasons were self-interest, capitalism, and the ideals of silicon valley.

### Monk Chapter 2 - Networking (31-49)
#### 2.0. Introduction
#### 2.1. Connecting to a Wired Network
- [x] Connect to a Raspberry Pi via SSH
- [x] Use on of the lab demos: ssh pi@laurenpi 
#### 2.2. Finding Your IP Address
1. Demonstrate two different methods to find your IP address 
- $ hostname -I
- $ ifconfig
#### 2.3. Setting a Static IP Address
*Just skim this section.*
#### 2.4. Setting the Network Name of a Raspberry Pi
1. Explain how to change the hostname of a RPi
- $ sudo raspi-config
- select Network Options 
- opens a form in which you can enter the new network name 
- restart your Raspberry Pi for the changes to take effect
#### 2.5. Setting Up a Wireless Connection
1. Explain how to set up wifi on a RPi
- $ sudo raspi-config
- select Network Options
- select WiFi 
- prompt appears, input the SSID and password
#### 2.6. Connecting with a Console Lead
#### 2.7. Controlling the Pi Remotely with SSH
1. Demonstrate how to connect and disconnect to a RPi via SSH
- $ sudo raspi-config
- $ ssh yourIPAdress -l pi
3. Demonstrate how to perform basic filesystem task over SSH
- once in you can use cd, ls and basic terminal commands to move and create fiels in pi over ssh

