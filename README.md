# StackOverflow Developer Survey Analysis

This project analyzes the StackOverflow Developer Survey data to answer a variety of questions regarding developers' work, demographics, preferences, and tools used globally.

## Table of Contents
- [Overview](#overview)
- [Project Setup](#project-setup)
- [Data Analysis Steps](#data-analysis-steps)
  - [Data Cleaning](#data-cleaning)
  - [Exploratory Data Analysis](#exploratory-data-analysis)
  - [Key Insights](#key-insights)
- [Questions Answered](#questions-answered)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)

## Overview

The goal of this project is to analyze StackOverflow's Developer Survey data to explore various aspects of the development profession, such as:
- Developer job satisfaction
- Preferred programming languages
- Work environment preferences
- Salary analysis
- Developer demographics

The dataset provides a comprehensive view of the developer community worldwide, including details on their coding experience, career satisfaction, programming languages, and more.

## Project Setup

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/stackoverflow-survey-analysis.git
   cd stackoverflow-survey-analysis
2.  **Install dependencies:**
   ```bash
   pip install -r requirements.txt
  ```
3. **Prepare the Data:**
  - i provided simple of data, if you need all data contact me

## Data Analysis Steps

The first step in the analysis is cleaning the dataset. This involves handling missing values, converting data types, and parsing specific columns that contain multi-value entries. Key steps include:

- Handling missing values: Removing or replacing missing data as needed.

- Data transformation: Converting columns such as Age, YearsCode to numeric values for analysis.

- Splitting and exploding multi-value columns: For example, splitting DevType and LanguageWorkedWith columns that contain semicolon-separated values.

## Exploratory Data Analysis

The next step is to perform some exploratory data analysis (EDA) to identify key patterns and insights:

1. Visualizing distributions: Understanding the distribution of variables like Age, YearsCode, and Satisfaction.

2. Identifying relationships: Analyzing relationships between variables such as Age vs Years of Coding Experience and Salary vs Developer Type.
   
## Key Insights

After the analysis, we uncover some interesting findings, such as:

1. **Age distribution: Developers in the 25-35 age range are the largest group.**

2. **Popular programming languages: JavaScript, Python, and Java are the most commonly used languages.**

3. **Satisfaction: Job satisfaction tends to increase with experience and developer type.**

4. **Salary patterns: Developers in certain roles, such as Data Scientists, tend to earn higher salaries.**

## Questions Answered
This analysis answers several questions about developers worldwide, such as:

1. How many developers are writing code for open source?

2. How much money do developers earn globally?

3. How satisfied are developers with their jobs globally?

4. What is the relation between the age of a developer and their work?

5. What social media sites do developers use?

6. Which is the most popular operating system among developers?

7. Why do most developers update their resumes frequently?

8. What programming languages have developers worked with, and which languages do they want to use in the future?

9. Which type of work location is preferred by developers?  


## Dependencies
- pandas

- seaborn

- matplotlib

- numpy

## Contributing
If you would like to contribute to this project, feel free to fork the repository and create a pull request. For any bugs or issues, open an issue in the repository.

