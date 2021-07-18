# Table of Contents

1. [Overview](#overview)
2. [Installation](#installation)
3. [Project Motivation](#motivation)
4. [File Descriptions](#files)
5. [Results](#results)
6. [Licensing, Authors, and Acknowledgements](#licensing)


---

# Overview <a name="overview"></a>

The CRISP-DM methodology is applied in order to extract relevant information from the work performed by the Maintenance and Repair (M&R) division in SGS Chile, one of the world's leading inspection, verification, testing and certification company, which is present in this South American country.

# Installation <a name="installation"></a>

This project uses Python 3.7.1, along with Jupyter Notebook. The following libraries are necessary for running the notebook:
- re 2.2.1
- pickle 4.0
- datetime 4.3
- spacy 3.0.3
- python -m spacy download es_core_news_lg
- numpy 1.20.2
- pandas 1.2.4
- gensim 4.0.1
- pyLDAvis 3.3.1
- matplotlib 3.0.2
- seaborn 0.10.1
- wordcloud 1.8.1

# Project Motivation <a name="motivation"></a>

For this project, I was interested in exploring a real business dataset according to my field (Industrial Engineering) where I could apply the insights from my Udacity Data Scientist Nanodegree Program and extract meaningful information. To get a better understand about the business I will be following the next questions:

1. What are the periods when M&R receives the most number of work orders (OT)? Is there a peak? Any pattern or tendency?
2. How long does it take to the M&R area to  attend the requests? and how much time does a worker spend fixing the issues?
3. What are the most common type of failures or issues that require attention? Are they representative according to the business?

The data we will be working with is in Spanish since the company is from Chile, but the results and all the description will be in English. 

# File Descriptions <a name="files"></a>

The repository is divided in three folders.

- **data**: It contains the `List_Report_Gestion_30082019061320.xls` data set, which has the detail of the maintenance and repair work orders (OT) done by the M&R area from July 2018 to August 2019. The data is two years old due to company policies when publishing results in blogs and repositories such as this one. This folder also contains the `Data_Schema.xls` that basically explain each of the columns and it has a proper translation. There are more files but they derive as a result of the notebook.
- **images**: Multiple figures that are generated from the notebook and diagrams that help to complement the information
- **notebook**: Basically is the core of the project. It contains the `Insights from a real business case in Chile - CRISP DM methodology.ipynb` notebook that allows to anwswer the three business questions from above.


# Results <a name="results"></a>

All the results are included in the notebook. Nevertheless, the main findings of the code can be found at the post available here.


# Licensing, Authors, Acknowledgements <a name="licensing"></a>

All data here belongs to [SGS Chile](https://www.sgs.cl/). It is absolutely forbidden to use this information for commercial purposes, only for educational purposes.
The data is two years old due to company policies
