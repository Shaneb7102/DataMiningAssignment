# Spotify Tracks Dataset - Predictive Analytics Project

## Project Overview
This project involves using an excerpt from the Spotify dataset to perform predictive analytics, including exploratory data analysis (EDA), clustering, and classification. The dataset used is available at [Spotify Dataset on Hugging Face](https://huggingface.co/datasets/maharshipandya/spotify-tracks-dataset).

## Team Information
The names and IDs of the students in your project group, which parts of the project each student has worked on, and what percentage of the whole work on the project is their contribution. If you submit multiple notebooks, include this information in all notebooks. If the percentage of work done by each student is not specified, it will be assumed that all team members contributed equally to the project.

## Tasks

### 1. Exploratory Data Analysis (EDA)
Exploratory data analysis: Perform exploratory data analysis of the dataset. Comment on your observations.

### 2. Clustering
Clustering: Construct and train clustering pipelines for k-means and DBSCAN. When clustering drop the column track_genre. For k-means find the best value of k. Visualise the clusterings and discuss their usefulness for a better understanding of the underlying patterns in the dataset.

### 3. Classification
Classification: Let m be the median of column popularity. Replace column popularity with a binary column popularity_binary with two values: 0 for popularity ≤ m and 1 for popularity > m. Attempt at least three different classification algorithms for training models that can be used for predicting the value of popularity_binary. Construct a pipeline for each of the algorithms you have chosen. Evaluate the trained models and select the best model. Explain your choice in a markdown cell. Aim at training a model that is as good as possible. In this process, you may attempt various data preparation and possibly dimensionality reduction strategies.
## Submission
- **Deadline:** Sunday, 27th of April, 23:55
- Submit Jupyter Notebooks on **Brightspace**.

## Marking Scheme
| Section      | Criteria for Higher Marks | Marks |
|-------------|--------------------------|-------|
| **EDA** | Utilize various plotting techniques, provide insights, and draw conclusions. | 8 |
| **Clustering** | Fine-tune parameters, use grid search, and describe clusters. | 9 |
| **Classification** | Fine-tune parameters and optimize models with grid search. | 8 |


