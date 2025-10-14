## Student Performance Analysis

This is student Performance Analysis perform by Bongkodmas Tankul 6713371 and Chitisa Chakpetch 6713357 for EGBI 222 Computer Programming pair project. The dataset we use are from https://www.kaggle.com/datasets/mexwell/student-scores/data

Our project presents an **exploratory data analysis (EDA)** of a **student performance dataset**.  
The dataset includes various attributes related to students, such as demographic information, academic performance across multiple subjects, weekly self-study hours, career aspirations, and participation in part-time jobs and extracurricular activities.

The goal of this analysis is to **explore relationships between these attributes** and **gain insights into factors that may influence student performance and behavior**.  
Through this process, we aim to identify key trends, correlations, and patterns that can inform educational strategies and student support initiatives.

This analysis was conducted and visualized by the user.  
You can view the complete code and results in the notebook: **[`Student_performance_analysis.ipynb`](./Student_performance_analysis.ipynb)**

## Dataset Description

The dataset used for this analysis is `student-scores.csv`.

It contains **2000 rows** and **17 columns**. Each row represents a unique student.

Here is a brief description of each column:

*   **id**: Unique identifier for each student (integer).
*   **first_name**: The first name of the student (object/string).
*   **last_name**: The last name of the student (object/string).
*   **email**: The email address of the student (object/string).
*   **gender**: The gender of the student (object/string).
*   **part_time_job**: Indicates if the student has a part-time job (boolean).
*   **absence_days**: The number of days the student was absent (integer).
*   **extracurricular_activities**: Indicates if the student participates in extracurricular activities (boolean).
*   **weekly_self_study_hours**: The number of hours the student spends on self-study per week (integer).
*   **career_aspiration**: The stated career aspiration of the student (object/string).
*   **math_score**: The student's score in Math (integer).

## How to Run the Code

To run this analysis, you will need access to Google Colaboratory and the dataset file (`student-scores.csv`).

1.  **Open the Notebook in Google Colab:** Upload or open the provided Jupyter Notebook file (`.ipynb`) in Google Colab.
2.  **Connect to the Runtime:** Ensure you are connected to a Colab runtime. You can do this by clicking on "Connect" in the top right corner of the notebook interface. A connected runtime will show RAM and Disk usage.
3.  **Ensure Data Accessibility:** Make sure the `student-scores.csv` file is located in your Google Drive at the following path: `/content/drive/MyDrive/student-scores.csv`. The notebook is configured to read the data from this specific location.
4.  **Run the Code Cells:** Execute each code cell in the notebook sequentially, starting from the first cell. You can run a cell by clicking the play button next to it or by pressing `Shift + Enter`.

Following these steps will execute the data loading, exploration, and visualization code presented in the notebook.

*   **history_score**: The student's score in History (integer).
*   **physics_score**: The student's score in Physics (integer).
*   **chemistry_score**: The student's score in Chemistry (integer).
*   **biology_score**: The student's score in Biology (integer).
*   **english_score**: The student's score in English (integer).
*   **geography_score**: The student's score in Geography (integer).

  ## Key Findings

The code in this notebook performs exploratory data analysis on the student performance dataset to uncover patterns and insights. The visualizations and statistical summaries reveal several key findings:

*   **Weekly Self-Study Hours:** The distribution of weekly self-study hours shows a wide range, with a concentration around 0-10 hours and another peak around 25-30 hours. This suggests varying study habits among students.
*   **Gender Distribution:** The dataset contains a nearly equal distribution of male and female students.
*   **Part-Time Job Impact:** The analysis on the impact of part-time jobs on cumulative score was attempted but failed to execute correctly in the provided notebook state. Therefore, no conclusion can be drawn from the current execution regarding this relationship.
*   **Extracurricular Activities:** Approximately 60% of students participate in extracurricular activities, while 40% do not.
*   **Career Aspirations:** Students have diverse career aspirations, with several distinct popular choices evident from the pie chart distribution.
*   **Subject Performance:** The subject score analysis shows variations in minimum, average, and maximum scores across different subjects. Biology appears to have the lowest minimum score, while most subjects have average scores around 80. Math, Physics, Chemistry, and Geography have perfect scores of 100 among some students, while English has a maximum score of 99. History has the lowest average score among all subjects.

The code's purpose is to load the dataset, perform basic data exploration and visualization, and highlight these descriptive statistics and distributions to help understand the characteristics of the student population and their academic profiles.

## Summary:
**Full report with graphs and visualizations can be found in: Student-Score-Summary.pdf**

Data Analysis Key Findings
*  The dataset contains 2000 rows and 17 columns, including student demographics, academic performance in seven subjects, self-study hours, career aspirations, and participation in part-time jobs and extracurricular activities.
*  The distribution of weekly self-study hours shows concentrations around 0-10 hours and 25-30 hours.
*  The dataset has a nearly equal distribution of male and female students.
*  Approximately 60% of students participate in extracurricular activities.
*  Students exhibit diverse career aspirations.
*  Subject scores vary, with Biology having the lowest minimum score and History having the lowest average score. Math, Physics, Chemistry, and Geography have maximum scores of 100, while English has a maximum of 99.
## Insights or Next Steps
*  Investigate the bimodal distribution of weekly self-study hours further to understand potential underlying factors or student groups.
*  Address the issue with the part-time job impact analysis to draw conclusions on its relationship with student performance.


