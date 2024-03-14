

In the following, I focus on a type of ML model that is based on deep learning. 
Deep neural networks are multilayered computational systems that perform numerical data transformations to predict output data based on input data. The basic computational sub-structures of a DNN are nodes that compute simple, linear and non-linear functions on values, so called activation functions, e.g. used for filtering, thresholding, pooling or normalization of values. Nodes are arranged in layers. Each node computes its function on values it receives from nodes of a previous layer and outputs its result to nodes in the next layer. Nodes of different layers are connected by edges. By each edge a weight is assigned to the output value of a node that serves as input to nodes in the next layer. Additional terms like biases can be assigned as well. The first layer is called input layer and abstracts raw data, e.g. visual image data, into numerical data. The last layer is called output layer. In the case of a classifier DNN the output layer indicates the labels with which to classify the input to the DNN. Hidden layers are the layers in between input and output layer. The more hidden layers there are, the deeper the DNN. This multi-layered arrangement allows for the complex, non-linear transformation of original input data. 

Key characteristics of DNN appear to mirror brain functioning. e.g. the way nodes of DCNN transform data to hierarchically compose more complex features from simpler representations is inspired by how different types of neurons hierarchically process perceptual stimuli in the ventral stream (Yamins and DiCarlo, 2016; Hong et al., 2016). Yamins and DiCarlo (2016) identify three criteria for for a model of the sensory cortical system: "stimulus-computability: The model should accept arbitrary stimuli within the general stimulus domain of interest", "Mappability: The components of the model should correspond to experimentally deinable components of the neural system" and "Predictivity" which means that the components of the model should accurately predict neuronal response patterns to stimuli outside the training domain. As DCNN are capable to generate responses to any kind of perceptual input image, their network layers can be mapped to observable structures of the ventral stream and predict neural response patterns to visual stimuli outside the training domain, Yamins and DiCarlo (2016) regard them as "good candidates for models of the ventral visual pathway".

However, despite some aspects of DNN being biologically inspired, their ability to serve as good explanatory models of the brain remains debated. The assumed difference between "simple and complex cells" that initially inspired the hierarchical feature composition among nodes that employ convolutional and pooling functions was challenged by new neuroanatomical findings (Priebe, Mechler, Carandini, & Ferster, 2004). Furthermore, despite overall DNN functioning mimicks neuronal functioning, central components of DNN algorithmic processes such as feed-forward processing and gradient descent are biologically implausible (NOT READ: Chirimuuta, 2020; Goodfellow et  al., 2016). Humphreys concludes that neural nets are "extremely crude models of real brains" (Humphreys, 2013, 580).











**DNN properties**
Buckner (2019) characterized deep neural networks in their increased depth, heterogeneity of nodes, sparse connectivity and employment of regularization techniques compared to perceptrons of earlier years of AI ML development. The introduction of a hidden layer into two-layer perceptrons unlocked the computation of an entire new set of functions. Adding further layers renders neural networks expontentially more efficient in their computations. DNN gain distinct task performance by the combination of nodes computing more elaborate and different activation functions (e.g. convolution, rectification or max pooling). This allows DNN to extract more and more abstract features from the input data. In contrast to fully-connected neural networks, the nodes in current DNN are only connected to nodes in previous and later layers that receive input from the same patch within the input data, e.g. from the same receptive fields of limited size in visual data. Sparse connectivity increases training and computational task efficiency. A DNN typically fails to generalize well beyond training, if it learned to predict idiosyncratic features of the training data, i.e. the DNN overfits training data. To counteract overfitting regularization techniques are used. These increase the reliance of network predictions on more generalizable characteristics of the input data, instead of pecularities.







**Key differences between perceptrons and DNN**
“Contemporary deep neural networks, while stemming from their simpler ancestors, differ in at least four important ways, as summarized by Buckner (2019): they contain many more layers, increasing their efficiency; they are composed of heterogeneous processing units with different activation functions; they are sparsely connected; and they use more techniques to avoid overfitting. These added complexities increase both performance and opacity.” (Creel, 2020, p. 20)

“The typical state-of-the-art DCNN, on the other hand, is (a) deep, containing anywhere from 5 to 250 (or more) layers; (b) heterogeneous, containing different kinds of processing nodes deploying different activation functions (especially convolutional nodes, rectified linear units or “ReLUs,” and nonlinear downsamplers like max poolers—each of which will be explained below); (c) sparsely connected, with later layers only taking input from nearby nodes with overlapping spatial receptivity from the previous layer (a fully-connected output layer is the common exception); and (d) deploys explicit techniques to avoid overfitting (such as dropout, which will also be explained below). Each of these features likely plays a role in making DCNNs orders of magnitude more efficient than shallower networks on the kinds of problems on which they reliably succeed.” (Buckner, 2019, p. 3) Properties of DNN