# F1 Racing Line Calculator

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/jerryvarghese1/F1_racinglines/main?filepath=Racing_Line_Calculator.ipynb)

Calculates racing lines for various F1 Tracks - launch in binder to see it in action!

Circuit JSON files acquired from https://github.com/bacinger/f1-circuits
- To check file names and track lengths, check the link above

Racing Line calculator acquired from https://github.com/cdthompson/deepracer-k1999-race-lines

## Use of Program
The main parameters to enter are listed at the top. Modify 'iters' for a more accurate racing line: the HIGHER 'iters' is, the longer the program will take to run, but the more accurate the racing line will be. Modify 'interp_value' for a more accurate racing line: LOWER values of 'interp_val' result in HIGHER resolution of the racing line (less discrete). Modify 'filename' to pick the track you want to analyze. Input the actual track length so that Shapely can create the correct external track limits. 

Hope you enjoy!
