# Brain-Tumor-detection-using-ConVnet-Algorithm
Early detection of medical condition like tumor in brain can be major step in treating it early , which will lower the cost of  . Using the ConvNEt architecture this model has been made . Using the libraries of KERAS and OPENCV and the project was made in the google colab environment.
The dataset used in the project to train the first model is known by the name, Brain-
Tumor-Detector. The dataset contains 2 folders: yes and no which contains 253 Brain MRI
Images. The folder yes contains 155 Brain MRI Images that are tumorous and the folder no
contains 98 Brain MRI Images that are non-tumorous. The data was split in the following way:
1. 70% of the data for training.
2. 15% of the data for validation.
3. 15% of the data for testing

	Insight into the algorithm: Convolution Neural Network (CNN)
●	It is a family of deep neural networks. The basic neural network is a network model inspired by the biological structure and function of the brain called neural networks. CNN has gained popularity in the field of image processing
●	The pre-processing required in a ConvNet is much lower as compared to other classification algorithms. While in primitive methods filters are hand-engineered, with enough training, ConvNets have the ability to learn these filters/characteristics.
●	The basic building blocks of CNN are discussed below.
●	Convolution layer. The convolution operator takes a set of block over the input image and it collects the weights and feeds it down to one block to the next layer.
●	Pooling and Stride. CNN can use any number of strides. It is not necessary to slide the window, pixel by pixel. Pooling layer performs a downsampling operation along the spatial dimensions (width, height) and results in a smaller dimensional output
![image](https://github.com/topgun007-oss/Brain-Tumor-detection-using-ConVnet-Algorithm/assets/83120036/eac3526e-062f-44ed-8df3-4074609cceb5)

●	ReLU transfer function. Rectified linear unit (ReLU) is a transfer function used in convolutional neural network. This is basically a linear function that converts all values less than zero to 0 and more than zero to 1.
●	Fully Connected Neural Network (FCNN). Fully connected layer is used in a convolution neural network as the last layer of the stack of convolution and pooling layer. Fully connected neural network has an input layer and one output layer. The number of hidden layers may vary.
