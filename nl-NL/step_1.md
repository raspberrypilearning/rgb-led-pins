Importeer RGBLED uit de picozero-bibliotheek en stel vervolgens de pinnen in voor een gemeenschappelijke kathode RGB-LED, gebruik de volgende code:

--- code ---
---
language: python filename: line_numbers: false line_number_start: 1
line_highlights:
---
from picozero import RGBLED

rgb = RGBLED(red = 1, green = 2, blue = 3) --- /code ---
