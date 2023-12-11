# Impact-of-Data-Cleaning-on-Visualizations

This study addresses the challenges associated with data visualizations on dirty data. We examine how different data cleaning approaches and dirty data mode influence the results of visualization recommendations. This project involves a thorough examination of various dirty data patterns, such as missing values, duplicate entries, outliers, and inconsistent data. 

The evaluation can be catogorized into two main parts:
1. Evaluation Metrics:
     - Synthetic Dataset_Metrics.ipynb: This notebook contains the code to load the clean college.csv dataset, manually create dirty datasets, and perform data cleaning to generate cleaned datasets. Evaluation metrics are computed over clean vs. dirty, dirty vs. cleaned, and clean vs. cleaned datasets. The computed metrics are saved in directory ./metrics
     - Airbnb_Metrics.ipynb: This notebook contains the code to load the Airbnb dataset and apply several data cleaning methods to generate cleaned datasets. Evaluation metrics are computed over dirty vs. cleaned datasets. The computed metrics are saved in directory ./metrics_airbnb
     - Summary Figures.ipynb: This notebook load the computed metrics and generate summary figures such as stacked/grouped barcharts and line charts to summarize our findings.
3. User Study:
     - Interview.ipynb: This notebook contains the code that an interviewee would run during an interview.

