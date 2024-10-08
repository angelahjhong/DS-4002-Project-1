## **2020 U.S. Election Tweet Sentiment Analysis**
**DS 4002 Project 1 Group 5**

## Software and Platform 
All code used the [Python](https://www.python.org/downloads/) language on a virtual machine in [Google Colab](https://colab.research.google.com/) 

**Packages Used:**
* Analysis: [VADER](https://pypi.org/project/vaderSentiment/) Python package was used to run sentiment analysis - Documentation on how to install VADER
* EDA & Visualization: [pandas](https://pypi.org/project/pandas/), [numpy](https://pypi.org/project/numpy/), [matplotlib](https://pypi.org/project/matplotlib/), [wordcloud](https://pypi.org/project/wordcloud/), and [seaborn](https://pypi.org/project/seaborn/) 
* Statistics: [scipy.stats](https://docs.scipy.org/doc/scipy/reference/stats.html)
* These links are provided for package documentation

## Documentation 
Our data was pulled from [Kaggle](https://www.kaggle.com/datasets/manchunhui/us-election-2020-tweets/data) - it was too large to upload as a file onto GitHub
* **SCRIPTS folder:** contains "Project1_Part1_SentimentAnalysis.ipynb" and "Project1_Part2_FrequentWords.ipynb" which are notebooks to our sentiment analysis, frequently used words. "Project1_Part3_StatisticalSignificance.ipynb" was created to find and test the statistical significance of our mean sentiment scores for Trump and Biden.
* **DATA folder:** contains "Project_EDA.ipynb" which is a file that instructs the user how to download our data from Kaggle, data cleaning, and EDA. "DataAppenix.pdf" stores our data, figures, and other descriptive statistics.
* **OUTPUTS folder:**  "ResultsAppendix.pdf" stores visualized figures and statistical analysis computed from our study. 
* **REFERENCES folder:** contains "References.pdf" which includes references used throughout this project

## How to Reproduce Results 
**To reproduce these results:**
* First follow to instructions to download the data Biden & Trump - located in our DATA folder under "Project1_EDA.ipynb"
* Run the file titled "Project1_Part1_SentimentAnalysis.ipynb" - located in our SCRIPTS folder, to view sentiment analysis
* Run the file titled "Project1_Part2_FrequentWords.ipynb" - located in our SCRIPTS folder, to view our computed frequent words
* The PDF files titled "DataAppendix.pdf" and "ResultsAppendix.pdf" contain all figures run from our analysis 
