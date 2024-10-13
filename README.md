# [SQL in MySQL] Tech Layoffs from COVID to now
## 1. Introduction:
This project utilized the dataset from https://www.kaggle.com/datasets/swaptr/layoffs-2022.
For this project, I performed data cleaning and conducted exploratory data analysis.
## 2. Let me cook:
### Data Cleaning
I follow 4 steps whenever I clean data:
#### 1. Remove Duplicates
Using ROW_NUMBER to identify duplicates (which have row_number > 1) and then remove all of them
* SQL code ![image](https://github.com/user-attachments/assets/2d994a7f-55da-41e9-b987-6ce753f6a954)

* Query results ![image](https://github.com/user-attachments/assets/b4dddf8d-fdc4-40d1-9716-85f88921e6d4)

Create new table that contain the row_number in it, then we delete the row_number > 2


#### 2. Standardize data
#### 3. Null values
#### 4. Remove unnecessary columns
