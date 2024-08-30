What is the overall argument that Sullivan is making?
Sullivan rejects the popular claim that the opacity and complexity of DNN models are an in-principle problem for gaining understanding from DNN models. In contrary, she argues that it is not the opacity and complexity of DNN models that are the limiting factor when considering DNN as explanatory models, but like with any other model, simple or complex, it comes down to whether the model is linked to the target phenomenon. She introduces the notion of link uncertainty as the actual limiting factor.
i.e. "the problem of model opacity is a function of LU"

What does Sullivan rejects?
She rejects that model opacity is an internal problem, but it is an external problem of linking the model to the target.
>[!Sullivan]
>“model opacity should not be understood as simply an internal problem that requires greater transparency of how the model works. Model opacity qua opacity need not undermine explanation or understanding from complex ML models. Instead, the problem of model opacity is largely an external problem connecting the model to the target. Specifically, the problem of opacity is a function of how much link uncertainty (LU) the model has.” (“Scientific Understanding and Representation: Modeling in the Physical Sciences”, 2022, p. 307)
>
>“However, in order to explain and gain understanding with an ML model the problem of opacity greatly depends on features external to the model instead of features internal to it (i.e., link uncertainty and empirical support, explanatory functions, and the social and personal significance of the model and its domain).” (“Scientific Understanding and Representation: Modeling in the Physical Sciences”, 2022, p. 318)

According to Sullivan, what of the model is the basis for its decision?
The basis for model decision are its higher-level abstract features and "how those features are externally supported in providing insight into the target phenomenon that matters for understanding".

As T&S' approach is concerned with understanding correlations between features represented by data, is it helpful to understand in which feature relationships higher-level abstract features are engaged in?

What is the role of ML interpretability methods for Sullivan's approach?
ML interpretability methods make it so that the problem of model opacity becomes an external problem of LU rather than an internal problem of lack of transparency.
They do this by providing us with model transparency of exactly those model details on which the trained ML model relies on to make its decision.


What is link uncertainty?
At best, by using a model we want to understand what the actual causes of a phenomenon are. To enable the understanding of actual causes, the causes that the model identifies must be empirically (or scientifically) validated as actual causes. As long as the causes identified by the model are not empirically (or scientifically) shown to be the actual causes, there is a high degree of link uncertainty between the model and the target phenomenon.

What does it mean "to link a model to the target"?
"linking the model’s inferences to the target phenomenon".



For which models is link uncertainty important?
It is important to remove link uncertainty for any kind of model. 
>[!Sullivan]
>“This general claim about the importance of removing link uncertainty in order to gain understanding stretches beyond the cases of minimal and complex models.” (Sullivan, 2022, p. 27)


How can link uncertainty be removed?
The question of how to remove link uncertainty is the question of how to establish a link between model and target.
>[!Sullivan]
>“In my view, higher-level goals of algorithms are necessarily important for evaluating LU and the scope of possible understanding. Concerning ML models, the trained model executes an algorithm that has a specific classification or predictive task / goal. How the algorithm achieves the goal is an implementation question of the various steps that the learned model takes to reach an output, such as a set of learned weights. Which specific learned weights are necessary to know—and their level of description—for understanding phenomena with ML models is the question. I have argued that the answer to this question partly depends on the epistemic risk facing the model and is largely an external question regarding LU.” (Sullivan, 2022, p. 2)


Highest-level algorithm?
The goal of the highest-level algorithm of a trained DNN must be known for understanding to be possible. It seems that Sullivan adheres to the notion that a trained DNN executes a "highest-level" algorithm that is identical to what the DNN is designed to do. For her, this algorithm is known and knowable.

>[!Sullivan]
>“However, the general goal of the algorithm must be known for understanding to be possible.” (Sullivan, 2022, p. 2)
>“In my view, higher-level goals of algorithms are necessarily important for evaluating LU and the scope of possible understanding.” (Sullivan, 2022, p. 2)


Lower-level algorithm?
>[!Sullivan]
>“The lower-level algorithms become the way of implementing higher-level algorithms. Thus, lower-level algorithm goals are also a matter of implementation.” (Sullivan, 2022, p. 2)


What is implementation opacity?
The way how an algorithm achieves its goal is opaque.
How an algorithm is implemented is opaque.


Is implementation opacity relevant for understanding a phenomenon from ML models?
No, Sullivan argues that implementation opacity is irrelevant, i.e. for the question whether a trained DNN enables understanding or not, the opacity of how the algorithm is implemented is irrelevant.

What is **the** question regarding the ML model output?
The output of a trained ML model is determined by the implementation of a set of learned weights. Sullivan implies that understanding phenomena with ML models requires to know some of the learned weights and their "level of description". The question which learned weights need to be known depends on the "epistemic risk facing the model". It is an "external question regarding LU".


