There are four codes inside this folder.

(1) 2 channel Input data with CNN 
(2) 1 channel Input data with CNN 
(3) 2 channel Input data with CNN and LSTM
(4) 1 channel Input data with CNN and LSTM

Each code shows the accuracy, FAR, FRR, TPR and EER in training and testing set. 
Also, it gives the execution time in training and testing. 
To be clear, execution time for testing is time for building the threshold of EER in testing set. Thus, real testing will be shorter.
In addition, it shows the feature visualization of convolution filters in each layer. Here, we average the filters to make it 1-dimension.

You can also use (1) and (2) for augmentation cases. 

Here, we attach the PRRB (Capnobase) input data which only possesses single-session. 
Input data consists of '# of data X # of features X # of channels'. For 1 channel, it is '# of data X # of features'.

For more detail and accessing other datasets, please email to daeyon.hwang@mail.utoronto.ca.

