# pandas-challenge

Discrepancies between requirements and starter code file.  In the School Summary section the requirement is looking for:
+ Calculate the number of schools with math scores of 70 or higher (2 points)
+ Calculate the number of schools with reading scores of 70 or higher (2 points), but the starter code is showing calculation for passing rate instead of number of schools. 
+ Use the code provided to calculate the per capita spending (2 points), when there was no code provided in the starter code file.

So I used my own code to calculate per capita spending, and only calculate % passing math and reading (the percentage of students who passed math and reading).  However, I included this line of code as comment to demostrate calculate the number of schools with math scores of 70 or higher:
per_school_passing_math = school_percent_passing_math[school_percent_passing_math >= 70].count()
