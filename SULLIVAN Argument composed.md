## Research question

**To what extent is model opacity a problem for understanding from ML models?**
To what extent is opacity of ML models relevant for understanding a target phenomenon that the ML model bears on?
Is opacity of ML models an in principle problem for understanding a target phenomenon?

Model opacity as a problem for understanding in degrees?
Model opacity as a problem for understanding in principle?

## Sullivan's 2022 paper structure

1. introduction
2. how explain and provide understanding
	1. which role do algorithms play in explaining phenomena
	2. the importance of explanatory questions for understanding
3. algorithms are black boxed by obscuring implementation at various levels
4. cases of DNN models
5. DNN: level of link uncertainty prevents understanding

1 She introduces scientific understanding using models by introducing simple models.
She characterizes simple models compared to complex models.
She introduces her key example for complex ML models and illustrates its usefulness.
She touches on factors that contribute to model opacity and explanatory questions.
She gives an outline of her argumentation and conclusion and lays out the paper structure.

2 She introduces how models are used for scientific explanation and understanding.
She touches the various views on the relation between explanation and understanding.
She briefly expresses her view on the relation between explanation and understanding.
She clarifies that she doesn't need to go deeper than that for her argumentation.
**She clarifies which specific kind of opacity is of interest.**

**She introduces her key example for simple models, the Schelling model.**
She states the model aim and its scientific context of application/ discussion.
She illustrates why the Schelling model is simple.
She touches on explanatory q.s one could ask the model and on their relation to knowledge (e.g. of input-output relations relevant for black boxes, too)
She touches on variation of implementation and complexity.
**She introduces her key distinction between understanding model implementation and understanding the phenomenon using the model.**
She restates her key question in light of this distinction (understanding model implementation necessary for understanding the phenomenon?)

Based on Schelling model, she illustrates how-possibly q.s, the role the model plays in explanation and understanding of possible causes.
She illustrates model mapping as the basis for identifying possible causes.
She illustrates that understanding of actual causes needs empirical validation.

**She introduces her key argument of link and link uncertainty.**
She illustrates a high level of link uncertainty based on Schelling model.
She illustrates how Schelling model was empirically validated.
Based on a hypothetical scenario, she illustrates how Schelling model would not enable true understanding without a link.
She expands on how a link is established and how evidence depends on the phenomenon and the model.
She clarifies that the epistemic value of the model remains even after a link was established.
She briefly links the previous insights based on Schelling model to ML models.

3 She introduces black box models and touches on level of black boxing/ opacity.
She reintroduces ML models as highly black boxed models.
She restates her key question in light of the ML models as highly black boxed models.

3.1 She introduces implementation black boxes as models with opaque detail implementation.
She introduces the comparison of algorithmic models where variations in detail implementation do not make a difference for higher-level implementation.
**She illustrates how understanding detail implementation is irrelevant for understanding target phenomena: implementation irrelevance.**
She links implementation black boxes and impl. irrelevance back to Schelling model.
Based on Schelling model, she illustrates implementation irrelevance.
**She concludes that implementation black boxing/ opacity is not an in-principle problem for understanding target phenomena.**
She introduces cases where implementation black boxes do impede understanding
- if lower-level implementation impacts higher-level implementation/ goals
- if one is concerned with understanding model implementation
- if one needs to track intra-model states

3.2 Based on previous algorithmic models, she illustrates levels of implementation black boxes.
She briefly points out the practical benefit of levels of impl. black boxes.
She points out cases where levels of impl. black boxes are potentially problematic (for the modeler)
She links levels of impl. black boxes back to Schelling model.
Based on Schelling model, she illustrates mid-level impl. black boxes that make no difference for high-level implementation.
She restates and illustrates her conclusion that insight into impl. black boxes is irrelevant for understanding the target phenomenon in the case of Schelling model.
She restates her key argument that link uncertainty impedes understanding.
Based on a hypothetical scenario, she illustrates a highest-level black box in Schelling model.
**She illustrates how a highest-level black box is incompatible with understanding.**
She illustrates how background knowledge of the phenomenon turns a highest-level black box into a simple black box.
**She concludes that the level of black box is coupled with background knowledge of model and phenomenon.**
**She further concludes that the level of black box, type of explanatory question and amount of link uncertainty matter for understanding.**
- highest-level impl. black box is incompatible with understanding
- impl. black box matters for understanding detail model implementation
- link uncertainty impedes understanding

4 She investigates whether DNN models are a highest-level black box.




For her argument to work, she needs to dismiss model opacity as being a relevant criterion.
Based on that, she dismisses model opacity as an in-principle problem for understanding.

## Introduction to the problem of opacity

Models that are simple are easier to understand compared to models that are complex. 
Simple models seem to enable more understanding than complex models.
How simple models work is easier to understand compared to how complex models work.
i.e. simple models are more transparent than complex models.
Thus, model simplicity and transparency seem relevant criteria for models to enable understanding of phenomena.

