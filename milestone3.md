## Milestone 3: Gathering materials, planing design, creating LED matrix!

### Planning:
- want to use 16x16 LEDS, need to buy 250
- 2D array (decided not to do 3D because the phases wouldn't be as clear)
- LEDs, then a layer of acryllic, then i will solder the wires of the LEDs together and connect them underneath, then another layer of acryllic (see image with drawings below)
- 2 x 17x17cm acryllic sheets, thickness ~ 0.5cm
- 4 x small pieces of acryllic to connect the two slabs
- do I want to convey more information? could use a general LED display in addition to the array
  - potential information to convey: time, date, cloud cover, progress bar of rise/set
  - should the moon in day time look different then night time? 

### Sketches of designing and planning:
![Screen Shot 2022-04-19 at 8 23 29 PM](https://user-images.githubusercontent.com/70282901/164122206-c68a99d2-93f6-48f1-9eee-2c880a8b4bde.png)

![Screen Shot 2022-04-19 at 8 24 48 PM](https://user-images.githubusercontent.com/70282901/164122238-694736f5-4fba-4b36-91d4-1c730efdcca4.png)

![Screen Shot 2022-04-19 at 8 42 44 PM](https://user-images.githubusercontent.com/70282901/164124306-cd694c0c-039f-415d-a257-c768a604167b.png)

![Screen Shot 2022-04-19 at 8 42 50 PM](https://user-images.githubusercontent.com/70282901/164124550-4b2bb5a6-9314-42b7-82aa-74c642da7260.png)

### Wiring and Circuit Design:
- common row cathode arrangement for array
- either 32
-  pin headers or use a shift register to limit the number of inputs
- ![Screen Shot 2022-04-20 at 1 04 26 PM](https://user-images.githubusercontent.com/70282901/164284852-e76cdb62-9827-488d-9f32-48a5ff859862.png)
- https://www.circuitspecialists.com/blog/build-8x8-led-matrix/

### Materials:
- [ ] 256 LEDs
- https://www.amazon.com/CHANZON-PC-59042-Emitting-Assorted-Arduino/dp/B01AUI4VSI/ref=sr_1_5?crid=3BO31A8G4SPG7&keywords=white%2Bled%2Bcircuit&qid=1650334424&sprefix=white%2Bleds%2Bcircuits%2Caps%2C45&sr=8-5&th=1#
- [ ] 2x 17cmx17cm acryllic (where do I buy?) color?
- [ ] 4x small pieces of acryllic to connect the two slabs
- [ ] 16 x 200 ohm resistors
- [ ] 3 x shift register 74HC595
- [x] RPi
- [x] solder materials
- [ ] heat shrink tubes?
- [ ] solderable perf board?

### Steps to create matrix:
1. insert LEDs with all the cathodes and anodes aligning
2. connect all cathodes for each column
3. connect all anodes for each row
4. do not let them touch eachother!
5. connect resistors before anodes and then to power inputs
6. connect cathodes to ground

## Useful links on how to make Matrix:
- https://www.youtube.com/watch?v=evA4Fp1G76E
- https://www.youtube.com/watch?v=evA4Fp1G76E 
- https://www.youtube.com/watch?v=D_QBlFIQk-o 
- https://www.youtube.com/watch?v=PZRUtKYCpms 
- https://www.youtube.com/watch?v=mNqzkDugvSw 
- https://www.instructables.com/DIY-3D-LED-Cube-With-a-Raspberry-Pi/

## Controlling LED Matrix:
- https://www.youtube.com/watch?v=Degt4HUzWXY
- 

### Next milestones:
- Make matrix!
- convert code to print on matrix instead of an array
- run code with matrix
- trial and error
