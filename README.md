# EIP_Assignment
### Name : Kiran Kumar G
### Email: kirankumarnbg@gmail.com
### Batch : 5


# Epoch: 

Epoch is the term we use for one full cycle which is made of one forward propagation and one back propagation. We can decide the number of cycles in our training by setting the number of epochs at pre training stage. There is common question in the minds of first timers about the selection of number of epochs before training which will help to utilize resources of computing unit efficiently. The answer is Selection of number of epoch at which validation set loss starts to increase and training set loss starts to get decrease which in other term over fitting of the model. Hence selection of number of epochs is very important parameter which helps to use resources and time efficiently.

# Feature Map: 

Feature map in a convolutional neural networks are the outputs of the filters after convolution. Each feature map carries certain information about the image  and they are unique from one another. Number feature maps in a network are depend on selection of number of filters because each filters/kernel produces its own feature map. The size of the feature map  depend on filter size, strides, padding and input size. Feature maps from different layers stacked and they gets update during each epochs till the completion of training.


# Activation Functions :

Activation functions are the functions we have at the end of the node which takes the experesion of input amd weights to produce the output. Activation functions are very imporatant in the machine learning and plays importent roles in intermediate layers. There are many kinds of activation functions like Sigmoid, Relu, tanhx and softmax. In recent days relu has become very famous activation function for the intermadiate layers because it avoids the problem of deminishing gradient effectively compare to sigmoid which was famous before the relu function. We use softmax activation function to get the multi class probabilities.              

![](https://cdn-images-1.medium.com/max/1600/1*ZafDv3VUm60Eh10OeJu1vw.png)

# Convolution : 

Convolution Nueral network has become very famous option for the image classification task after the introduction of GPU and it got wide responce after Alexnet model 2012. The convolution process takes place when the filters/kernel convolve on the input images which creates the dot product. Each filters with specific strides and size move on the image to produce the dot product with the pixels which creates feature maps. These feature maps will have specific features which tells unique information about the image. The filters weights gets update in each epochs after backpropogation through the number of layers.We can use maxpooling layers which reduces the size of the image during intermediate layers.

![](https://cdn-images-1.medium.com/max/1000/1*7S266Kq-UCExS25iX_I_AQ.png)

# Filters/Kernel :

Filters/Kernel in the Convolution nueral network are the matrix of random numbers with defined sizes. Filters convolved on the images creates the output which are called feature maps.Each filters creats the different feature maps which will helps to identify the diffrent features of the image. The size of the filters and stride plays very important role in identifying the different features. The filters weights get updates in each epoch to get the better accuracy. The depth of the feature maps always equal to number of filters.   
                
![](https://i.stack.imgur.com/3m7mW.png)
