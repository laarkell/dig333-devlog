# Week 06




## Context

John Correll, Igloo White (2004)
- Summary: This article talks about how the US was strategically bombing Vietnam but a few, including Secretary of Defense Robert S.
McNamara, decided that it would be better to create barriers prohibiting north vietnam from south with mines and sensors. One proposal included creating sesors that look like dog poop but it got shot down because there were no dogs on the Ho Chi Minh Trail. Igloo white was the combinatino of the Igloo White consisted of over 20,000 sensors, the orbiting aircraft, and the infiltration Surveillance Center. The sensor data was used for many things including monitoring, updating, and tracking the direction and speed of trucks so that aircraft could pursue and attack. In the end, the sensors detected thousands of trucks, that were then destroyed by air strike. 
- Quote: "The report proposed building an antipersonnel barrier across Vietnam below the Demilitarized Zone and an antivehicular barrier, consisting of mines and battery-powered sensors, along the Ho Chi Minh Trail in Laos."
- Comment: This article was interesting,and it was a unique application to this technology. It is interesting to see that the military is the reason behind many technological advancements. 
- Question: I wonder if sattellites have replaced these sensors? It is a much safer option than going in and placing sensors.

Mayo Nissen Unseen Sensors: Constantly Sensing but Rarely Seen (2014)
- Summary: This article notes that sensors are everywhere, and whether we notice them or not they are sensing us. Sensors are owned and used by the government and by private buisnesses and people. For example, the Domain Awareness System was created after 9/11 to monitoring devices in Manhattan. The article dives into the types of sensors found in NYC and what they do. The list includes the, Remote Traffic Microwave Radar Sensor, RFID E­ZPass Reader, Horizontally Polarized Panel Antenna, NYC Street Light Status, Water Meter Transmission Unit, and so many more.
- Quote: "Rather these changes happen incrementally, infiltrating our everyday bit by bit
as technology falls in price and grows in utility, availability, and reliability, and
becomes socially and politically palatable."
- Comment: The Magnetometer / Parking Sensor stood out to me becasue it would be helpful to have in Davidson!
- Question: Are there sensors that are illegal to have and use? Do you have to have a license for any of them? This reminds me of the police scanners that people can have that are not illegal. 


## Experiments


### Experiment #11: Light and Sound

#### Outcomes & Takeaways
- The first circuit we created made an LED flash on for one second and off for another second
- Transistors switch from on and off depending on the direction that the current flows (b,e or c)
- Made adjustments and removed parts to create second circuit which functioned as an ultra-simple sound synthesizer

#### Comments & Variations
- Having a symmetric circuit is important for the first one in this experiemnt so that the on and off of the LED is equal
- Speaker was extremely quiet but we did hear noise 

#### Questions
- They described how you change the pitch of the sound from the speaker, is there a way to change the volume?


