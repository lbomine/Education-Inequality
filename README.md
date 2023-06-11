# Education Inequality • Data 3320, Spring 2023
Addresses the inequality of educational opportunity in U.S. high schools. We are focusing on average student performance on the ACT or SAT exams that students take as part of the college application process and if socioeconomic factors may be used to predict school performance.

## Requirements
To complete this project, Google Colaboratory is used as the main software. This is a web-based IDE for Python (programming language). Python libraries are also utilized to help clean and plot the data. GitHub is used to store the files of this project and make it easily accessible for reference when working with the data.

## Data
This project utilizes two data sets [`EdGap_data.xlsx`](https://github.com/lbomine/Education-Inequality/blob/main/EdGap_data.xlsx) and [`ccd_sch_029_1617_w_1a_11212017.csv`](https://www.dropbox.com/s/lkl5nvcdmwyoban/ccd_sch_029_1617_w_1a_11212017.csv?dl=0). 

The primary data set is the EdGap data set from [EdGap.org](https://www.edgap.org/#5/37.875/-96.987) which includes information about average ACT or SAT scores for schools and several socioeconomic characteristics of the school district in 2016. The secondary data set is basic information about each school from the [National Center for Education Statistics](https://nces.ed.gov/ccd/pubschuniv.asp).

### Additional Step Data Sources
[Education Commission of the States](https://www.ecs.org/) provides reports that compare educational policies across 50 states. We found 2 different reports about non-course requirements for high school graduation from 2019 and the school year 2017-2018. Even though we are working with 2016-2017 data, the 2017-2018 is a good start to learn about the states that have SAT/ACT requirements as graduation.

[Education Week](https://www.edweek.org/teaching-learning/what-tests-does-each-state-require/2017/02) provides a table with the 2016-2017 data of the states that require SAT/ACT and other exams.

## Data Preparation
Used this [Data Preparation Notebook](https://github.com/lbomine/Education-Inequality/blob/main/Education%20Inequality%20Data%20Preparation%20-%20Leiana%20Omine.ipynb) to import the data sets and prepare the data.
<br> <br> Steps Taken:
- Inspected the contents of each data set.
- Converted data types of columns of the data frames to the correct types.
- Removed unnecessary parts of the data sets.
- Identified missing values in the data sets. Imputed or removed NaN values.
- Ensured that the data frame is in a tidy, or long, format.
- Renamed the columns to follow best practices of being lowercase, snake_case, and understandable.
- Created derived variables that will be useful in the analysis.
- Exported the clean data sets:
  - [Testing Data](https://github.com/lbomine/Education-Inequality/blob/108fad5d7c9ff71a8ed69f66cb6e2a8c6b7061fb/clean_education_test.csv)
  - [Training Data](https://github.com/lbomine/Education-Inequality/blob/108fad5d7c9ff71a8ed69f66cb6e2a8c6b7061fb/clean_education_train.csv)

## Data Analysis
Used this [Analyis Notebook](https://github.com/lbomine/Education-Inequality/blob/108fad5d7c9ff71a8ed69f66cb6e2a8c6b7061fb/Education%20Analysis%20-%20Leiana%20Omine.ipynb) to analyze the cleaned data set and produce all necessary results for the final conclusion. Additional questions were proposed to assist our understanding and interpretation of the data.

### Additional Step
1. What is the relationship between the requirement for students to take the ACT/SAT and the average scores on these tests across different states?
2. Since the data does not include all the states, does this affect the relationship between ACT performance and socioeconomic factors? Can the inclusion of ACT/SAT requirements help counteract this bias?

## Author
Leiana Beatriz Omine - Student at Seattle University

## License
Materials in this repository may be reused but not modified.
