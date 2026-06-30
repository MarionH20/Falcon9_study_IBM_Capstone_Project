## Falcon 9 Study IBM capstone Project, Short description

Target of the study is to predict whether the Falcon 9 first stage will land successfully. <br>
The study is performed on JupyterLite using Python programming. <br>
Data collection of Falcon 9 launches between 2010 and 2020 was performed via SpaceX AI and Webscraping of the Falcon 9 wikipedia page. <br>

### Table of Contents

├── Falcon9_study_IBM_Capstone_Project/ <br>
│   ├── 1_jupyter-labs-spacex-data-collection-api.ipynb <br>
│   ├── 2_jupyter-labs-webscraping.ipynb: Webscraping notebook <br>​
│   ├── 3_labs-jupyter-spacex-Data wrangling.ipynb: Data wrangling notebook <br>
│   ├── 4_jupyter-labs-eda-sql-coursera_sqllite.ipynb: EDA - SQL querries notebookb <br>
│   ├── 5_edadataviz.ipynb: EDA - visualization notebook​ <br>
│   ├── 6_lab_jupyter_launch_site_location.ipynb: Folium interactive visualization notebook <br>
│   ├── 7_SpaceX_Machine Learning Prediction_Part_5.ipynb: model development notebook <br>
│   └── 08_predictive_modeling.ipynb8_Dashboard_PlotlyDash.ipynb: PlotlyDash interactive visualization notebo <br>
│   └── Falcon9_final_report.pdf <br>
│   └── README.md <br>


### Project Overview

SpaceX reuses the first stage to reduce costs, so predicting a successful landing is crucial, for instance for its competitors.<br>
This is the final project of the IBM Data Science Professional Certificate.

### Data
The data comes from SpaceX API and Wikipedia web scraping of the Falcon 9 article.

### Methodology

#### Steps: 
Data collection via API request and Webscraping,<br>
Data wrangling, <br>
EDA (exploration) and visualization (matplotlib, Folium, plotly/dash),<br>
Modeling (logistic regression, SVM, decision tree, KNN) and evaluation (accuracy, confusion matrix, classification report)<br>

### Results / Key Findings

The KNN classification model shows the best overall performance and an accuracy of 0.83, meaning 15 launches predicted correctly over 18.<br>​
Considering the precision metric, with the target to limit as much as possible the false positive, the decision tree is the best model. <br>
Precision: 0.82, meaning only 2 landings were predicted wrongly successful. <br>​
To improve the reliability of the models and the prediction, it should be considered to increase the volume of available data.<br>​​
There is no feature with a predominant influence on the target variable. Instead, multiple features with complex relationships have a moderate influence on the target variable. <br>​​​
To further improve the model, other tuning option could be tested, like the lasso regression for logistic regression. 
Another possibility is to get an understanding of the feature roles and refine further their selection.<br>​​
For further details refer to the final report Falcon9_final_report.pdf

### How to Run
Clone the repository, and open notebooks in Jupyter.

### Tools & Libraries
Python, pandas, numpy, scikit-learn, matplotlib/seaborn, folium, plotly/dash, BeautifulSoup, SQL.

### Acknowledgments

Project's context is the IBM Data Science Professional Certificate/ Course 10/12: Applied Data Science Capstone on Coursera.

### Author / Contact

Marion Houliere<br>
www.linkedin.com/in/marionhouliere
