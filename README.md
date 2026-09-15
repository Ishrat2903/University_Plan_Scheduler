# UniPlan – SI University Scheduler

## M603A Advanced Algorithms Project

**Student:** Ishrat Shaikh    

## Overview

UniPlan is a university timetable scheduling system developed for the Advanced Algorithms project.

The system combines several algorithms to create a valid timetable and reduce unused classroom capacity.

### Algorithms

- Greedy Scheduling
- Conflict Graph
- Welsh–Powell Graph Colouring
- Dynamic Programming for Room Optimisation
- Recursive Backtracking Repair
- Schedule Validation

## Dataset

- 5,000 students
- 300 professors
- 50 rooms
- 5 campuses
- 1,366 classes
- 400 modules
- 1,550 required sessions

The main dataset is located in:

```text
data/SI_University_Scheduling_Dataset_AUDITED_FINAL.xlsx

## How to Access and Use

1. Open the GitHub repository:

   `https://github.com/Ishrat2903/University_Plan_Scheduler`

2. Click **Code → Download ZIP** and extract the project folder.

3. Make sure **Python 3** is installed on the computer.

4. Open Terminal/Command Prompt in the extracted project folder.

5. Install the required Python packages:

```bash
pip install -r requirements.txt

1. To run the Scheduling web app use:
  python src/app.py
2. To open the web application use:
  http://127.0.0.1:5000
