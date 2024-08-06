I have simulated the 2D Ising model in python using the metropolis algorithm.<br/><br/>
In the animations, you can see that when the lattice is initially 50% negative spin atoms, and BJ=0.7 (relatively low temperature), magnetic domains are formed and the average spin approaches 0.<br/><br/>
When the lattice is initially 75% negative spin atoms, and BJ = 0.7, the average spin approaches -1. This means that the spins become oriented in the same direction.<br/><br/>
When the lattice is initially 75% negative spin atoms, but BJ = 0.2 (high temperature), the atoms have enough energy from the heat bath and do not need to orientate themselves in one direction. Therefore the average spin approaches 0.<br/><br/>
This temperature dependent behaviour can be seen in the 'Equilibrium Spin and Energy Plot' image.<br/><br/>
In the 'Heat Capacity Plot', a phase change can be seen around (k/J)T = 2.
