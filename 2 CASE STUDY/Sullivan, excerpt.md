### Sullivan's argumentation
Model opacity does not impede understanding phenomena.
Black boxes do not interfere with understanding phenomena.
Understanding the phenomena is independent from understanding model implementation. 
Questions of how a model works are unrelated to how-possibly, -actually or understanding-why questions.
Knowing more about model implementation does not increase understanding.
Understanding phenomena simply needs to have a highly predictive model and knowing its high-level properties.
1. DNN implementation black boxes are like any other black boxes like in factorials or the Schelling model
2. the only problem would be if DNN were a highest-level black box, but DNN are not a highest-level black box, because we have understanding of their high-level properties
3. Thus, understanding DNN implementation is irrelevant for understanding phenomena


Understanding the phenomena depends on link uncertainty.
Understanding model implementation does not help us with it - it is musguided to try.
1. Level of opacity is independent of link uncertainty
2. 

### Sullivan's assumptions
- Black boxes in Schelling model are compatible with how-possibly, how-actually and understanding-why.
- The way DNN are black boxed is similar to how other models are black boxed.
- DNN generalization can be ensured based on statistical assumptions.
- Sullivan's argument works for all types of DNN, a difference in structure and implementation does not matter.
- We have understanding of high-level properties of DNN.
	- Having no direct control over the modelling process (like for the Schelling model) is not a problem to have understanding of high-level functioning of DNN.
	- Background knowledge on DNN modelling and DNN properties and the use of indirect means are sufficient to ensure that the DNN is not black-boxed at the highest level and to gain understanding of high-level functioning of the DNN.
	- We know enough of the DNN modelling process to "make intelligent changes to improve output and prediction"
- prior knowledge helps to link a model to the target
- link uncertainty comes in degrees.
- If a DNN is able to answer how-actually questions it is due to low link uncertainty
- A model with high level of link uncertainty can contribute to lower its level of link uncertainty by pointing out patterns that then can be researched which then would reduce the link uncertainty
- a model can provide understanding precisely because link uncertainty is resolved 


Whether or not ML models enable understanding of phenomena is not a question of model opacity, but depends on the degree of link uncertainty between the model and the phenomenon. Opacity is not an in-principle problem for understanding from ML models, i.e. the reason why opaque do not enable understanding is not opacity, but link uncertainty.
Opacity is not the deciding factor for understanding from ML models. The implementation of ML models can be black-boxed on various levels without necessarily impeding understanding. 
- “A modeler may know the broad outline of the algorithm’s structure without knowing how each step is exactly implemented. In such a case, there is a black box around implementation; the implementation is either unknown or illegible to the modeler, the explainer, or the understander.” (Sullivan, 2022, p. 8)

Sullivan argues that understanding phenomena requires understanding higher-level emergent properties and not understanding detail implementations of the ML model. As these higher-level properties of the ML model are abstract representations of the relevant features of the target phenomenon she assumes that these properties drive the decision of the ML model. Thus, the higher-level properties are the relevant basis for understanding on the part of the ML model, and not its detail implementation. The detail model implementation is irrelevant for understanding.

As long as the ML model is not a highest-level black box, it can in-principle enable understanding. She discusses several factors that help to rule out that the level of opacity is lower than for a highest-level black box. The modeller has background knowledge of the model and the target which enables understanding of higher-level properties of the ML model. Indirect means such as saliency maps could help to check whether or not the model decides as intended, thus, higher-level understanding of the ML model's input-output-relations could be enabled. This would not be the case for a highest-level black box as one would only know the inputs and outputs, but not the relation that governs the overall model behavior. 

The model maps model elements to real-world elements in order to represent target features as abstract representations. The target features that are abstractly represented by the model are assumed to be the causally relevant features for the target phenomenon. For understanding to be possible it seems that it needs to be intelligible that the higher-level abstractions of the model are the cause that drives model behavior. The "link" between higher-level abstractions and model decision needs to intelligible.

For the Schelling model the preference parameter is an abstraction/idealization of a mechanism operating in the target phenomenon, in this case racial segregation, that is believed to be a causally relevant mechanism. The preference parameter is implemented as a simple algorithm in the model computing the percentage of same type-elements in the direct surrounding of a model element and iterates until at least 30 % of all surrounding model elements are of the same type for each element. Thus, the preference parameter determines the behavior of the model elements and the higher-level emergent pattern, in this case a segregation pattern between different type-model elements:
- “There are countless implementations of Schelling’s model that follow the same basic higher-level algorithm regarding satisfying neighbourhood preferences.” (Sullivan, 2022, p. 9)

Sullivan argues that in the case of the Schelling model the modeler knows the "basic higher-level algorithm", i.e. the preference parameter, which is driving the overall model decision. The modeler is in fact the one who sets the preference parameter at 30 % in the first place. In order to gain understanding of the phenomenon that the model bears on, here racial segregation, it is relevant to have epistemic access to the higher-level patterns that are driven by the preference parameter. When Sullivan argues for implementation irrelevance, she argues that the overall functioning of the higher-level algorithm stays the same, despite a change in lower-level implementation. How the algorithm comes to its result might change, but not the algorithmic result itself. When the higher-level algorithm stays the same, the result of the algorithm stays the same - a segregated pattern will emerge. Sullivan argues that our understanding from the Schelling model depends on the higher-level emergent pattern and not on details of how the model is implemented on a lower-level. As much as it is irrelevant for the emergence of the higher-level pattern whether the model is implemented with red vs. green or blue vs. orange model elements, transparency of detail model implementations is irrelevant for our understanding of the target phenomenon:
- “In order to gain understanding of segregation using Schelling’s model, you do not need to peer inside and see the implementation here. We have the same level of understanding of the mechanisms of segregation whether or not the implementation black box is removed. The explanation does not rely on the specific movements of, say, coin-267, but on the macrolevel emergence of a segregated pattern” (Sullivan, 2022, p. 11)

