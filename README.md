# Verilog-A Frequency Divider BIST circuit
[![DOI](https://zenodo.org/badge/341025882.svg)](https://zenodo.org/badge/latestdoi/341025882)

This Verilog-A cell is aimed to speed up the simulations of a frequency divider. Due to the similar nature of the circuits, it is also capable to simulate a mixer.
It measures the most important characteristic of a frequency divider: the sensitivity curve.
The main motivation behind this work was to overcome the cumbersome and sluggish post-processing of a huge number of parametric simulation results.
Two csv files will be created, whose name can be configured as instance parameters.
One of the them will contain the only the sensitivity curve (frequency and the corresponding minimal required amplitude value), while the other includes additional informations, such as output power, average core and buffer power consumption.
No signal has to be saved in the simulations, which saves storage area.

Though the circuit has been intended to be used for our given circuit, it has been written in a way to make it general purpose.
If you have improvement ideas, or you have added extra features, please let me know.
