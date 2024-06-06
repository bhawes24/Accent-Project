# Accent Recognition

## Description
This project seeks to train a model to recognize a speaker's native language from a speech sample. Two methods were used. 
The first simply passes the speech sample through a convolutional neural network. 
The second uses one of two CNNs. The sample is discriminated into one of two categories using KMeans clustering, then passed to the corresponding CNN. 
We found that the second method significantly outperformed the first.

## Data and Acknowledgments
Data for this project can be found here: https://www.kaggle.com/datasets/rtatman/speech-accent-archive/data.  
Weinberger, S. (2013). Speech accent archive. George Mason University.  
This project was done as part of CS5841 (Machine Learning) at Michigan Technological University in collaboration with Sandeep Chilukuri and Brian Conn.
