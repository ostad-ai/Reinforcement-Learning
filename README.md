# Reinforcement Learning (RL)
(under construction)
1) **Introduction:** <a href="./RL-introduction.ipynb">Reinforcement Learning: Introduction</a>
<figure>
<img alt="RL: Essential elements" src="./Media/RL-intro.jpg" width="50%">
<figcaption>Figure 1. Reinforcement Learning: Essential elements.</figcaption>
</figure>
<hr>

2) **Markov Decision Process:** A Markov decision process (MDP) is a mathematical framework used for modeling decision-making. We have an *agent* (e.g., the robot) that interacts with an *environment* by taking actions, transitioning between states, and receiving rewards. Here, we review the concepts and formulae of MDPs and remind the **Markov property** of them. Finally, we give an example in Python for a simple grid world.
<figure>
<img alt="RL: State-action-next state-reward" src="./Media/RL-MDP-fig-1.jpg" width="50%">
<figcaption>Figure 2. The agent at state s<sub>t</sub> takes action a<sub>t</sub>. Then, the environment goes to state s<sub>t+1</sub> and gives reward r<sub>t+1</sub>.</figcaption>
</figure>
<hr>

3) **Returns, policy, and value functions** Return is the discounted accumulated rewards that an agent receives over time. The policy is a strategy that the agent uses to select its action at each state. The value functions are the expected returns. We review these technical terms and give an example in Python. 
4) **Bellman equations, Bellman optimality equations, and optimal policy:** With the Bellman equations, we get the Bellman optimality equations. With the Bellman optimality equations, we are able to estimate the optimal value functions. Consequently, the optimal policy can be obtained from the optimal value functions. This is one way to solve an RL problem. Here, a Python code is available for using Bellman optimality equation of state-value function. It is reminded that the Python code is a bit advanced at this stage. 