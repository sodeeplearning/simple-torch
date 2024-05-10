A simple library for faster working with PyTorch.
Functions and classes in this library:
1) Regularization - class for regularization with functions L1_Regularization - for first-level regularization, L2 - for second-level regularization, Regularization - for custom regularization
2) Model_Using - class for comfortable-using models in PyTorch. This class has several functions:
     -Train - for training supervised models
     -Use - function for estimating something with model
     -Save - saving model's weights
     -Load - loading model from weights
     -Info - information about model through torch_summary
3) Residual_Block - convoluion block with residual connection that helping with fading gradients
4) getting_files - get all pathes to files from a folder (path to a folder as an argument)
5) Inception_Block - combining severeal convolution blocks to take differnce in object sizes into account
6) GlobalMaxPooling - taking max values from all channels (not recommending this, cause you lose a lot of information and sometimes model can't be teached)
7) Conv_Block - convoluion block with dropout, activation, batch normalization, max pooling
8) Up_Conv - convolution block with upsampling with scale_factor as one of arguments
9) Conv - convolution block with activation and normalization (recommended for UNet implementation)
10) jpg_tensor - converting jpg bytes to a torch tensor (with a path to a file as an argument)
11) imshow - showing tensor 