However, complex models like DNN are more and more in use.
DNN are opaque, increasingly complex and cannot address a wide range of explanatory questions.
Yet, DNN have high predicitive power and increasingly so.
Predictive power is another relevant criterion for models to enable understanding (other criteria?)
One might think that scientists using DNN either trade understanding for some other reason (e.g. pragmatic reasons as the DNN just produces practical results) or that they are misguided in using DNN.
Sullivan argues that model simplicity and transparency are not needed for understanding phenomena. For her, they are not relevant criteria for models to enable understanding.
She argues that complex and opaque models such as DNN can provide understanding nonetheless.
Or to say it differently, that it is not due to complex and opaque models being complex and opaque that they cannot provide understanding.
She argues that the there needs to be a link connecting the model to the target phenomeon that is needed for understanding. 
For her, this link being established by empirical evidence is a relevant criterion for models to enable understanding.

## Sullivan needs to show

For her argument to work, she needs to dismiss model opacity as being a relevant criterion.
She introduces implementation black boxes as a way in which a model can be opaque.
She shows that implementation black boxes are not a in-principle problem for understanding except for the case of a highest-level black box.
Based on that, she dismisses model opacity as an in-principle problem for understanding.

==She introduces black boxes.==
==She introduces black boxes as model which implementation is opaque at various levels.==
==She establishes that implementation is irrelevant as long as long as the higher-level emergent properties remain the same.==
==As long as the higher-level emergent properties of the model remain the same, the model's ability to enable understanding remain the same.==
==Thus, she then dismisses implementation as being relevant for understanding phenomena.==
==She then shows that if a model== 



## Conditions for Model-Oriented vs. Target-Oriented Understanding

She illustrates various model-related concepts on the basis of simple models.
The Schelling model is her key example for simple models.

Based on the Schelling model, she introduces the distinction between understanding how the model works, i.e. how the model is implemented, e.g. algorithmically, and understanding a phenomenon that the model bears on.
Let's call the first model-oriented understanding concerned with understanding model implementation and the other target-oriented understanding concerned with understanding the target phenomenon that the model explains.

For her it makes sense that the possibility to gain model-oriented understanding does not depend on gaining target-oriented understanding.
i.e. if one is interested in understanding model implementation, one does not need to understand the target phenomenon that the model explains.
Understanding model implementation in principle requires model transparency. 
If the model is not transparent, its implementation cannot be investigated.
Thus, model opacity is in principle a problem for understanding model implementation.

But is model opacity in principle a problem for understanding a target phenomenon, too?
To what extent is model opacity relevant for understanding a phenomenon the model bears on?
Does one need to understand model implementation, to gain understanding of a target phenomenon?
In relation to ML models these are the questions she is interested in.

## Model Implementation

For her argument to work, she needs to dismiss model opacity as being a relevant criterion for models to enable understanding of a target phenomenon.
Implementation black boxes are a way in which a model can be opaque.
She shows that model opacity is not in principle relevant for understanding a phenomenon as implementation black boxes are compatible with understanding a phenomenon:
- when the model is not black boxed at the highest-level
- when the model is used to gain understanding of the target phenomenon and not on how the model works
- when the amount of link uncertainty is low

Models can be implemented differently.
e.g. the same computational model can be implemented differently by using different programming languages. Or it can be implemented not on a computer, but on a mechnical device.
As long as the input-output relation remains the same, a model shows the same high-level emerging pattern, i.e. the model identifies the same possible causes as being actual causes of the target phenomenon.
When the high-level emerging patterns stay the same, the basis for understanding gained from the model stay the same.
i.e. to gain understanding of a target phenomenon from a model, it is irrelvant when lower-level implementations of the model change, as long as the high-level emerging patterns of the model stay the same.
e.g. as long as the computational model computes the same output pattern based on the same input, it is irrelevant whether the model is implemented in python or c#.

## Implementation Black Boxes
- modelling process of DNN involve implementation black boxing
	- e.g. sub-routines, function calls, unpredictable algorithms
	- deeper black boxing by unpredictable parameterization during training and optimization
- DNN = highest-level black box? No.
	- e.g. no knowledge of goals, no knowledge of I/O-relation, only input & output known
	- background knowledge of the ML model & phenomenon to be understood
	- knowledge of high-level model goals (does the ML model do what it should?)
- Implementation Irrelevance:
- Implementation black boxes, i.e. opacity and complexity of ML models is not an in-principle problem for understanding
- For understanding target phenomena using ML model, knowledge of detail implementation is not needed
- i.e. variations in detail implementation do not matter for understanding
- ML model can give us understanding of possibilities surrounding the target phenomenon – but what about understanding  actual causes?

The implementation of a model can be opaque, i.e. it is unknown or unintelligible to the modeler.
Models whose implementation is opaque are called black boxes.
There are different ways in which a model implementation can be black boxed. 
e.g. function calls (e.g. sig()) calling sub-routines which are not known to the modeler are a type of basic implementation black box. Or the implementation of in principle unpredictable algorithms (e.g. in ...) is a type of implementation black box.

Implementation black boxes can also occur at various levels of implementation.
i.e. the level of the black box can vary.
A highest-level black box is completely opaque.
We do not know anything of what phenomenon it models or how it models the phenomenon.
Thus, a highest-level black box is incompatible with understanding a target phenomenon.
In the case of a highest-level black box model opacity impedes understanding. 
The black box being completely opaque is the reason that it cannot provide any understanding.

