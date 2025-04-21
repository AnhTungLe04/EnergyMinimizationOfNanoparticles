This project addresses the global optimization problem of determining the n-nanoparticle cluster configuration that yields the minimum potential energy (also as known as Lennard-Jones cluster global minima), using numerical conjugate gradient method.

So far I have conducted 1000 simulations for each n-number of particles to yield the minimum results of the potential energy with their trajectories after every step of conjugate gradient method. The deviation compared to the published paper is still significant, especially when n increases from 11 particles. I am actively working on a way to optimize the results as well as reduce the computational cost.

A visualization of how the particles of a 13-particle cluster relocate towards the state of minimal potential energy is saved in nano.traj file, which can be observed the the command line: $ ase gui nano.traj
