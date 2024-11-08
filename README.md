# Autonomous Robot Goal Seeking and Collision Avoidance In the Physical World: An Automated Learning and Evaluation Framework based on PPO Method
We design an existing automated evaluation framework so that the user can input more specific training parameters before the actual testing, allowing for easily repeatable experiments with any number of iterations. Our work also allows the framework to evaluate the agent's testing performance. We show this by first defining a source simulated environment that's similar to one of the target real-world environments. We then set up three physical environments (Empty maze as Maze 1, maze similar to the simulation maze as Maze 2, and the maze with one slab of wall in the middle as Maze 3) to show the performance difference of the agent in different physical environments including familiar and unforseen environments. Our experiments show that sufficient training in simulation can greatly improve the agent's performance when transferred to physical environments. With our framework, statistical results such as goal rates can be output as a CSV file for later analysis. For more details, please see our paper:
[(**TO DO**: Autonomous Robot Goal Seeking and Collision Avoidance In the Physical World: An Automated Learning and Evaluation Framework based on PPO Method.pdf](https://github.com/Ac31415/RL-Auto-Eval-Framework)


## **How to run**
**This code requires:**

**TO DO**


### Simulation Results

**TO DO Analysis**

<img src="https://github.com/Ac31415/RL-Auto-Eval-Framework/blob/main/figs/SimGoalRatesTraining.png" width="600" height="400">
<br/><br/>

<img src="https://github.com/Ac31415/RL-Auto-Eval-Framework/blob/main/figs/SimCumGoalsTraining.png" width="600" height="400">
<br/><br/>

<img src="https://github.com/Ac31415/RL-Auto-Eval-Framework/blob/main/figs/SimAveRewardsTraining.png" width="600" height="400">
<br/><br/>

<img src="https://github.com/Ac31415/RL-Auto-Eval-Framework/blob/main/figs/PPO_100_Runs_Training.png" width="600" height="400">
<br/><br/>