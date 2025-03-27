# Board Game Analysis: A comparison between personal game collections and a list of games from Board Game Geeks 
Captstone project for Code: You exploring the relationships between housing availability, prices, and schools in Southern Indiana.


## Overview

This project aims to better understand the board game collection of a devout, avid gamer, Adam Bartoszek. The analysis compares various aspects of his collection to an export from a board gaming enthusiast website, [BoardGameGeek](https://boardgamegeek.com).  The analysis will focus on breakouts of age range appropriateness and "domains" (the style of gameplay) to see what contrasts (if any) exist between personal collections and the board game community as a whole.


## Datasets

All the datasets are provided within this project as .csv files.  All were obtained directly or indirectly through BoardGameGeek.

- Adam Bartoszek's collection (AB_Collection.csv) was a direct export of his library from BoardGameGeek
- Judd Jacob's collection (JJ_Collection.csv) was a direct export of his library from BoardGameGeek
- [BoardGameGeek export via Kaggle](https://www.kaggle.com/datasets/threnjen/board-games-database-from-boardgamegeek) (bgg_dataset.csv)
- A mapping document created to aid in analysis and visualization of age range suggestions (AgeRangeMapping.xlsx)

### Structure

Within the Jupyter notebook, I accomplish the following steps:

- **Project Description:** Explain the intention of the project and the datasets.

- **Module imports, data paths, data frame creation** Complete various package imports, specify file locations and create beginning data frames

- **Function Creation:** Created functions for data cleansing, tagging, etc. for use in data preparation

- **Data Manipulation and Merging:** Applied the functions and other steps to combine the data into one whole for analysis preparation.  Also added columns as necessary to aid in analysis.

- **Beginning the Analysis:** Began filtering and completing maths for review and visualization

- **Visualizations :** Used Matplotlib to visualize the results.


## Features Utilized for the project

  | Feature        | Description                           |
  |----------------|---------------------------------------|
  | Read TWO data files| Used 3 CSV files and a created excel spreadsheet|
  | Clean your data and perform a pandas merge with your two data sets, then calculate some new values based on the new data set.      | Cleaned my data and merged (multiple times) with pandas. Created some new columns and calculated percentages and other aggregates |
  | Make 3 matplotlib plots | Three plus graphs were created |
  | Utilize a virtual environment      | Created a venv. |
  | Create a Data Dictionary for your project | Created a Data Dictionary specific to this project. |
  | Notate your code with markdown cells in Jupyter Notebook | Heading, descriptions and various steps are in cluded throughout the notebook utilizing markdown |

## Getting Started

To run this project, follow these steps:

1. Clone the repository: `git clone https://github.com/your-username/your-project.git`
2. Create a virtual environment
3. Install the necessary dependencies: `pip install -r requirements.txt`
4. Explore the Jupyter notebooks or scripts in the respective folders

## Dependencies

Python
Pandas
Jupyter Notebooks
Matplotlib

AI (ChatGPT) was consulted for explanations on why certain parts of code worked, troubleshoot errors and providing data labels within some graphs.



###  Virtual Environment Instructions
---
1. After you have cloned the repo to your machine, navigate to the project 
folder in GitBash/Terminal.
1. Create a virtual environment in the project folder. 
1. Activate the virtual environment.
1. Install the required packages. 
1. When you are done working on your repo, deactivate the virtual environment.

Virtual Environment Commands

| Command | Linux/Mac | GitBash |
|---------|-----------|---------|
| Create | `python3 -m venv venv` | `python -m venv venv` |
| Activate | `source venv/bin/activate` | `source venv/Scripts/activate` |
| Install | `pip install -r requirements.txt` | `pip install -r requirements.txt` |
| Deactivate | `deactivate` | `deactivate` |