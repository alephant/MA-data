**Not all ML models have a high level of opacity like in neural networks**
“Not all ML systems are thought to be opaque. In the main it has only been neural networks which have been considered to pose serious problems for explanation. Linear and logistic regression techniques, decision trees, and even random forest forecasting, do not pose the sorts of difficulties which plague neural networks.” (Zerilli, 2022, p. 7) 

**DNN functioning is epistemically accessable in a formal-mathematical sense, but not in a semantic sense that permits us to understand how the DNN comes to its prediction**
“From the above, it should be clear that there is a straightforwardly mathematical sense in which deep neural networks are fully transparent. All weights on all connections across the network, billions as there may be, are both available for inspection and computationally tractable. However, while formally precise, neural network logic is largely semantically unintelligible. That is, the mathematical expression of a fully trained neural network model cannot, in general, be given an intelligible interpretation in terms of the target system such that one can understand or comprehend how the parts interact and contribute to the network’s outputs.” (Duede, 2023, p. 1091) 

“From a purely formal point of view, black box systems constitute a “mathematical glass box.”” (Zerilli, 2022, p. 8)

---

**DNN are not fathomable and are highly opaque as they are characterized by non-linearity, high dimensionality and quasi-independent parameterization**
“The opacity of a ML model is often defined by reference to the properties of linearity and dimensionality. Linearity and low dimensionality together can be said to make a system and/or its operations fathomable, in the sense that “a person can contemplate the entire model at once” (Lipton 2017, 4).” (Zerilli, 2022, p. 7)

“The most complex systems, such as deep learning networks, are inscrutable to the extent that they model relationships which are not linear and incorporate extremely large feature spaces. Their operations are thus neither fathomable nor intelligible, in the above senses.” (Zerilli, 2022, p. 7)

“There is also the added complication that their model parameters are learned quasi-independently, even in supervised learning scenarios.” (Zerilli, 2022, p. 8)

Thus, the opacity of DNN is categorically different from how other complex linear models are difficult to understand.

**in Zerilli: Lack of fathomability due to complexity impedes understanding how the model relates features to produce outputs**
“Fathomability is understood to be the extent to which a person can understand, straight away, how the model relates features to produce outputs. As a result, the more complex a model (e.g., increased dimensionality, extreme nonlinearities, etc.), the less fathomable it becomes.” (Duede, 2023, p. 1092) 





**DNN lack functional transparency**
“However, in all but the smallest networks it would be difficult to predict the outcome without tracing each step or to understand the behavior of the network, especially if the network includes feedback loops. More importantly, without further analysis it would be unclear to the observer why this neural net successfully classified an image and to what extent each of the neurons contributed to the result, or why different neural nets might have different patterns of classification. In this sense, although we know how the learning algorithm works and what formal guarantees (if any) we have about its performance, we do not know how the learned “algorithm” brings about the classification result. Thus we lack functional transparency.” (Creel, 2020, p. 21)

Knowledge of the learning algorithm doesn't bring about knowledge of how the trained DNN comes to its outcome.

**in Creel: DNN lack functional and structural transparency**
“In the case of a deep neural network, it is not possible to know which algorithm is implemented by the network precisely because the algorithm is developed autonomously during training. As a result, DNNs also lack what Creel calls “structural” transparency in that it is not clear how the distribution of weights and (hyper)parameterization of the neural network implements (realizes) the algorithm that it has learned. Therefore, for Creel, DNNs are opaque—neither “fathomable” nor “intelligible” in Zerilli’s sense.” (Duede, 2023, p. 1092) 

**Functional opacity of DNN due to complexity**
“However, it is just not the case that we know f in the same way we know the factorial function.” (Räz and Beisbart, 2022, p. 7)

“Second, even if we granted that ̂ f were implemented by a DNN, ̂ f is not known in the way in which the factorial is known because ̂ f is extremely complex.” (Räz and Beisbart, 2022, p. 7)

The true and learned classifier function cannot be described like the true factorial function because of complexity. It is practically impossible to know the true classifier function.


----------

