# AutoML with AWS

Welcome to my GitHub repository, where I've documented my journey through a series of labs focused on implementing AutoML (Automated Machine Learning) using AWS (Amazon Web Services) for various natural language processing (NLP) tasks. These labs are designed to help me work with AWS services and tools for data preparation, model training, and bias analysis.

## Lab 1: Register and Visualize Dataset

### Introduction

In this first lab, I started by ingesting and transforming a customer product reviews dataset. I leveraged AWS data stack services, including AWS Glue and Amazon Athena, for data ingestion and querying. Additionally, I used AWS Data Wrangler to analyze the dataset and generate insightful visualizations.

## Lab 2: Detect Data Bias with Amazon SageMaker Clarify

### Introduction

Bias in data can significantly impact machine learning models. In this lab, I focused on detecting and understanding data bias before model training. I analyzed the dataset for bias, generated a bias report, and prepared the dataset for subsequent model training. This step is crucial for fairness and accuracy in machine learning.

## Lab 3: Train a Model with Amazon SageMaker Autopilot

### Introduction

In my third lab, I utilized Amazon SageMaker Autopilot to train a natural language processing (NLP) model based on BERT. The model's primary objective was to analyze customer feedback and classify messages into three sentiment categories: positive, neutral, and negative. SageMaker Autopilot streamlined the model training process, making it efficient and effective.

## Lab 4: Train a Text Classifier using Amazon SageMaker BlazingText

### Introduction

In my final lab, I employed the SageMaker BlazingText built-in algorithm to build a text classifier. My goal was to predict the sentiment of each customer review. BlazingText, a variant of FastText, was chosen for its word2vec-based capabilities, which enhance the quality of text classification. For more detailed information on BlazingText, refer to the [official documentation](https://docs.aws.amazon.com/sagemaker/latest/dg/blazingtext.html).

---

I hope you find this documentation useful for your AutoML project on AWS! Feel free to use it as a template for your repository and customize it further to provide additional details about each lab and how they can be executed.