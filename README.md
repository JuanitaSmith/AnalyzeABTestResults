## Data Analysis Nanodegree

---
## Project 3: Analyze A/B Test Results
#### Created by: Juanita Smith
#### Last date: 7 November 2022

---



## Analyze A/B Test Results

<img src="images/img.png" alt="drawing" width="300"/>



## Project Overview

This project was completed as part of the 'Data Analyst' nanodegree with Udacity. 

A/B tests are very commonly performed by data analysts and data scientists.
For this project, you will be working to understand the results of an A/B test run by an e-commerce website. 
The company has developed a new web page in order to try and increase the number of users who "convert," meaning the number of users who decide to pay for the company's product. 
Your goal is to work through this notebook to help the company understand if they should implement this new page, keep the old page, or perhaps run the experiment longer to make their decision.

The data and the Jupyter Notebook template, were provided by Udacity. 
   

## Data

- Data were supplied by Udacity. Below is a description of the data provided:

<center>

|Data columns|Purpose|Valid values|
| ------------- |:-------------| -----:|
|user_id|Unique ID|Int64 values|
|timestamp|Time stamp when the user visited the webpage|-|
|group|In the current A/B experiment, the users are categorized into two broad groups. <br>The `control` group users are expected to be served with `old_page`; and `treatment` group users are matched with the `new_page`. <br>However, **some inaccurate rows** are present in the initial data, such as a `control` group user is matched with a `new_page`. |`['control', 'treatment']`|
|landing_page|It denotes whether the user visited the old or new webpage.|`['old_page', 'new_page']`|
|converted|It denotes whether the user decided to pay for the company's product. Here, `1` means yes, the user bought the product.|`[0, 1]`|
</center>


## Requirements
- Python 3 (Python 3.9 interpreter was used)
- Libraries needed:
    - pandas==1.4.4
    - numpy==1.21.5
    - matplotlib==3.5.2
    - jupyter notebook=1.0.0
    - nb_conda=2.2.1
    - statmodels=0.13.2
    - scipy=1.7.3


## Installation

To clone the repository: 'https://github.com/JuanitaSmith/AnalyzeABTestResults.git'


## Resources used:

- [How to find critical Z value (Z alpha)] (https://www.youtube.com/watch?v=BVMHQWZgGF4)
- [How to interpret p_value](https://knowledge.udacity.com/questions/919986)
- An introduction to Statistics with Python by Thomas Haslwanter
- Analyze_ab_test_results_notebook](https://knowledge.udacity.com/questions/669807)
- Example 9.1.2 on this [page](https://stats.libretexts.org/Bookshelves/Introductory_Statistics/Book%3A_Introductory_Statistics_(Shafer_and_Zhang)/09%3A_Two-Sample_Problems/9.01%3A_Comparison_of_Two_Population_Means-_Large_Independent_Samples), courtesy www.stats.libretexts.org