Sullivan argues that lower-level implementation black boxes can get in the way of understanding. This would be the case when lower-level algorithms change in an unpredictable fashion, i.e. their implementation is black-boxed to the modeler, and their unpredictability makes the overall system behavior unpredictable. In this case the functioning of the higher-level algorithm would not stay the same and the higher-level emergent pattern would change in an unpredictable fashion. e.g. in the case of the Schelling model, there is a lower-level algorithm that implements randomization which coins move next. If this unpredictable algorithm would change the higher-level algorithm implementing the preference parameter, so that in one iteration of the algorithm it would be 30 &,  in the next it would be 40 % and then it would be 90 %, then the higher-level emergent pattern would change in a way that understanding would be impeded.
- in this case Sullivan argues that “there is something about the implementation of a higher level algorithm that is obscured.” (Sullivan, 2022, p. 10)

However, Sullivan argues that for the Schelling model it is actually the case that the functioning of the higher-level algorithm computing neighborhood preference stays intact. It continues to implement a 30 %-preference despite the lower-level randomized algorithm is unpredictable. Thus, also the higher-level emergent segregation pattern based on which one can gain understanding of segregation in the real-world remains intact. The absolute localization of the pattern changes due to randomization, but the pattern remains intact relative to overall dimensions of the output space. 

When the mechanism based on individual preference that is assumed to be operating in the target phenomenon can be empirically validated as an actual mechanism driving racial segregation, then the Schelling model is linked to the target phenomenon. Sullivan would argue that the Schelling model could then answer explanatory how-actually questions concering the target phenomenon and would enable understanding of actual causes of racial segregation compared to only possible causes. 

This implies that Sullivan is striving for explanatory understanding that is enabled by establishing a link between model and target. 

Sullivan uses the Schelling model to argue from analogy that what is true for simple models is also true for complex models such as DNN. And her argument works for all types of DNN architecture:
- “The exact structure and implementation of each type of DNN varies. However, the nuances of these different techniques do not impact the larger argument concerning opacity and understanding;” (Sullivan, 2022, p. 13)

The melanoma DNN takes as input-data images of melanoma and healthy moles and classifies which is which. The melanoma DNN is trained on training data of sample pairs containing a feature represented by input data (an image depiciting a melanoma) and a label represented by output data (classification as melanoma). During training the parameterization of the melanoma DNN is optimized to maximize the probability for right predictions. In the end, a DNN implements  more and more abstract representations of target features and the DNN is trained to identify the features that are most relevant to make a good prediction of the target.

Sullivan argues that the melanoma DNN implements a classifier function that abstracts features of the target phenomenon, in this case melanoma, that represents features that are assumed to be causally relevant for melanoma. A DNN is a complex model as it implements computations that are unintelligible to the modeler. 

Sullivan assumes that during the modelling process the DNN "learns" the higher-level algorithm that governs its input-output relation. In analogy to the higher-level algorithm that drives the decision of the Schelling model, the DNN's learned higher-level algorithm drives the overall model decision. She further adheres to the notion that this higher-level algorithm is intelligible. The modeler has sufficient knowledge to understand the higher-level algorithm and properties that govern the overall functioning of the DNN as she states that the modeler knows 
- “enough about the modelling process (the higher level algorithms that train and create the deep patient model) such that one can build a model—and make intelligent changes to improve output and prediction.” (Sullivan, 2022, p. 18)
- “Once the model is trained, the modeler still has a general idea of how the finalized model works in virtue of having knowledge about how the model was trained and validated.” (Sullivan, 2022, p. 18)

Sullivan argues that even though the melanoma DNN is a complex model, its higher-level functioning is intelligible. It is not a highest-level black box. And even though lower-level implementation details are opaque, understanding them is not relevant for understanding melanoma which the DNN bears on. Analogous to the Schelling model, model implementation is irrelevant for understanding the target phenomenon. Or to put it differently, implementation black boxes in both simple or complex models that prevent understanding how the model works do no prevent understanding of the phenomenon.
- “So, while the modeler does not have direct control over the modelling process, a contrast case with Schelling’s model, still the process is not black boxed at the highest level, such that it would prevent understanding of the phenomenon the resulting model aims to capture.” (Sullivan, 2022, p. 18)
- “However, different types of saliency testing are enough to satisfy our need to know the high level details of how the model works to open the door to understanding the phenomenon the model bears on” (Sullivan, 2022, p. 18)
- “Simply having a highly predictive model, and knowing the high-level emerging properties of the model, uncovers that it is possible to use a machine learning representation for disease prediction. Importantly, it is not necessary to look inside the implementation black box to answer these types of howpossibly questions. All that is needed is the higher-level understanding of how the system is able to identify high-level patterns within data.” (Sullivan, 2022, p. 20) **attacked by R&B objection 1**

Sullivan argues that once the link uncertainty is resolved, the deep patient DNN can enable understanding of disease development and risk factors.
The melanoma DNN enables understanding of medical interventions and their relevance.

There is extensive amount of medical knowledge and scientific justification that identifies the visual appearances of moles as highly relevant for the classification of melanoma. 


The problem that I see is that there could be a meaningful difference between model implementation being irrelevant versus understanding model implementation being irrelevant. R&B seem to dispute the first in the case of DNN and argue that model implementation of DNN is very much relevant for understanding from DNN. It could be that Sullivan's analogy from simple to complex models fails in this regard, i.e. that it is not so simple to argue that because detail implementations of the Schelling model are irrelevant for its overall model decision as the basis for understanding from it, that the computational implementation of a DNN is irrelevant for its overall classification that is the basis for understanding from DNN.

