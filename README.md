# Project-5-Reinforcement-in-Pacman
In this project, you will implement value iteration and Q-learning. You will test your agents first on Gridworld (from class), then apply them to
a simulated robot controller (Crawler) and Pacman.

As in previous projects, this project includes an autograder for you to grade your solutions on your machine. This can be run on all questions
with the command:
`python autograder.py`

It can be run for one particular question, such as q2, by:
`python autograder.py -q q2`

It can be run for one particular test by commands of the form:
`python autograder.py -t test_cases/q2/1-bridge-grid`

The code for this project contains the following files, available as a zip archive.

| Files you'll edit:           |                                           |
|------------------------------|-------------------------------------------|
| `valueIterationAgents.py`    | A value iteration agent for solving known MDPs. |
| `qlearningAgents.py`         | Q-learning agents for Gridworld, Crawler, and Pacman. |
| `analysis.py`                | A file to put your answers to questions given in the project. |

| Files you should read but NOT edit: |                                           |
|-------------------------------------|-------------------------------------------|
| `mdp.py`                            | Defines methods on general MDPs.          |

| Files you might want to look at     |                                           |
|-------------------------------------|-------------------------------------------|
| `learningAgents.py`                 | Defines the base classes `ValueEstimationAgent` and `QLearningAgent`, which your agents will extend. |
| `util.py`                           | Utilities, including `util.Counter`, which is particularly useful for Q-learners. |
| `gridworld.py`                      | The Gridworld implementation.             |
| `featureExtractors.py`              | Classes for extracting features on (state, action) pairs. Used for the approximate Q-learning agent (in `qlearningAgents.py`). |

| Files you can ignore:               |                                           |
|-------------------------------------|-------------------------------------------|
| `environment.py`                    | Abstract class for general reinforcement learning environments. Used by `gridworld.py`. |
| `graphicsGridworldDisplay.py`       | Gridworld graphical display.              |
| `graphicsUtils.py`                  | Graphics utilities.                       |
| `textGridworldDisplay.py`           | Plug-in for the Gridworld text interface. |
| `crawler.py`                        | The crawler code and test harness. You will run this but not edit it. |
| `graphicsCrawlerDisplay.py`         | GUI for the crawler robot.                |
| `autograder.py`                     | Project autograder                        |
| `testParser.py`                     | Parses autograder test and solution files |
| `testClasses.py`                    | General autograding test classes          |
| `test_cases/`                       | Directory containing the test cases for each question |
| `reinforcementTestClasses.py`       | Project 6 specific autograding test classes |

**Files to Edit and Submit:** You will fill in portions of valueIterationAgents.py , qlearningAgents.py , and analysis.py during the
assignment. Once you have completed the assignment, you will submit these files to Gradescope (for instance, you can upload all .py files
in the folder). Please do not change the other files in this distribution.

**Evaluation:** Your code will be autograded for technical correctness. Please do not change the names of any provided functions or classes
within the code, or you will wreak havoc on the autograder. However, the correctness of your implementation – not the autograder’s
judgements – will be the final judge of your score. If necessary, we will review and grade assignments individually to ensure that you receive
due credit for your work.
