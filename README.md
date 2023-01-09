# pandas-challenge
Data is imported from two .csv files and run in a Python script through Jupyter Notebook. 
Data addresses individual student performance at 15 high schools, including reading and math scores, and includes information about the types of schools (District or Charter) and school budget. Data from these two combined .csv files includes the following:
    - Student ID
    - Student Name
    - Student Gender
    - Student Grade
    - School Name
    - Studnet Reading Score (out of 100)
    - Student Math Score (out of 100)
    - School ID
    - School Type (district or charter school)
    - School Size (in number of students attending)
    - School Budget (in USD)

<h1>District Summary</h1>
This brief summary dataframe lists the following information:
    - Total number of high schools
    - Total number of students in all four grade levels at all schools
    - Total combined budget for all schools (in USD)
    - Average math score across all schools and students
    - Average reading score across all schools and students
    - Percentage of students in all schools who are passing math (have a score >= 70 in math)
    - Percentage of students in all schools who are passing reading (have a score >= 70 in reading)
    - Percentage of students in all schools who are passing both math and reading (have a score >= 70)

<h1>School Summary</h1>
This dataframe summarizes information about each high school in the dataset. It lists the following information:
    - The name of the high school
    - The type of school (district or charter)
    - The total number of the students at the school
    - The total budget for the school
    - The total budget alloted for each student (total students/total school budget)
    - The average math score of students at the school
    - The average reading score of students at the school
    - The percent of students at the school who are passing math (have a score >= 70 in math)
    - The percent of students at the school who are passing reading (have a score >= 70 in reading)
    - Percentage of students at the school who are passing both math and reading (have a score >= 70)

<h1>Highest-Performing Schools by Percentage of Overall Passing</h1>
This dataframe sorts the information above (in 'School Summary') by the top 5 schools who have the highest percentage of students passing both math and reading (have a score >= 70).

<h1>Lowest-Performing Schools by Percentage of Overall Passing</h1>
This dataframe sorts the information above (in 'School Summary') by the 5 schools who have the lowest percentage of students passing both math and reading (have a score >= 70).

<h1>Math Scores by Grade</h1>
This dataframe summarizes math score information about each high school in the dataset. It lists the following information:
    - The name of the high school
    - The average math score for 9th grade students at the school
    - The average math score for 10th grade students at the school
    - The average math score for 11th grade students at the school
    - The average math score for 12th grade students at the school

<h1>Reading Scores by Grade</h1>
This dataframe summarizes reading score information about each high school in the dataset. It lists the following information:
    - The name of the high school
    - The average reading score for 9th grade students at the school
    - The average reading score for 10th grade students at the school
    - The average reading score for 11th grade students at the school
    - The average reading score for 12th grade students at the school

<h1>Scores by School Spending</h1>
This dataframe summarizes the relationship between high school budget spending per student and test scores in math and reading. It lists the following information:
    - Four spending ranges in USD of the total budget alloted for each student (total students/total school budget)
    - The average math score for students who attended schools that allotted funding to each student in a specific range
    - The average reading score for students who attended schools that allotted funding to each student in a specific range
    - The percent of students passing math (scoring >= 70 in math) who attended schools that allotted funding to each student in a specific range
    - The percent of students passing reading (scoring >= 70 in reading) who attended schools that allotted funding to each student in a specific range
    - The percent of students passing both math and reading (scoring >= 70 in both subjects) who attended schools that allotted funding to each student in a specific range

<h1>Scores by School Size</h1>
This dataframe summarizes the relationship between the size of a high school and student test scores in math and reading. It lists the following information:
    - Three size ranges (Small, Medium, and Large) based on the number of students enrolled at a high school
    - The average math score for students who attended schools of each size
    - The average reading score for students who attended schools of each size
    - The percent of students passing math (scoring >= 70 in math) who attended schools of each size
    - The percent of students passing reading (scoring >= 70 in reading) who attended schools of each size
    - The percent of students passing both math and reading (scoring >= 70 in both subjects) who attended schools of each size

<h1>Scores by School Type</h1>
This dataframe summarizes the relationship between the type of high school (district or charter) and student test scores in math and reading. It lists the following information:
    - The type of school (district or charter)
    - The average math score for students who attended schools of each type
    - The average reading score for students who attended schools of each type
    - The percent of students passing math (scoring >= 70 in math) who attended schools of each type
    - The percent of students passing reading (scoring >= 70 in reading) who attended schools of each type
    - The percent of students passing both math and reading (scoring >= 70 in both subjects) who attended schools of each type