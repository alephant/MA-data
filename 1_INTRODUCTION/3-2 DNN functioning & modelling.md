## DNN modelling
DNN 

Signal propagation in a biological neural network can illustrate data transformation in a DNN. As DNN are trained the connective strength, i.e. the weights between nodes change in order to perform a certain task.  signal transfer from node to node can be prohibited or inhibited. As nodes receive differently weighted input data their respective activation functions compute different output signals. In the final layer a classification is achieved as the signal from the whole network converges on a final output label.

During training the weights in a DNN change in order to enable model decisions that are correct in the context of the task at hand, e.g. making correct classifications. 
As the weights determine how the input data gets transformed throughout the deep net and resulting activation in the final layer, the weights are adjusted according to some computational learning method. One frequently used learning method is called error backpropagation learning. In simplified terms, an error function is applied starting from the final layer n. The error function computes the difference between current and desired numerical input into layer n and adjusts the link weight between layer n-1 and n accordingly. Then the difference between current and desired input into layer n-1 is calculated and link weights between layer n-2 and n-1 are adjusted accordingly. This error signal backpropagates till it reaches the first input layer. Backpropagation is a supervised learning method as the error sinal and the corresponding weight adjustments are determined by a classification that is assigned as correct classification by humans.

Function description of DNN implementation
The input-output relation of a DNN can be described by an estimator function f. 
FOOT: Whether or not a DNN does in fact implement an estimator function is disputed. 
An estimator f is essentially a function that makes predictions. In the context of machine learning, it takes input data (features) and predicts an output (labels). The form of the output depends on the task. An estimator f is defined by its parameters. Parameters of a DNN are its weights and biases that are assigned to values that can be thought of as the connection strength between nodes. ML optimization means that the estimator's parameterization is optimized to best "fit the data". Parameter optimization is achieved during training. The parameterization is tested on data not used for training to ensure that the DNN generalizes well on new data.
Thus, a trained DNN is characterized by its network architecture (number of nodes and layers, type of activation function employed) and its parameterization (how the trained network transforms data based on parameters aquired during training)

### Functioning

**Stochastic gradient descent "powers" nearly all of DL**
“It is exactly this mapping, established during the training phase, that provides DNNs with their predictive capabilities. To see this, recall that “[n]early all of deep learning is powered by [...] stochastic gradient descent” (Goodfellow et al., 2016, p. 147), which means the iterative minimization of a ‘loss function’ through several rounds of training (also called ‘epochs’).” (Boge, 2022, p. 46) 

**DNN use is driven by the assumption that true function f is in the set of all functions f representable**
“Deep learning is a machine learning technique based on artificial neural networks that is widely used for prediction and classification tasks. The goal of deep learning is to automate the search for a function ˆ f that approximates the true function f that generates observed data. The fundamental assumption that motivates the use of deep learning is that f is in the set of functions F representable by a neural network given some particular architecture and (hyper)parameterization. Of course, for any given parameterization k, we have no way of knowing a priori whether f is element of Fk. However, deep neural networks are universal approximators (Hornik et al. 1989), so the assumption is at least principled.” (Duede, 2023, p. 1091)

**An increase in DNN complexity does not necessarily lead to higher classification performance**
“Also, while this may appear counter-intuitive, ML algorithms do not always perform better with more features.” (Morello et al., 2014, p. 1660)

### Modelling, Training

**Iterative fitting of a model to a training set**
“But the training stage thus also amounts to an iterative fitting of the model to a training set: It proceeds by a successive change of free parameters in response to the ‘loss’ experienced when offering a certain output for the data points encountered. If this is done carefully so as to avoid over- and underfitting to the training set (and with some tricks such as unsupervised pre-training of individual layers),5 a DNN can excel in handling so far unencountered examples.” (Boge, 2022, p. 47)

**DNN exploit learned patterns that are potentially unknown to the modeler**
“But letting a trained DNN loose on actual data of interest, it may be able to exploit the patterns encountered during training—of which the scientist may be fully unaware—to successfully predict further points to that pattern. As we saw above, this ideally leads to the recognition of new, scientifically interesting phenomena such as pulsars, i.e., to new discoveries.” (Boge, 2022, p. 47) 

**A DNN model understood as input-output mapping is not inherently explanatory as its parameters and non-linear functions do not carry any representative meaning**
“For a DL model, weights and biases are merely parameters to be adjusted automatically during training and h [some non-linear activations functions of hidden layers] represents a hyperparameter to be chosen in advance. Beyond that, they are in general not assigned any specific meaning at all: Just consider how for a deep network with some hundreds or even thousands of nodes, no scientist will presumably be able—or even bother—to sort out what each and every weight and bias might represent.” (Boge, 2022, p. 49)

**Hyperparameters determine the class of DNN**
“The choice of a class of DL models from which to choose, i.e., the general type of parameterized function to be adapted during the training, is effected by means of hyperparameters: those parameters, like number of layers, nodes, or even choice of activations, determining the general architecture and those, like learning rate or batch size, determining the training process.” (Boge, 2022, p. 51) 







**Supervised and unsupervised ML training**
“There are two main classes of ML systems: “supervised” and “unsupervised.” Generally speaking, supervised ML systems assist with prediction—involving, in the simplest case, a mapping from some known input x to an unknown output y. This mapping is made possible through training, which in turn takes place on a set of pre-labeled input-output pairs (xi , yi). If we wanted to train a system to recognise the image of a dog or cat, for example, we might conceive of xi as a feature vector (consisting of all the notable features of the object in question, e.g. ear, tail, fur, nose, etc.), and conceive of yi as the set of class designations corresponding to those features (we can specify that y takes one value in {1, ..., C}, where C stands for the number of classes; here C = 2, i.e. DOG or CAT). In this example, “supervision” would consist of a human labeler “telling” the system which features pertain to a dog and which to a cat. If D = {(xi , yi)}, where D is the training set, then we can say that as the size of D grows, the more “experience” the system acquires and the more accurate the system will be in its predictions when used on unseen data. The difference with unsupervised learning is that there is no similar process of labeling—no output data yi used in training—so D = {xi}. (Unsupervised learning is thus concerned less with prediction than with description, or the discovery of patterns in datasets.)” (Zerilli, 2022, p. 6)

