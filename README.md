Open ended evolution(OEE) is a term coined to generally describe how evolutionary processes like biological evolution seem to never end, constantly displaying increases in complexity, novelty, and diversity.

OEE emerged from early computer simulation experiments which were working with evolution and ecological dynamics. A common occurrence was that even if the author's were intentionally trying to make the simulation continuously evolve, each simulation would reach a state of stasis where nothing discernibly novel would evolve.

![image](https://raw.githubusercontent.com/nathan-cain15/ap-research-proj/main/Karl-Sims.jpg)

Picture from Karl Sim's Evolved Virtual Creatures (1994)

Research into OEE has produced theories and frameworks to hypothesize how an open-ended simulation can be built. Although not the only area of OEE research, it is promising as it brings progress to building an OEE simulation, however other areas are important like coming up with better definitions and tools to identify OEE.

For my research, I mainly built off of the works of Tim Taylor and Wolfgang Banzhaf, who laid the groundworks for how an OEE system can be built. They discuss avenues that can be taken to build such a system, and what elements it would contain. The element I looked at was building a simulation in a physical environment with evolving entities that would directly interact with their environment to evolve. A criticism of past simulations were that they are simply not complex enough, and so therefore can not produce complex results.

The simulation was coded in Unity due to its powerful physics engine. For the design, the simulation is populated by "entities". For the purpose of this research, they were made up of two bones connected by a joint, and a muscle. The environment acts like a fluid and is populated by food squares which replenish over time. The food provides the entities energy which is used for movement and reproduction. However, the entities use two different storages for energy, one used for reproduction and the other for movement. At the start of an entity's life, it is given a set amount of energy which is used for movement. This means that an entity's lifespan is predetermined. However for reproduction, each food consumed is added to it's reproduction energy storage. Once it reaches an amount calculated using the structural make up of the entity, a copy entity is produced with some mutations. Mutatable elements include time between muscle contraction, the force of muscle contractions, length of bones, or angle between bones. 

For the time period I had to write the paper, only initial tests could be ran to get an understanding of how the simulation behaved. Data was collected based on population statistics and the evolveabe properties. Some interesting dynamics were seen which have not been seen in prior simulations, like boom and bust cycles. The trends in the graphs show that evolution is occurring, however the population will reach a state of stasis once there is not enough room for the population to grow.

Although the results may not be very interesting, if built off of, this simulation may show promising results. An example change could be allowing for the evolution of new structural components. From this, new strategies for moving through the environment could develop.


![gif](https://raw.githubusercontent.com/nathan-cain15/ap-research-proj/main/simulationgif.gif)
Results from Experiments

![image](https://raw.githubusercontent.com/nathan-cain15/ap-research-proj/main/averagebonelengthexperiment1run3.png)
![image](https://raw.githubusercontent.com/nathan-cain15/ap-research-proj/main/averagetimescaleexperiment1run3.png)
![image](https://raw.githubusercontent.com/nathan-cain15/ap-research-proj/main/totalentitiesexperiment1run3.png)
![image](https://raw.githubusercontent.com/nathan-cain15/ap-research-proj//main/totalfoodexperiment1run3.png)
