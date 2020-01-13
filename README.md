This is the code for solving the “FrozenLake-v0” environment using DQN Learning.
<b>CartPole-v1</b>

<b>Description about the environment</b>

A pole is attached by an un-actuated joint to a cart, which moves along a frictionless track. The system is controlled by applying a force of +1 or -1 to the cart. The pendulum starts upright, and the goal is to prevent it from falling over. A reward of +1 is provided for every timestep that the pole remains upright. The episode ends when the pole is more than 15 degrees from vertical, or the cart moves more than 2.4 units from the center.




Approaches
1. random movements
in this approach we choose an random action (left or right) given a paticular state of the enviroment. need not to say this approach performs very poorly because it does not take into consideration the present state.
this approach because of its random nature is quite un predictable.

![CartPole-v1](https://github.com/sainijagjit/Reinforcement-Learning-CartPole-v1/blob/master/random.gif)


2. using deep neural networks
in this approach we take generate training data by randomly taking actions on the enviromnent . if the run is succesful that is the pole is balanced on the cart from more than 100 time steps we add this example to out training set. this approach aims that we can learn how to balance the pole by learning from good training examples. we then fit the model to this training data and try to predict the outcome that is action for any new observation.

![CartPole-v1](https://github.com/sainijagjit/Reinforcement-Learning-CartPole-v1/blob/master/reinforcement-gif.gif)
