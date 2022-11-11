# Reinforcement Learning
## COMS4061A MiniHack the Planet Assignment

## REINFORCE with Baselines**
![](https://github.com/Harushii18/RLAssignment/blob/main/REINFORCE.gif)




## DQN
![](https://github.com/Harushii18/RLAssignment/blob/main/DQN%20GIF.gif)



**Group members:**
- Feziwe Melvin Shongwe (2135313)
- Phola Bavuma (1848739)
- Derrin Naidoo (2127039)
- Suraksha Motilal (2108903)

## About the Project

MiniHack is a powerful sandbox framework for easily designing novel RL environments ranging from small rooms to complex, procedurally generated worlds. By leveraging the full set of entities and environment dynamics from NetHack, one of the richest grid-based video games, MiniHack allows designing custom RL testbeds that are fast and convenient to use.

![Image of quest hard environment](https://minihack.readthedocs.io/en/latest/_images/quest_hard.png)

Your task is to create an agent that can navigate the Quest-Hard dungeon
and accrue as many points as possible. Work in groups of three to four
people. You must implement methods from two of the following categories
to solve the problem.
- A value function method (e.g. DQN [3])
- A model-based method (e.g. MCTS [4])
- A policy method (e.g. REINFORCE [5]
- A hierarchical method (e.g. Option-Critic [6])

## Agents

Three agents were chosen to navigate the dungeon and were based on the following models:
<ol>

<li> REINFORCE with baseline
<li> DQN
<li> Actor-Critic

</ol>

## Installation information

All installations have been incorporated into the code itself. No installations are required if the code is run on Google Colab. Should one decide to run it locally, it is recommended that the code is run on a Linux (Ubuntu) operating system and all sudo apt updates that are in the code are run on the terminal. This code also relies heavily on [NLE](https://github.com/facebookresearch/nle) and [MiniHack](https://github.com/facebookresearch/minihack). The following article helped with NLE installation issues: [NLE Issue 117](https://github.com/facebookresearch/nle/issues/117) 


## Contributions

Please note that we had worked on Google Colab and uploaded the files to Github after confirming our models. The commits to this repository do not reflect the group contributions of all the members toward this project. All group members contributed equally to this project.

## Submission issues

The video named REINFORCE.mp4 in the Moodle Submission was incorrectly named and contains the Best Run for DQN. There should be two agent videos: one for DQN and another for REINFORCE, as seen in this repository.
