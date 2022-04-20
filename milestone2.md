## Milestone 2: Determine how to control LED matrix and what input code is needed:

#### Plan:
- in order to visulaize the arrays and to print out the phases without having the actual LED array, I will be creating 2D arrays with 1s and 0s to demonstrate the phases
- this will be like a demo-matrix to test out if the code works
- then ill convert these arrays to the LED matrix array in order to turn on the proper LEDs


- [x] write the 8 structures with X and O s
  - comma delitted with multi lines
- [x] convert the structures in 2D arrays
- [x] write code that prints said array depending on an input (in python)
- [x] convert code to send high (1) for every X and send low (0) for every 0

- **2D array code link: https://github.com/laarkell/MOONlight/blob/main/phaseprint.py**

### Notes:
- decided to change to 16x16 to make it bigger
  - need to remake 2D arrays for phases 
- use ASCII generator and import images of moon to determine which are high and low, good way to cut time
- export and convert informtaion to 2D array
- use diagram of LEDs seen below

![Screen Shot 2022-04-18 at 9 36 41 PM](https://user-images.githubusercontent.com/70282901/163903602-b2f1a18c-28b6-49b5-8bcf-70d9adb142c4.png)

![moon_phases_uppergraphic-scaled](https://user-images.githubusercontent.com/70282901/163080264-dbae0d84-adf0-4f9a-bd00-5c15725f8bac.jpg)

### Using ASCII to generate phases instead of manualy drawing and entering them:
- https://www.dcode.fr/binary-image
- ![Screen Shot 2022-04-20 at 3 45 42 PM](https://user-images.githubusercontent.com/70282901/164310692-54f52892-bd34-4710-b767-09d2668127a7.png)
- not exactly what I want, but close!


## OLD matrices used for phases:

#### New Moon:
##### 0 0 0 0 0 0 0 0
##### 0 0 0 0 0 0 0 0
##### 0 0 0 0 0 0 0 0
##### 0 0 0 0 0 0 0 0
##### 0 0 0 0 0 0 0 0
##### 0 0 0 0 0 0 0 0
##### 0 0 0 0 0 0 0 0
##### 0 0 0 0 0 0 0 0

#### Waxing Crescent:
##### X 0 0 0 0 0 0 0
##### 0 X X 0 0 0 0 0
##### 0 0 0 X X X 0 0
##### 0 0 0 0 X X X X
##### 0 0 0 X X X 0 0
##### 0 0 X X 0 0 0 0
##### 0 X X 0 0 0 0 0
##### X 0 0 0 0 0 0 0

#### First Quarter:
##### X X 0 0 0 0 0 0
##### 0 X X X X 0 0 0
##### 0 0 0 X X X X 0
##### 0 0 0 0 X X X X
##### 0 0 0 X X X X 0
##### 0 0 X X X X 0 0
##### 0 X X X X 0 0 0
##### X X 0 0 0 0 0 0

#### Waxing Gibbous:
##### X X X 0 0 0 0 0
##### 0 X X X X X 0 0
##### 0 0 0 X X X X 0
##### 0 0 0 X X X X X
##### 0 0 0 X X X X 0
##### 0 0 X X X X 0 0
##### 0 X X X X 0 0 0
##### X X X 0 0 0 0 0

#### Full Moon:
##### 0 0 0 X X 0 0 0
##### 0 0 X X X X 0 0
##### 0 X X X X X X 0
##### X X X X X X X X
##### 0 X X X X X X 0
##### 0 0 X X X X 0 0
##### 0 0 X X X X 0 0
##### 0 0 0 X X 0 0 0

#### Waning Gibbous:
##### 0 0 0 0 0 X X X
##### 0 0 0 X X X X 0
##### 0 X X X X X 0 0
##### X X X X X 0 0 0
##### 0 X X X X X 0 0
##### 0 0 0 X X X 0 0
##### 0 0 0 0 X X X 0
##### 0 0 0 0 0 X X X

#### Last Quarter:
##### 0 0 0 0 0 0 X X
##### 0 0 0 X X X X 0
##### 0 0 X X X 0 0 0
##### X X X X 0 0 0 0
##### 0 0 X X X 0 0 0
##### 0 0 0 X X X 0 0
##### 0 0 0 0 X X X 0
##### 0 0 0 0 0 0 X X

#### Waning Crescent:
##### 0 0 0 0 0 0 0 X
##### 0 0 0 0 X X 0 0
##### 0 0 X X X 0 0 0
##### X X X X 0 0 0 0
##### 0 0 X X X 0 0 0
##### 0 0 0 X X X 0 0
##### 0 0 0 0 0 X X 0
##### 0 0 0 0 0 0 0 X

### Useful links:
- https://docs.arduino.cc/built-in-examples/display/RowColumnScanning

### Next milestones:
- combine all code to take in informaiton and output correct phase 2D array
- make creative decisions on matix and order parts
- construct matrix
