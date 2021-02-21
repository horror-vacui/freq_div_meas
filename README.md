# Verilog-A Frequency Divider BIST circuit

This Verilog-A cell is aimed to speed up the simulations of a frequency divider. Due to the similar nature of the circuits, it is also capable to simulate a mixer.
It measures the most important characteristic of a frequency divider: the sensitivity curve.
The main motivation behind this work was to overcome the cumbersome and sluggish post-processing of a huge number of parametric simulation results.
Two csv files will be created, whose name can be configured as instance paramters.
One of the them will contain the only the sensitivity curve (frequency and the corresponding minimal required amplitude value), while the other includes additional informations, such as output pwoer, average core and buffer power consumption.
No signal has to be saved in the simulations, which saves storage area.

Though the circuit has been intended to be used for our given circuit, it has been written in a way to make it general purpose.
If you have inprovement ideas, or you have added extra features, please let me know.