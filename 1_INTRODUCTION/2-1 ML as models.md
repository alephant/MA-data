Weisberg (2013, 15) sees models as "interpreted structures": the structure of the Schelling model e.g. is a set of states and transitions. The interpretation of the structure "tell us what the model is about and set up relations of denotation between models and their intended targets".

**What of the model carries the explanatory force?**
Types of models can be distinguished in how they are used to give scientific explanations. 
For explanations given by computational models such as Schelling model, the explanans is typically the transition rules or the algorithm. "Schelling explained segregation by pointing out that small decisions reflecting small amounts of bias will aggregate to massively segregated demographics. Neither the time sequence of the model's states nor the final, equilibrium state of the model carries the explanatory force; ==the algorithm itself is needed==." (Weisberg, 2013, 20)

So while mathematical and computational models are not ontologically distinct, they are practically different in how they explain and represent the phenomenon of interest.

Weisberg argues that to understand "the nature of models and model-world relations, we should be thinking about models much closer to the level of abstraction at which they function" (Weisberg, 2013, 23).
Schelling model functions on the basis of abstracting from individual preference to model agent's preference. 
What is the level of abstraction at which DNN function?

**Model parameters**
"Model descriptions also contain parameters, which are fixed and taken to be exogenous, outside the scope of what the model can represent directly."
e.g. the model parameter of Schelling model that represents individual preference is pre-set, similar to how nothing in a DNN directly informs the setting of its hyperparameters, they are pre-determined by the modeler.

**Computational models - algorithm - causal properties**
The core structure of computational models is procedural. This means that the computational structure, e.g. the algorithm can be understood as a set of instructions that carries out a procedure. 
"[Computational models] represent causal properties of their targets by relating these causes to procedures." (Weisberg, 2013, 31)

**Model descriptions**
Model descriptions specify models, models realize model descriptions. (Weisberg, 2013, 35)
The relationship between model descriptions to models is many-to-many. (Weisberg, 2013, 35)
Mathematical models can only be manipulated using their abstract descriptions in the form of mathematical equations.
Computational models are typically described abstractly by explicating the model's procedures in programming code or discrete mathematics (Weisberg, 2013, 38).

Model construal: interpretation of model structure (Weisberg, 2013, 3.3)
"These four components of construal constitute the theorists' interpretation of the model":
Assignment: "explicit specifications of how parts of real or imagined target systems are to be mapped onto parts of the model"
Scope: specifies which aspects of potential target phenomena are intended to be represented by the model
Fidelity criteria: describe how similar the model must be to the world in order to be considered an adequate representation (dynamical: how close must the model prediction match the behavior of the phenomenon; representational: how closely must the internal model structure match the causal structure of the phenomenon)

**Idealization**
An idealized model represents its target system in some distorted way, i.e. misrepresents its properties.

**Galilean idealization**: introducing distortions into models in order to make them more computationally tractable. The key features of practicing Galilean idealization are: pragmatic, for computational tractability, nonpermanent, expecting future de-idealization and more accurate representation
==Is this the kind of idealization involved in DL?==

**Minimalist idealization**: "a minimal model contains only those factors that make a difference to the occurrence and essential character of the phenomenon in question" (Weisberg, 2013, 100)
==Or are minimal models constructed by employing DNN models?==

==Does **Multiple-Models Idealization** has anything to say to a **combination of Sullivan's and T&S' approach to using DNN as scientific models**?==

What is the relation between models and targets?
The weighted feature-matching account of similarity says that "models stand in representational relations to their targets, not lacking too many of these features, and not having too many extra features".
"Scientific context, as specified by the modeler's construal, determines the choice and weighting of important features." (Weisberg, 2013, 173).
For computational models, "features of models are compared to mathematical representations of features of targets"



idealization, simulation, abstraction, similarity:
- “The semantic conception provides a straightforward answer to the question of how models give us knowledge of the world: they specify structures that are posited as possible representations of either the observable phenomena or, even more ambitiously, the underlying structures of the real target systems.” (Knuuttila and Merz, 2009, p. 4) ==semantic approach to modelling==
- “Thus, according to the semantic view, the structure specified by a model represents its target system if it is either structurally isomorphic or somehow similar to it.” (Knuuttila and Merz, 2009, p. 4)