What does LU measure?
LU can be understood as a measure of how well external causal support justifies the explanation that is induced by the ML model.

Can an ML model provide understanding itself?
No, an ML model alone cannot provide understanding. The ML model induces an explanation that must be linked with external causal support. 
>[!Sullivan]
>“It is not the ML model alone that provides understanding; the model induces an explanation paired with external links connecting the model to the phenomena that enables understanding. This is why I argued that most ML models merely provide how-possibly explanations. The ML models do not provide causal support themselves, but rather indicate possible (causal) hypotheses that additional research must justify through reducing LU.” (Sullivan, 2022, p. 4)



What does Sullivan mean when she dismisses FAI by saying that "a view from nowhere is untenable"?
The relevance of implementation details for understanding phenomena cannot be answered in-principle, but the relevance depends on what the target of understanding is.


What is the conflict between T&S' TML hypothesis and Sullivan's notion of implementation irrelevance?
Sullivan's defense of the possibility of understanding from ML models despite their opacity relies on the implementation irrelevance of certain details. 

What do T&S claim that Sullivan's argument against opacity as an in-principle problem for understanding relies on, and what does it actually rely on?
>[!TS]
>“Sullivan’s argument refutes that DL models cannot be used for understanding merely due to some opacity, but the reliance on the implementation irrelevance of certain details, particularly their irrelevance to the target of understanding, is essential for this defense.” (Shech and Tamir, 2022, p. 10)

Sullivan differentiates implementation details according to their level of abstraction. Lower-level details can be opaque without causing a problem for understanding. However, the goals of higher-level algorithms and higher-level emergent properties need to be known in order to evaluate LU and gain understanding from ML models.
Sullivan does not argue for the irrelevance of learned parameter instantiations per se.
So it is not that Sullivan argues for the irrelevance of details comparable to "topological facts" in the map example. She argues that if the high-level algorithmic goal is to represent a target system, it is irrelevant how this goal is achieved, i.e. how the topological facts are expressed through the model implementation.
>[!Sullivan]
>“I am not suggesting that the topological features of the map are irrelevant for adequately representing, say, NYC’s subway system. On the contrary, for the draw_subway_map() algorithm to be successful, the topological features of the map output must share the relevant topological features of NYC’s subway system. How these topological features are expressed (or computed)—either by a visual depiction of nodes and edges or in mathematical notation—does not affect the general goal of representing NYC’s subway system.” (Sullivan, 2022, p. 2)



Why does Sullivan dismiss T&S' approach to distinguish different kinds of implementation details?


As Sullivan assumes that we know enough about "high-level decision points of the model", understanding from ML models becomes an external problem. Is this assumption fair?


When Schelling model is run on a computer, can we say that it is irrelevant to know all detail parameterization of the computer? 
If it is irrelevant, why is it not similarly irrelevant to know all detail parameterization of an ML model?


Is T&S' approach a way to reduce LU? "Reducing LU may require a comparison between different models,..."


Does the map analogy (implementation opacity is irrelevant as it is irrelevant to use red or blue ink to draw a map) actually work?


On what (implicit?) notion does FAI build on?
Contrary to Sullivan's "pure implementation irrelevance" stane, T&S argue that there are in-principle differences between implementation details on whether or not they are relevant or not for understanding. 
T&S use "topological facts" to illustrate what an implementation detail would look like for which variation would in fact matter to the target phenomenon (navigation) compared to other in-principle irrelevant details such as color choice.

What does Sullivan have against this "in-principle difference between implementation details"-view of T&S?
She argues that this "view from nowhere" is not reasonable, as "relevance is related to a target".

How is the buildup to FAI?
“What distinguishes functionally approximate irrelevance from implementation irrelevance is that in the former varied details matter to the studied target, but they are varied only in ways that approximately preserve the relevant aspects of the phenomenon to be understood.” (Shech and Tamir, 2022, p. 10)
varied details matter to the studied target: implicit notion behind FAI
varied only in ways that approximately preserve the relevant aspects of the phenomenon to be understood: FAI

How does this reasoning for FAI look like?
T&S open up a can of worms themselves (certain implementation details matter which creates a dilemma for understanding when they are opaque). And close it themselves (FAI fixes this supposed dilemma).

Or to put it differently: 1) Because Sullivan's reliance on pure implementation irrelevance is problematic for understanding, we introduce the notion that certain implementation details are in fact in-principle relevant for the target of understanding; 2) our notion causes a dilemma as these relevant implementation details cannot be used to for understanding as they are opaque; 3) we fix the dilemma that we introduced by positing that these implementation details matter to the target of understanding, but only insofar they do not substantially change the relevant aspects of the target of understanding.

What is the "role and degree" of FAI?
The role of FAI is to fix the dilemma and to make opaque implementation details that are relevant to the target compatible with understanding

