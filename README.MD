A Git repository containing the simulations for the rocket trajectory involved 
in the Cambridge University Spaceflight Society's 'Recovery Challenge'.

Simulations are named according to their author:

| Name   | File name     | Comments                                                                                                                  |
|--------|---------------|---------------------------------------------------------------------------------------------------------------------------|
| Andrew | `andrew_sim.py` | Uses LSODA integration (variable order), should be fairly accurate but slower. Plots against time, from 120 km. Assumes no drag over 81 km (zero density).                        |
| Barty  | `barty_sim.py`  | Uses Euler integration, fast, plots against height, from 120 km. Has atmospheric data over 81 km.                                                                     |
| Ben    | `ben_sim.py`    | Uses Euler integration, fast, plots against height, from 120 km. Has atmospheric data over 81 km.                                                                        |
| Ellis  | `ellis_sim.py`  | Uses Euler integration, calculates max acceleration and velocity at 1 km against surface area, fast. Plots against height, from 81 km. |

Just run the files to get the plots. 
Either one should be fine to run. If you need to alter one of the codes choose whichever is cleanest. 
(In my very biased opinion that's `andrew_sim.py`)