**==new understanding of the TML:==**
relationships of features = abstraction of T
represented by the data = intra-model inferences on it
Intra-model inferences on data representations let us understand abstraction of T.
==Data representations are understood through different modes of understanding reveal different aspects of the target through different relationships of features in the abstraction of T.==

There are various ways how input data X and output data Y are related among each other.
Through training the model learns conditional probabilities of p(y given x).
These learned conditional probabilities can be described by a probability distribution.
i.e. the trained model acquired a learned probability distribution(Y given X).

The learned probability distribution estimates the actual probability distribution.
The actual probability distribution is assumed to describe the real-world relationships between features in the external target as they are represented in the relationships between X and Y data.
i.e. the relationships between X and Y data could tell us something about the real-world feature relationships.

However, due to the opacity of the ML model one cannot look at the detail parameterization of the ML model to understand something about the real-world feature relationships as they are represented by the data.

The detail parameterization of a ML model directly influences the learned probability distribution.

However, due to ML model opacity, we do not know how the learned probability distribution estimates the actual probability distribution that could tell us something about the real-world feature relationships as they are represented in the relationships between X and Y data.

How can we still understand something about the real-world feature relationships as they are represented by the data?

What if the detail parameterization does not matter to what can be understood of the real-world feature relationships as they are represented by the data?

i.e. yes, the detail parameterization matters to how the learned probability distribution estimates the actual probability distribution, but only in ways that are irrelevant for understanding something about the real-world feature relationships as they are represented in the relationships between X and Y data.

i.e. even with ML model opacity, one can still understand different ways how real-world features are related by drawing intra-model inferences based on how input data X and output data Y are related.




**T&S key approach:**  
“we show how direct analysis of an estimator’s learned transformations (specifically, the hidden layers of a deep learning model) can improve understanding of the target phenomenon and reveal how the model organizes relevant information.” (Shech and Tamir, 2022, p. 1)

To improve understanding how a ML model draws inferences on T, i.e. how the ML model enables understanding of T (= how the ML model comes to an optimal estimation of probability across output elements/ distribution of probability mass across elements of state space for random variables Y) 
- we need to draw intra-model inferences on how the ML model organizes raw input data to optimally estimate y-targets (vertical link)
- to understand learned representation layers (TML targets, bottom horizontal link)


So, it is about understanding how the ML model data is structured to enable optimal estimation / optimal prediction / enable optimal understanding.

T&S are interested in understanding what powers understanding from the ML model.
By "interacting directly with the model" one can gain understanding of how the model enables understanding of T.
e.g. a map enables understanding of a city. So one can use the model to draw inferences on the city. But we can also look at how the inferences on the city are drawn, i.e. understand how the map enables understanding of the city by looking at the relevant similarities between the map and the city.
So the question that T&S are interested in is: 
How does a ML model enable understanding of T? How can we improve understanding from ML models on T?


**==By understanding aspects of how input data and output data are related you understand features of the external target abstractly represented by the data==**

By drawing intra-model inferences, you better understand the TML targets, i.e. you better understand abstractions of T. 
By drawing intra-model inferences, you better understand which features of the target in abstract representation ==**are in some sort relevant to the external target.**==
- ***==does T&S approach truly help us better understand how and if the DNN represents relevant features of the external target?==***
By understanding how input and output data are related, you gain understanding of the external target insofar it is abstractly represented by the relationships.


**Difference between structural organization of model data and relationships of features represented by the data:**
We draw ==intra-model== inferences on the structural organization of model data (vertical side)
We draw ==model inferences== on the relationships of features represented by the data (bottom side)

**Distinction between how x data is related to y data in some sense and how the data abstractly represents relationships of features of the external target**

### How ML outcome relates to TML target
The TML target "closely relates to how a learned distribution estimates the “actual” distribution describing a phenomenon’s studied features".
Model outcome depends on the underlying learned distribution.
Model outcome depends on the "relationships of features represented by the data" (TML target).

**But what does this mean?**
- what does it mean for a learned distribution to approximate the "true" distribution in relation to "understanding the phenomenon"?



### Key difference & analogy between map and ML model

==**By making intra-map inferences you understand the mapping relation to the external target.**==
==**By making intra-model inferences you understand the mapping relation to the abstraction of the external target. This is what it means to have a narrow view of understanding.**==


