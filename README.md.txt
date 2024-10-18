                                                             Data Merging 




1. Overview :

  This project focuses on demonstrating essential data manipulation techniques, specifically the merging and concatenation of datasets       
  using pandas. 

2. Key Topics Covered :

 - Data Loading: Loading datasets from CSV files into pandas DataFrames.

 - Merging DataFrames: Combining multiple datasets using merge() with various types of joins (inner, outer, left, right).

 - Concatenating DataFrames: Using concat() to append or combine datasets.

 - Data Aggregation: Grouping data and performing aggregations such as sum, mean, and count after merging.

3. Datasets Used:

 - Courses Dataset (Toy Dataset):
 
   A simple dataset containing information about various courses.

   Columns: course_id,course_name,price

   Description: This is a toy dataset representing different courses offered, along with their pice.

 - Students.csv (Toy Dataset)

   This dataset provides information about students enrolled in various courses.

   Columns: student_id,name,partner

   Description: A toy dataset containing details of students including their id, name, and partner.

 - reg-month1.csv Dataset (Toy Dataset) 

   Registration details of students for various courses, captured separately for months November .

   Columns: student_id,course_id

   Description: This is a toy dataset showing which students registered for which courses.

 - reg-month2.csv Dataset (Toy Dataset) 

   Registration details of students for various courses, captured separately for months December .

   Columns: student_id,course_id

   Description: This is a toy dataset showing which students registered for which courses.

 - Matches Dataset (Real-World Dataset)

   Contains detailed information about sports matches, including the teams, match outcomes, and dates.

   Columns: id,season,city,date,team1,team2,toss_winner,toss_decision,result,dl_applied,winner,win_by_runs,win_by_wickets ... etc

   Description: A real-world dataset capturing the outcome of various sports matches, useful for analyzing team performances.

 - Deliveries Dataset (Real-World Dataset) 

   Provides ball-by-ball details of sports matches, tracking each delivery made by bowlers to batsmen.

   Columns: match_id,inning,batting_team,bowling_team,over,ball,batsman,non_striker,bowler,is_super_over,wide_runs,bye_runs,legbye_runs ..... etc

   Description: This real-world dataset gives detailed data on each delivery in sports matches, allowing for granular performance analysis.
  
4. Requirements

 - To run this project, you'll need:

   Python 3.x
   Jupyter Notebook
   Pandas
   NumPy

 - You can install the required libraries using the following command:

   pip install pandas numpy

5. How to Use

 - Clone this repository
 
   git clone https://github.com/Ranjeet-Kumar60/merging.git