![Screen Shot 2022-03-02 at 3 52 39 PM](https://user-images.githubusercontent.com/70282901/156447792-db24ba5b-48fd-47f0-8e59-011a68deb5de.png)
![Screen Shot 2022-03-02 at 3 52 27 PM](https://user-images.githubusercontent.com/70282901/156447799-198aae6d-1778-4423-8fb0-b5055d074658.png)


### Experiment #12: Joining two wires together

#### Outcomes & Takeaways
- The solder melts almost instantly when the iron touches it and it sort of bubbles until it hardens
- I tested the battery connections with an LED to be sure the connection was correct

![Screen Shot 2022-03-02 at 3 52 33 PM](https://user-images.githubusercontent.com/70282901/156447824-fe366947-b725-47a3-98f6-7d7c95be6368.png)

#### Comments & Variations
- I have soldered before but I have surprisingly never done two wires! I have only attached wires to a arduino
- In class we attached a single wire to the battery conection wire that had many small wires in it
- We didnt get to use the heat shrink wrap becasue we didn't have a heater

#### Questions
- Can a circuit get hot enough that the solder material melts? What if the extermal conditions are really hot? If so are there alternative materials?


### Experiment #13: Roasting an LED

#### Outcomes & Takeaways
- lots of current passing through the LED created excessive heat which breaks the component
- plastic is not a good thermal conductor but metal is
- You can use an aliigator clip as a heat sink in order to pull the heat away from delicate components

#### Comments & Variations
- Its always safer to use a heat sink to protect components especially when building a complicated circuit
- We only had acess to one level power of soldering iron but I was able to see the affect of the heat sink by feeling the aligator clip and by everntually burnign out the LED

#### Questions
- What other materials are good heat sinks? Can you build a heat sink into your circuit?


### Monk Chapter 6 - Python Lists and Dictionaries, Recipes and outcomes:

#### 6.1. Creating a List
- format to create a list: a = [34, 'Fred', 12, False, 72.3]
#### 6.2. Accessing Elements of a List
- a = [34, 'Fred', 12, False, 72.3], a[1], Fred
#### 6.3. Finding the Length of a List
- len(list)
#### 6.4. Adding Elements to a List
- a.append("new item")
- a.insert(2, "new2")
- a.extend(b) where b is another lists that is added to the end of a
#### 6.5. Removing Elements from a List
- a.pop()removes last element in list a
- a.pop(0) removes element in 0 position
#### 6.6. Creating a List by Parsing a String
- "abc def ghi".split()
- "abc--de--ghi".split('--')
#### 6.7. Iterating Over a List
- a = [34, 'Fred', 12, False, 72.3]
- for x in a:
- print(x)
- 34
#### 6.8. Enumerating a List
- a = [34, 'Fred', 12, False, 72.3]
- for (i, x) in enumerate(a):
- print(i, x)
- (0, 34)
#### 6.9. Sorting a List
- a.sort()
#### 6.10. Cutting Up a List
- l = ["a", "b", "c", "d"]
- l[1:3]
- ['b', 'c']
#### 6.11. Applying a Function to a List
- [x.upper() for x in l] 
#### 6.12. Creating a Dictionary
- to create a dictionary, you use the {} notation 
- a = {'key1':'value1', 'key2':2}
#### 6.13. Accessing a Dictionary
- a['key1']
- 'value 1'
#### 6.14. Removing Entries from a Dictionary
- phone_numbers.pop('Jane')
#### 6.15. Iterating Over Dictionaries
- for name in phone_numbers:
- print(name)


### Monk Chapter 9 - Hardware Basics, Basic recipes for setting up Raspberry Pi general-purpose input/output (GPIO) connector

#### 9.0. Introduction
#### 9.1. Finding Your Way Around the GPIO Connector
1. Explain the difference between 26- and 40-pin layouts.
- top 26 pins are same in both 26 and 40 pin layouts so that you can use software built for 26 pins
- extra pins on the 40 have 3 ground pins and 9 extra GPIO pins
2. Add a printable GPIO pin template to your RPi. 

![Screen Shot 2022-03-09 at 3 52 49 PM](https://user-images.githubusercontent.com/70282901/157533985-89a98a0a-164e-4973-8720-14702fac51e4.png)

3. Describe the difference between digital vs. analog I/O pins
- an analog pin can take on a number of values or voltages whereas a digital pin only has 1,0 or high and low
- the RPi only had digital pins but you cna convert them to analog with a converter of sorts

#### 9.2. Keeping Your Raspberry Pi Safe When Using the GPIO connector
1. List important tips for keeping RPi safe when using GPIO
- dont touch GPIO with metal when its on
- dont power with more than 5V
- conect GND pin to ground always
- do not put more then 3.3V on any GPIO pin
- no more than 16mA per output
- do not draw more than 250mA in total

#### 9.8. Using a Breadboard with Jumper Leads
1. Connect a breadboard to the RPi with jumpers

![Screen Shot 2022-03-09 at 10 04 59 PM](https://user-images.githubusercontent.com/70282901/157580608-326424fe-30e3-4b66-996f-7a84b960d0d9.png)

#### 9.9. Using a Breadboard with a Pi Cobbler
1. Explain the benefits of a Pi Cobbler-type connector
- you can assemble all components on breadboard and just plug in ribbon when ready
- easier to connect components since its labeled
- you can solder to it
- you can transfer to a perma-proto board without having to redesign
#### 9.10. Using a Raspberry Squid
1. Describe an RPi Squid: an RBG LED that has resistors built in and has color-coded female header leads so that it can plug into the GPIO pins of a RPi
#### 9.14. Powering a Raspberry Pi with Batteries
1. Describe considerations when powering an RPi with batteries
- only can take 5V so you might need a voltage regulator if you want to use a 9V
- voltage regulator will heat up alot
- 600mA max current

