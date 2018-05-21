# Bible_text_classification
TEXT CLASSIFICATION ON BIBLE DATA SET INTO OLD AND NEW TESTAMENT:

--> There are basically four folders:

1) The first folder is bible_data_set: Contains the input dataset

2) Machine Learning is the folder that contains two python notebooks and their respective models in the internal model folder.
	
	a) training_word2vec.ipynb : Trained on all samples using word2vec Vectorization and SVM classification algorithm.

	     contains the answer to first two questions :

	     1) Classification into old and new testament : Accuracy --> 78%
	     2) The cosine distance between light and dark comes out to be 0.5777796

	b) training_tfidf.ipynb : Trained on all samples using TFIDF Vectorization and SVM classification algorithm.

	     contains the answer to first question :

	     1) Classification into old and new testament : Accuracy --> 92.03729503804523%

3) Deep Learning is the folder that contains 1 python notebook and its respective model.

	a) NLP-BIBLE.ipynb : Trained on all samples using word2vec Vectorization and LSTM classification.

	     contains the answer to first two questions :

	     1) Classification into old and new testament : Accuracy --> 74.42%
	     2) The cosine distance between light and dark comes out to be 0.0026299357414245605

4) Nouns_seggregation is the fourth folder that contains 1 python notebook.

	a) noun_seggregation.ipynb : Creates a data_with_noun.csv file in the bible_data_set folder with first 1000 sentences 
				     and their respective nouns in the noun column. Due to processing time problem ,only 1000
				     sentences have been processed. 
