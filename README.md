## Data Anonymization: Privacy Threats in US Census Microdata Analysis. 
This repository contains an analysis of the US Census Bureau's microdata from the 2010 census. The current analysis focuses on understanding the privacy threats associated with the non-anonymized dataset and exploring techniques to preserve privacy while analyzing the data.

### Dataset 
The dataset used for this analysis is the microdata from the 2010 census. It provides detailed information about individuals and households in Delaware. The dataset can be downloaded from the following link:
[Delaware Microdata](https://www2.census.gov/census_2010/12-Stateside_PUMS/Delaware/).

### Getting Started
To replicate or explore the analysis conducted in this repository, please follow these steps:

Clone this repository to your local machine.
Navigate to the repository's directory.
Download and decompress the dataset from the provided link and place it in the data/ directory.
Open the notebook using Jupyter or any compatible environment.
Follow the instructions in the notebook to perform the analysis and implement the privacy-preserving techniques.
Feel free to modify the notebook and experiment with different approaches to enhance the analysis and privacy preservation.

### Parts
* Part A: Privacy Threats and Anonymization Techniques
In this exercise, we analyze the dataset and discuss the privacy threats and anonymization techniques. Answer the following questions based on the dataset:

Which attributes can act as quasi-identifiers and why?
Which of the following properties holds for the data: (a) anonymized, (b) pseudonymized, or (c) encrypted? Explain the key differences between these approaches in relation to GDPR.
Explain how a person can be identified.
Define differential privacy and explain the importance of the privacy parameter 'e'.

* Part B: Analysis and Privacy-Preserving Techniques
In this exercise, we load the dataset into a Jupyter recommended and perform various analyses while preserving privacy using differential privacy techniques. Perform the following steps:


Load the dataset into a Python notebook and display the first few rows to understand the data.
Use the Amnesia anonymization tool to apply k-anonymity to the dataset. Comment on the resulting dataset.
Plot the distribution of numeric features in the dataset using histograms.
Apply a random noise mechanism to some of the numeric columns using the Gaussian mechanism. The noise should be added in a way that preserves differential privacy.
Calculate the differentially private averages for the individuals using the noisy data.
Plot the distribution of numeric features after adding the noise. Experiment with different values of the privacy parameter 'e' and comment on the effect of differential privacy on the results.

 
### Contributors

- [x] [Foteini Nefeli Nouskali](https://github.com/FoteiniNefeli)
- [x] [Dimitris Matsanganis](https://github.com/dmatsanganis)


![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
