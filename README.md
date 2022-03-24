# College major versus earning potential

For this project we'll be working with a dataset on the job outcomes of students who graduated from college between 2010 and 2012. The original data on job outcomes was released by [American Community Survey](https://www.census.gov/programs-surveys/acs/), which conducts surveys and aggregates the data. FiveThirtyEight cleaned the dataset and released it on their [Github repo](https://github.com/fivethirtyeight/data/tree/master/college-majors).

## Aim

To Visualize the effect of gender distribution and popularity of various college majors on the future
earnings potential.

## Dataset

Each row in the dataset represents a different major in college and contains information on gender diversity, employment rates, median salaries, and more. Here are some of the columns in the dataset:

* `Rank` - Rank by median earnings (the dataset is ordered by this column).
* `Major_code` - Major code.
* `Major` - Major description.
* `Major_category` - Category of major.
* `Total` - Total number of people with major.
* `Sample_size` - Sample size (unweighted) of full-time.
* `Men` - Male graduates.
* `Women` - Female graduates.
* `ShareWomen` - Women as share of total.
* `Employed` - Number employed.
* `Median` - Median salary of full-time, year-round workers.
* `Low_wage_jobs` - Number in low-wage service jobs.
* `Full_time` - Number employed 35 hours or more.
* `Part_time` - Number employed less than 35 hours.

## Data Cleaning

* Dropping NULL values form the dataset.
* Renaming column names to snakecase.

## Data Analysis

* Few majors are extremely popular than the rest.
* A student pursuing a popular major isn't guaranteed to make more money than those pursuing a less popular major.
* A student pursuing a popular major doesn't necessarily have more opportunity than those pursuing a less popular major. 
* There are majors with low unemployment rate and very high earning potential.
* Students that majored in subjects that were majority female probably make less money than those with less share of women.
* Majors with more full time employees tend to make between 30,000 and 50,000.
* Majors with high earning potential has low unemployment rate when compared with majors of low earning potential.
* Engineering contain predominantly male students and Education, Health, Psychology & Social Work contain predominantly female students.
* Business is the category with maximum number of students and interdisciplinary is the one with least number of students.

## Conclusions

Some conclusions are paradoxical in nature and they are as follows.

* A student enrolled in a popular major isn't guaranteed to have a high earning potential.
* Majors with greater women share tends to have less earning potential. 
* There are majors with low unemployment rate and very high earning potential.

The effects of gender distribution and popularity of majors on the future earning potential is successfully visualized.
