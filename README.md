# EVA_Assignment-9-Phase2 (P2_S9)

## Twin Delayed Deep Deterministic Policy Gradient (TD3)

Twin Delayed Deep Deterministic Policy Gradient is a Deep Reinforcement Learning Algorithm, which is an improvement over the
Deep Deterministic Policy Gradient (DDPG) algorithm. DDPG has a drawback of constantly overestimating the Q values of the critic network
which build up errors. TD3 concurrently learns a Q function and a policy.
TD3 focusses on reducing the overestimation of bias.
Following are the main features of TD3 :- 
a) Using a pair of critic networks

Clipped Double-Q Learning. TD3 learns two Q-functions instead of one so its called TWIN, and uses the smaller of the two Q-values to form the targets in the Bellman error loss functions.

b) Delayed updates of the actor

Delayed Policy Updates. TD3 updates the policy (and target networks) less frequently than the Q-function. There is one policy update for every two Q-function updates.

c) Action noise regularisation
Target Policy Smoothing. TD3 adds noise to the target action, to make it harder for the policy to exploit Q-function errors by smoothing out Q along changes in action.

![GitHub Logo](/logo.png)

