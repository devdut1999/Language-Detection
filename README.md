# Language-Detection

**Task :**  Implement a method to identify the language a document is written in . 

**Dataset Used** **:[**http://www.statmt.org/europarl/** ](http://www.statmt.org/europarl/)**

I cleaned the data, generated a csv file from each language corpus and then merged these csv files to create a single (multi-label) dataset, so that we can use it in the supervised training. 

**Drive Link (Data, Predictions and Models) :**  [**https://drive.google.com/drive/folders/1UWe1KH3Hyppc1U52b13k_v7P1uRwt16e?usp =sharing** ](https://drive.google.com/drive/folders/1UWe1KH3Hyppc1U52b13k_v7P1uRwt16e?usp=sharing)

**Models Implemented** 

I have implemented 2 models : 

1) **LSTM Model :** I have used a 2 layer LSTM model in which the 1st layer ia a Bi- directional LSTM and the 2nd layer is a normal LSTM layer. 

	Using the following model I obtain the following results on the **Validation** set : 

	**Precison :** 99.8% 

	**Recall     :** 99.6% 

	**F1 Score :** 99.7% 

	
