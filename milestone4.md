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

### Coding Plan:
- shift register: 1 input, 8 outputs
- use 1 GPIO pin as output from code, send this into the input for first shift register
- into GPIO send row 0 [0] then row i+1 [i+1] until i = 7

![Screen Shot 2022-05-04 at 3 48 29 PM](https://user-images.githubusercontent.com/70282901/166814535-600c1153-6246-4580-b779-3dececbbb4c7.png)

![Screen Shot 2022-05-04 at 3 50 56 PM](https://user-images.githubusercontent.com/70282901/166814898-e1404702-01f0-49c4-910b-89c5a460df38.png)

### Construction reminders:
- check LEDs before connecting!
- need 220 ohm resistor inbetween all row outputs and matrix
- common cathode design!
- 5V input 

### Useful links:
- ** https://peppe8o.com/use-a-8x8-led-matrix-with-raspberry-pi-and-python/ **
- https://www.youtube.com/watch?v=Degt4HUzWXY
- 
