# formula1strategy

This project aims to train a machine learning model to be able to determine if given past race data, generate a pre-race strategy, and then as each lap of the race completes, determine if the driver should perform a pit stop and what tire should be fitted. Then, based on the performance of the new tire, regenerate a new strategy for the remainder of the race. 

Feature #1:
Using past race data, generate a pre-race strategy. 
Input: historical race data
Output: Predicted lap pace, total race time, and pit stop laps.

Feature #2: 
During the race, predict the next lap time based on past laptimes. Potentially use linear or polynomial regression
Input: predicted lap pace, actual lap pace
Output: Next lap pace, predicted lap pace for the next n laps

Feature #3:
Determine if the driver should pit. Inputs are predicted next lap pace
Input: Next lap pace, predicted lap pace for the next n laps
Output: Pit or not pit, new strategy for the remainder of the race

Featuer #n:
Accomodate for unforseen situations like rain or safety and virtual safety cars

Data Source: https://www.kaggle.com/datasets/rohanrao/formula-1-world-championship-1950-2020
