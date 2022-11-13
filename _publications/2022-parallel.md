---
title: "Parallel Sensor-Space Lattice Planner for Real-Time Obstacle Avoidance"
collection: publications
permalink: /publication/2022-parallel
excerpt: 'This paper presents a parallel motion planner for mobile robots and autonomous vehicles based on lattices created in the sensor space of planar range finders.'
date: 2022-01-01
venue: 'Sensors'
paperurl: 'http://bmrocamora.github.io/files/Parallel_Sensor-Space_Lattice_Planner_for_Real-Time_Obstacle_Avoidance.pdf'
citation: 'Martinez Rocamora, B., Jr.; Pereira, G.A.S. Parallel Sensor-Space Lattice Planner for Real-Time Obstacle Avoidance. Sensors 2022, 22, 4770. https://doi.org/10.3390/s22134770.'
---
Abstract:
This paper presents a parallel motion planner for mobile robots and autonomous vehicles based on lattices created in the sensor space of planar range finders. The planner is able to compute paths in a few milliseconds, thus allowing obstacle avoidance in real time. The proposed sensor-space lattice (SSLAT) motion planner uses a lattice to tessellate the area covered by the sensor and to rapidly compute collision-free paths in the robot surroundings by optimizing a cost function. The cost function guides the vehicle to follow a vector field, which encodes the desired vehicle path. We evaluated our method in challenging cluttered static environments, such as warehouses and forests, and in the presence of moving obstacles, both in simulations and real experiments. In these experiments, we show that our algorithm performs collision checking and path planning faster than baseline methods. Since the method can have sequential or parallel implementations, we also compare the two versions of SSLAT and show that the run time for its parallel implementation, which is independent of the number and shape of the obstacles found in the environment, provides a speedup greater than 25.

[Download paper here](http://bmrocamora.github.io/files/Parallel_Sensor-Space_Lattice_Planner_for_Real-Time_Obstacle_Avoidance.pdf)

Recommended citation: Martinez Rocamora, B., Jr.; Pereira, G.A.S. Parallel Sensor-Space Lattice Planner for Real-Time Obstacle Avoidance. Sensors 2022, 22, 4770. https://doi.org/10.3390/s22134770.
