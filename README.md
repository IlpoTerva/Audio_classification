# Audio_classification

**Introduction**

This was a school course project which was done in group of two.

The problem which we are solving in this project is determining whether data sample belongs to which one of two classes using a binary classification algorithm. The task for which we are finding a solution for is done through programming. We chose to utilize the python programming language which has a wide variety of libraries and features for this audio processing project. 

In this project the chosen machine learning algorithm was k-Nearest Neighbours (k-NN).

**Data description** 

From different vehicles we chose car and tram as our classes for this project. Data samples of cars we collected 25 samples and 23 samples of trams in total we had collected about 50 samples in total. The length of one sample was 5 to 6 seconds long. 

The car data samples were collected from next to road in Tampere, Tesoma. The data samples of cars were recorded by using Apple iPhone 13 and using its built-in application voice memos. Mainly the samples were cars driving towards and cars driving away from the recording device. A few samples were cars slowing down and braking near the recording device 

The tram data samples were mostly collected next to the road where also trams drive in Hervanta. The data samples of the trams were recorded on Oneplus 8t phone utilizing its recorder application. Most of the trams were driving by and past the recorder, some trams were slowing down.  

**Feature extraction**

We used four different methods to extract features from the audio which were: MFCC (Mel-frequency cepstral coefficients), chroma feature and Mel-frequency spectrogram.

