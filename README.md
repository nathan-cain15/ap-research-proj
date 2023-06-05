# ap-research-proj

Ap research is a course where each student choices a topic and spends the entire year researching said topic, identifying a gap, and performing research to address the gap.

Open ended evolution(OEE) is a term coined to generally describe how evolutionary proccesses like biological evolution seem to never end, constantly displaying increases in complexity, novelty, and diversity.

This study came from early computer simulation experiments which were working with evolution and ecological dynmaics. A common occurance was that even if the author's were intentionally trying to make the simulation continously evolve, each simulation would reach a state of stasis where nothing discerably novel would evolve.

Research into OEE has produced theories and frameworks to hypothosize how an open-ended simulation can be built. Althrough not the only area of OEE research, it is promising as it brings progress to building an OEE simulation, however other areas are important like coming up with better definitions and tools to identify OEE.

For my research, I mainly built off of the works of Tim Taylor and Wolfgang Banzhaf, who layed the groundworks for how an OEE system can be built. They discuss mainy avenues that can be taken to build such a system, and what elements it would contain. The element I looked at was building a simulation in a physical environment with evolving entities that would directly interact with their environment to evolve. A critism of past simulations were that they are simply not complex enough, and so therefore can not produce complex results.

The simulation was coded in Unity due to its powerful physics engine. For the design, it is populated by things I call entities. For the purpose of this research, they were made up of two bones connected by a joint, and a muscle. The environment acts like a fluid and is populated by food squares which replenish over time. The food provides the entiites energy which is used for movement and reproduction. However the entities use two different storages for energy, one used for reproudction and the other for movement. At the start of an entities' lifetime it is given a set amount of energy which is used for movement, this means thatan entities' lifespan is predetermined. However for foodreproduction, each food 
