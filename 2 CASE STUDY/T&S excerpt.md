**T&S key approach:**  
To improve understanding how a ML model draws inferences on T, i.e. how the ML model enables understanding of T (= how the ML model comes to an optimal estimation of probability across output elements/ distribution of probability mass across elements of state space for random variables Y) we need to look at learned representation layers (i.e. data representations) to gain understanding, i.e. draw intra-model inferences on how the ML model organizes raw input data to optimally estimate y-targets.
- ***=="how the model organizes raw input data to optimally estimate y-targets" = data representations?==***

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

### Key difference & analogy between map and ML model

==**By making intra-map inferences you understand the mapping relation to the external target.**==
==**By making intra-model inferences you understand the mapping relation to the abstraction of the external target. This is what it means to have a narrow view of understanding.**==


**ML model-as-a-map analogy:**
By looking at how the map represents the city, you gain understanding of the mapping relation between the map and the city layout.
You look at the map, and then you look into the world, and then you see the data on the map is organized like this, and because there is some similarity/isomorphic mapping you look into the world and you can draw inferences about the world (bottom horizontal link).

By looking at how the ML model-as-a-map organizes input data to estimate output data, you gain understanding of the mapping relation between the structural (internal?) organization of the data and the abstract representation of T.
You look at the structural organisation of data on the ML model-as-a-map, and because there is some similarity/isomorphic mapping you look into the abstraction of T (TML targets) ***==and draw inferences about some relevant features of the target in abstract representation (bottom horizontal link).==***

***==So you can draw inferences on the external target (actual T) by drawing inferences on the TML target (abstraction of T) ??==***

**You do not take the ML model-as-a-map and draw direct inferences on the world.**
**But you draw inferences on the abstract representation of the world.**

***==Are they truly saying: by looking at the abstract representation of T (which is not looking at actual T), you better understand the external target?==***

### Mapping relations according TML hypothesis?
- there needs to be some mapping relation between how the ML model organizes x to y data and the abstraction of T
- ==is there a twofold mapping? ==
	- Data representation mapping understood by looking at sampling methodology? (top horizontal link)
	- Data transformation through learned representation layers (vertical link)
	- ***==M to TML-mapping understood by intra-model inferences (bottom horizontal link)==***


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



### Wide vs narrow view of understanding from ML models

==Sullivan's target of understanding refers to the external target T==
==T&S' target of understanding refers to the abstraction of T==

==**By making intra-map inferences you understand the mapping relation to the external target.**==
==**By making intra-model inferences you understand the mapping relation to the abstraction of the external target. This is what it means to have a narrow view of understanding.**==

### C-Schema
The horizontal top of the C-schema concerns the modeling or representational relationship between M and T
- as the top link determines what the model represent, the top link also determines whether or not the model can be linked to the target "shit in, shit out?"
- ==T&S identify this relationship as relevant for determining link uncertainty:== does M model, i.e. identify features that are causally relevent to T?

Last, on the horizontal bottom side, M is used to relevantly draw inferences and answer questions about, or impute properties to, T.
- this link is what "understanding" refers to: using M to understand T
- ***==but isn't this what identifies what the driving cause in T is, thus, what needs to be empirically validated acc. Sullivan? (so it is the bottom link that determines link uncertainty and not the top?)==***


By sampling data (x,y) one gains a sample probability distribution that estimates the true probability distribution p(sampled output element y of state space Y given sampled input element x of state space X).
A ML algorithm (i.e. the estimator function scoring conditional probabilities of (x,y)) "learns" to best estimate the true probability distribution.
The scoring conditional probabilities of (x,y) induces a sample probability distribution.
A trained ML algorithm induces a sample probability distribution (any output element y of state space Y given the sampled input element x of state space X) by how probable it estimated (i.e. scores) an output element y given sampled input elements x. 


### Modes of Understanding
By "modes of understanding", T&S refer to different ways to draw intra-model inferences. 
==It is not about modes of understanding the enable to draw intra-model inferences!==

**Modes of understanding = to draw inferences on different aspects of how the model data is structured:**
- IR: understanding how well the model can estimate target features given input data
- IF: understanding of what particular features of input data are important for correctly estimating target features
- LR: understanding how input data is transformed in learned representations to estimate target features

==***I guess that the modes of understanding are to understand this mapping relation between the organisation of model data and the abstraction of T?***==












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

