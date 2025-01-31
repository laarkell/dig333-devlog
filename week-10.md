
# Week 10


## Milestone 2: Determine how to control LED matrix and what input code is needed

#### Plan:
- [x] write the 8 structures with X and O s
  - comma delitted with multi lines
- [x] convert the structures in 2D arrays
- [x] write code that prints said array depending on an input (in python)
- [x] convert code to send high for every X and send low for every 0

- code link: https://github.com/laarkell/MOONlight/blob/main/phaseprint.py

- helpful link: https://docs.arduino.cc/built-in-examples/display/RowColumnScanning
- use diagram of LEDs seen below
- would it be useful to create a demo matrix to test out?
  - INSTEAD write code that prints out the correct X,0s matrix in order to test if its working

![moon_phases_uppergraphic-scaled](https://user-images.githubusercontent.com/70282901/163080264-dbae0d84-adf0-4f9a-bd00-5c15725f8bac.jpg)

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
