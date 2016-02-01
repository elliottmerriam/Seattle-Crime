# Seattle-Crime
Visualization and prediction of crime in Seattle by category

IPython notebook to visualize crime data from Seattle PD records and predict crime category based on time/location features.

This code is adapted from a notebook written by Kaggle member papadopc to to obtain a very high ranking on 
the Kaggle San Fransisco Crime Classification leaderboard (3rd place as of 2-1-16; see 
https://www.kaggle.com/c/sf-crime/forums/t/15836/predicting-crime-categories-with-address-featurization-and-neural-nets/103225)

A key aspect of the model's success is the conversion of street addresses (tens of thousands of unique values)
to a log-odds likelihood metric, which greatly improves the model's performance.

The model is convolutional neural network implemented using the Keras library.  