Can "topological facts" in the map example and "learned parameter instantiations" in ML models be compared?


What do T&S mean by varied details matter to the studied target, but "only in ways that __approximately__ preserve the relevant aspects of the phenomenon to be understood"?


How do T&S qualify what "significant parameter detail differences" mean?


What is the relation between TML target and target phenomenon?



What do T&S mean by "appropriate target of understanding with ML models"?
Similar to how a learned distribution is a good estimate of the actual distribution of the target features, 
the TML target gives us insight into the actual target.
By drawing intra-model inferences on the TML target, we gain a better understanding of the actual T.

>[!TS]
>“Our hypothesis is that the appropriate target of understanding with ML models closely relates to how a learned distribution estimates the “actual” distribution describing a phenomenon’s studied features.” (Shech and Tamir, 2022, p. 8)


What do intra-model inferences do?
Intra-model inferences give us insight into the TML target and by doing so give us understanding of the actual T.

What are the different modes of understanding?
A different mode of understanding means to draw intra-model inferences on different aspects of feature relationships as they are represented by data, thus, gaining understanding of different aspects of actual T.
So there are different modes how one can gain understanding of actual T by means of drawing intra-model inferences.

How are the modes of understanding related to each other?
What is their target??

What do the modes of understanding actually help us to understand of the TML targets?
>[!TS]
>“Although the three modes of ML understanding explored in Section 4 are not intended to be comprehensive, we emphasize that a predictable relationship between the represented features __is not necessarily causal__. Background scientific theory is vital for inferring causal claims from information-theoretic claims about features.” (Shech and Tamir, 2022, p. 18)

T&S seem to admit that modes of understanding mostly provide correlative understanding of feature relationships represented by data. 
i.e. FI understanding tells us which x-data highly correlates with y-targets and can thus be attributed as important in predicting target features as represented by data.
But FI understanding does not provide us with an understanding of whether target features represented by x-data (e.g. the visual appearance of a skin area) are causally related to target features represented by y-data (e.g. the dermatological state).



What does Sullivan mean by arguing that T&S have a "model-centric view of understanding phenomena"?
For Sullivan, the key problem is that data relationships (i.e. the TML target, i.e. relationships of features represented by data) are not used as a means to further provide understanding by some explanation that is induced by the ML model, but that T&S see data relationships as the target of ML understanding themselves. 
For Sullivan, these data relationships are part of the model. Thus, the TML hypothesis is model-centric.
The notion of model-based explanations put forward by Lawler & Sullivan is relevant here.
In support of this notion that the TML is model-centric, FAI serves as an indication that T&S are invested in the idea that some model implementation details can be inherently relevant irrespective of what the target is.

==But how different in being model-centric or not are data relationships (T&S) vs. higher-level emergent features (Sullivan)?==



Could it be that Sullivan misunderstands T&S' approach as "model-centric"?
It could be that the TML target is about the external target as much as the model output of e.g. the melanoma DNN that Sullivan uses as an example to illustrate her self-described "model-as-means" view.
The TML target is the "relationships of features represented by data". T&S explain that by "relationships of features" they mean the real-world relationships between features of the target phenomenon. They explain that by "represented features" they mean measurable properties of model data that are associated with the phenomenon insofar model data represents target features. The model output of the melanoma DNN is part of its model data. It is used to gain understanding of the target phenomenon. So I don't understand why Sullivan claims that there is a difference between both approaches in what the target of understanding is or how much emphasis is put on the model.

What part of the model is used to gain understanding of the target?
Sullivan: model prediction; emergent high-level properties
T&S: relationships/ properties within model data
How different is that?


So according to T&S, there are some implementation details that do in fact matter to the studied target compared to other implementation details that are "purely irrelevant implementation details like coding language etc." (learned parameterization).
And accounting for FAI, there are some aspects of the of target feature relationships that can be understood (IR, FI, LR).


What do T&S understand by misrepresentation link uncertainty?
When model data does not only represent intended features, but other not intended features of the target phenomenon. Thus, link uncertainty between the model and target is caused as the model data misrepresents features of the target to be understood.
T&S argue that correcting for empirical LU alone is not enough to ensure a clear link between model and target. A background of scientific evidence in support of the model can lower empirical LU, but the model data can still misrepresent target features, e.g. by data leakage or a confounding bias in data sampling, preparation or y-target labeling. Thus, for a ML model to enable understanding of the target phenomenon, it is necessary to prevent empirical as well as misrepresentation LU.
FI and LR understanding can help to prevent misrepresentation LU.


What is the reasoning behind Sullivan's characterization of T&S' approach as being "model-centric"?
Is it true that the "target of the TML hypothesis consists of understanding the model"?
How is T&S' approach truly different from Sullivan's?
How target-centric is Sullivan's approach really?