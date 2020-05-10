# STAT564 Project 3

## Abstract

COVID-19 data is used in many types of research up to now. Our COVID-19 data source is the EU Open Data portal. It is combined with the Google mobility data and the World Bank classification data based on Gross Domestic Product (GDP). The goal of this project is classifying countries based on their GDP classes while exploring the societal impacts of the COVID-19 with supervised machine learning algorithms such as K-Nearest Neighbor, Decision Tree, Logistic Regression, Support Vector Machine, and Gaussian Naive Bayes and then developing an interactive dashboard for the most accurate algorithm. The data is re-arranged; the mobility data and COVID-19 data are merged based on countries. The GDP data is used as the country label and five different algorithms are performed on the training and test dataset, which is split as 0.8 and 0.2 of the whole dataset, respectively. The results show that the best accuracy is belonging to the K-Nearest Neighbor (KNN) algorithm, which is 0.84. The dashboard is developed depend on KNN algorithm and it enables to observe different results by changing indicators and parameters used in the figures. It has six different graphs showing in different tabs. The first tab includes two figures for data exploration, and the second tab is for displaying the selection of K - value importance with two graphs. Furthermore, the third and fourth tabs include a KNN graph and two confusion matrices.





## References


COVID-19 Community Mobility Report. (2020). COVID-19 Community Mobility Report. https://www.google.com/covid19/mobility?hl=en

COVID-19 Coronavirus data—COVID-19 cases worldwide—Ecodp.common.ckan.site_title. (2020). https://data.europa.eu/euodp/en/data/dataset/covid-19-coronavirus-data/resource/55e8f966-d5c8-438e-85bc-c7a5a26f4863

GDP (current US$) | Data. (2018). The World Bank. https://data.worldbank.org/indicator/NY.GDP.MKTP.CD?most_recent_value_desc=true

Gilbert, T. (2019). TannerGilbert/Tutorials. GitHub. https://github.com/TannerGilbert/Tutorials

How does the World Bank classify countries? – World Bank Data Help Desk. (2020). The World Bank. https://datahelpdesk.worldbank.org/knowledgebase/articles/378834-how-does-the-world-bank-classify-countries

ipywidgets—Jupyter Widgets 7.5.1 documentation. (n.d.). Retrieved May 6, 2020, from https://ipywidgets.readthedocs.io/en/latest/index.html

K nearest neighbors. (n.d.). Pythonspot. Retrieved May 3, 2020, from https://pythonspot.com/k-nearest-neighbors/

K-Nearest Neighbors Algorithm in Python and Scikit-Learn. (n.d.). Stack Abuse. Retrieved May 3, 2020, from https://stackabuse.com/k-nearest-neighbors-algorithm-in-python-and-scikit-learn/

Lau, S. (n.d.). nbinteract: Generate Interactive Web Pages From Jupyter Notebooks. 12.

Matplotlib: Python plotting—Matplotlib 3.2.1 documentation. (n.d.). Retrieved May 3, 2020, from https://matplotlib.org/index.html

python—Why is cross_val_score substantially lower than .score or roc_auc_score? (2019). Cross Validated. https://stats.stackexchange.com/questions/392115/why-is-cross-val-score-substantially-lower-than-score-or-roc-auc-score

Scikit-learn: Machine learning in Python—Scikit-learn 0.22.2 documentation. (2020). https://scikit-learn.org/stable/index.html

sklearn.metrics.plot_confusion_matrix—Scikit-learn 0.22.2 documentation. (n.d.). Retrieved May 3, 2020, from https://scikit-learn.org/stable/modules/generated/sklearn.metrics.plot_confusion_matrix.html#sklearn.metrics.plot_confusion_matrix

