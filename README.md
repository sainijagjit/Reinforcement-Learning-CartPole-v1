This is the code for solving the “FrozenLake-v0” environment using DQN Learning.
<b>CartPole-v1</b>

<b>Description about the environment</b>

A pole is attached by an un-actuated joint to a cart, which moves along a frictionless track. The system is controlled by applying a force of +1 or -1 to the cart. The pendulum starts upright, and the goal is to prevent it from falling over. A reward of +1 is provided for every timestep that the pole remains upright. The episode ends when the pole is more than 15 degrees from vertical, or the cart moves more than 2.4 units from the center.




Approaches
1. random movements
in this approach we choose an random action (left or right) given a paticular state of the enviroment. needles to say this approach performs very poorly because it does not take into consideration the present state.
this approach because of its random nature is quite un predictable. On 10 trails runs the max time of survival is 118 timesteps and acg survival time of about 21 time steps which is pretty bad.


![CartPole-v1](https://github.com/adibyte95/CartPole-OpenAI-GYM/blob/master/gif%20images/random.gif)
