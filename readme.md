# Project Title: Predicting Potential Customers for a Marketing Campaign Using Machine Learning

### Description
In this study, we aimed to identify potential customers for a marketing campaign by using machine learning techniques on a dataset of demographic and purchasing behavior data. We first preprocessed the data by handling missing values and scaling numerical features, and then applied Random Forest and Gradient Boosting classifiers to predict customer clusters.

We found that the Gradient Boosting classifier had higher accuracy, precision, recall, and F1-score compared to the Random Forest classifier, and identified the top 10 most significant indicators for predicting customer clusters as number of cars in the PLZ8 region, year of birth, and different categories of the CAMEO_DEU_2015 attribute. These findings can help the company target their marketing efforts more effectively and reach their desired audience.

### Dependencies
- **Python 3.x** - A popular programming language for data analysis and scientific computing.
- **scikit-learn** - A software machine learning library for Python that provides various classification, regression, and clustering algorithms including support vector machines, random forests, gradient boosting, k-means, and DBSCAN. It is designed to interoperate with the Python numerical and scientific libraries NumPy and SciPy.
- **pandas** - A library for data manipulation and analysis that provides data structures for efficiently storing large datasets and tools for working with them.
- **numpy** - A library for scientific computing that provides functions for working with large, multi-dimensional arrays and matrices of numerical data.
- **matplotlib** - A low-level library for creating static, animated, and interactive visualizations in Python.
seaborn - A higher-level library built on top of matplotlib that provides a more concise API for creating common types of visualizations.

matplotlib and seaborn are libraries for data visualization. matplotlib is a low-level library for creating static, animated, and interactive visualizations in Python, while seaborn is a higher-level library built on top of matplotlib that provides a more concise API for creating common types of visualizations. These libraries are used in the project to create plots and visualizations of the data and model performance.

### Data Sources
- Udacity_AZDIAS_052018.csv - Demographic data for the general population of Germany; 891211 (rows) x 366 features (columns).
- Udacity_CUSTOMERS_052018.csv - Demographic data for customers of a mail-order company; 191652 (rows) x 369 features (columns).
- Udacity_MAILOUT_052018_TRAIN.csv - Demographics data for individuals who were targets of a marketing campaign; 42982 persons(rows) x 367 columns.
- Udacity_MAILOUT_052018_TEST.csv - Demographics data for individuals who were targets of a marketing campaign; 42833 persons(rows) x 366 columns).

### Instructions for Running Code
1. Clone the repository to your local machine
2. Navigate to the directory where the repository has been cloned
3. Run the Jupyter notebook file "Predicting Potential Customers for a Marketing Campaign.ipynb"

### Author
Tone Pettit

#### UDACITY DATA SCIENCE NANODEGREE PROGRAM
###### Date
2022.12.19