**Opacity of ML models is not an in-principle problem for evaluating their decisions on the basis of human practical reasoning**
“So long as we are concerned with the evaluation of decisions, the formal prerequisites of explanation are in many cases satisfied by the quotidian form of explanation that practical reasoning assumes. That human practical reasoning takes this form is instructive for the kinds of explanations we can reasonably demand of ML systems because such systems function in loco hominum, and indeed have parity with humans not only in respect of how they are situated, as decision agents, but also in respect of the epistemic status they afford, as Type 2 systems.” (Zerilli, 2022, p. 36) 

**Epistemic opacity is not a problem when DNN are used to guide science in the "context of discovery"**
“What I hope to have shown in this paper is that, despite their epistemic opacity, deep learning models can be used quite effectively in science, not just for pragmatic ends but also for genuine discovery and deeper theoretical understanding. This can be accomplished when DLMs are used as guides for exploring promising avenues of pursuit in the context of discovery.” (Duede, 2023, p. 1097)

“However, I argue that there are many cases in which ==the epistemic opacity of deep learning models is epistemically irrelevant to justifying claims arrived at with their aid==. That is, it is justifiably possible to effectively use and gain scientific knowledge from epistemically opaque systems without sacrificing any justificatory rigor at all.” (Duede, 2023, p. 1093)

Epistemic concerns should be different when neural network outputs are treated as scientific findings in their own right (context of justification) versus when outputs serve to guides in the process of scientific discovery (context of discovery)

**Neural network outputs need not be treated as claims that directly stand in need for scientific justification**
“Be that as it may, the outputs of epistemically opaque models need not be treated in this way. Rather, they can serve as aspects or parts of a process of discovery. While the process ultimately leads to claims that stand in need of justification, the part played by an opaque model in that process can, itself, be epistemically insulated from the strong sort of evaluation that is applied to findings in the context of justification. ==In this way, neural network outputs can serve to facilitate discovery without their outputs or internal logic standing in need of justification==.” (Duede, 2023, p. 1093) 

**How DNN can contribute to science in the context of discovery**
“In the context of discovery, ==the outputs of neural networks can be used to guide attention and scientific intuition toward more promising hypotheses== but do not, themselves, stand in need of justification. Here, outputs of opaque models serve to provide reasons to or evidence for pursuit of particular paths of inquiry over others (see Figure 1).” (Duede, 2023, p. 1094)

**How an opaque DNN contributes to theory building**
“In this case, a fully opaque DLM has profound implications for our theoretical understanding of earthquake dynamics. Namely, the ability to accurately predict phenomena orients scientific attention to empirical desiderata necessary for more accurate theory building. Moreover, it is epistemically irrelevant to justifying the improved theory that we cannot verify whether and how any of the geophysical quantities that were determined to be of relevance are, in fact, represented in the network. This is because it is not the network’s predictions that stand in need of justification but, rather, the theory’s itself.” (Duede, 2023, p. 1097)

**Cichy presents three reasons why DNN have explanatory power despite their opacity**
Comparing DNN-based modelling approaches to other modelling approaches can illustrate the difference in transparency. Mathematical-theoretical modelling is used to investigate visual representations in primates. Here, parameterization, interaction between parameters and their mapping to parts of the target phenomenon are all transparent to the modeler, as model parameters such as geometrical primitives are identified in advance and are a priori mapped to cortical activations. 
The detail parameterization of DNN is aquired through training and not set in advance. Thus, it is not directly interpretable how the usually high number of model parameters interact and how they map onto elements of the target phenomenon. 
However, Cichy argues against the problem of opacity of DNN threefold:
DNN provide an explanation that is different in nature compared to other model classes. DNN explanations are teleological and are not based in a specific kind of isomorphic or similarity mapping. 
DNN are actually quite similar to mathematical-theoretical models. The DNN is defined by a set of parameters that are defined by the modeler in advance, i.e. model architecture, training material, training procedure and objective are all known prior the DNN is trained. Cichy argues that the difference in model parameters does not imply a difference in the capacity to explain, but is due to a difference in the way they represents the target system. 
In a model-of-model approach they characterize DNN as one type of model among a diverse set of models. DNN are not less capable of explanation, but add to the toolbox of available models due to their specific profile of desiderata.
Lastly, they argue that DNN will be made more transparent in the future through advanced XAI methods. As these methods increase their level of transparency, DNN become better suited to explain and enable understanding. It might be even the case that their high level of complexity might be feature and not a bug as DNN could serve to model highly complex phenomena such as brain activity. 