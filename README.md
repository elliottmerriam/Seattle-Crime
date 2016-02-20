# Seattle-Crime
Visualization and prediction of crime in Seattle by category

IPython notebook to visualize crime data from Seattle PD records and predict crime category based on time/location features.

A key aspect of the model's success is the conversion of street addresses (tens of thousands of unique values)
to a log-odds likelihood metric, which greatly improves the model's performance.

The model is a convolutional neural network implemented using Keras.  
