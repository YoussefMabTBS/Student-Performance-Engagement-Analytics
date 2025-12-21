# BI Project - Student Analytics

All data files except one large file are included.

## Missing File: studentVle.csv (400MB)

Due to file size limits, `studentVle.csv` is not included and must be downloaded separately.

### How to get studentVle.csv:
1. Visit: https://analyse.kmi.open.ac.uk/open_dataset
2. Download the complete **OULAD dataset** (it will download all files as a package)
3. Extract and copy only `studentVle.csv` from the download
4. Place `studentVle.csv` in the `data_raw/` folder

**Note**: The download includes the entire OULAD database, but you only need the `studentVle.csv` file for this project.

## How to Run
1. Download `studentVle.csv` as described above
2. Place it in `data_raw/` folder
3. Run `etl/etl_student_analytics.ipynb`
4. Cleaned data will be generated in `data_cleaned/`
