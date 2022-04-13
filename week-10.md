
# Week 00


## Milestone 2: Determine how to control LED matrix and what input code is needed

#### Plan:
- write the 8 structures as 2D arrays with X and O s
- comma delitted with multi lines
- helpful link: https://docs.arduino.cc/built-in-examples/display/RowColumnScanning
- ![moon_phases_uppergraphic-scaled](https://user-images.githubusercontent.com/70282901/163080264-dbae0d84-adf0-4f9a-bd00-5c15725f8bac.jpg)

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
