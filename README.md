# Stack Overflow 2023 Survey Analysis

This project analyzes the Stack Overflow 2023 Survey using PostgreSQL and Power BI. The analysis is divided into several sections covering various aspects of the survey data, including demographics, learning to code, salary and experience, programming languages, databases, and platforms.

# Insights

## Demographics

### Education
Analysis of the education levels of respondents.

### Age
Analysis of the age distribution of respondents.

### Developer Type
Analysis of the various developer types among respondents.

### Country
Analysis of the geographic distribution of respondents.

## Learning to Code

### Learning to Code Sources
Analysis of the various sources respondents use to learn to code.

### Learning to Code Online Sources
Analysis of the online sources respondents use to learn to code.

### Learning to Code Online Courses and Certificates
Analysis of the online courses and certificates respondents use to learn to code.

## Salary and Experience

### Relationship Between Median Experience and Median Salary by Developer Type
Scatter plot showing the relationship between the median years of experience and median salary for different developer types.

### Average Years of Experience by Developer Type
Bar plot showing the average years of experience for different developer types.

### Median Yearly Salary by Developer Type
Bar plot showing the median yearly salary for different developer types.

## Programming Languages

### Jaccard Index Matrix
Matrix showing the Jaccard Index for pairs of programming languages to indicate how often they are used together.

### Tree Map
Tree map visualization of programming languages.

### Programming Languages Bar Plot
Bar plot showing the distribution of programming languages used by respondents.

## Databases

### Jaccard Index Matrix
Matrix showing the Jaccard Index for pairs of databases to indicate how often they are used together.

### Tree Map
Tree map visualization of databases.

### Databases Bar Plot
Bar plot showing the distribution of databases used by respondents.

## Platforms

### Jaccard Index Matrix
Matrix showing the Jaccard Index for pairs of platforms to indicate how often they are used together.

### Tree Map
Tree map visualization of platforms.

### Platforms Bar Plot
Bar plot showing the distribution of platforms used by respondents.

## Folder Structure

### SQL
- **analysis**: Contains SQL scripts for data analysis.
- **reading_survey_results**: Contains SQL scripts for reading survey results.

### Power BI
- **sof2023.phit**: Power BI file containing the analysis and visualizations.
- **sof2023.pdf**: PDF export of the Power BI visualizations.

### Data
- **raw data**
  - **survey_results_public.csv**: Raw survey data.
  - **survey_results_schema.csv**: Schema of the survey data.
- **processed data**
  - **avg_yearspro.csv**: Processed data file containing average years of experience.
  - **learncode.csv**: Processed data file containing learning to code information.
