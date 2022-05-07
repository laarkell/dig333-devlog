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


![IMG_9473](https://user-images.githubusercontent.com/70282901/167275302-ccd504d6-1ab9-4797-a420-b7fff09db0b6.jpg)

![IMG_9472](https://user-images.githubusercontent.com/70282901/167275304-e900ab71-91b0-42e2-acb4-765c9cbb1b6a.jpg)

### Coding Plan:
- shift register: 1 input, 8 outputs
- use 1 GPIO pin as output from code, send this into the input for first shift register
- into GPIO send row 0 [0] then row i+1 [i+1] until i = 7
- Code Link: https://github.com/laarkell/MOONlight/blob/main/moonlight.py

![Screen Shot 2022-05-04 at 3 48 29 PM](https://user-images.githubusercontent.com/70282901/166814535-600c1153-6246-4580-b779-3dececbbb4c7.png)

![Screen Shot 2022-05-04 at 3 50 56 PM](https://user-images.githubusercontent.com/70282901/166814898-e1404702-01f0-49c4-910b-89c5a460df38.png)

![download](https://user-images.githubusercontent.com/70282901/166994284-76d8ee7b-d01e-4d9e-8a54-a884eb46108f.jpg)


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
