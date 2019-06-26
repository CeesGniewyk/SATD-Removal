Dataset from the paper:"Automatically Learning Patterns for Self-Admitted Technical Debt Removal"


CalibrationIterationsCNNandRNN.csv contains the Error Rate and the Time Cost varying the number of iterations for both the CNN and the RNN approach.
Calibration_Embedding_Size_RNN.csv reports the Precision and the Recall for each SATD removal strategy varying the embedding size for the source-based RNN classifier.
CalibrationLayersAndNeuronsRNN.csv reports the Precision and the Recall for each SATD removal strategy varying the number of layers and the number of neurons in each layer for our souce-based RNN classifier.
CalibrationNeuronsCNN.csv reports the Precision and the Recall of the comment-based CNN classifier varying the number of neurons in each hidden layer of the network.
CalibrationWindowSize_Layer_Embedding_TrainingWord2vec_Preprocessing.csv reports the Recall, the Precision and the F_Score for each SATD removal category varying the parameters reported in the name of the file: the embedding size, the type of training for Word2Vec, the type of preprocessing being applied to the SATD comments, the window size and finally the number of hidden layers. 
ResultClassification.csv reports the result of the different approaches and the human-created baseline related to the 712 SATD-removals in our training/testing dataset.

The data and the code will be available after acceptance. 