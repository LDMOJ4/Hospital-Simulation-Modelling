# Hospital-Simulation-Modelling

## The brief
Simulate the flow of patients through a new specialised Diabetes Centre in a hospital. I was provided with the known activity nodes and a mixture of data and testimony of how. Software used was Simul8.

## Interesting features of the simulation model
1) Used data to fit distributions to one of the activity nodes to suggest a distribution for people going through that node using maximum likelihood estimators.
2) Split individuals by their type of diabetes.
3) Take blood tests to create a separate loop for blood and combine back with the correct patient using unique identifiers.
4) Assign different resources (doctors, receiptionists, nurses, etc.) to each of the activity nodes.
5) Create a resource schedule for the different resources. Pool resources that can do the same task.
6) Create KPI's such as time in the system and waiting time at reception.
7) Create an accurate warm up period before recording KPI's to allow the system to enter a steady state, calculated using Welch's procedure.
8) Simulate 100's of runs to accurately create 95% confidence intervals for KPI's.
9) Calculate paired t confidence intervals accurately (the confidence intervals of the differences not the diffrence of the confidence intervals).

## Annotated Model
<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/77ecce68-24ad-47d2-bb05-0fa6c47b5ffb" />

## Model Improvement Results (Simulated)
- Increased proportion of people that successfully made it through the model within the day by 17%.
- Increased proportion of insulin based patients through sytem in 120 minutes by 340%.
- Increased proportion of people seen by reception in less than 15 minutes by 42%.

## Project Results
- Achieved a grade of 78%
