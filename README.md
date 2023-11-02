## Description 

- Initialise a mean for each arm, taken from a normal distribution.
- use each arms' moving average reward as value function.
- reward for each arm is a sampel from its normal distribution based of the arms mean value.
- epsilon greedy strategy, Otherwise exploit arm with biggest current average reward.
- Visualise normal disrtibution for each bandit.
- compares how average reward changes with different epslion values.
- added softmax action selection and displayed the effect of changing tau values.