**ML model-as-a-map analogy:**
By making inferences on the abstraction of the city of the right details, one can (better) the city layout.
By looking at how the map represents the city, you gain understanding of the mapping relation between the map and the city layout.
You look at the map, and then you look into the world, and then you see the data on the map is organized like this, and because there is some similarity/isomorphic mapping you look into the world and you can draw inferences about the world (bottom horizontal link).
- “The map represents ==an abstraction of the right details==, enabling judgments based directly on the map’s topology to be linked back to things like understanding how to navigate the represented subway system.” (Shech and Tamir, 2022, p. 9)

By looking at how the ML model-as-a-map organizes input data to estimate output data, you gain understanding of the mapping relation between the structural (internal?) organization of the data and the abstract representation of T.
You look at the structural organisation of data on the ML model-as-a-map, and because there is some similarity/isomorphic mapping you look into the abstraction of T (TML targets) ***==and draw inferences about some relevant features of the target in abstract representation (bottom horizontal link).==***

***==So you can draw inferences on the external target (actual T) by drawing inferences on the TML target (abstraction of T) ??==***

**You do not take the ML model-as-a-map and draw direct inferences on the world.**
**But you draw inferences on the abstract representation of the world.**

***==Are they truly saying: by looking at the abstract representation of T (which is not looking at actual T), you better understand the external target?==***

### Mapping relations according TML hypothesis?
- there needs to be some mapping relation between how the ML model organizes x to y data and the abstraction of T
- ==is there a twofold mapping? ==
	- mapping between M data representation and T - ***==not TML??==*** (top horizontal link)
	- Intra-model inferences on data transformation (vertical link)
	- mapping between M and TML (bottom horizontal link)


### TML target = appropriate target of understanding for ML models
**Do T&S mean the following?**
To understand relationships of features represented by the data, you have to understand how the ML model organizes raw input data to optimally estimate y-targets.

i.e. to understand the TML target, you have to draw intra-model inferences on how model data is structured.

The TML target ***==refers==*** to the external target phenomenon that the ML model is used to understand. 
The TML target is the relationship patterns of target features as they are represented by the data.
The TML target is an abstract representation of relationships of features of the external target.
==The TML target is not how the ML model organizes raw input data to optimally estimate y-targets.==
The TML target does not refer to the vertical side of the C-schema!
Thus, T&S can say that:
- “In order to study trained ML models, especially complex DL models, **==for insight into external targets==**, we must first clarify how a **==link from ML models to TML targets==** (horizontal bottom side of a C-schema) may work.” (Shech and Tamir, 2022, p. 9)

T&S understand the TML target similar to the "learned" probability distribution estimating the "true" distribution describing the external target phenomenon's features.

### Different words that all refer to TML targets
- estimator's learned transformations
- learned representation layers
- relationships of features represented by the data, feature relationships
- learned sample probability distribution



### C-Schema for T&S approach
Horizontal top link concerns the modeling or representational relationship between M and T
- as the top link determines what the model represent, the top link also determines whether or not the model can be linked to the target "shit in, shit out?"
- ==T&S identify this relationship as relevant for determining link uncertainty:== does M model, i.e. identify features that are causally relevent to T?
- ***==However, T&S would then identify an different target for each horizontal link: external T at the top, TML-target at the bottom==***

Vertical side concern making intra-model inferences on data transformations

Intra-model inferences give then the basis for the horizontal bottom side that concerns the understanding of the TML target which then improves understanding of T.
- this link is what "understanding" refers to: using M to understand T
- ***==but isn't this what identifies what the driving cause in T is, thus, what needs to be empirically validated acc. Sullivan? (so it is the bottom link that determines link uncertainty and not the top?)==***


By sampling data (x,y) one gains a sample probability distribution that estimates the true probability distribution p(sampled output element y of state space Y given sampled input element x of state space X).
A ML algorithm (i.e. the estimator function scoring conditional probabilities of (x,y)) "learns" to best estimate the true probability distribution.
The scoring conditional probabilities of (x,y) induces a sample probability distribution.
A trained ML algorithm induces/ learned a sample probability distribution (any output element y of state space Y given the sampled input element x of state space X) by how probable it estimated (i.e. scores) an output element y given sampled input elements x. 
The sample probability distribution is then generalized to the distribution underlying the whole input population. 
- ==“That is, the result of an ML training process is an estimator f0 for random variable Y given X, such that the model can estimate conditional probabilities p0(Y=y given X=x) induced by the scoring function f0 for given x values.” (Shech and Tamir, 2022, p. 7)==

