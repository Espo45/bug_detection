## List of scripts

### 1. <a href='1_loading_data.ipynb'>Loading data</a>

**Description**: a script that loads the files put into `../data` and put it into a dictionary, called `datasets`, that contains all the 9 datasets that will be used in the analysis; it also creates an alias for every dataset


### 2. <a href='2_eda.ipynb'>EDA</a>

**Description**: explorative data analysis on the rough dataset


### 3. <a href='3_data_manipulation.ipynb'>Data manipulation</a>

**Description**: data manipulation process on the rough dataset, including transformation of defects into dichotomous and splitting of datasets into train and test sets


### 4. <a href='4_analysis.ipynb'>Analysis</a>

**Description**: application of the seven state-of-the-art machine learning classifiers to each datasets; building of an optimized XG-Boost model; computation of AUC and F1 scores


### 5. <a href='5_results.ipynb'>Results</a>

**Description**: comparison between the scores of the different models; computation of SHAP values on XG-Boost models; individuation of relevant features