The level of the black box depends on our background knowledge. (depends or influenced?)
Depending on the background knowledge the level of the black box is compatible with understanding a target phenomenon or not.

We can differentiate in background knowledge of the model and of the phenomenon.
e.g. we only know the input and output of a model, but we do not know how the input and output are related, i.e. the high-level emerging patterns of the model are unknown or unintelligible. 
Then it seems implausible that we can use the black box to gain understanding of a phenomenon as there is no basis for our understanding.
e.g. the high-level emerging patterns of the model are intelligible, but we do not know anything about the phenomenon they represent. 
Then it seems implausible that we can use the black box to gain understanding of that phenomenon.

Thus, the depth of the black box is influenced by:
- background knowledge of the model
- background knowledge of the phenomenon

When we have relevant background knowledge a model is not black boxed at the highest level.
When a model is not a highest-level black box, it is compatible with understanding a target phenomenon.
When a model is not a highest-level black box, model opacity is not a problem for understanding a target phenomenon.
Thus, whether or not model opacity is relevant for understanding needs to be considered in relation to the level of the black box.
Thus, model opacity is not in principle relevant for understanding.

Besides the level of the black box there are other factors that need to be considered as well.
- the explanatory question asked
- the degree of link uncertainty

## Explanatory Understanding
- “Algorithms on their own are not explanations. It is only when algorithmic models are used to answer a question about some event or phenomenon that they explain.” ([Sullivan, 2022, p. 3](zotero://select/library/items/GQGEYW5N))

A model on its own is not an explanation.
A model only gives an explanation of some phenomon when it is used to answer an explanatory question about that phenomenon.
She adopts the view that explanation aims at understanding.
So depending on the explanatory question asked, the model can give different explanations that aim at understanding different things.
She differentiates between understanding gained from the model when it gives how-possibly explanations compared to how-actually explanations.
How-possibly explanations enable understanding on how the target phenomenon is possibly caused.
How-actually explanations enable understanding on how the target phenomenon is actually caused.
She does not say anything about the exact relation between explanation and understanding or the nature of explanation and understanding, as this is not of her concern. 
For her, explanatory questions are interesting as they tell us something about whether or not a model can enable understanding or not.
By determining which explanatory questions a model can answer and which it cannot answer, one can isolate criteria for understanding.
When asking the model explanatory questions on how the model is implemented, model opacity is clearly a criterion for understanding model implementation. 
If the model is opaque, one cannot gain understanding on how the model is implemented.
When asking the model explanatory questions on how the target phenomenon is possibly caused, ....


## Link Uncertainty introduced by Schelling model

On the basis of Schelling model, she introduces the idea of link uncertainty.
Schelling model can give how-possibly explanations.
If we want it to give how-actually explanations, the explanations need empirical justification.
Schelling model systematically relates model elements with real-world elements. This is called mapping.
The Schelling model maps model elements to real-world elements in order to identify possible causes as being actual causes of the target phenomenon.
The ultimate goal of identifying possible causes as actual causes of the target phenomenon is to explain and understand the target phenomenon.
However, if the identification of possible causes as being actual causes of the target phenomenon is not empirically validated, there is no link connecting the model to the target phenomenon.
If there is no link connecting the model to the target phenomenon, the model cannot give how-actually explanations, and thus, it cannot enable understanding on how the target is actually caused.
If the identification of possible causes as being the actual causes of the target phenomenon is empirically validated, then a link connecting the model to the target phenomenon is established.
If there is a link connecting the model to the target phenomenon, the model can give how-actually explanations, and thus, it can enable understanding on how the target is actually caused.

In the beginning, there was no empirical evidence validating the identification in Schelling model.
It could not explain and enable understanding of its target phenomenon (not even possibilities?)
Later, some empirical evidence was found that validated the identification in Schelling model.
i.e. now there was some empirical evidence that the possible causes as being identified as actual causes by the Schelling model were indeed actual causes of the target phenomenon.
Schelling model can now give how-actually explanations and thus, enable understanding of the how the target is actually caused.
But only to the extent that there is a link connecting the model to the target phenomenon.
"The stronger the link, the greater possible understanding the model can provide."

## What is true for simple models is also true for complex models

Whether or not opacity of ML models  for understanding considering level of black box, explanatory questions asked, link uncertainty

She then applies what is true for simple models to complex models on the basis of the deep patient model as her key example for a complex ML model:
To answer whether or not opacity is a problem for understanding from DNN she considers that:
- DNN are not black boxed at the highest level
- DNN can provide us with how-possibly explanations, ie. they allow for understanding of possibilities; as for simple models it requires empirical evidence to establish link between DNN and its target phenomenon to allow for understanding actual causes surrounding the phenomenon
- as a DNN's level of link uncertainty is reduced by empirical evidence, the better it can provide understanding of a phenomenon















## Conclusion

transparency and simplicity are not relevant for understanding

link uncertainty is relevant for understanding

