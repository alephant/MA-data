The melanoma DNN was developed to classify skin cancer based on images of skin lesions. The DNN was trained on on a dataset of dermatologist-labelled clinical images containing >2000 diseases. Its performance to classify malignant versus benign skin lesions was tested against 21 expert dermatologists on biopsy-proven clinical images. Malignant and benign lesions are difficult to classify as they share many visual features. The melanoma DNN outperforms the average expert performance.
Early-detection of skin cancer is crucial to improve the survival rate for melanoma. With current mobile devices having the computing power to run DNN, proactive tracking of skin lesions and early detection of melanoma could be significantly improved. 
To understand Sullivan's view on the opacity problem, it is helpful to look at the different answerability of explanatory questions that we could ask of the melanoma DNN. We could ask questions of how the model works which can be answered by looking at how the model is implemented. 
A key aspect of the implementation refers to how the trained DNN is parameterized, i.e. which parameter values for weights, biases etc. were acquired through training that determine the functioning of the deep net. Due to model complexity the parameterization of a DNN is not easily accessible. Accordingly, the problem of opacity can be understood as the problem of having no clear knowledge of the whole parameterization of a DNN. The whole set of parameter values that determine the classification of the melanoma DNN is not known. Thus, the question arises whether one could gain understanding from a model of which the determining factors for its output is unknown.
Or we could asks questions on the phenomenon that the model bears on, i.e. skin disease in the case of the melanoma DNN. 

Sullivan argues that understanding model implementation is not necessary for understanding of the phenomenon that the model bears on. 


Bridge to implementation irrelevance:
what is meant by implementation
explanatory questions regarding implementation vs phenomenon
opacity (impl. black boxes) only negatively impacts the answerability of expl. questions regarding implementation
contrary to knowledge of higher-level workings of the ML model, knowledge of "lower-level workings" (finegrained weights etc.) is irrelevant
to understand model implementation "it is not necessary to know how the model maps on to some real-world phenomenon" (p.5)

implementation opacity: opacity of how ML algorithm and trained models implement functions, i.e. opacity of how the ML algorithm achieves its goal or task

Based on the introduction of how the algorithmic computations of a DNN can be described according to their level, Sullivan argues that DNN such as the melanoma DNN are not black-boxed at the highest-level.
For Sullivan the question whether or not an implementation detail is relevant for understanding, and thus, whether or not its opacity is problematic for understanding, depends on whether it must be known for understanding to be possible. 
Sullivan adheres to the notion that a trained DNN executes a algorithm that is identical to what the DNN is designed to do. For her, the goal of this "highest-level" algorithm is known and its transparency is necessary for ML understanding. 

e.g. the melanoma DNN is built to classify skin cancer based on visual input data. 





###### TML hypothesis, x and y-data, distributions, relation between TML and T:
For T&S, understanding with ML models requires the identification of the appropriate target of understanding. For them, this the Target of ML models, i.e. TML target. 
T&S define the TML target, i.e. the appropriate target of understanding with ML models, as the "relationships of features represented by the data". What do they mean by that?

The model data of a DNN can be subsumed as x and y-data. x-data is the input data on which data transformations are executed given the respective neural network architecture and parameterization. Y-data is the output data which determines the ML prediction or classification. T&S write “Our hypothesis is that the appropriate target of understanding with ML models closely relates to how a learned distribution estimates the “actual” distribution describing a phenomenon’s studied features.” (Shech and Tamir, 2022, p. 8)
Both x and y data represent features of the target phenomenon, e.g. in a DNN used for classification of skin diseases, x-data represents how a section of skin looks, and y-data represents what its dermatological state is. The way how X and Y are related among each other, i.e. the conditional probabilities p(Y given X) tell us something about the relationship of features in the target phenomenon. Through training, the parameterization of a DNN model change in such a way that the prediction of Y-data given X-data is optimized, i.e. the model acquires a learned probability distribution(Y given X) that is assumed to be the best estimate of the "actual" probability distribution that describes all feature relationships active in the target phenomenon.

On this notion, T&S clarify that the target phenomenon identified by the TML hypothesis is still the real-world phenomenon, i.e. the real-world relationships between its features - as they are represented by the data - and not the "actual" distribution describing said target features: “While the targeted relationships are described by such a , we emphasize that it is the real world relationships between features implied by the description that are the target phenomenon not itself.” (Shech and Tamir, 2022, p. 8)
Hereby, the represented feature relationships that are identified as the TML targets can be thought of "measurable properties associated with the phenomenon” (Shech and Tamir, 2022, p. 8).

As these represented feature relationships are part of the intrinsic makeup of the model, drawing inferences on them are intra-model, i.e. intra-model inferences give us insight into the TML target. 
As the TML target captures relevant aspects of the real-world phenomenon (i.e. its feature relationships as they are represented by data), insight into the TML target allows for a certain epistemic access into the properties of the real-world phenomenon (see T&S use of C-schema).

###### T&S modes of understanding:
T&S introduce three modes of understanding that can be used to gain understanding of different aspects of a TML target, i.e. feature relationships as represented by the data, and thus, of different feature relationships in the target phenomenon. A different mode of understanding means to draw intra-model inferences on different aspects of feature relationships as they are represented by data, thus, gaining understanding of different aspects of the real-world phenomenon.

IR (informative relationship) understanding indicates that there is some signal in x-data that is relevant for predicting y-data. 
FI (feature importance) understanding indicates which features in x-data are more or less relevant for predicting y-data.
LR (learned representation) understanding indicates how learned representations (e.g. intrinsic properties of the vector space such as relative angle or position of vectors) are organized to transform x-data to optimally predict y-data.

