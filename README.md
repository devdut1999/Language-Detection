# Language-Detection

**Task :**  Implement a method to identify the language a document is written in . 

**Dataset Used** **: [**http://www.statmt.org/europarl/** ](http://www.statmt.org/europarl/)**

I cleaned the data, generated a csv file from each language corpus and then merged these csv files to create a single (multi-label) dataset, so that we can use it in the supervised training. 

**Drive Link (Data, Predictions and Models) :**  [**https://drive.google.com/drive/folders/1UWe1KH3Hyppc1U52b13k_v7P1uRwt16e?usp =sharing** ](https://drive.google.com/drive/folders/1UWe1KH3Hyppc1U52b13k_v7P1uRwt16e?usp=sharing)

**Models Implemented** 

I have implemented 2 models : 

1) **LSTM Model :** I have used a 2 layer LSTM model in which the 1st layer ia a Bi- directional LSTM and the 2nd layer is a normal LSTM layer. 

	Using the following model I obtain the following results on the **Validation** set : 

	**Precison :** 99.8% 

	**Recall     :** 99.6% 

	**F1 Score :** 99.7% 
	
	**epoch|  train\_loss|  valid\_loss|  accuracy|  time|** 
	--|--|--|--|--
	0| 3.174304|  3.174028|  0.991781| 35:04 
	1| 3.174232|  3.174012|  0.993948| 35:08 
	2| 3.174252|  3.173991|  0.996563| 35:07 
	3| 3.174207|  3.173995|  0.995737|  35:06 
	4| 3.174287|  3.174070|  0.968439|  35:21 
	5| 3.174207|  3.173987|  0.995023|  35:21 
	6| 3.174199|  3.173990|  0.993714|  35:26 
	7| 3.174184|  3.173987|  0.994759|  35:24 
	8| 3.174258|  3.173986|  0.996451|  35:14 
	9| 3.174238|  3.173986|  0.997149|  35:01 

	-------Ending Training--------  

	
