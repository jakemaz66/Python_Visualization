# Automated Health Metric Data Visualization Project

This project is designed to automate the process of loading health metric data from Excel files, cleaning and preparing the data, and generating visualizations based on chosen metrics for multiple hospitals. The automation implemented in this project has the potential to save days' worth of manual reporting time.

## Table of Contents

- [Introduction](#introduction)
- [Tools and Skills Used](#tools-and-skills-used)
- [Process Overview](#process-overview)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

In healthcare, analyzing and reporting health metric data for multiple hospitals is a time-consuming and error-prone task. This project leverages Python automation to streamline this process, significantly reducing the time and effort required for data processing and visualization.

## Tools and Skills Used

- Python
- Jupyter Notebook
- pandas
- os
- seaborn
- Excel data handling
- Data cleaning and manipulation
- Data visualization

## Process Overview

The project follows a step-by-step process for automating the data analysis and visualization of health metrics:

1. **Data Loading**: The project uses pandas to load data from Excel files containing health metric data for multiple hospitals.

2. **Data Cleaning**: The data is cleaned and prepared for analysis through various operations, including string manipulations, handling missing values, and data validation.

3. **Data Visualization**: Users can choose a specific health metric for analysis. The project automatically generates visualizations, such as bar charts or line graphs, for all hospitals, making it easy to compare and assess the performance of each hospital.

4. **Automation and Saving**: Once the visualizations are generated, the project automatically saves the results to a specified file path, ensuring that the reports are readily available for further analysis or reporting.

This automation drastically reduces the manual effort and time required to create reports for multiple hospitals. It ensures consistency and accuracy in the reporting process.

## Usage

To use this project, follow these steps:

1. Clone the repository to your local machine.

2. Install the required dependencies, which include pandas and seaborn:

   ```bash
   pip install pandas seaborn
   ```

3. Open the Jupyter Notebook containing the automation script and adjust to your data needs.

4. The script will automatically generate and save visualizations in the specified file path.

5. Customize the script as needed for your specific use case by modifying the data loading, cleaning, and visualization processes.
