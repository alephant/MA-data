DNN opacity in context

**Not all ML models have a high level of opacity like in neural networks**
“Not all ML systems are thought to be opaque. In the main it has only been neural networks which have been considered to pose serious problems for explanation. Linear and logistic regression techniques, decision trees, and even random forest forecasting, do not pose the sorts of difficulties which plague neural networks.” (Zerilli, 2022, p. 7) 

**Epistemic opacity is a context-dependent feature of computational science**
“Here a process is epistemically opaque relative to a cognitive agent X at time t just in case X does not know at t all of the epistemically relevant elements of the process.” (Humphreys, 2009, p. 618)

**What are the epistemically relevant elements acc. to Boge?**
“In fact, the unknowns are what makes w-opacity (and DL, accordingly) special: They correspond to ==automatically discovered insights==; ==complex, non-obvious features that can be abstracted from the data== and allow the machine to discriminate. ==Their existence is an empirical matter==, so I will provide examples below. ==It is these very features that drive predictive success== but, as the examples will show, at the same time yield the greatest prospects for understanding. They are hence epistemically relevant.” (Boge, 2022, p. 61)

=="complex, non-obvious features that can be abstracted from the data" sounds a lot like T&S approach.==



A cognitive agent is not able to know and understand all epistemically relevant elements of a computational process.
Key question based on Humphreys: can I make justifiable claims on the basis of a process of which it is impossible to know all its epistemically relevant factors?

**DNN functioning is epistemically accessable in a formal-mathematical sense, but not in a semantic sense that permits us to understand how the DNN comes to its prediction**
“From the above, it should be clear that there is a straightforwardly mathematical sense in which deep neural networks are fully transparent. All weights on all connections across the network, billions as there may be, are both available for inspection and computationally tractable. However, while formally precise, neural network logic is largely semantically unintelligible. That is, the mathematical expression of a fully trained neural network model cannot, in general, be given an intelligible interpretation in terms of the target system such that one can understand or comprehend how the parts interact and contribute to the network’s outputs.” (Duede, 2023, p. 1091) 

“From a purely formal point of view, black box systems constitute a “mathematical glass box.”” (Zerilli, 2022, p. 8)

**Useful ML models have unavoidable complexity, and thus, opacity**
“Though a machine learning algorithm can be implemented simply in such a way that its logic is almost fully comprehensible, in practice, such an instance is unlikely to be particularly useful. Machine learning models that prove useful (specifically, in terms of the ‘accuracy’ of classification) possess a degree of unavoidable complexity.” (Burrell, 2016, p. 5)

---
DNN functional, computational opacity and its relation to model complexity

**DNN are not fathomable and are highly opaque as they are characterized by non-linearity, high dimensionality and quasi-independent parameterization**
“The opacity of a ML model is often defined by reference to the properties of linearity and dimensionality. Linearity and low dimensionality together can be said to make a system and/or its operations fathomable, in the sense that “a person can contemplate the entire model at once” (Lipton 2017, 4).” (Zerilli, 2022, p. 7)

“The most complex systems, such as deep learning networks, are inscrutable to the extent that they model relationships which are not linear and incorporate extremely large feature spaces. Their operations are thus neither fathomable nor intelligible, in the above senses.” (Zerilli, 2022, p. 7)

“There is also the added complication that their model parameters are learned quasi-independently, even in supervised learning scenarios.” (Zerilli, 2022, p. 8)

Thus, the opacity of DNN is categorically different from how other complex linear models are difficult to understand.

**in Zerilli: Lack of fathomability due to complexity impedes understanding how the model relates features to produce outputs**
“Fathomability is understood to be the extent to which a person can understand, straight away, how the model relates features to produce outputs. As a result, the more complex a model (e.g., increased dimensionality, extreme nonlinearities, etc.), the less fathomable it becomes.” (Duede, 2023, p. 1092) 



**Boge: the two dimensions to the opacity-problem of DNN**
“As a matter of fact, it is easy to recognize the very same process involved in h-opacity as involved also in w-opacity. This is what it means that there are two dimensions to ‘the’ opacity-problem in DL, instead of two problems. When a DNN learns to approximate a desired function, it is hence not only opaque how, precisely, it achieves this goal: It is also opaque what it is about the data that drives this process.” (Boge, 2022, p. 62)

**Boge: h-opacity refers to the opacity of how the machine learns; it concerns mainly functional transparency**
“The point hence is that, despite some abstract analogies between human and Deep Learning, it is in important respects opaque how the machine learns. Call that h-opacity. ==H-opacity concerns the way in which a DNN automatically alters the instantiated function in response to data==.” (Boge, 2022, p. 59)

**Functional opacity due to genetic programming**
“A program generated by machine learning may fail to be functionally transparent if its algorithm was developed autonomously, without being programmed by a person, as in genetic programming.” (Creel, 2020, p. 10)

