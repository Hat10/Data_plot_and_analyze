# PuttiPuttiPlott
Plotting and analyzing data. Under construction.

PuttiPuttiPlott.py takes in 1 or more datafiles (.txt, .csv etc) and graphs it. Additionally, it can also find and mark peaks and valleys.
However, the accuracy for finding peaks/valleys is heavily dependent on noice level. This is something I'm experimenting with and trying to find a good algorithm for.
Working on: Menu (low priority), measuring width, FWHM etc. of holes/valleys/peaks that can futher be analyzed with utilities.py

Utilities.py takes in 1 or more datafiles (.txt, .csv etc) and and returns a text file (and print) with Mean, max, min, STD, RSD, RMS values.
Menu function is under construction. Takes in datafile with or without header, where data is in columns below header.
Working on: data can either be organized in columns or rows. This is low priority
