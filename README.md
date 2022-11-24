# Ecology Sim
## Overview
Ecology Sim, as the name suggests, is a simulator designed to explore various ecological and biological concepts, including: predator/prey dynamics, natural selection, the flow of energy through the system, and the nested hierarchical organization of systems involved.

The subject of the simulation is a small section of natural environment in a temperate savanna biome including sparse trees, herbaceous plant and shrub ground cover, water sources, and a few small populations of animals. The design of the simulation is focused on the "complex entities" (herbaceous plants, shrubs, and animals, collectively) whose dynamics are deemed interesting enough to study and are on comparable timescales to each other. These complex entities, beyond just interacting with each other, are formed in turn by the interaction of the subsystems which make them up.

### Simulation Categorization
The simulation is:
- Stochastic: The behavior of simulated creatures depends partially on randomly generated numbers.
- Dynamic: The target of study is the way in which the simulated environment and creatures therein change over time.
- Temporally Continuous: Updates occur in fixed time steps.
- Spatially Discrete: Objects in the simulation are placed in the cells of a regular grid.

### Visualization
The state of the simulation is illustrated visually by simple 2D graphics that abstract away all of the internal entity dynamics to focus on entity interactions. The dynamic states of the entities' subsystem components are recorded and displayed graphically when prompted by the user.

## Technologies Used
This project is written in C++ using Qt 6.4.1 (the most recent version as of the creation of this repo).

As the requirements for building develop this section will be updated to include more relevant information.

## Project Goals
### C++ and Qt Proficiency
Out of the programming languages I've learned over the years I'm strongest in C++. With this project I hope to further develop my skill with the language and its more nuanced aspects. More complex projects benefit more from the affordances of visualization and graphical interfaces. Qt is a mature and well documented framework that fits in nicely with this goal.

### Large Project Management
I've worked with large projects before in an academic context but not yet had a chance to fully implement a personal project at this scale. With my engineering degree work, the requirements were always external and the methodology already defined. With full control of this project's requirements and methodology I hope to test my design skills in a more open-ended context.

### Subsystem Design and Integration
One significant design challenge presented by this project is the specification, implementation, and especially integration of the many subsystems comprising each agent in the simulation. These issues are not unique to the design of simulations, but can come from any problem domain requiring a complex solution. Thus I hope the skills I gain in completing this project will transfer well to future projects and to my professional life.

### ALife and Simulation Technique Exploration
I've always been fascinated by the technical aspects of simulation design and the study of ALife. This project gives me a chance to get hands-on experience in both of these areas.
