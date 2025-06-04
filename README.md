# Replacement-number-calculations
You can find here the code for calculation of the replacement number for SIR and SIIS model. 

The numerical simulations are based on stochastic models for population with finite size N. To find the replacement number R, we cound the number of new cases from the _tracked_ individual. Each simulation stops once the tracked individual becomes healed. The averages are then made from many repetitions of the simulation. Although the simulation can be made _continuous_, in a sence to track the state of the population at each moment, for computational efficiency, we chose to look only at the moments of _change_ - when an individual becomes healed, or new infection appears. Thus, we use the embedded Markov chain, instead of the continuous-time one.

The theoretical values are obtained by numerical simulation of the models (SIR and SIIS) to find the sizes of the compartments as a function of time, and numerical calculation of the integrals needed for the replacement number.

More details can be found in the manuscript.
