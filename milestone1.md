## Milestone 1 Update:

### Final project pitch:
- https://docs.google.com/presentation/d/1EIneGAy3JiBcfAgK7P5TFMXoqEmvOhoRnrpqi6fBKRQ/edit#slide=id.gf39c443cad_0_44

### Progress:
- [x] sucessfully created (found) python code that prints the moon's phase name

![Screen Shot 2022-04-06 at 2 33 44 PM](https://user-images.githubusercontent.com/70282901/162044498-3cbb35f0-5bb0-44af-963d-3674bea7d80b.png)

- api code github: https://github.com/laarkell/MOONlight/blob/main/getapi.py
- print phase from calculations code github: https://github.com/laarkell/MOONlight/blob/main/mooncalc.py
- [x] Convert phase information into usable (binary) data that prints a result to confirm results
- conversion to understand what is what:
  - 0: "New Moon", 000
  - 1: "Waxing Crescent", 001
  - 2: "First Quarter", 010
  - 3: "Waxing Gibbous", 011
  - 4: "Full Moon", 100
  - 5: "Waning Gibbous", 101
  - 6: "Last Quarter", 110
  - 7: "Waning Crescent", 111

- [x] locate rise and set information depending on location and add to code
- rise and set code github: https://github.com/laarkell/MOONlight/blob/main/rise-set.py

## Useful links:
- http://www.wdisseny.com/lluna/?lang=en
- https://gist.github.com/miklb/ed145757971096565723
- https://github.com/Broham/suncalcPy

### Next milestones:
- convert this information into 2D arrays to be printed onto LED matrix
- write code that prints correct 2D array for phase
- combine all code to take in informaiton and output correct phase 2D array
- make creative decisions on matix and order parts
- construct matrix
