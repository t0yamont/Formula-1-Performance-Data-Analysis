# Formula 1 Driver and Race Data analysis for performance maximization
<img width="1200" alt="Screenshot 2023-04-04 at 7 48 02 AM" src="https://user-images.githubusercontent.com/99470852/229669829-7762e338-5e22-4e40-9e0a-3ab8d479b0db.png">

## Introduction 

The Formula 1 (F1) racing championship is an intensely competitive motorsport that produces extensive data during races, including telemetry from cars, performance metrics, driver statistics, and race results. This project leverages data analysis techniques to extract deeper insights from F1 data, aiming to enhance team performance, optimize race strategies, and improve overall race outcomes.
This repository features data analysis of Formula One (F1) races, with data accurate up to the 2023 Bahrain Grand Prix. The analysis is conducted using Python and various data analysis libraries such as Pandas, Numpy, and Matplotlib.

## Data Source
The dataset is sourced from Kaggle, a well-known platform for data science competitions. It includes details about F1 drivers, the seasons they competed in, race data, and points earned.

## File Structure
- F1DriversDataset.csv - This file contains the raw dataset in CSV format
- formula1.ipynb - A Jupyter notebook used for data analysis
- plots - A directory that holds the plots generated from the data analysis.
- README.md - The file you are currently reading

## Data Cleaning
The origianl dataset contains missing values and inconsistent data types. I used the Pandas library for data cleaning, addressing the missing values and converting data types to suitable formats for analysis.

## Data Analysis
The data is examined to uncover insights and address various questions about F1 races. The analysis involves correlation studies and visualizations created with the Matplotlib library.

The questions explored here are:
1. How does the number of seasons a driver compete in relate to their total race wins?
2. How is the number of championships won compare to the number of seasons competed in? 
3. Does the decade a driver participates in affect their average win rate relative to their number of race starts?
4. How is the number of podium finishes relate to the number of pole positions for drivers who have been champions?


## Conclusions
The data analysis uncovers fascinating insights about F1 races, the drivers who have competed, and the championships won. These findings are documented in the Jupyter notebooks and visualized in the plots directory.s



## References
Original idea and repository: https://github.com/chandanamulagund/Maximizing-Performance-Data-Analysis-of-Formula-1-Driver-and-Race-Data/tree/main 

Kaggle dataset: https://www.kaggle.com/datasets/dubradave/formula-1-drivers-dataset

Pandas documentation: https://pandas.pydata.org/docs/

Matplotlib documentation: https://matplotlib.org/stable/contents.html

