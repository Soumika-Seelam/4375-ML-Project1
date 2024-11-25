# 4375-ML-Project1

## Project

### Introduction
Our study leverages the UCEC RNA-Seq dataset to estimate gene expression levels using a Deep Neural Network (DNN). Because DNNs can handle complicated data with non-linear connections, they are perfect for this purpose. To increase effectiveness and precision, we standardized the dataset's dimensionality. With a test set Mean Absolute Error (MAE) of 0.306, Mean Squared Error (MSE) of 0.153, and R-Squared Score of 0.698, the first findings show the model's potential. Our approach, findings, possible uses, and recommendations for more research will all be covered in this paper. 

### Purpose
In molecular biology and computational genomics, predicting gene expression levels is essential because it can facilitate improvements in disease diagnosis, prognosis, and treatment. Understanding gene expression in a condition like Uterine Corpus Endometrial Carcinoma  (UCEC) can help create customized therapy, uncover possible treatment targets, and offer insights into the molecular basis of the disease. Predicting gene expression accurately is not just a computational problem but also an essential first step in unraveling the intricacies of UCEC.

The goal of this project is to use the TCGA Pan-Cancer Atlas dataset to estimate normalized RNA-Seq gene expression levels for the UCEC cancer subtype. Our goal is to use Python's ability to describe complex relationships and scale effectively to big datasets to create a DNN from scratch.

### Dataset
STAR-TPM dataset (~60,000 genes, 586 samples, and normalized RNA-Seq expression data)

The normalized RNA-Seq expression data in the STAR-TPM dataset includes measurements of almost 60,000 genes in 586 samples. Transcriptomic profiles are captured in this dataset using TPM normalization which accounts for gene length and sequencing depth to ensure comparability between genes and samples.

### Data Processing
- Z-score normalization
- PCA for dimensionality reduction


## Before Running
### Disclaimers
- Python 3.8+
- No need to upload dataset, hosted on Box
- !wget, !gunzip commands are Colab specific, can remove those two lines if not using Google Colab
- certain features are dropped during preprocessing. If you would like to modify the dataset, update problematic_features
- cells should be run sequentially in order to avoid errors

## How to Run
1. Execute Data Processing Cell (say yes "do you wish to overwrite (y or n)?")
2. Run all of the cells in sequential order
3. At the bottom of the 'Run Experiment' section, you can change the parameters to carry out different experiments.
4. Can view all history of experiments in the log at the very bottom of the program
5. Can reference log to see 
