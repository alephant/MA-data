**T&S key approach:**  
To improve understanding how a ML model draws inferences on T, i.e. how the ML model enables understanding of T (= how the ML model comes to an optimal estimation of probability across output elements/ distribution of probability mass across elements of state space for random variables Y) we need to look at learned representation layers (i.e. data representations) to gain understanding, i.e. draw intra-model inferences on how the ML model organizes raw input data to optimally estimate y-targets.

So, it is about understanding how the ML model data is structured to enable optimal estimation / optimal prediction / enable optimal understanding.

T&S are interested in understanding what powers understanding from the ML model.
By "interacting directly with the model" one can gain understanding of how the model enables understanding of T.
e.g. a map enables understanding of a city. So one can use the model to draw inferences on the city. But we can also look at how the inferences on the city are drawn, i.e. understand how the map enables understanding of the city by looking at the relevant similarities between the map and the city.
So the question that T&S are interested in is: 
How does a ML model enable understanding of T? How can we improve understanding from ML models on T?

### C-Schema
The horizontal top of the C-schema concerns the modeling or representational relationship between M and T
- ==T&S identify this relationship as relevant for determining link uncertainty:== does M model, i.e. identify features that are causally relevent to T?

Last, on the horizontal bottom side, M is used to relevantly draw inferences and answer questions about, or impute properties to, T.
- this is link is what "understanding" refers to: using M to understand T


By sampling data (x,y) one gains a sample probability distribution that estimates the true probability distribution p(sampled output element y of state space Y given sampled input element x of state space X).
A ML algorithm (i.e. the estimator function scoring conditional probabilities of (x,y)) "learns" to best estimate the true probability distribution.
The scoring conditional probabilities of (x,y) induces a sample probability distribution.
A trained ML algorithm induces a sample probability distribution (any output element y of state space Y given the sampled input element x of state space X) by how probable it estimated (i.e. scores) an output element y given sampled input elements x. 


### Modes of Understanding
By "modes of understanding", T&S refer to different ways to draw intra-model inferences. 
==It is not about modes of understanding the enable to draw intra-model inferences!==

**Modes of understanding = to draw inferences on how different aspects of how the model data is structured:**
- IR understanding: understanding how well the model can estimate target features given input data
- IF: understanding of what particular features of input data are important for correctly estimating target features
- LR: understanding how input data is transformed in learned representations to estimate target features




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

