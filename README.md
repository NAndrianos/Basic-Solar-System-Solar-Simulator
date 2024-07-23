# Basic Solar System Solar Simulator
In this project, we simulate the interaction of the planets in a solar system. In addition to the Sun (that we always place at the centre of our simulated universe),
there could be up to 9 of the other planets in the order they appear relative to their distance to the Sun.  
If we choose 1, then we will consider Mercury only (in addition to the Sun, of course). 
If we choose 3, then we are only considering Mercury, Venus, and the Earth in our simulation.  
Here we will be nice and we will give Pluto back its designation as a planet (It was discovered in 1930 as the 9th planet in our solar system, 
but in 2006 it was officially stripped off of its title as a planet and is now considered a dwarf planet).  
Our objective is to simulate and calculate the position and velocity of each planet at any time from a set starting point. 
The updates will be done using a discrete event simulation in which we update the info of each planet at a set simulation time intervals.  
Initially (at simulation time 0), all planets are put on the x axis. When the simulation starts, at each update interval (discrete event of the simulation), 
the program calculates the forces that the Sun and all planets apply to each other and consequentially calculates the new position of each planet (the Sun remains at the centre). 
