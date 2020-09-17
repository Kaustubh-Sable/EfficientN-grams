I.	Original source for the code base.
	
	Dataset
	republic.txt from project gutenberg. The text file should be in respective folders.
	

	HMM
	https://www.youtube.com/watch?v=s3kKlUBa3b0 
	
	Back-off Model
	 https://medium.com/@davidmasse8/predicting-the-next-word-back-off-language-modeling-8db607444ba9   
	
	LSTM Model
	https://medium.com/coinmonks/word-level-lstm-text-generator-creating-automatic-song-lyrics-with-neural-networks-b8a1617104fb  


II. 
	HMM_Model.ipynb : Implemented methods to train and evaluate the model with the baseline model.
	
	backoff_model.ipynb : Code to train the model was referred from the medium blog. Implemented own methods to preprocess the data and evaluate the predictions made by the
						  model with our baseline model.
	
	word_level_lstm_config_1.ipynb : Referred model architecture from the medium Blog. Implemented methods to preprocess data, train the model and evaluate the model with the baseline model.
									 To train the model under different network configurations run word_level_lstm_config_2.ipynb and word_level_lstm_config_3.ipynb.
	




III.	Software Requirements:
	
	Trained and tested on google collab.
	
	Python 3.6	
	Keras 2.1.5  
	tensorflow-gpu 1.14
	flake 8 3.5.0
	numpy 2.0.0
	sklearn 0.0
	nltk 3.2.5
	pandas 0.25.3
	matplotlib 3.1.2
