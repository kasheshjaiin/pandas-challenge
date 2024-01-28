# School District Analysis

## Overview

This repository contains the analysis of a school district's performance, focusing on key metrics such as average scores in math and reading, percentage of students passing math and reading, and overall passing rate. The analysis is broken down by spending per student, school size, and school type.

## Files

- `PyCitySchools.ipynb`: Jupyter Notebook containing the Python code for the school district analysis.
- `Resources/schools_complete.csv`: CSV file containing school data.
- `Resources/students_complete.csv`: CSV file containing student data.

## Analysis Summary

### Spending Analysis

- Created spending bins and categorized schools based on per student budget.
- Calculated average math and reading scores, as well as passing percentages, for each spending range.
- Assembled the results into a DataFrame named `spending_summary`.

### School Size Analysis

- Established size bins and categorized schools based on the total number of students.
- Calculated average scores and passing percentages for each school size category.
- Assembled the results into a DataFrame named `size_summary`.

### School Type Analysis

- Grouped the data by school type (charter or district) and calculated average scores and passing percentages.
- Assembled the results into a DataFrame named `type_summary`.

## Results

- `spending_summary`: Summary of school performance based on spending per student.
- `size_summary`: Summary of school performance based on school size.
- `type_summary`: Summary of school performance based on school type.

## Usage

To reproduce the analysis, you can run the code in the `PyCitySchools.ipynb` Jupyter Notebook using the provided CSV files.

## Libraries Used

- pandas
- NumPy
