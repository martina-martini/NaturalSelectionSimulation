# NaturalSelectionSimulation
Simulation of natural selection stochastic processes and survival models based on real data found online

## Assignment 
Consider a simulator for natural selection with the following simplified simulation model:
 - All the individuals belong to S different species Let s be the index of each species, s=1...S
 - The initial population of s is equal to P(s) The reproduction rate for each individual is lambda The theoretical lifetime  LF(k) of individual k whose parent is d(k) is distributed according to the following distribution: LF(k)= uniform(LF(d(k),LF(d(k)*(1+alpha)) with probability prob_improve uniform(0,LF(d(k)) with probability 1-prob_improve, where prob_improve is the probability of improvement for a generation and alpha is the improvement factor (≥ 0). ù
 - The individuals move randomly in a given region and when individuals of different species meet, they may fight and may not survive. In such a case, the actual lifetime of a individual may be lower than its theoretical lifetime.
 - A died individual cannot reproduce.

🔗 PDF report attached
