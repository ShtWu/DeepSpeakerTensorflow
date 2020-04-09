# Speaker Verification
This is a speaker verification project. 

Data set is based on Voxceleb1 with over 10k uttrances.

Attention mechanism and triplet loss are applied.

In predefined folder, following functions are defined:

data_pipeline: the module is created to transform origin .wav signals(which can be recorded also) into speaker features in the form of rolling windows.

models: this module contains major component of predefined dnn models, classes corresponds to different models which contains a builder to set up graph for itself.	
	returns an object with tensors needed of the computation graph. 

trainer: this module contains functions to train, predict, finetune, save, load models. 
	 Fed with tensors, dataframe. 

A clip of testing case: 

https://www.youtube.com/watch?v=i6oHFi6Il8c&t=10s


	


