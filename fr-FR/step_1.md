Importe RGBLED à partir de la bibliothèque picozero puis définis les broches pour une LED RGB à cathode commune, en utilisant le code suivant :

--- code ---
---
language: python 
filename: 
line_numbers: false 
line_number_start: 1
line_highlights:
---
from picozero import RGBLED

rgb = RGBLED(red = 1, green = 2, blue = 3)

--- /code ---
