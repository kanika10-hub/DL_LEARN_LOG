
Learnt about different types of Neural Networks 
 ANN (ARTIFICIAL NN )- INDENTIFIES PATTERNS AND MAKE PREDICTIONS )
1) CNN (CONVOLUTION) - to process data that has grid like structure , eg images , applies filters to extract imp features 
2) RNN(RECURRENT)- designed to hadnle sequential data , eg- time series or text 
3) FNN(FEEDBACK)- data flows in one direction , t/p to o/p , no loop or cycles 
4) RBFN(RADICAL BASIS FUNCTION ) - designed to work with data that can be modeled in radial or circular way. 


worked on cnn and learnt how filters work - 
A filter is a tiny matrix that searches for patterns , eg- edge detector , cicle detector , vertical line detector , 
the filter sildes over the image , that sliding operation is called <convolution>. 

Image
↓
Convolution
↓
ReLU
↓
Pooling
↓
Convolution
↓
ReLU
↓
Pooling
↓
Flatten
↓
Dense Neural Network
↓
Prediction
