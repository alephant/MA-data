### On Creel

- **crucial question on functional transparency:** does this mean to know what the overall algorithmic goal of DNN is, e.g. its classification goal? what is "the" algorithm that a DNN instantiates?
- Does Sullivan's approach at least require functional transparency of a ML model?
- On Creel's notion of functional transparency relating Sullivan: it sounds like variation in detail implementation does not impede functional transparency i.e. detail implementation (relations between its part) is irrelevant, but "higher-level algorithmic goals" still to be known for opaque ML models to provide understanding?
- A. variation in detail implementation of a ML models does not impede functional transparency
- B. ML models that employ genetic programming fail to be functionally transparent
- A. & B. collide
- how would I differentiate a kludge from a non-kludge without understanding detail implementation? this sounds a lot like to guarantee and maintain functional transparency one needs detail insight that makes functional transparency irrelevant in the first place?
- “Only at a higher level does structural opacity emerge.” (Creel, 2020, p. 15) 
	- Doesn't this run counter Sullivan's claim that knowledge of higher-level emerging properties is needed to gain understanding from opaque ML models? 
	- This would mean that counter what I previously said structural opacity is in fact relevant for understanding as it concerns higher-level properties and not detail implementation
- 


### failed analogies
- a climate model is very different from a deep patient DNN as I cannot imagine how it would be empirically validated in the same sense as the DNN would be empirically validated?
- sub-models of a climate model could theoretically be empirically validated, but the whole model with all kludges (and admittedly it seems that there are a lot of untheorerical parts to a climate model)?
- as Sullivan argues that a good model is one that is linked to the target, it sounds like climate models can never be good models?


ON T&S:
- key question: is FAI and the ways to fix misrepresentation LU that are proposed by T&S themselves compatible?
- If preventing data misrepresentation link uncertainty needs model transparency, then how can the reasoning behind FAI be upheld that dismisses opacity 
- see “With the functionally approximate irrelevance of particular parameter details ensured, IR understanding even with “highest level” opacity is possible.” (Shech and Tamir, 2022, p. 11)
- **How can opacity be irrelevant for FI understanding of intra-model feature relationships while at the same time data misrepresentation has identified as an additional factor contributing to link uncertainty?**
- This would reinstate opacity as a problem for linking the model to the target as opacity would impede the fixing of data misrepresentation LU
- **criticism**: we could know that there is a similarity relationship in the general characteristics of the model-internal data relationships, but we could not say how these data relationships would look like, right?