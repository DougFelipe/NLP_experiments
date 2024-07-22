# Data Science and NLP Project 

## Project Description
This repository contains a project focused on analyzing privacy policies from various companies and sectors using unsupervised learning methodologies and natural language processing (NLP). The primary objective is to extract and process data from these documents to automatically categorize new privacy policy texts.

## Repository Structure
- `Projeto_Data_Science_and_NLP.ipynb`: Notebook containing the complete implementation of the project, including preprocessing, exploratory analysis, vectorization, similarity calculation, and clustering.
- `README.md`: This file, providing the description and instructions for the experiments.

## Objective
The experiments aim to evaluate how different unsupervised learning methodologies can be applied to analyze and categorize privacy policies, identifying patterns and similarities among the documents.

## Running the Project on Google Colab
The scripts are designed to be run on Google Colab, where all necessary dependencies are installed automatically. Simply open the `Projeto_Data_Science_and_NLP.ipynb` notebook on Google Colab and execute the cells.

### Step-by-Step Instructions for Execution on Google Colab
1. Open the `Projeto_Data_Science_and_NLP.ipynb` notebook on Google Colab.
2. Execute all the cells sequentially to load the data, perform preprocessing, and conduct the analyses.
3. During execution, you will need to authenticate your Google Drive account to access the PDF privacy policies stored in the Drive.

## Preprocessing
Preprocessing involves several steps to prepare the texts for analysis:
- **Reading and Extracting Text from PDFs:** The PDF documents are downloaded from Google Drive, and the text is extracted and stored in a list.
- **Tokenization:** The extracted text is split into tokens (individual words).
- **Normalization:** Tokens are converted to lowercase and filtered to remove non-alphabetic or very short tokens.
- **Stop Words Removal:** Common and irrelevant words (stop words) are removed from the tokens.

## Exploratory Analysis
- **Word Count:** Generation of graphs for the 50 most frequent words in the processed texts.
- **N-Gram Analysis:** Generation of bigrams and trigrams to analyze the most frequent word combinations.

## Text Representation and Similarity
- **TF-IDF:** Processed texts are vectorized using TF-IDF to represent word importance.
- **Cosine Similarity:** Similarity between documents is calculated using the cosine similarity metric, and a similarity matrix is plotted.

## Clustering and Group Analysis
- **Hierarchical Clustering:** A dendrogram is generated to visualize the similarity hierarchy among the documents.
- **K-Means Clustering:** Texts are grouped into clusters using K-Means. The optimal number of clusters is determined by inertia analysis.
- **Cluster Similarity and Token Analysis:** Similarity between documents within each cluster is analyzed, and the most frequent words in each cluster are plotted.

