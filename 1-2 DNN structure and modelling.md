- perceptrons as DNN ancestors already surprising for prediction and explanation?
- introducing DNN structure, DNN properties amounting to complexity, "layers of abstraction"

The most basic structure of neural network is called a perceptron. It consists of an input and an output layer. 
Perceptrons were developed from the early 80s
- as models for what?
- higher preditive power compared to other network structures?

Deep neural networks are multilayered computational systems that perform numerical data transformations to predict output data based on input data.
The basic computational sub-structures of a DNN are nodes that compute simple, non-linear transformations on numerical data, so called activation functions. EXAMPLES for activation functions.
Nodes are arranged in layers. Each node computes its function on input data it receives from nodes of a previous layer and outputs its result to nodes in the next layer. Nodes of different layers are connected by edges. By each edge a weight is assigned to the output value of a node that serves as input to nodes in the next layer. Additional terms like biases can be assigned as well. The first layer is called input layer and and abstracts raw data into numerical form.
The last layer is called output layer. In the case of a classifier DNN the output layer indicates the labels with which to classify the stimulus input to the DNN. Hidden layers are the layers in between input and output layer. The more hidden layers there are, the deeper the DNN. 
Signal propagation in a biological neural network can illustrate inter-layer data propagation in a DNN. As weights change numerical data to fall below or above certain thresholds, signal transfer from node to node can be prohibited or inhibited. As nodes receive differently weighted input data their respective activation functions compute different output signals. In the final layer a classification is achieved as the signal from the whole network converges on a final output label.

## Backpropagation learning
During training the weights in a DNN change in order to enable model decisions that are correct in the context of the task at hand, e.g. making correct classifications. As the weights determine signal propagation throughout the deep net and resulting activation in the final layer, the weights are adjusted according to some computational learning method. One frequently used learning method is called error backpropagation learning. In simplified terms, an error function is applied starting from the final layer n. The error function computes the difference between current and desired numerical input into layer n and adjusts the link weight between layer n-1 and n accordingly. Then the difference between current and desired input into layer n-1 is calculated and link weights between layer n-2 and n-1 are adjusted accordingly. This error signal backpropagates till it reaches the first input layer. Backpropagation is a supervised learning method as the error sinal and the corresponding weight adjustments are determined by a classification that is assigned as correct classification by humans.

## Function description of DNN implementation
- introducing T&S "estimator's learned transformation" to "intra-model inferences", model implementation & parameterization, classifier function governing i/o-relation
The input-output relation of a DNN can be described by an estimator function f. 
FOOT: Whether or not a DNN does in fact implement an estimator function is disputed. 
An estimator f is essentially a function that makes predictions. In the context of machine learning, it takes input data (features) and predicts an output (labels). The form of the output depends on the task. An estimator f is defined by its parameters. Parameters of a DNN are its weights and biases that are assigned to values. ML optimization means that the estimator's parameterization is optimized to best "fit the data". Parameter optimization is achieved during training. The parameterization is tested on data not used for training to ensure that the DNN generalizes well on new data.
Thus, a trained DNN is characterized by its network architecture (number of nodes and layers, type of activation function employed) and its parameterization (how the trained network transforms data based on parameters aquired during training).









