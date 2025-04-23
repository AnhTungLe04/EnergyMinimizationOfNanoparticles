This project addresses the global optimization problem of determining the n-nanoparticle cluster configuration that yields the minimum potential energy (also as known as Lennard-Jones cluster global minima), using numerical conjugate gradient method. It covers 4 tasks in total.

*Task 1:* Implement all functions for initalizing random positions, calculating potential energy and interactive forces, as well as line search and conjugate gradient methods. 

*Task 2:* Do a 1000-time simulation by executing the code 1000 times for each number of particles of the cluster to yield the minimum potential energies (U_min) and store their numbers of Conjugate Gradient Step (CGSteps) and trajectories. Plot U_{min} and CGSteps required to reach it as a function of N, saved in task2.png.

*Task 3*: For this minimum case at each N, plot the evolution of potential energy as a function of CGStesps, saved in task3.png, and visualize the particles.Visualizations of how the particles of a N-particle cluster relocate to approach the state of minimum potential energy is saved in 'Trjectories' director, which can be observed the the command line: $ ase gui Trajectories/nano{N}.traj

*Task 4*: The macroscopic scaling estimate for nanoparticle energy is given by U_macro(N) = a + bN^(2/3) + cN. Fit the minimum potential energy data to this formula using least squares minimization and find the constants a, b, c. Finally plot the U_min - U_macro as a function of N, saved in task4.png.