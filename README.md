# School_District_Analysis

## Overview

Analysis of student funding and student's standardized testing scores data was conducted to assist the school board and superintendent in making decisions regarding the school budges and priorities. Math and reading scores data was analyzed on various schools students attended. Furthermore, the school board has notified the chief data scientist, Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. The school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned to Maria for help. Maria has requested that the math and reading scores for Thomas High School be replaced with NaNs while keeping the rest of the data intact.

## Results

How is the district summary affected?

- The district summary data isn't affected. %Passing Math, %Passing Reading, and %Overall Passing have miniscule changes for Thomas High School as shown below from the district summary data frame.

###District Summary Before

![district_summary_df_before]("C:\Users\ariv9\Washu-Bootcamp\Module_4\School_District_Analysis\Resources\district_summary_df_before.png")

### District Summary After

![district_summary_df_after]

How is the school summary affected?

- %Passing Math, %Passing Reading, and %Overall Passing is affected for Thomas High School. There is a significance increase after for each as seen below.

### School Summary Before

![school_summary_df_before]()

### School Summary After

![school_summary_df_after]()

How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

- Replacing the ninth grader' math and reading scores does not affect Thomas High School's performance relative to other schools as they are still ranked second before replacing and after with an %Overall Passing of %90 respectively.

### Before

![top_schools_before]()

### After

![top_school_after]()
How does replacing the ninth-grade scores affect the following:

- Math and reading scores by grade are affected by that they display NaN for Thomas High School.
- Scores by school spending does not have any significate changes.
- Scores by school size aren't affected significantly
- Scores by school type aren't affected significantly

### Summary

Four changes that were observed after replacing the ninth grade reading and math scores with NaNs were:

- ninth grade students have NaN for both reading and math
- a total of 461 students (9th graders) were removed from the analysis
- %Passing Math increased significantly for Thomas High School.
- %Passing Reading increased significantly for Thomas High School
