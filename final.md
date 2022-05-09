## Final Project: Utility / No Utility: MOONlight

### Creator Statement:


The MOONlight is an LED matrix that shows when the moon is in the sky and what phase it is depending on your location. It can be decorative, useful, and not useful. It is completely handmade and only requires power through a wall outlet. It is targeted towards astronomers and moon lovers. It can be used to alert someone what the phase of the moon is. For example, some people love to go look at full moons, and this device would show them when the moon is full and when it’s getting close to full. Contrary to popular belief, the moon is not in the sky every night. The MOONlight is a great device for when it is a cloudy day and the moon can’t be seen, or for a photographer that loves to capture the moon. The device can also be displayed as an art piece because of its aesthetic design. While there are some theoretical uses for this device, in reality, you can just go outside and look for the moon or go online and find out what phase it is with a simple google search. This device technically doesn't perform a task, solve a problem or make life easier. Therefore, it is useful and useless at the same time. I have a personal interest in space and the moon, which is where the idea for this device came from. When I was browsing for devices to make, I saw an LED matrix, and from there I thought about interesting things to display on it. If I were to have this device, I would use it as an art piece and have it set up on display. I also think it would be a nice reminder to look at the moon when it is up. 


On the literal side, the MOONlight is a device that lights up when the moon has risen and turns off when the moon has set depending on your location. Currently its location is set to Davidson, NC. When it lights up, it displays the correct phase that the moon is in at that time. The materials I used to create the MOONlight include a large sab of orange acrylic, 256 white LEDs, 4 shift registers, lots of wires, and a Raspberry Pi 4. The LEDs were soldered into a hand-made 16 by 16 LED matrix.  The matrix is controlled by a large python file that uses known constants, and physics equations to calculate the current phase, and the rise and set times for the moon at a certain location. I then designed matrices for each phase and setup CRON TAB to update the device very 5 minutes. The Raspberry Pi connects to WIFI and it gets power from a wall outlet. Originally, I planned to pull the moon information (rise, set, phase) from an API. However, I had trouble pulling it from the internet and I realized I could calculate the information from equations and constants. I was able to do so with loads of help from online examples and files. The two areas that took up the most time in my project was the building and the coding. The building took hours on end and including drilling 512 holes by hand and soldering 512 joints. The other area, the coding, involved creating 3 separate files, one for rise and set, one for phase, and one for controlling the matrix. I then had to combine them all and add in CRON TAB in order to have it running continuously. 


I am very happy with the outcome of my final project. Appearance wise, it is exactly what I had envisioned and planned, and I am glad I chose to hand-make it. I tested the code on Monday 5/9 and it sucessfully turned on at 1:30pm when the moon had risen! The only things I wish I was able to fix on my project were the few LEDs that were out. I removed them and resoldered them, but they didn’t seem to want to turn on. If I were to continue improving it, I would add a way for the user to change the location and I would add a way to display more information. For example, a countdown to when the moon sets.


![Screen Shot 2022-05-07 at 10 04 25 PM](https://user-images.githubusercontent.com/70282901/167278703-309575a7-3133-46d0-a1ee-023986c9c22e.png)

![Screen Shot 2022-05-08 at 7 59 02 PM](https://user-images.githubusercontent.com/70282901/167321178-3f4ffb2e-3752-4bbf-a517-ebf945cc6b59.png)

![Screen Shot 2022-05-08 at 7 59 09 PM](https://user-images.githubusercontent.com/70282901/167321230-dae6f48a-7d85-4c4c-9890-0fa0ea246d57.png)

![Screen Shot 2022-05-07 at 10 04 13 PM](https://user-images.githubusercontent.com/70282901/167278706-d0b55ef4-61c5-46ce-a024-3b1e26245538.png)

![Screen Shot 2022-05-07 at 7 33 54 PM](https://user-images.githubusercontent.com/70282901/167275356-b784987d-ebb8-4b42-962e-de595eef7ac2.png)


### Deliverables:
- Final Code file: https://github.com/laarkell/MOONlight/blob/main/moonrn.py
- Similar circuit diagram (but with a 16x16 and 4 shift-registers:https://peppe8o.com/wp-content/uploads/2021/05/Raspberry-PI-8x8-led-matrix-wiring-diagram.jpg 
- Proposal: https://docs.google.com/presentation/d/1EIneGAy3JiBcfAgK7P5TFMXoqEmvOhoRnrpqi6fBKRQ/edit#slide=id.gf39c443cad_0_44
