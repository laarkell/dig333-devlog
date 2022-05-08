## Milestone 4: Constructing LED matrix, compiling code, and last minute things!

### Plan:
- construction of matrix
- matrix testing using battery, resistor circuit
- edit code to print out proper information to matrix
- compile code files to one
- test run and work out errors!

### Progress Updates:
![Screen Shot 2022-05-04 at 1 41 10 PM](https://user-images.githubusercontent.com/70282901/166747416-d88b85b7-23bc-4a33-b9f6-bc9c79c2e055.png)

![Screen Shot 2022-05-04 at 1 41 16 PM](https://user-images.githubusercontent.com/70282901/166747428-5ee73e59-b904-4f17-9769-d85d0379aa78.png)

https://user-images.githubusercontent.com/70282901/167204323-94bc5eb6-4d26-418d-8ba7-7d3ea8674e64.mov

![Screen Shot 2022-05-07 at 7 33 54 PM](https://user-images.githubusercontent.com/70282901/167275337-28babdce-1fcf-4147-9719-cb36cf0213be.png)

![Screen Shot 2022-05-07 at 7 33 45 PM](https://user-images.githubusercontent.com/70282901/167275339-a4eee124-7069-4c0f-8171-bdf762fc3a0e.png)


### Coding Plan:
- shift register: 1 input, 8 outputs
- use 1 GPIO pin as output from code, send this into the input for first shift register
- into GPIO send row 0 [0] then row i+1 [i+1] until i = 7
- Code Link: https://github.com/laarkell/MOONlight/blob/main/moonlight.py
- use CRON TAB

![Screen Shot 2022-05-04 at 3 48 29 PM](https://user-images.githubusercontent.com/70282901/166814535-600c1153-6246-4580-b779-3dececbbb4c7.png)

![Screen Shot 2022-05-04 at 3 50 56 PM](https://user-images.githubusercontent.com/70282901/166814898-e1404702-01f0-49c4-910b-89c5a460df38.png)

![download](https://user-images.githubusercontent.com/70282901/166994284-76d8ee7b-d01e-4d9e-8a54-a884eb46108f.jpg)

![Screen Shot 2022-05-08 at 6 38 52 PM](https://user-images.githubusercontent.com/70282901/167320840-30158280-5aff-4f31-86ea-b1aa1ab8d9eb.png)


### Construction reminders:
- check LEDs before connecting!
- need 220 ohm resistor inbetween all row outputs and matrix
- common cathode design!
- 5V input 
- bottom wires are short which is cathode
- top wiresare long and called anode
- 

### Useful links:
- ** https://peppe8o.com/use-a-8x8-led-matrix-with-raspberry-pi-and-python/ **
- https://www.youtube.com/watch?v=Degt4HUzWXY
- 
