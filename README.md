# NLP-The-Simpsons-and-9-11
An investigation of the impact of 9/11 on spoken dialogue from television series, The Simpsons, from 1989 to 2016 using Python.
Data was obtained from Prashant Banerjee via Kaggle at https://www.kaggle.com/prashant111/the-simpsons-dataset

**Data**

Contained in file "The Simpsons Data.zip"

**Notebooks**

Analysis of George Bush Speech and 9/11 Commission Report - Similar cleaning and analysis done for the official 9/11 commission report and an address given by George Bush

Data Cleaning for The Simpsons - Cleaning of the script data to extract only the spoken dialogue from the raw text 

Exploratory Analysis for The Simpsons - Initial exploration of data including word frequencies, Zipf distribution, Entropy, Heaps' Law

Partition Script by Year and Map Lines - Separation of the cleaned data by air year, calculation of average sentiment per year, and most common word per year

Sentiment Analysis - Uses two different sentiment calculators (TextBlob and VADER) to calcualte the polarity of each line

TFIDF Frequencies of 9-11 Words in The Simpsons - Calculates and plots frequencies of usage of top 50 and 25 TF-IDF tokens from the report and speech

TF-IDF for 9/11 Report and Speech Compared to General Corpus - Calculates TF-IDF frequencies from the report and speech compared to Moby Dick

Topic Analysis with LDA - Uses LDA to classify the script into topics, including an assessment of the ideal number of topics using coherence scoring 

