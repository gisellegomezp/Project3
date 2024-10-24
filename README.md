
# Sentiment Analysis of Amazon Appliance Reviews

## Project Overview

This project is a part of our AI and Machine Learning bootcamp final project, aimed at performing sentiment analysis on customer reviews from the Amazon Appliance dataset. Our goal is to build machine learning models that analyze customer feedback and provide insights into consistently positive or negative reviewers, ultimately assisting in understanding brand perception.

## Table of Contents

- [Problem Statement](#problem-statement)
- [Data](#data)
- [Models and Techniques](#models-and-techniques)
- [Evaluation Metrics](#evaluation-metrics)
- [Results](#results)
- [Future Development](#future-development)
- [Installation](#installation)
- [Contributors](#contributors)


## Problem Statement

With the increasing number of customer reviews online, it becomes critical for companies to understand sentiment behind product feedback to improve services and customer experience. This project focuses on using sentiment analysis to evaluate customer feedback on appliances, specifically identifying reviews that are consistently positive or negative, to provide insights into product and brand performance.

## Data

We used a subset of Amazon reviews focusing on the appliance category. The dataset was processed and stored as Parquet files for efficient management, given its large size. Basic cleaning, transformation, and exploration steps were performed to prepare the data for model training.

### Data Source

- Amazon Appliance Reviews Dataset (2023)
- Parquet files are used to handle the large volume of data

## Models and Techniques

The following machine learning and natural language processing models were explored in this project:

1. **VADER Sentiment Analysis**: A lexicon and rule-based sentiment analysis tool.
2. **RoBERTa Transformer Model**: A transformer-based model fine-tuned for sentiment analysis tasks.
3. **TF-IDF**: A traditional term frequency-inverse document frequency model.
4. **Doc2Vec/Word2Vec**: Tools for capturing semantic relationships between words in the reviews.
5. **Polar**: Used for data management during exploration.

We are also incorporating the **VADER** library, which was not covered in the class, to deepen our analysis.

## Evaluation Metrics

The performance of the models is evaluated based on the following metrics:
- **Accuracy**
- **Precision**
- **Recall**
- **F1 Score**

## Results

Initial results indicate that sentiment analysis can provide valuable insights into customer reviews. We are comparing multiple models to identify the best approach for analyzing customer sentiment. We are still in the process of expanding our results with additional graphs and performance metrics.

## Future Development

In the future, we aim to expand the scope of our project by:
- Identifying consistently positive or negative reviewers.
- Linking product reviews to brands to assess overall brand sentiment.
- Using external tools like UPC_Index.com to enhance our analysis.

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
2. Install the required libraries:
3. Run the Jupyter notebook for data exploration and model training:
4. The project also includes a script for model training that can be run with:

## Contributors

- **Mike Saunders**
- **Lonnie Aldregde**
- **Giselle Gomez**

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
