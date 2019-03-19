Readme
In this project, we use DenseNet121，169，264 to implement very high resolution remote sensing image scene classification. 

The dataset is UC Merced dataset so that in the fully connected layer and softmax classifier, the number of parameter is set to be 21. 

Note that since the network structure is extremely large, here we can use the L2 regularization to fight against the over-fitting problem.
(refer to line 27-29 and line 124 in DenseRS.py)

The process is listed as follows. 
Step1. copy UC Merced dataset into the file folder and extract it.
 
Step2. run tfdata.py to generate training data and test data (The format is tfrecord). 

Step3. run DenseRS.py to train the model. Note that you can adjust the hyper-parameters according to your own dataset. 

Step4. run test.py to test the model on the test data. 

For any other question, please connact 2009biqi@163.com 

Enjoy！