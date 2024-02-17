It seems that Sullivan adheres to the following view when it comes to modelling DNN:
The model is a function. Before training the set of weights describe a function that is far from capturing the phenomenon. During training the set of weights change and describe a function that better captures the phenomenon. The function that truly captures the phenomenon can never be reached. After training the set of weights describe a function that is a close approximation of the true target function. The DNN "learns" its own algorithm that governs the input-output relation and drives the model decision. This higher-level algorithm is the result of the modelling process.
- “In machine learning, the word “hypothesis” is often used interchangeably with “model”. A hypothesis is a function described by the set of weights that is presumed to capture the phenomenon. The target function is the function that will truly capture the phenomenon. Often the target function is an ideal that is not reachable; the goal is to settle on a hypothesis that is as close to the ideal target function as possible (see Mitchell [1997]).” (Sullivan, 2022, p. 16)
- “The result of the modelling process produces a DNN model that follows its own algorithm that it learned through the modelling process. The modelling process is what determines the set of steps or rules that the resulting model will follow with any new input data it receives.” (Sullivan, 2022, p. 17)
- “So, while the modeler does not have direct control over the modelling process, a contrast case with Schelling’s model, still the process is not black boxed at the highest level, such that it would prevent understanding of the phenomenon the resulting model aims to capture.” (Sullivan, 2022, p. 18)
- “Once the model is trained, the modeler still has a general idea of how the finalized model works in virtue of having knowledge about how the model was trained and validated.” (Sullivan, 2022, p. 18)
  
The question however is:
- Is the assumption correct that it is the function described by the set of weights that drives the model decision?
- Is the analogy between the higher-level algorithm and the classifier function in the DNN correct correct?
- Can this function be understood analogous to the higher-level algorithm of the Schelling model?
- Is there even something like a "function" that is implemented by the DNN?
- Is this function intelligible to the modeler?  
- What does actually drive the DNN model decision?
- Is this function only based on the optimized set of weights after training? 
- Or is the final function better described by the whole history of sets of weights during training? i.e. it cannot be described solely on the basis of the final parameterization?

## failed analogies
- a climate model is very different from a deep patient DNN as I cannot imagine how it would be empirically validated in the same sense as the DNN would be empirically validated?
- sub-models of a climate model could theoretically be empirically validated, but the whole model with all kludges (and admittedly it seems that there are a lot of untheorerical parts to a climate model)?
- as Sullivan argues that a good model is one that is linked to the target, it sounds like climate models can never be good models?
## no link vs weak link?
- “Without empirical evidence validating that the possible causes identified by Shelling’s model are actual causes, there is no link connecting the model to the phenomenon. There is a high level of link uncertainty, that is, a lack of scientific and empirical evidence supporting the link that connects the model to the target phenomenon.”
- “to reduce link uncertainty”
- “when the link uncertainty is removed”
- lack of selectivity: no link that needs to be established? Or link with high level of uncertainty?
- Is it even possible within Sullivan's own framework that link uncertainty can be completely "removed"?
- “There is a high level of link uncertainty, that is, a lack of scientific and empirical evidence supporting the link that connects the model to the target phenomenon.”
- **point of attack** lack of selectivity: right before lack of validating that the modeled causes are the actual causes means "no link", now there is a link, but it is not supported by evidence, i.e. the exiting link has a high level of uncertainty
- “The way of establishing the necessary link”
- critique: it needs to say "the way of reducing link uncertainty" or "the way of supporting the established, but weak link"
- “to reduce link uncertainty”
- critique: here, she switches back to degrees of uncertainty of an established link
- “The stronger the link, the greater possible understanding the model can provide.”
- again, here degree of link is about degree of possible understanding
- “once the link uncertainty is resolved”
- and again, can link uncertainty ever be resolved?
- “because of reducing link uncertainty”
- I thought it was about "resolving link uncertainty"?

## what is meant by empirical evidence?
- “What constitutes the amount and kind of scientific evidence needed to reduce link uncertainty will differ depending on the phenomenon and the model. In the case of Schelling’s model, link uncertainty is inversely related to the amount and quality of empirical evidence connecting individual preferences to causes of segregation and a lack of evidence that suggests a different overriding causal factor.”
- “The level of scientific justification and background knowledge linking the appearance of moles to instances of melanoma is extensive”
- “Understanding is narrowed to a population subset, which is common in medical sciences. Just like many other scientific models, the usefulness of the model depends on the target system and the explanandum. If certain parameters change, the given model ceases to be the right model for explaining.”
- empirical/ scientific evidence, background knowledge, model, phenomenon, contextual parameters – what else does impact link / link uncertainty?


## distinction between understanding how the model works and using the model to understand the phenomenon?
- “There is a distinction between understanding and explaining how the model works and using that model to understand a phenomenon of interest. If one is chiefly concerned about explaining or understanding how a given model is implemented, it is not necessary to know how the model maps on to some real-world phenomenon. The question of this paper, on the other hand, is to what extent understanding the model is necessary for gaining understanding of the phenomenon that the model explains.”
- how distinct are these perspectives really?
- is it true that understanding how the model maps onto the phenomenon is irrelevant for understanding model implementation?
- however, from that it does not follow for Sullivan that if you are mainly interested to understand how the model maps onto a phenomenon, you do not need understanding of model implementation  
- **point of attack** "is it possible to argue for the possibility of understanding from ML models without saying anything about what this understanding is?"
- "how is it possible schizo can be predicted and correlated with features found in medical records?"
- but is that a how-possibly question asked to understand possibilities surrounding target systems OR to understand how the model works?
- RELEVANT to reinstall opacity as relevant factor for understanding
- if understanding how a phenomenon is possibly predicted using the model necessitates insight into the model workings, then model opacity impedes  understanding.
- if understanding how a phenomenon is possibly predicted using the model does not necessitate insight into the model workings, then model opacity  does not impede understanding.

## mapping? (relevant for distinction?)
- “This mapping allows us to interpret the results of the simulation as identifying a possible causal mechanism of segregation.”
- critique and ?: what does "mapping" mean?
- what does it mean that "it maps onto a possible population"?
- to what does the algorithmic model (its "key features") map onto?
- to the modelled "causes and dependencies operating in the target phenomenon"?
- to the target itself (segregation)?
- is the mapping getting empirically validated?
- is the connection between identified causes and actual causes empirically validated?
- "empirically validated" means "connecting identified causes to actual causes
- "validating the model-target mapping" means empirically validate the possible causes identified


### Creel:
- it seems like Sullivan employs a notion of transparency while arguing for DNN not being highest-level black boxes, i.e. the high-level algorithms and properties of DNN are transparent. At first glance, this seems to be what Creel calls "functional transparency", i.e. the modeler has epistemic access to knowing “high-level, logical rules according to which the system will transform a given input into an output.” (Creel, 2020, p. 9) 
- However at second glance, Creel's notion of functional transparency seems to not apply to DNN
- I don't whether this is relevant or not