**de Regt: models are explanatory, i.e. they can provide some understanding, because they represent their target and are intelligible (i.e. have qualities that facilitate their use)**
“De Regt takes understanding on the basis of models to be possible if they are explanatory qua representational (also Giere, 2006, Chapter 4). A similarly important role for representation is reserved by Morrison (1999, p. 63): The reason that models are explanatory is that in representing [their target] systems they exhibit certain kinds of structural dependencies. The model shows us how particular bits of the system are integrated and fit together in such a way that the system’s behaviour can be explained.” (Boge, 2022, p. 53)

“Hence, establishing ways in which to represent a certain target by means of a model allows us to map the relations established in the model onto relations pertaining, for all we know, to the target, and so, if the model’s behavior matches that of the target in relevant respects (e.g., segregation patterns emerge), we may infer an explanation of the observed target-behavior from the model (e.g., in terms of moving behavior being in part determined by preferences for neighborhood-composition).” (Boge, 2022, p. 54)

**de Regt: theories and models are explanatory if they have qualities that faciliate their use**
“In de Regt’s account, for representational models to explain, they must also be constructed under the principles of an intelligible theory, where a theory is intelligible if it has certain qualities that “provide conceptual tools for achieving understanding” (de Regt, 2017, p. 118; emph. added). ==Among these tools, de Regt (2017, p. 115) lists “visualization, mathematical abstraction, and causality [as] prime examples.”==” (Boge, 2022, p. 54)

“However, de Regt spells out the intelligibility of a theory in terms of “qualities [...] that facilitate the use of the theory” (de Regt, 2017, p. 40; emph. added), and Reutlinger et al. (2018, pp. 1084–1085) equally offer a use-oriented, empirically accessible explication of Strevens’ notion of grasping.” (Boge, 2022, p. 54)

i.e. the representations of the model need to be adquate to make target mechanisms intelligible

---



**Three distinct senses of DNN as "models" identified by Boge**
“In sum, at least three distinct senses of ‘model’ should be distinguished here, which, so far as I can see, exhaust the use of ‘model’ in the DL literature: (a) DNNs as (crude) models of actual brains, (b) the algorithms employed in DL as abstract, selective models of human learning, and (c) the input–output mappings approximated through training as models of features pertaining to the data, such as their statistical distribution.” (Boge, 2022, p. 46)

**DNN as models or techniques? DNN as crude models of the brain**
“Napoletani et al. (2011, p. 13) actually refrain from calling DNNs ‘models’ altogether and solely use ‘technique’. Humphreys (2013,  p. 580), on the other hand, acknowledges the possibility of “simulating neural dynamics” with DNNs, but also urges to “keep separate uses of neural nets as simulation models from their use as techniques in computational science”, and additionally finds most neural nets to be “extremely crude models of real brains[...].” The latter verdict is frequent in the literature (e.g. Chirimuuta, 2020; Goodfellow et  al., 2016; Sullivan, 2019), not least ==because feed-forward processing and gradient descent are biologically implausible==;” (Boge, 2022, p. 45)

**Algorithms employed in DNN as abstract models for human learning**
“Note that the learning algorithm involved in deriving this model may itself count as yet another model: Buckner (2018) points to the possibility of understanding concept abstraction on the basis of deep convolutional nets, without drawing too close a parallel to either brain processes or most details of human cognition. Similarly, it may be possible to understand certain errors made by DNNs in analogy to errors made by humans under similar conditions (Buckner, 2021, for discussion).” (Boge, 2022, p. 46) 

**Objectual approach by Knuuttila and Merz**
Knuuttila and Merz (2009) presents an objectual approach to modelling according to which a model is an 'concrete constructed object'. Its function is not representive, but productive. The way a model provides understanding depends on the way we interact with it and how it is implemented. Thus, a single model may provide a multiplicity of understanding depending on its practical use. The specific implementation of a model is key to understand how the model affords understanding. The objectual approach allows for models to be highly unrealistic while still allowing for understanding to be gained. 


A classical approach to scientific modelling is that relevant model features are measurable and specified, parameter values remain largely consistent across domains of application and model assumptions are few. On the other hand, the idea of DNN models is that their relevant model features are initially unspecified and are acquired through training. However, due to their high level of opacity, it proves to be difficult to determine which features a DNN model tracks and what the parameter values are. When DNN models are applied to new domains, their parameterization usually changes drastically (Scorzato_2024).