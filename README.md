Ap research is a course where each student choices a topic and spends the entire year researching said topic, identifying a gap, and performing research to address the gap.

Open ended evolution(OEE) is a term coined to generally describe how evolutionary processes like biological evolution seem to never end, constantly displaying increases in complexity, novelty, and diversity.

This study came from early computer simulation experiments which were working with evolution and ecological dynamics. A common occurrence was that even if the author's were intentionally trying to make the simulation continuously evolve, each simulation would reach a state of stasis where nothing discernibly novel would evolve.
![image](https://github.com/nathan-cain15/ap-research-proj/assets/62317727/e7f0ef67-8366-411b-a7b6-480fba67860f)

Research into OEE has produced theories and frameworks to hypothesize how an open-ended simulation can be built. Although not the only area of OEE research, it is promising as it brings progress to building an OEE simulation, however other areas are important like coming up with better definitions and tools to identify OEE.

For my research, I mainly built off of the works of Tim Taylor and Wolfgang Banzhaf, who laid the groundworks for how an OEE system can be built. They discuss avenues that can be taken to build such a system, and what elements it would contain. The element I looked at was building a simulation in a physical environment with evolving entities that would directly interact with their environment to evolve. A criticism of past simulations were that they are simply not complex enough, and so therefore can not produce complex results.

The simulation was coded in Unity due to its powerful physics engine. For the design, it is populated by things I call entities. For the purpose of this research, they were made up of two bones connected by a joint, and a muscle. The environment acts like a fluid and is populated by food squares which replenish over time. The food provides the entities energy which is used for movement and reproduction. However the entities use two different storages for energy, one used for reproduction and the other for movement. At the start of an entities' lifetime it is given a set amount of energy which is used for movement, this means that an entities' lifespan is predetermined. However for reproduction, each food provides energy which once it reaches a predetermined amount, calculated using the make up of the entity, a copy is produced with some mutations, which could either be the time between muscle contractions, the force to which the muscle contracts, or the length and angle of the bones.

For the time period I had to right the paper, only initial tests could be ran to get an understanding of how the simulation behaved. Data was collected based on population statistics and the evolve abe properties. Some interesting dynamics were seen which have not been seen in prior simulations, like boom and bust cycles. The trends in the graphs show that evolution is occurring, however the population will reach a state of stasis once there is not enough room for the population to grow.
Although the results may not be very interesting, if built off of, this simulation may show promising results. When designing the initial simulation, 3 separate components for the structure of entities were chosen so that the structure could evolve.
![image](https://github.com/nathan-cain15/ap-research-proj/assets/62317727/3c118a5e-f1aa-4136-bab6-993580ea3080)

![totalentitiesexperiment1run3](https://github.com/nathan-cain15/ap-research-proj/assets/62317727/37717c69-0e17-45e6-aaf8-569c9af8d738)
![averagebonelengthexperiment1run3](https://github.com/nathan-cain15/ap-research-proj/assets/62317727/c9d9496e-0f4e-42b2-ae1f-62db60676f69)
![averagetimescaleexperiment1run3](https://github.com/nathan-cain15/ap-research-proj/assets/62317727/3b096757-4787-4f97-944d-105b54af48bb)
![averagemuscleforceexperiment1run3](https://github.com/nathan-cain15/ap-research-proj/assets/62317727/0ca48e2d-ceea-4c73-b05b-a6e201d20490)
