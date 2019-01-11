# Keras Notes

## Getting the input shaped correctly.
Keras expects an numpy array of [samples,time steps,features]

For an image you would see something like (256,256,3) for a 256x256 image with rgb values for pixels.

For working with signal data (1-dimensional convolutions) you may have to create the dimensions.

Essentially you have each row has N entries each of which is one feature. For example:

row 1:  10, 20, 30
row 2:  16, 32, 25


In this example, the data provided has shape (2,3). To do a convolution on it reshape it into (samples,time steps, features) which in this case is (samples,timesteps,1) or in this case (2,3,1).

So the initial array before reshaping looks like:
[
[10,20,30],
[16,32,25]
]

When reshaped
[
[ [10],[20],[30] ],
[ [16], [32], [25] ]
]