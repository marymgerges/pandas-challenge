# Module 4 Pandas Challenge

## Summary of the Analysis
### District Summary
This section combined the two provided files into one dataset.
Then I calculated the total number of unique schools, total number of stuents, total budget, average math score, average reading score, percentage of students who passed math, percentage of students who passed reading, and percentage of students who passed both math and reading.
Next, I created a dataframe that displayed this information.

### School Summary
In this section, I pulled the school types from the dataset. Then I calculated each of the following per school: total student count, total school budget, per student budget, average math score, average reading score, percentage of students who passed math, percentage of students who passed reading, and percentage of students who passed both math and reading.
Using this information, I created a dataframe to showcase each category.
I also made a copy of this dataframe in this section because it was going to be manipulated in later sections.

### Highest-Performing Schools (By % Overall Passing)
This section pulled the top 5 performing schools based on the percentage of students who passed both math and reading and displayed their total student count, total school budget, per student budget, average math score, average reading score, percentage of students who passed math, percentage of students who passed reading, and percentage of students who passed both math and reading.

### Bottom Performing Schools (By % Overall Passing)
This section pulled the bottom 5 performing schools based on the percentage of students who passed both math and reading and displayed their total student count, total school budget, per student budget, average math score, average reading score, percentage of students who passed math, percentage of students who passed reading, and percentage of students who passed both math and reading.

### Math Scores by Grade
In this section, the average math scores data was separated by grade for each school and then displayed in a dataframe.

### Reading Scores by Grade
In this section, the average reading scores data was separated by grade for each school and then displayed in a dataframe.

### Scores by School Spending
For this section, I created a copy of the school summary. Then, using the provided the bins and bin labels, I categorized the per student budget based on the bins. Using the school summary dataframe, I added a new column to the end of the dataframe for the spending ranges per student for each school. The formatting for the dataframe was also provided.
Next, I used the provided code to calculate each of the following based on spending ranges per student: average math score, average reading score, percentage of students who passed math, percentage of students who passed reading, and percentage of students who passed both math and reading. This information was then displayed as a dataframe.

### Scores by School Size
For this section, I used the provided bins and bin labels in order to categorize the school size based on the bins. Using the school summary dataframe, I added a new column to the end of the dataframe for the size for each school.
Next, I used the provided code to calculate each of the following based on school size: average math score, average reading score, percentage of students who passed math, percentage of students who passed reading, and percentage of students who passed both math and reading. This information was then displayed as a dataframe.

### Scores by School Type
I calculated each of the following based on school type: average math score, average reading score, percentage of students who passed math, percentage of students who passed reading, and percentage of students who passed both math and reading. This information was then displayed as a dataframe.

## Conclusions
Under the "Scores by School Spending" section, I noticed that the higher the spending ranges per student, the lower the percentage of overall passing, which is a little surprising.
In the "Scores by School Type" section, charter schools seem to do better in both math and reading than district schools, which seems logical.
