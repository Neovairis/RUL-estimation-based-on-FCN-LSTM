# RUL-estimation-based-on-FCN-LSTM
For better estimation of aero-engine RUL, we concatenate 1-D CNN and LSTM in a parallel structure.
No matter which model you choose, you have to do data normalization first. 
Then convert data into the corresponding format, for example, [batch, time step, input dimension] is the input format of LSTM. 
These two pre-processing step are very important.
