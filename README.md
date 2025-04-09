# Project Management Report Generator

This C program helps in generating a project management report by evaluating the completion status, deadlines, and costs of tasks in a project. The program allows users to input task details, status, and deadlines, then calculates and displays key project statistics such as total tasks completed, tasks completed on time, and total cost/profit/loss of the project. This C program generates a project management report by evaluating the completion status, deadlines, and costs of tasks in a project. It helps in calculating project performance and determining overall efficiency.

## Features

- **Task Data Input**: Collects task details such as title, allocated person, status (completed or incomplete), submission date, and deadline.
- **Deadline Evaluation**: Evaluates whether tasks were completed on time, before the deadline, or missed the deadline.
- **Project Performance Evaluation**: Provides project efficiency feedback based on task completion and deadlines.
- **Cost Calculation**: Calculates total project cost, profit, and loss based on task completion status.
- **Efficiency Assessment**: Categorizes project performance into various efficiency levels.

## Example Output
Enter total number of tasks : 
3
TASK NUMBER : 1
Enter title of the task : 
Task1
Enter name of allocated person for the task: 
John
TITLE OF THE TASK : Task1
NAME OF ALLOCATED PERSON FOR THE TASK : John
Enter status of task (1=complete, 0=incomplete) : 
1
STATUS OF THE TASK : COMPLETE 
Enter date of submission of the task (DD MM YYYY) : 
10 05 2024
Enter deadline date (DD MM YYYY) : 
15 05 2024
Enter cost of the task : 
1000
THE DEADLINE HAS BEEN MET BEFORE TIME
TASK NUMBER : 2
Enter title of the task : 
Task2
Enter name of allocated person for the task: 
Alice
TITLE OF THE TASK : Task2
NAME OF ALLOCATED PERSON FOR THE TASK : Alice
Enter status of task (1=complete, 0=incomplete) : 
0
STATUS OF THE TASK : INCOMPLETE
Enter cost of the task : 
500
TASK NUMBER : 3
Enter title of the task : 
Task3
Enter name of allocated person for the task: 
Bob
TITLE OF THE TASK : Task3
NAME OF ALLOCATED PERSON FOR THE TASK : Bob
Enter status of task (1=complete, 0=incomplete) : 
1
STATUS OF THE TASK : COMPLETE 
Enter date of submission of the task (DD MM YYYY) : 
12 06 2024
Enter deadline date (DD MM YYYY) : 
10 06 2024
Enter cost of the task : 
1500
THE DEADLINE HAS NOT BEEN MET
TOTAL NUMBER OF COMPLETE TASKS : 2 
TOTAL NUMBER OF TASKS COMPLETED ON OR BEFORE DEADLINE : 1 
PERCENTAGE OF TASKS COMPLETED IN THE PROJECT : 66.666667 
PERCENTAGE OF TASKS COMPLETED ON OR BEFORE DEADLINE : 33.333333 
TOTAL COST OF THE PROJECT : 3000.00
TOTAL PROFIT OF PROJECT : 2500.000000 
TOTAL LOSS OF PROJECT : 500.000000 
THE PROJECT IS PERFORMED WITH SATISFACTORY EFFICIENCY BUT IT SHOULD BE IMPROVED
TOTAL LOSS OF 500.000000 HAS OCCURRED 
***********************************************
                PROJECT COSTS                
TOTAL COST OF THE PROJECT : 3000.00
TOTAL PROFIT OF PROJECT : 2500.000000 
TOTAL LOSS OF PROJECT : 500.000000 
***********************************************