### Functionally Approximate Irrelevance
A ML model's learned probability distribution depends directly on parameterization and model architecture.
FAI is when variations in parameterization change how the learned distribution is induced by the model, but only in ways that preserve 

***==FAI is when variations in parameterization change the TML target, but only in ways that preserve the relevant features of the external target phenomenon that the TML target is an abstraction of.==***



Parameterization influences how the TML target "looks" (which feature relationships it represents).
FAI means that a parameterization preserves how a TML target "looks" relative to another different parameterization that generate a equivalent TML target

To understand the TML target, you have to draw intra-model inferences on how model data is structured.
But if the difference in how the model data is structured is functionally approx. irrelevant, then understanding of the TML target is still possible.
### Modes of Understanding
By "modes of understanding", T&S refer to understanding different aspects of the TML target. 
==It is not about modes of understanding that enable to draw intra-model inferences!==

***==Modes of understanding = to draw inferences on/ attributing which features of the TML target are predictive of the external target phenomenon==***
- Informative Relationship: 
- Feature Importance: attribute which x-features are predictive of the target
- LR

==***I guess that the modes of understanding are to understand this mapping relation between the organisation of model data and the abstraction of T?***==


### what T&S have to say about Sullivan
“Sullivan’s argument refutes that DL models cannot be used for understanding merely due to some opacity, but the reliance on the implementation irrelevance of certain details, ==particularly their irrelevance to the target of understanding==, is essential for this defense.” (Shech and Tamir, 2022, p. 10)

“Our account may be interpreted as a refinement of Sullivan, making explicit that accounting for role and degree of approximation matters to understanding.” (Shech and Tamir, 2022, p. 10)
-  






Classifier function is implemented by DNN vs is a property of DNN:
The classifier function is an abstract way to describe what the DNN does. 
It is like to say a map has an orientation function: given the location features I see in the world as input, the map puts out the location on the map that enables me to orient myself in the world, i.e. understand where I am in the world. 


“On the vertical side of the C-schema, one interacts with M directly to draw inferences” (Shech and Tamir, 2022, p. 4) 
- "on the vertical side one interacts with M directly to understand relationships among data"
- **understanding relationships among data = to draw intra-model inferences**


“Inferences about how well the model can estimate y-targets given x-data, exploration of what particular features of x-data tend to play important roles in (correct) estimations of y-targets, and the study of how network parameters and hidden layer transformations organize and restructure x-data to effectively estimate y-targets are all examples of “vertical” inferences in a C-schema.” (Shech and Tamir, 2022, p. 8)
- To make intra-model inferences is to understand how well the model can estimate output elements given input elements.

“For instance, in a typical map (or map-like) model, we can not only use M to draw inferences about T but we can also see how such inferences are drawn, for example, because of relevant similarities or isomorphic relations associated with M and T (say, a map and a city)” (Shech and Tamir, 2022, p. 5) 
- **understanding gained from maps vs ML models:**
- using the model to understand something of T 
- **"interacting directly" with the model to understand how the model enables understanding of T**
	- so this concerns "what powers understanding" from the model
	- so T&S are interested in what powers understanding from the model/ how the model enables understanding of T

How does a map enable understanding of a T? By relevant similarities between the map and T  
How does a ML model enable understanding of T? By relevant structural similarities between the ML model and and abstraction of T

“We argue below that while DL models do not necessarily provide understanding in the same manner as (say) map representations, learned representation layers may be leveraged to improve understanding by providing insight into how a DL model learns to organize raw input data to optimally estimate y-targets.” (Shech and Tamir, 2022, p. 7) 


“Inferences about how well the model can estimate y-targets given x-data, exploration of what particular features of x-data tend to play important roles in (correct) estimations of y-targets, and the study of how network parameters and hidden layer transformations organize and restructure x-data to effectively estimate y-targets are all examples of “vertical” inferences in a C-schema.” (Shech and Tamir, 2022, p. 8) 

