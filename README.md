# Text Analysis with Machine Learning
<h2>Summary:</h2>
This repository contains the project "Text Analysis with Machine Learning", which focuses on analysing text data using machine learning techniques. For this project, twitter sentiment analysis dataset was selected and explored using a machine learning algorithm. The project includes a comprehensive report and extensive Python code from Jupyter notebooks.

<h2>Project Overview:</h2>

  <li><b>Dataset: The analysis uses the Twitter Sentiment Analysis dataset obtained from Kaggle, which includes a vast collection of tweets discussing various aspects of vaccination.</b></li>
  
  <li><b>Objective: To investigate the incidence and character of negative emotions about vaccinations, such as vaccine hesitation and skepticism, and to identify any racial or discriminatory sentiments in vaccine-related discussions on Twitter.</b></li>
  
  <li><b>Methodology:</b></li>
  - Data Preprocessing: Cleaning and preparing the text data by removing special characters, digits, and links, tokenizing the text, and converting all terms to lowercase.
  - Word2Vec Model Training: Training the Word2Vec model to create dense vector representations of words based on their context in the corpus, aiming to identify semantic connections within the tweets.
  - Visualisation of Word Embeddings: Using t-distributed stochastic neighbor embedding (t-SNE) to visualize the high-dimensional word embeddings in a lower-dimensional space to explore semantic patterns and correlations in the text data.
  - Word Frequency Analysis and Word Cloud Visualization: Due to the initial limitations of the Word2Vec approach, switching to word frequency analysis and word cloud visualization to capture the essence of the discourse.
  
  <b>Findings:</b>
The analysis revealed unexpected patterns, such as the prominence of discussions about video games like EA Madden NFL and NBA 2K in the dataset, overshadowing the anticipated vaccine-related debates.
The top frequently used words included terms related to video games, highlighting the complexity and unexpected trends in Twitter discussions.
Ethical Considerations: The project reflects on the ethical implications of AI and data analysis, emphasizing the importance of user privacy, consent, and addressing biases in the data.

  <li>Content:</li>
Appendix: Complete Python code from the Jupyter notebooks used in the analysis.
