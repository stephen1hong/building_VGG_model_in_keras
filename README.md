# Building a VGG_model in keras 

We can generalize the specification of a VGG-block as one or more convolutional layers 
with the same number of filters and a filter size of 3×3, a stride of 1×1, same padding 
so the output size is the same as the input size for each filter, and the use of a rectified 
linear activation function. These layers are then followed by a max pooling layer with a size 
of 2×2 and a stride of the same dimensions.

reference: Jason Brownlee, "How to implemnt VGG,..."
