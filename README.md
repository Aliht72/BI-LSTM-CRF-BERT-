# README

This README file provides an overview of the project and its objectives. It outlines the challenges in extracting information from building regulation codes and proposes a deep neural network-based approach to address these challenges. The project focuses on applying Named Entity Recognition (NER) techniques to UK building regulations in order to extract semantic and syntactic information.

## Introduction

The Building Regulations establish standards for constructing buildings, including requirements for insulation. However, complying with these regulations and confirming conditions can be time-consuming and lead to ambiguous outcomes. This project aims to automate the process by using NER and Information Extraction (IE) techniques.

Identifying named entities is crucial for various natural language processing tasks such as question answering, machine translation, and information extraction. Manual and semi-automated approaches using predefined rules or annotations have limitations in terms of flexibility and scalability. Therefore, this project proposes a deep neural network-based approach for IE and NER in building regulation rules.

## Methodology

The project employs the BiLSTM-CRF and Transformer learning strategies for training on both general and regulation building annotated data. However, due to the lack of annotated data in the target domain, the paper suggests providing annotated data using the transformer's learning strategy.

The methodology involves data preprocessing, including data cleansing, sentence segmentation, and tokenization. The dataset is annotated using the beginning, inside, and outside (BIO) labeling scheme to indicate the location of information elements. The annotated dataset is then used for training and testing the deep learning models.

## Results

The deep learning models are evaluated using precision, recall, and F1 measure metrics. The results are calculated based on Micro and Macro averages, with Micro averaging recommended for handling class imbalance.

The project provides hyperparameters for both the BiLSTM-CRF and BERT models used in the experiments. The BiLSTM-CRF model uses TensorFlow and Keras, while the BERT model utilizes the Transformers library.

## Conclusion

In conclusion, this project aims to automate the extraction of semantic and syntactic information from UK building regulations using NER techniques and deep neural networks. The proposed methods show promising results in extracting information from building regulation codes. The README also provides important information about the dataset, hyperparameters, and evaluation metrics used in the project.

Please refer to the full report for a detailed description of the project, including previous research, preprocessing methods, model architectures, and evaluation results.
