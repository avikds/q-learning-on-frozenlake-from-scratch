# Q-Learning on FrozenLake from Scratch

Build a tabular Q-learning agent that learns to navigate the FrozenLake environment using an epsilon-greedy exploration strategy. You'll implement every piece from the Q-table and update rule to training loops and greedy evaluation.

## How to run

```bash
python scaffold.py
```

## Steps

- [x] **1.** init_q_table
- [x] **2.** max_q_value
- [x] **3.** greedy_action
- [x] **4.** sample_random_action
- [x] **5.** should_explore
- [x] **6.** epsilon_greedy_action
- [x] **7.** decay_epsilon
- [x] **8.** td_target
- [x] **9.** td_error
- [x] **10.** q_learning_update
- [x] **11.** interaction_step
- [x] **12.** run_training_episode
- [x] **13.** train_q_learning
- [x] **14.** extract_greedy_policy
- [x] **15.** run_greedy_episode
- [x] **16.** evaluate_success_rate

## Results

```
FrozenLake: 16 states, 4 actions
Q-table shape: (16, 4)
Reward history length: 2000
Mean reward first 100 episodes: 0.010
Mean reward last 100 episodes:  0.000
Greedy policy (first 8 states): [0, 0, 0, 0, 0, 0, 0, 0]
Greedy action at state 0: 0
Max Q-value at state 0: 0.0000
Single greedy episode reached goal: False
Greedy success rate over 100 episodes: 0.00
```
