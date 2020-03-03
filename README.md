# Cooperating-and-adversarial-agents-in-the-Hurricane-Evacuation-Problem
Using MinMax-Tree and Alpha–beta pruning to Simulate a competition between agents for rescue as much as they can 
the simulator run each agent in turn, performing the actions returned by the agents, and update the world accordingly. Additionally, the simulator capable of displaying the world status after each step, with the appropriate state of the agents and their score. The agent individual Each agent program (a function) works as follows. The agent is called by the simulator, together with a set of observations. The agent returns a move to be carried out in the current world state. The agents can observe the entire state of the world.

Types of plays:

-Adversarial (zero sum game): each agent aims to maximize its own individual score minus the opposing agent's score. Here you should implement an "optimal" agent, using mini-max, with alpha-beta pruning.

-A semi-cooperative game: each agent tries to maximize its own individual score. The agent disregards the other agent score, except that ties are broken cooperatively.

-A fully cooperative both agents aim to maximize the sum of individual scores.
