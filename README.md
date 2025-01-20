# TBL-Duralink

This Arduino/C++ code was written for the failsafe system on [TBL Durables line striping machines](https://www.tbldurables.com).

Macroscopically, the system reads pressures from two sensors, one for the "catalyst" and one for the "durables" fluids on board the machine. It then assess whether or not the machine is a in an abnormal or dangerous state based on a series of heuristics.

A short demo video of the system can be found [on Google Drive](https://drive.google.com/file/d/1q6E0JCHUhbnugHH2Au4M56ltq75N8Avo/view?usp=sharing). This sofware was written entirely by myself.