T&S make clear that modes of understanding provide correlative but not causal understanding of feature relationships in the target phenomenon, i.e. FI understanding tells us which x-data highly correlates with y-data and can thus be understood as important in predicting target features as represented by data.
But FI understanding does not provide us with an understanding of whether target features represented by x-data (e.g. the visual appearance of a skin area) are causally related to target features represented by y-data (e.g. the dermatological state). T&S argue that "background scientific theory is vital for inferring causal claims from information-theoretic claims about features.” (Shech and Tamir, 2022, p. 18).

###### Dilemma, FAI as backbone to TML, example to illustrate FAI
Contrary to Sullivan, T&S do not reject the in-principle relevance of certain implementation details of a ML model for understanding and illustrate how Sullivan's view on implementation irrelevance would lead to a dilemma in regards to the TML hypothesis. The detail parameterization of a ML model directly influences how X and Y data are related, i.e. how the relationships of features of the target phenomenon are represented by the data, and thus, how well the learned probability distribution estimates the actual distribution. Following Sullivan's As the TML hypothesis identifies feature relationships as represented by data as the appropriate target of ML understanding, ML opacity of implementation details regarding the TML target would impede understanding of feature relationships of the target phenomenon. directly refers to certain ML implementation details that ideally need to be epistemically accessible to make sense of said feature relationships. This implies that the opacity of ML implementation details regarding feature relationships would impede understanding of target feature relationships as represented by the data.

To solve this problem, T&S introduce Functionally Approximate Irrelevance (FAI) as a "refined" account of Sullivan's general account of implementation irrelevance.
T&S argue that implementation details can in fact be differentiated into implementation details that are irrelevant and details that are in-principle relevant for ML understanding, i.e. for which a variation in these implementation details would impact understanding of the target phenomenon to be gained. However, FAI resolves this dilemma as it identifies those cases in which “varied details matter to the studied target, but they are varied only in ways that approximately preserve the relevant aspects of the phenomenon to be understood.” (Shech and Tamir, 2022, p. 10).
e.g. other than color choices, topological facts represented by a map model, cannot be described as mere implementation details that carry no significance for understanding from said map model. A change in topological facts would matter the map's target phenomenon, i.e. navigation of a target system. However, if topological facts of a map would be different, but only insofar as they "approximately preserve the relevant aspects of the phenomenon to be understood", then the difference in implementation is functionally approximately irrelevant for understanding.

To reiterate, T&S argue as follows: as the TML hypothesis posits feature relationships represented by data as the appropriate target of ML understanding, implementation details regarding those feature relationships are relevant for ML understanding; looking at TML targets from Sullivan's view of implementation irrelevance introduces a dilemma, as opaque implementation details regarding feature relationships do not allow for epistemic access and thus, for understanding the TML target; the dilemma is solved by positing that these implementation details matter to feature relationships of the target phenomenon as represented by data (the target of understanding), but only insofar they do not substantially change the relevant aspects of the feature relationships of the target phenomenon represented by data. Thus, the distinction into implementation details that are irrelevant versus those that are in-principle relevant for ML understanding is crucial for FAI. And FAI is crucial to render such implementation details that are opaque compatible with understanding.

###### Target-related vs principled view on implementation irrelevance
For both Sullivan and T&S, epistemic opacity is not an in-principle problem for understanding. But both rest their account on a different view of implementation irrelevance. For Sullivan, whether or not certain implementation details are relevant for understanding phenomena cannot be answered in-principle, but the relevance depends on what the target of understanding is. Thus, her view on implementation irrelevance could be described as "target-related", i.e. the relevance of implementation details, and thus, the question whether or not their opacity is problematic for understanding, depends on the target phenomenon that the ML model is built to provide understanding for.
T&S view implementation irrelevance in a principled fashion, i.e. certain implementation details of a ML model are in-principle relevant for understanding, whereby the view is "FAI-enabled" as opaque implementation details are functionally irrelevant as long as relevant aspects of the target phenomenon to be understood are approximately preserved in feature relationships represented by data.


introduce relevant concepts of both accounts
introduce melanoma DNN as case study
illustrate concepts, key similiarities and differences through melanoma DNN





What is relevant for understanding? Necessary for understanding from ML models
Sullivan: link between M and T
T&S: “similarly trained models irreconcilably diverge in their feature importance implications, approximate irrelevance comes into question” (Shech and Tamir, 2022, p. 12)

What in the model is the basis for understanding of T??
Sullivan: “abstract patient representation where only the most important derived dimensions remain” (Sullivan, 2022, p. 16)
T&S: 

What is the target of understanding?
Sullivan: real-world target phenomenon (e.g. disease development in the deep patient DNN)
T&S: feature relationships represented by the data (TML target)

What kind of understanding can we gain?
Sullivan: “there are several explanatory questions that might be interesting to ask of the model, each with varying levels of answerability. Some of these questions are howpossibly questions and some of these questions are more pointed why- and how-actually questions.” (Sullivan, 2022, p. 23)
T&S: “we emphasize that a predictable relationship between the represented features is not necessarily causal. Background scientific theory is vital for inferring causal claims from information-theoretic claims about features.” (Shech and Tamir, 2022, p. 18)
“Origin theories about causal links such as PHT are not merely suspect; they fall outside the scope of target features to be understood by ML models according to the TML hypothesis.” (Shech and Tamir, 2022, p. 19)
One cannot gain causal understanding based on the feature relationships represented by data





