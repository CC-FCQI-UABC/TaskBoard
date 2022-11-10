# TaskBoard
Task Board Agent-Based Model

TaskBoard is a Task Board Agent-Based Model programmed in NetLogo.

## WHAT IS IT?

The model aims to illustrate how employees perform a project execution, visualize the task's processing, and depict the Burndown Chart, which integrates the description of the work to do (scope), the deadlines for its execution (schedule), and the calculation of its costs and the resources required for its implementation (cost). 

Specifically, we are addressing the following questions: How do the execution delays or advances impact project behavior? How does the task board illustrate the employees' work capacity? Can managers make reasonable decisions regardless of why workers cause delays or produce overruns in their assignments? 

To consider our model realistic enough for its purpose, we use the following patterns: The model addresses classic problems of Project Management (PM). It plays the typical task board where workers are assigned to complete a task backlog in project performance. Workers could delay or advance in the task execution, and we calculate Burndown Chart and visualize the project behavior in a task board. 

## HOW IT WORKS
The model includes the following entities: task and employee. The workspaces and the task board are spatial and temporal resolution and extent.

In the model, agents represent employees executing tasks in a simple, agile production system. Each agent takes a job from the backlog and performs it in the set time. The interface displays employees and tasks on a Kanban-like task board. To-do tasks are in the red card column, jobs in progress are in the yellow card column, and completed tasks are in the green card column.

The most critical processes of the model, which we repeated every step, are: firstly, the employee picks tasks from the to-do backlog. Then the employee moves assignments to the in-progress queue. Finally, the employee achieves and carries tasks to the done cue.

The most important design concepts of the model are a task backlog, a task board, and players (or employees).

  1. The task backlog is a task backlog (to-do column) that requires individuals to complete it. The task board is task states portrayed on a task board to visualize the project's advancement.

  2. The players or employees must take as many as permitted tasks from the "to-do" queue and deliver them to the "done" cue in the panel. While a player is working on an assignment, he must keep the assignment tag in the "in-progress" column.

  3. The cost and schedule plan has a task-planned cost in hours and start-finish time, but the worker could delay or advance in completing the job, or environmental situations could increase and decrease the final cost. 

  4. The Burndown Chart depicts the processing of the task in the project execution.


## HOW TO USE IT

### Setup

  1. First, establish the number of employees involved and the number of tasks to perform on the project.
  2. Second, the setup procedure will generate the number of tasks selected with random units of effort with values between 1 and 10 and the desired set of employees.
  3. Third, establish the probability that a task will be late and the probability that it will be ahead. For an ideal scenario, the chance is zero in both cases.
  4. Finally, decide how many tasks each worker will be able to execute simultaneously. The budget at completion is the sum of all the story points or units of effort defined for each job.


### Running the model

1. Run the simulation step by step or in continue running.
2. On the fly, alter the values of probability-of-delay, probability-of-advance, or assigned-tasks-employee to see the consequences on the burndown chart and system state.

### After finishing simulation

1. Review the outcomes (burndown chart and final values).
2. Download tasks and employees' status to a CSV file if required. 


## THINGS TO NOTICE

Note that although the probabilities of delay and progress are equal, the project does not necessarily end with the estimated cost.

## THINGS TO TRY

1. Try to create different configurations by imagining scenarios according to experience. 
2. Try loading sample tasks from the CSV files. One sample file comes from a software development project with 12299 tasks. The second file comes from a Microsoft Project sample file with a basic software development project template with 61 tasks. 

## EXTENDING THE MODEL

* Loading the tasks from a CSV file demonstrates how we can import representative scenarios for analysis. The model can be extended by loading new files with sample tasks.

* Also, we can extend the model by adding new metrics to measure the performance of the production system and do estimates for forecasting.

* We could try adding human factors to the model. In that case, we could also add the decision-making attributes of individuals or some social factors resulting from their interactions and relationships.

* Adding emergent behaviors resulting from the interaction of team members could add complexity to the model to explore the production system as a complex adaptive system.


## CREDITS AND REFERENCES

This model is an output of a research project supported by the internal research project fund of the Autonomous University of Baja California. Project registry: 300/6/C/11/22.
