# Augmentation_and_feature_weighting
This project focuses on two key aspects of natural language processing (NLP): Text Augmentation and Text Feature Weighting, specifically in the context of medical transcripts.
1. Text Augmentation
The goal of this module is to enhance the diversity of text data using various augmentation techniques. The implemented methods include:

Synonym Replacement: Replacing words with their synonyms using WordNet.
Random Insertion: Inserting random words into the text.
Random Deletion: Removing words with a certain probability.
These techniques help generate more training samples, improving the robustness of NLP models.

2. Text Feature Weighting
This module focuses on representing textual data in numerical form for machine learning models. It includes:

Term Frequency (TF) Representation: Uses CountVectorizer to convert text into a frequency matrix.
TF-IDF (Term Frequency-Inverse Document Frequency): Computes word importance based on its occurrence across multiple texts.
Binary Encoding: Converts text into a binary matrix representation.
These methods are essential for feature extraction in NLP tasks like classification and clustering.

Applications
Enhancing NLP models for medical data analysis.
Improving text classification performance by balancing dataset variations.
Extracting relevant textual features for downstream ML tasks.
