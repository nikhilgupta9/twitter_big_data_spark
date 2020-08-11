# Twitter Big Data Analysis

Project - Twitter Big Data Analysis using Apack Spark on Microsoft Azure

Tools: Azure, Python, Apache Spark, Spacy, NLTK, SQL, TF-IDF, PCA

- Setup a Spark cluster on Azure to process 90 Gb of Twitter text data in JSON format 
- Extracted 96 out of 326 features and performed Exploratory Data Analysis using PySpark and MLlib
- Six degrees of separation verification by visualizing users on a Network Graph
- Misspelled word correction and analysis using Natural Language Processing tool Spacy 
- Topic modelling using Latent Dirichlet Allocation (LDA)
- User cluster visualization through a word cloud using Qlik Sense

## Instructions
* Please start with **readme_main.pdf** for the instructions to run the Jupyter Notebook specific to Spark for the Pre-processing and most of the analysis.

* Please go through **readme_local.md** for the instructions to run the Jupyter Notebook specific to local machine which contains a couple of analytics based on the outputs of previous spark pre-processing.

We had to run it in two separate notebooks because of few limitations we are facing with Microsoft Azure HDInsights.