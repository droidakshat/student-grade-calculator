# Student Grade Report Script

This small Python program reads a CSV file of student marks, works out their totals and percentages, assigns grades, and saves the results into two files — a new CSV and a text summary.

What it does

- Opens a file called students.csv.

- Checks it has the columns: name, math_score, science_score, english_score.

- Calculates: total score (math + science + English) and percentage (average of the three scores)

- Gives each student a grade:

90% and up = A

80–89% = B

70–79% = C

60–69% = D

below 60% = F 

- Saves everything into:

    output_report.csv – full table with totals, percentages, and grades

    report.txt – quick text list of names, grades, and percentages





How to run

1. Install Python 3.

2. Install the libraries:

3. Put your students.csv file in the same folder

4. Run the script:

5. The two output files will appear in the same folder.