# Real Time VQA
This Repository contains code of a VQA model.
The first notebook which is "Preprocessing" contains code to preprocess the VQA Dataset. It aims to clean and make the data (images, questions and answers) ready to be fed into a model.
The produced data are structured and saved into tfrecord binary files, ready to be directly read from tensorflow API as a dataset of tuples (image, question, answers) where each of this data is in form of numerical vectors.

The second notebook contrains the architecture of the model, the model is composed of different modules combine to form a VQA model. 
![architecture](https://github.com/ThegreatShible/MyVQA/blob/master/assets/VQA_arch.PNG)

