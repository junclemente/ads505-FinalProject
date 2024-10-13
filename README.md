# ads505-FinalProject

# Installation

To set up and run this project, please follow these steps: 

1. Clone the repository
2. Navigate to the project directory 
3. Create a virtual environment using conda. The environment used for this project can be found in the `environment` folder. 
4. Activate the virtual environment.
5. Launch the Jupyter Notebook to run the analysis. 

# Project Intro / Objective

A newly established business school is exploring whether a data-driven approach to their admissions process can be more effective that their current method of using intuition. By adopting a data-driven strategy, the school hope to uncover patterns in student admissions that can improve decision-making and lead to better post-graduation outcomes, such as higher job placement rates. 

The school has provided data from its first graduating class, including information on undergraduate degrees, MBA performance, work experience, and employment status two months after graduation. The objective of this project is to identify key factors that strongly correlate with post-graduation employment. These insights could be used to refine the admissions process, allowing the school to admit candidates with a higher likelihood of success, resulting in better graduation rates and job placement outcomes. 

A data-drive approach has the potential to improve the efficiency of the admissions process but also positions the school as a forward-thinking and prestigious institution. The ultimate goal is to ensure continuing success for future graduates and to enhance the school's reputation as a trusted destination for aspiring MBA candidates.  

# Contributors

- [Jun Clemente](https://github.com/junclemente)

# Methods Used

- Data Cleaning and Preprocessing
- Exploratory Data Analysis (EDA)
    - Univariate Analysis
    - Bivariate Analysis
- Predictive Modeling
    - Decision Tree
    - K-Nearest Neighbor
    - Logistic Regression
- Hyperparameter Tuning
    - RandomizedSearchCV
    - GridSearchCV
- Model Evaluation
    - Classification Reports
        - Accuracy
        - Recall
        - Precision 
        - F1
    - k-Fold Cross Validation
    - AUC-ROC 

# Technologies

- Python
- Pandas
- NumPy
- Matplotlib/Seaborn
- Sckit-learn
- Scipy
- Statsmodels
- Jupyter Notebooks
- Kaggle
- Github
- Conda

# Project Description 

This project aims to determine if there are identifiable factors that can predict job placement success for MBA graduates. By analyzing data provided on the business school's first graduating class, the project will determine key indicators that correlate with job placement within two months of graduation. 

## Data Dictionary

- Student ID: a unique identifier for each business school student.
- Undergrad Degree: The student's undergraduate degree.
- Undergrad Grade: The student's final grade average from their undergrad degree (0-100).
- MBA Grade: The student's final grade average from our master's degree program (0-100).
- Work Experience: Indicator of the student's work experience prior to the program (Yes/No).
- Employability (before): The student's score from a third-party test that measures their appeal to employers in selected industries, taken during the admission process (0-500).
- Employability (after): The student score from the same test, taken after obtaining their Master's.
- Status: Indicator of the student's employment status (Placed/Not Placed).

# License

MIT License

Copyright (c) 2024 Jun Clemente

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

# Acknowledgements

- Graduate Business School Dataset. (n.d.). Retrieved September 26, 2024, from https://www.kaggle.com/datasets/oluwatosinamosu/graduate-business-school-dataset
- Junclemente/ads505-FinalProject. (n.d.). Retrieved September 26, 2024, from https://github.com/junclemente/ads505-FinalProject




