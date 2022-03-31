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
