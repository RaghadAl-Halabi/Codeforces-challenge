<img width="640" alt="photo_2023-06-18_04-20-41" src="https://github.com/RaghadAl-Halabi/Codeforces-challenge/assets/97301483/425b8f9c-90d1-400e-b7a4-0b3d31a25120">

# Codeforces-challenge
This project collects, preprocesses Damascus University students solved problems data on Codeforces and extracts specific features (Features engineering) that might be useful to later on predicting their performance in solving programming problems in the C++ programming language.

# Datasets description:

**1- Problemset_df:**

This dataset contains data about the most 100 solved problems Codeforces users.

**2- friends_problemset_df:**

This dataset contains data about the solved problems by Damascus University from the problems of the previous dataset.

**3- Problems_submission_source_code_50_df:**

This dataset contains data about Damascus University students submissions on 50 problems from the problems of the previous dataset.

_Note: This data needed 4 different computers to be collected faster._


**4- Friends_problems_df:**

The final dataset that contains the following features:

problem name, its class, tutorial code difficulty, general concepts in tutorial code, problem difficulty, problem tags, and its solving times on codeforces as well as, student name, his previous solved problems counts, along with their classes, and the y value which represents his code difficulty

## The used tools:

**Programming language:** Python

**Coding environment:** Jupyter Notebook and Colab

**Libraries:** Numpy, Pandas, html, requests, BeautifulSoup, re
