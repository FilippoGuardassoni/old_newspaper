![](https://github.com/pragyy/datascience-readme-template/blob/main/Headerheader.jpg)

# Frequent Pattern Mining of Old Newspaper using Apriori Algorithm

![GitHub release (latest by date including pre-releases)](https://img.shields.io/github/v/release/pragyy/datascience-readme-template?include_prereleases)
![GitHub last commit](https://img.shields.io/github/last-commit/FilippoGuardassoni/old_newspaper)
![GitHub pull requests](https://img.shields.io/github/issues-pr/FilippoGuardassoni/old_newspaper)
![GitHub](https://img.shields.io/github/license/FilippoGuardassoni/old_newspaper)
![contributors](https://img.shields.io/github/contributors/FilippoGuardassoni/old_newspaper) 
![codesize](https://img.shields.io/github/languages/code-size/FilippoGuardassoni/old_newspaper)

# Project Overview

Frequent Itemset Mining (FIM) is one of popular data mining technique with frequent pattern or itemset as representation of data. In other words, it is used to extract knowledge from a variety of datasets and applications. The main downsize of the process is that it is data and computing intensive. In fact, big data are the center of many realities now and growing exponentially: every day we create around 2.5 quintillion bytes. On the other hand, the chose algorithm must scan the dataset iteratively for many times to produce meaningful information. During the recent years, several efficient and scalable frequent itemset mining algorithms for big data analytics have been proposed by many researchers along with the rise of parallel and distributed computing to achieve higher efficiency. In this study, the Apriori and FP-Growth algorithms are chosen to analyze the Old Newspaper dataset composed of 16,806,041 records. After filtering and pre-processing the dataset, the algorithms are implemented in the Apache Spark framework. In particular, FP-Growth is implemented using MLlib, the Spark scalable machine learning library with tools that make practical ML scalable and easy. Apriori is not supported directly by Spark, and thus computed “manually” through various steps. In conclusion, FP-Growth reached a solution within reasonable time. On the other hand, Apriori revealed to be not efficient enough for large scale computation as a small subset was selected to be analyzed in order to prevent crashes.

# Installation and Setup

In this section, provide detailed instructions on how to set up the project on a local machine. This includes any necessary dependencies, software requirements, and installation steps. Make sure to include clear and concise instructions so that others can easily replicate your setup.

I like to structure it as below - 
## Codes and Resources Used
In this section I give user the necessary information about the software requirements.
- **Editor Used:**  Informing the user of the editor used to produce the project.
- **Python Version:** Informing the user of the version of python used for this project. If you are using some other language such as R, you can mention that as well.

## Python Packages Used
In this section, I include all the necessary dependencies needed to reproduce the project, so that the reader can install them before replicating the project. I categorize the long list of packages used as - 
- **General Purpose:** General purpose packages like `urllib, os, request`, and many more.
- **Data Manipulation:** Packages used for handling and importing dataset such as `pandas, numpy` and others.
- **Data Visualization:** Include packages which were used to plot graphs in the analysis or for understanding the ML modelling such as `seaborn, matplotlib` and others.
- **Machine Learning:** This includes packages that were used to generate the ML model such as `scikit, tensorflow`, etc.

The level of granularity you want to provide for the above list is entirely up to you. You can also add a few more levels, such as those for statistical analysis or data preparation, or you can simply incorporate them into the above list as is.

# Data

The very crucial part of any data science project is dataset. Therefore list all the data sources used in the project, including links to the original data, descriptions of the data, and any pre-processing steps that were taken.

I structure this as follows - 

## Source Data
In this section, I list all of the data that was used, along with the source link and a few lines that describe each data. You can also explain each of the data attributes in greater detail if you wish.

## Data Acquisition
Data collection is not always as simple as downloading from Kaggle or any open source website; it can also be gathered through API calls or online scraping. So you can elaborate on this step in this section so that the reader can obtain the dataset by following your instructions.

## Data Preprocessing
Acquired data is not always squeaky clean, so preprocessing them are an integral part of any data analysis. In this section you can talk about the same.

# Code structure
Explain the code structure and how it is organized, including any significant files and their purposes. This will help others understand how to navigate your project and find specific components. 

Here is the basic suggested skeleton for your data science repo (you can structure your repository as needed ):

```bash
├── data
│   ├── data1.csv
│   ├── data2.csv
│   ├── cleanedData
│   │   ├── cleaneddata1.csv
|   |   └── cleaneddata2.csv
├── data_acquisition.py
├── data_preprocessing.ipynb
├── data_analysis.ipynb
├── data_modelling.ipynb
├── Img
│   ├── img1.png
│   ├── Headerheader.jpg
├── LICENSE
├── README.md
└── .gitignore
```

# Results and evaluation
Provide an overview of the results of your project, including any relevant metrics and graphs. Include explanations of any evaluation methodologies and how they were used to assess the quality of the model. You can also make it appealing by including any pictures of your analysis or visualizations.

# Future work
Outline potential future work that can be done to extend the project or improve its functionality. This will help others understand the scope of your project and identify areas where they can contribute.

# Acknowledgments/References
Acknowledge any contributors, data sources, or other relevant parties who have contributed to the project. This is an excellent way to show your appreciation for those who have helped you along the way.

For instance, I am referencing the image that I used for my readme header - 
- Image by [rashadashurov](https://www.vectorstock.com/royalty-free-vector/data-science-cartoon-template-with-flat-elements-vector-27984292)

# License
Specify the license under which your code is released. Moreover, provide the licenses associated with the dataset you are using. This is important for others to know if they want to use or contribute to your project. 

For this github repository, the License used is [MIT License](https://opensource.org/license/mit/).
