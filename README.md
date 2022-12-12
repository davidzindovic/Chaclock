# Ambiental-Clock
A LED based clock that runs on the ESP8266 microcontroller. 
The 12 numbers light up depending on the time (approximation of 5 min), while the main 9 segment "picture" includes a color fade depending on the time of day.
The code includes a sleep mode , which resets the uC entirely in order to prevent the timer overflow. 
(in order to prevent any visible change upon reset - since it will most likely happen during the night)
The clock fades on sometime during the morning and fades off at a certain point during nightime.

The colors and silhuette are meant to simbolize a meditating person, relating to chakras - hence the name Chaclock.
