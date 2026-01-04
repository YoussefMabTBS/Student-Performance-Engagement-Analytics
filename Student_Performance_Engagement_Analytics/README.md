This project uses the Open University Learning Analytics Dataset (OULAD),
a real-world educational dataset published by the Open University.

Due to the large size of the raw data (~500MB), raw files are not included
in this repository.

To reproduce the ETL process:
1. Download the dataset from:
   https://www.kaggle.com/datasets/anlgrbz/student-demographics-online-education-dataoulad?select=studentVle.csv
2. Extract the CSV files.
3. Place the following files into the `data_raw/` directory:
   - studentInfo.csv
   - courses.csv
   - assessments.csv
   - studentAssessment.csv
   - studentVle.csv
4. Run the ETL notebook located in `etl/etl_student_analytics.ipynb`.