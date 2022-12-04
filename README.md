# Arduino-Hero-Morse-Code-Project
This project was a side project and challenge to myself. I purchased a 30 days lost in space adventure kit by Inventr.io. I am using it to learn how to program as well
as learn something new like circuits. 

This Morse Code side project was exciting for me. I connected a LED to the bread board and program the LED to flash and hold light to symbolize dots(di) and dashes(dah) 
in morse code. The code that was written is attached to this repo.



For this project we are going to write code to translate morse code to a phrase. Using the Hero Board and the Arduino IDE, write commands to spell out ‘Hello World” in
Morse Code using the LED on the bread board provided. 

1)	Determine the patterns we need for the translation
      1 dot = 1 unit, Dash = 3 units, Space between letters is 3 units, Space between words = 7 units
 
2)	Formulate how the code will be written in Arduino.

    What will be the starting point?  power off led for 5 secs (5000ms)
      H = 1 sec, 1 sec, 1 sec, 1 sec
      E = 1 sec
      L = 1 sec, 3 sec, 1 sec, 1 sec
      L = 1 sec, 3 sec, 1 sec, 1 sec
      O = 3 sec, 3 sec, 3 sec
      SPACE 7 units = 1 sec, 1 sec, 1 sec, 1 sec, 1 sec, 1 sec, 1 sec
      A = 1 sec, 3 sec
      J = 1 sec, 3 sec, 3 sec, 3 sec

3)	Write the code!!
