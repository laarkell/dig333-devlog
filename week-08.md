# Week 08

### Monk Chapter 11 - Motors:
- servo motor ~ 5V, high precision
  - gpiozero import App, slider 
- PWM = pulse width moderation
- DC motor = control speed, power, rotate continuously
  -  gpiozero import motor 
- stepper motor, rotates continuously and you can accurately position them
  -  gpiozero import motor 
  - unipolar and bipolar


### Monk Chapter 12 - Digital Inputs:
- push switch ~ GPIO pin
  - import button
  - you can turn on/off
  - you can toggle something
- toggle or slide switch allows you to see what its set on by looking at it, but often fragile
- debouncing a button is important so that it doesnt jump back and forth
  - use bounce_time to set debouncing of switch or button
- keypad and mouse~ hat you can add and control
- GPS ~ hat you can add, used GPIOs

### Links for Project:

[Final Project Proposal Slides](https://docs.google.com/presentation/d/1EIneGAy3JiBcfAgK7P5TFMXoqEmvOhoRnrpqi6fBKRQ/edit?usp=sharing)


[Tutorial slides](https://docs.google.com/presentation/d/1DkuRocFw_YWWC5KsnEIsCsaxf4aZFNY1BP93Qqrq1GI/edit?usp=sharing)

### Milestone 1 Update 
#### Research and find APIs needed to get all information that needs to be passed to the LED matrix:
- created new github repo
- attempted to get code in python to run to get information needed on moon
  - moon info needed: phase, rise, set, date
- link to API: https://dev.timeanddate.com/docs/astro/
- made an account on the site, free trial 
  - access key: sdV4VfLW1J
  - secret key: urvp9Ka73g6q7BZ0Fd4U
- link to GitHub: https://github.com/laarkell/MOONlight/blob/main/getapi.py

![Screen Shot 2022-04-05 at 9 16 55 PM](https://user-images.githubusercontent.com/70282901/161876370-0e154702-c661-4f84-89fc-a0d42d24639b.png)


#### Left to do for this milestone:
- need to locate moon information from the given python file
- print information and run in terminal
- 