**Computational opacity of algorithms that involve emergent properties, complexity effects etc. like in DNN is not easily resolved by process decomposition**
“The difficulty in determining which emergent properties, complexity effects, or unexpected errors the code might possess cannot always be resolved by being able to trace the code line-by-line or function-by-function. Only at a higher level does structural opacity emerge.” (Creel, 2020, p. 15)

Higher-level emergent properties are not decomposable (see Humphrey, 2004)

“Thus, a second source of opacity would remain even if hand checking were possible: the program would still not be fully transparent because we could not understand how all the steps interact to bring about the algorithm or to what extent each individual step contributed to the final result.” (Creel, 2020, p. 15)



**Functional opacity of DNN due to complexity**
“However, it is just not the case that we know f in the same way we know the factorial function.” (Räz and Beisbart, 2022, p. 7)

“Second, even if we granted that ̂ f were implemented by a DNN, ̂ f is not known in the way in which the factorial is known because ̂ f is extremely complex.” (Räz and Beisbart, 2022, p. 7)

The true and learned classifier function cannot be described like the true factorial function because of complexity. It is practically impossible to know the true classifier function.




**In addition to complexity, epistemic opacity is also due to demands of human reasoning not being met**
“opacity that stems from the mismatch between mathematical optimization in high-dimensionality characteristic of machine learning and the demands of humanscale reasoning and styles of semantic interpretation.” (Burrell, 2016, p. 2)

**Computational opacity due to different kinds of data that influence machine vs human decision-making**
“Part of the ineliminable opacity of complex computational systems comes from the fact that the factors that influence machine classifications or predictions are of different kinds from those described as reason-giving by humans. Even when information that is sufficient for machine classifications or predictions is available, its difference in kind and scale means that it explains little to us.” (Creel, 2020, p. 31)


---
DNN lack functional and structural transparency, relation between structural and functional opacity

**DNN lack functional transparency**
“However, in all but the smallest networks it would be difficult to predict the outcome without tracing each step or to understand the behavior of the network, especially if the network includes feedback loops. More importantly, without further analysis it would be unclear to the observer why this neural net successfully classified an image and to what extent each of the neurons contributed to the result, or why different neural nets might have different patterns of classification. In this sense, although we know how the learning algorithm works and what formal guarantees (if any) we have about its performance, we do not know how the learned “algorithm” brings about the classification result. Thus we lack functional transparency.” (Creel, 2020, p. 21)

Knowledge of the learning algorithm doesn't bring about knowledge of how the trained DNN comes to its outcome.

**in Creel: DNN lack functional and structural transparency**
“In the case of a deep neural network, it is not possible to know which algorithm is implemented by the network precisely because the algorithm is developed autonomously during training. As a result, DNNs also lack what Creel calls “structural” transparency in that it is not clear how the distribution of weights and (hyper)parameterization of the neural network implements (realizes) the algorithm that it has learned. Therefore, for Creel, DNNs are opaque—neither “fathomable” nor “intelligible” in Zerilli’s sense.” (Duede, 2023, p. 1092) 

**Structural opacity is not correlated with functional opacity similar to how acc. to Sullivan knowledge of model implementation is irrelevant for understanding phenomena from the model**
“It is possible to know the algorithm that the code realizes but not know how the code realizes it, i.e. to have functional but not structural transparency.” (Creel, 2020, p. 13)

**The degree of structural opacity is a function of model complexity**
“The structural opacity of a large cosmology or climate simulation is an accidental function of size and accretion; a similar but smaller program would be easier to understand.” (Creel, 2020, p. 19)

---

Why DNN opacity is a problem

**One position is that neural network transparency is epistemically essential to gain knowledge from ML applications**
“What all of these reasons have in common is a commitment to the idea that neural network transparency is epistemically essential to effectively use and gain knowledge from powerful artificial intelligence applications in scientific and societal settings (Gunning et al. 2019).” (Duede, 2023, p. 1093)

This commitment invokes the idea that without transparency, “scientists are unable to understand the outputs of their models, are powerless to explain why the models perform the way they do, cannot provide justification for the decisions they make on the basis of the model output, are uncertain whether and to what extent the models reflect our values—on and on.” (Duede, 2023, p. 1093)

---

DNN opacity as context-dependent problem

**Lack of interpretability is problematic for high-stakes decision-making settings**
“While lack of interpretability is of particular concern in highstakes decision-making settings where accountability and value alignment are salient (e.g., medical diagnosis and criminal justice) (Falco et al. 2021; Hoffman 2017)” (Duede, 2023, p. 1090) 

**Opacity can be seen as problematic for research settings**
“opacity of deep learning models may also be of concern in basic research settings where explanations and understanding represent central epistemic virtues and often serve as justificatory credentials (Khalifa 2017)” (Duede, 2023, p. 1090)

**Opacity is problematic in the "context of justification"**
Concern arise “when network outputs are treated as scientific claims that stand in need of justification (e.g., treated as candidates for scientific knowledge, or treated as the basis for high-stakes decisions)” (Duede, 2023, p. 1090)


----------
DNN opacity not critical for understanding

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