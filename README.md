# Student_performance_analysis
This project analyzes the performance of students based on various factors using a dataset (https://1drv.ms/x/c/0347b1504075ab17/EbIx5gTb5m5KpIf54Stp-HoBL9Kyzn-pLzjq2Pmd8_zLsQ?e=7VEuXI&nav=MTVfezkwQjAyRjNBLURFNTAtNEIyNC04OUI0LTYxNDYwMjFBNTJENX0). The analysis explores different aspects such as demographic information, family background, and academic performance indicators to understand the factors influencing students' final grades.

# Dataset Description
1 school - student's school (binary: "GP" - Gabriel Pereira or "MS" - Mousinho da Silveira);
2 sex - student's sex (binary: "F" - female or "M" - male)
3 age - student's age (numeric: from 15 to 22)
4 address - student's home address type (binary: "U" - urban or "R" - rural)
5 famsize - family size (binary: "LE3" - less or equal to 3 or "GT3" - greater than 3)
6 Pstatus - parent's cohabitation status (binary: "T" - living together or "A" - apart)
7 Medu - mother's education (numeric: 0 - none,  1 - primary education (4th grade), 2 – 5th to 9th grade, 3 – secondary education or 4 – higher education)
8 Fedu - father's education (numeric: 0 - none,  1 - primary education (4th grade), 2 – 5th to 9th grade, 3 – secondary education or 4 – higher education)
9 Mjob - mother's job (nominal: "teacher", "health" care related, civil "services" (e.g. administrative or police), "at_home" or "other")
10 Fjob - father's job (nominal: "teacher", "health" care related, civil "services" (e.g. administrative or police), "at_home" or "other")
11 reason - reason to choose this school (nominal: close to "home", school "reputation", "course" preference or "other")
12 guardian - student's guardian (nominal: "mother", "father" or "other")
13 traveltime - home to school travel time (numeric: 1 - <15 min., 2 - 15 to 30 min., 3 - 30 min. to 1 hour, or 4 - >1 hour)
14 studytime - weekly study time (numeric: 1 - <2 hours, 2 - 2 to 5 hours, 3 - 5 to 10 hours, or 4 - >10 hours)
15 failures - number of past class failures (numeric: n if 1<=n<3, else 4)
16 schoolsup - extra educational support (binary: yes or no)
17 famsup - family educational support (binary: yes or no)
18 paid - extra paid classes within the course subject (Math or Portuguese) (binary: yes or no)
19 activities - extra-curricular activities (binary: yes or no)
20 nursery - attended nursery school (binary: yes or no)
21 higher - wants to take higher education (binary: yes or no)
22 internet - Internet access at home (binary: yes or no)
23 romantic - with a romantic relationship (binary: yes or no)
24 famrel - quality of family relationships (numeric: from 1 - very bad to 5 - excellent)
25 freetime - free time after school (numeric: from 1 - very low to 5 - very high)
26 goout - going out with friends (numeric: from 1 - very low to 5 - very high)
27 Dalc - workday alcohol consumption (numeric: from 1 - very low to 5 - very high)
28 Walc - weekend alcohol consumption (numeric: from 1 - very low to 5 - very high)
29 health - current health status (numeric: from 1 - very bad to 5 - very good)
30 absences - number of school absences (numeric: from 0 to 93)
31 G1 - first period grade (numeric: from 0 to 20)
31 G2 - second period grade (numeric: from 0 to 20)
32 G3 - final grade (numeric: from 0 to 20, output target)

# Questions Explored:
1. How does the distribution of final grades (G3) vary between different schools (school)?
2. Is there a difference in final grades (G3) based on students' gender (sex)?
3. Does the type of address (urban/rural) have any impact on final grades (G3)?
4. How does family size (famsize) correlate with final grades (G3)?
5. Is there any relationship between parents' cohabitation status (Pstatus) and students' final grades (G3)?
6. Does the level of parents' education (Medu and Fedu) affect students' final grades (G3)?
7. How does students' weekly study time (studytime) relate to their final grades (G3)?
8. Is there any correlation between the number of past class failures (failures) and final grades (G3)?
9. Do students receiving extra educational support (schoolsup) perform better in final grades (G3)?
10. What is the distribution of final grades (G3) across different age groups?

# Analysis:
The analysis reveals several insights into the factors influencing students' final grades (G3):

- Parents' education level, both mother's (Medu) and father's (Fedu), emerges as one of the strongest predictors of final grades, indicating the importance of parental involvement in education.
- Weekly study time is positively correlated with final grades, suggesting the significance of consistent study habits in achieving better academic performance.
- Other factors such as gender, address type, family size, and parents' cohabitation status show less influence on final grades compared to parental education level and study habits.
- Past class failures negatively impact final grades, highlighting the importance of addressing academic challenges early on.
- The effectiveness of extra educational support programs (schoolsup) in improving final grades varies and warrants further investigation.
