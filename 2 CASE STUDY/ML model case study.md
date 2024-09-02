what is understood by understanding?

For T&S, understanding with ML models require the identification of the appropriate target of understanding. For them, this the Target of ML models, i.e. TML target. 
T&S define the TML target, i.e. the appropriate target of understanding with ML models, as the "relationships of features represented by the data". What do they mean by that?
The model data of a DNN can be subsumed as x and y-data. x-data is the input data, i.e. the data on which data transformations are executed given the respective neural network architecture and parameterization. Y-data is the data which determines the prediction or classification to be made. For T&S, both x and y data represent features of an actual target phenomenon, i.e. model data represents some aspect of a real-world phenomenon, e.g. x-data visually represents how a section of skin looks, and y-data represents what its dermatological state is. Through training, the parameterization of DNN model change in such a way that the prediction of y-data is optimized based on given x-data, i.e. a trained estimator function optimally relates x and y-data, so that feature relationships represented by model data more closely resemble some true feature relationships active in the target phenomenon. On this notion, T&S clarify that the target phenomenon identified by the TML hypothesis is still the real-world phenomenon, i.e. the real-world relationships between its features - as they are represented by the data: “The concept of represented features intuitively can be thought of as measurable properties associated with the phenomenon” (Shech and Tamir, 2022, p. 8).
Inferences on these data relationships are intra-model as they are part of the intrinsic makeup of the model. But for T&S, by drawing intra-model inferences on TML targets we want to better understand the actual target phenomenon comparable to "how a learned distribution estimates the “actual” distribution describing a phenomenon’s studied features.” (Shech and Tamir, 2022, p. 8). 
T&S introduce three modes of understanding that can be used to gain understanding of different aspects of a TML target, i.e. feature relationships as represented by the data, and thus, of different feature relationships in the target phenomenon. A different mode of understanding means to draw intra-model inferences on different aspects of feature relationships as they are represented by data, thus, gaining understanding of different aspects of actual T. 
IR (informative relationship) understanding indicates that there is some signal in x-data that is relevant for predicting y-data. 
FI (feature importance) understanding indicates which features in x-data is more or less relevant for predicting y-data,
LR (learned representation) understanding indicates how learned representations (e.g. intrinsic properties of the vector space such as relative angle or position of vectors) are organized to transform x-data to optimally predict y-data.
T&S make clear that modes of understanding provide correlative but not causal understanding of feature relationships as represented by data, i.e. FI understanding tells us which x-data highly correlates with y-data and can thus be understood as important in predicting target features as represented by data.
But FI understanding does not provide us with an understanding of whether target features represented by x-data (e.g. the visual appearance of a skin area) are causally related to target features represented by y-data (e.g. the dermatological state).
The TML hypothesis introduces a different perspective on how the opacity of implementation details of an ML model is relevant or irrelevant for ML understanding. 
As the TML hypothesis identifies feature relationships as represented by data as the target of ML understanding, the TML target directly refers to certain details of how a ML model is implemented that theoretically need to be epistemically accessible to make sense of said feature relationships. Thus, ML opacity of implementation details regarding feature relationships would be problematic for T&S' notion of ML understanding.
To alleviate this problem, T&S introduce Functionally Approximate Irrelevance (FAI) as a "refined" account of Sullivan's general account of implementation irrelevance.
Contrary to Sullivan, T&S argues that certain implementation details do in fact matter to ML understanding, i.e. that a variation in these implementation details would impact our understanding of the target phenomenon to be gained. FAI identifies those cases in which “varied details matter to the studied target, but they are varied only in ways that approximately preserve the relevant aspects of the phenomenon to be understood.” (Shech and Tamir, 2022, p. 10).
T&S argues as follows: Sullivan's reliance on pure implementation irrelevance is problematic for understanding according to the TML hypothesis, we introduce the notion that certain implementation details are in fact in-principle relevant for the target of understanding; 2) our notion causes a dilemma as these relevant implementation details cannot be used to for understanding as they are opaque; 3) we fix the dilemma that we introduced by positing that these implementation details matter to the target of understanding, but only insofar they do not substantially change the relevant aspects of the target of understanding.



FAI as backbone to TML hypothesis
illustrate TML hypothesis in the case of melanoma DNN




Throughout their work they rely on probability distributions to illustrate
By drawing inferences on T, a model is used to explain a phenomenon T and provide understanding of T. For T&S, by drawing intra-model inferences on the TML target, one can gain understanding of T, i.e. the actual target phenomenon.


What is irrelevant for understanding? Understanding of the ML model!
Sullivan: implementation irrelevance
T&S: functional approximate irrelevance
conclusion: epistemic/ structural opacity is no problem

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





