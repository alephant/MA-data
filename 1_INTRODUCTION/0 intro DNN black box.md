**Not all ML models have a high level of opacity like in neural networks**
“Not all ML systems are thought to be opaque. In the main it has only been neural networks which have been considered to pose serious problems for explanation. Linear and logistic regression techniques, decision trees, and even random forest forecasting, do not pose the sorts of difficulties which plague neural networks.” (Zerilli, 2022, p. 7) 

**DNN are not fathomable and are highly opaque as they are characterized by non-linearity, high dimensionality and quasi-independent parameterization**
“The opacity of a ML model is often defined by reference to the properties of linearity and dimensionality. Linearity and low dimensionality together can be said to make a system and/or its operations fathomable, in the sense that “a person can contemplate the entire model at once” (Lipton 2017, 4).” (Zerilli, 2022, p. 7)

“The most complex systems, such as deep learning networks, are inscrutable to the extent that they model relationships which are not linear and incorporate extremely large feature spaces. Their operations are thus neither fathomable nor intelligible, in the above senses.” (Zerilli, 2022, p. 7)

“There is also the added complication that their model parameters are learned quasi-independently, even in supervised learning scenarios.” (Zerilli, 2022, p. 8)

Thus, the opacity of DNN is categorically different from how other complex linear models are difficult to understand.

**Lack of fathomability due to complexity impedes understanding how the model relates features to produce outputs**
“Fathomability is understood to be the extent to which a person can understand, straight away, how the model relates features to produce outputs. As a result, the more complex a model (e.g., increased dimensionality, extreme nonlinearities, etc.), the less fathomable it becomes.” (Duede, 2023, p. 1092) 

**DNN functioning is intelligible in a formal-mathematical sense, but not in a semantic sense**
“From the above, it should be clear that there is a straightforwardly mathematical sense in which deep neural networks are fully transparent. All weights on all connections across the network, billions as there may be, are both available for inspection and computationally tractable. However, while formally precise, neural network logic is largely semantically unintelligible. That is, the mathematical expression of a fully trained neural network model cannot, in general, be given an intelligible interpretation in terms of the target system such that one can understand or comprehend how the parts interact and contribute to the network’s outputs.” (Duede, 2023, p. 1091) 

**Why DNN lack functional transparency**
“However, in all but the smallest networks it would be difficult to predict the outcome without tracing each step or to understand the behavior of the network, especially if the network includes feedback loops. More importantly, without further analysis it would be unclear to the observer why this neural net successfully classified an image and to what extent each of the neurons contributed to the result, or why different neural nets might have different patterns of classification. In this sense, although we know how the learning algorithm works and what formal guarantees (if any) we have about its performance, we do not know how the learned “algorithm” brings about the classification result. Thus we lack functional transparency.” (Creel, 2020, p. 21)

Knowledge of the learning algorithm doesn't bring about knowledge of how the trained DNN comes to its outcome.