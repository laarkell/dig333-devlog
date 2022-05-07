## Final Project: Utility / No Utility

### Creator Statement:



The MOONlight is and LED matrix that shows when the moon is in the sky and what phase it is. It is completely handmade and only requires power through a wall outlet. It is targeted towards astronomers and moon lovers. It can be used to alert someone that it is a full moon and that they should go out and look. It is great when it is a cloudy day and the moon can’t be seen, or for a photographer that loves to capture the moon. The MOONlight can also be displayed as an art piece because of its aesthetic design. While there are some uses for this device, in reality you can just go outside and look for the moon or go online with a simple google search. The device also does not perform a task, solve a problem or make life easier. I have a personal interest in space and the moon which is where the idea for this device came from. When I was browsing for devices to make, I saw an LED matrix, and from there I thought about interesting things to display on it. On the literal side, the MOONlight is a device that lights up when the moon has risen and turns off when the moon has set depending on your location. Currently its location is set to Davidson, NC. When it lights up, it displays the correct phase that the moon is in at that time. 


The materials I used included a large sab of orange acrylic, 256 white LEDs, 4 shift registers, lots of wires, and a Raspberry Pi 4. The LEDs were soldered into a hand-made 16 by 16 LED matrix.  The matrix is controlled by a large python file that uses known constants, and physics equations to calculate the current phase, and the rise and set times for the moon at a certain location. I then designed matrices for each phase and setup CRON TAB to update the device very 5 minutes. The Raspberry Pi connects to WIFI and it gets power from a wall outlet. Originally, I planned to pull the moon information (rise, set, phase) from an API. However, I had trouble pulling it from the internet and I realized I could calculate the information from equations and constants. I was able to do so with loads of help from online examples and files. The two areas that took up the most time in my project was the building and the coding. The building took hours on end and including drilling 512 holes by hand and soldering 512 joints. The other area, the coding, involved creating 3 separate files, one for rise and set, one for phase, and one for controlling the matrix. I then had to combine them all and add in CRON TAB in order to have it running continuously. 


I am very happy with the outcome of my final project. Appearance wise, it is exactly what I had envisioned and planned, and I am glad I chose to hand-make it. The only things I wish I was able to fix were the few LEDs that were out. I removed them and resoldered them, but they didn’t seem to want to turn on. If I were to continue improving it, I would add a way for the user to change the location and I would add a way to display more information. For example, a countdown to when the moon sets.




![Screen Shot 2022-05-07 at 7 33 54 PM](https://user-images.githubusercontent.com/70282901/167275356-b784987d-ebb8-4b42-962e-de595eef7ac2.png)


- Code: https://github.com/laarkell/MOONlight
- Proposal: https://docs.google.com/presentation/d/1EIneGAy3JiBcfAgK7P5TFMXoqEmvOhoRnrpqi6fBKRQ/edit#slide=id.gf39c443cad_0_44
