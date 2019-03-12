# Differential Knowledge Transfer with Relevance Weight (DTW)
Demo code for the paper "Multi-Agent Reinforcement Learning via Knowledge Transfer with Differential Noise and Relevance Weights"

### Required Dependencies:
- NVIDIA GPU
- Python 3.6, numpy 1.15.2, pyglet 1.3.2

### Notes:
#### 1. Introduction:
#### There are 4 objects in each environments:
- White cells represent a vacant space.
- Red cells represent robots.
- Grey cells represent rubbish or victims.
- Black cells represent barriers.

#### There are 3 experiments included in the demo code.
- Ex1 is the environment that robots collecting the rubbish at static positions.
- Ex3 is the environment that robots rescuing victims who have a probability of moving to a new position at each step.
#### In each experiment file directory, there are three enviroments.
- Random.py is used to test the performance of Random Method.
- RL.py is used to test the performance of Reinforcement Learning Method.
- TL.py is used to test the performance of basic Transfer Learning Method.
- TW.py is used to test the performance of Transfer Learning with Relevance Weights.
- DTW.py is used to test the performance of Differential Knowledge Transfer With Relevance Weights.
#### 2. Adjustable variables:
- Window size: WINDOW_WIDTH, WINDOW_HEIGHT
- Number of objects: RUBBISH_NUM (VICTIM_NUM in Ex3), BLOCK_NUM, BOT_NUM
- Barrier Positions: BLOCK_POSITION
