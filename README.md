# QS-Lap-Sim
Custom quasi-static lap time simulation built for University of Virginia's Formula SAE team.

This lap time simulation is useful for establishing full-vehicle trends and design criterion, and is set up for an FSAE EV using an Emrax 228.
My primary motivation for creating this project was to increase my team's and my own understanding of the relative dynamic performance impacts of making different changes to our vehicle. 

To customize with your own vehicle parameters, simply change the values of entries in the vp dict at the beginning of comp_score.py.

You can also sweep across ranges of different parameters and then plot or otherwise post-process the results. An example is included in example_sweep.py. 

The .tir file parser and Magic Formula solvers are designed for use with a Pacjeka 6.2 model. I fit mine using https://github.com/teasit/magic-formula-tyre-tool. I highly recommend this tool, since it automatically parses ASCII/Matlab TTC data. 
