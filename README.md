# EVA_Assignment-9-Phase2 (P2_S9)

## Twin Delayed Deep Deterministic Policy Gradient (TD3)

Twin Delayed Deep Deterministic Policy Gradient is a Deep Reinforcement Learning Algorithm, which is an improvement over the
Deep Deterministic Policy Gradient (DDPG) theorem. DDPG has a drawback of constantly overestimating the Q values of the critic network
which build up errors. TD3 concurrently learns a Q function and a policy.
TD3 focusses on reducing the overestimation of bias.
Following are the main features of TD3 :- 
a) Using a pair of critic networks
b) Delayed updates of the actor
c) Action noise regularisation

