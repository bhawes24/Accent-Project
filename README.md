# Accent Recognition

## Description
This project seeks to train a model to categorize a speaker's native language into one of five options (English, Spanish, Arabic, Mandarin, French) from a speech sample. Two methods were used. 
The first simply passes the speech sample through a convolutional neural network. 
The second uses one of two CNNs. The sample is discriminated into one of two categories using KMeans clustering, then passed to the corresponding CNN. 
We found that the second method significantly outperformed the first.

## Data and Acknowledgments
Data for this project can be found here: https://www.kaggle.com/datasets/rtatman/speech-accent-archive/data.  
Weinberger, S. (2013). Speech accent archive. George Mason University.  
This project was done as part of CS5841 (Machine Learning) during the Spring 2024 semester at Michigan Technological University in collaboration with Sandeep Chilukuri and Brian Conn. A PDF of the final poster presentation is included in the files.
