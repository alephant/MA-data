

- **goal**: “we show how direct analysis of an estimator’s learned transformations (specifically, the hidden layers of a deep learning model) can improve understanding of the target phenomenon”
- “We argue below that while DL models do not necessarily provide understanding in the same manner as (say) map representations, learned representation layers may be leveraged to improve understanding by providing insight into how a DL model learns to organize raw input data to optimally estimate y-targets.”
- **T&S key approach:** by looking at learned representation layers in DL one can gain understanding of how intra-model inferences are drawn (i.e. how the ML model learns to organize raw input data to optimally estimate target features) and by understanding how intra-model inferences are drawn one can gain understanding of the external target phenomenon

## narrow view on understanding
- **why narrow?**
- Direct analysis of how intra-model inferences are drawn in ML models improves understanding of external target phenomenon
- Target of ML Hypothesis: what is the appropriate target of understanding for ML models? TML-targets!

## T&S: scientific models vs ML models

- how the term model in ML contrasts with traditional usages of scientific models for understanding, resolving core ambiguities involving representational links to the target phenomenon: **not differentiating between the meaning of scientific model vs ML model creates misunderstanding about what is meant by "links to the target phenomenon" - T&S want to resolve these ambiguities**
- **understanding gained from maps vs ML models:** by looking at map representations one can gain understanding of how a map model draws inferences about the target system  



## (TML) Target of ML Hypothesis

- The target phenomenon of understanding with ML models is the relationship(s) of features represented by the data.”
- i.e. the appropriate ML target of understanding is not the external phenomenon
- but how “relationships of features found in the external phenomenon” are represented by data
- i.e. the hidden layers of a DNN
- the appropriate target phenomenon of understanding for ML models are **how intra-model inferences are drawn**
- **and these intra-model inferences are targeted by modes of understanding and this understanding is enabled through FAI**
- to say it differently: by understanding the "relationships of features represented by the data" (TML target intrinsic to the model) the "real-world relationships of features found in the external phenomenon" can be understood
- there are different modes of understanding depending which TML target one chooses; these enable different kinds of understanding of the external phenomenon
- Relation to link uncertainty: Based on this TML target-oriented understanding one is in the right position to evaluate link uncertainty between the ML model and the external target
- to say it differently, to properly evaluate link uncertainty and thus, make sure that the model enables understanding of the external target phenomenon, one needs to look at how intra-model inferences are drawn

## TML-targets

- What do the hidden layers of a DNN tell us?
- How intra-model inferences are drawn = TML-targets
- variation in implementation matters for the TML target (how the intra-model inferences are drawn), but not in ways relevant for understanding the external phenomenon as the variation in implementation is approx. irrelevant for modes of understanding using ML models such as IR understanding etc.
- 

## The problem with Sullivan's view on implementation irrelevance

- If implementation black boxes are irrelevant for understanding from ML models (Sullivan's take)
- how can we gain understanding of intra-model inferences which depends on insight into detail implementation (T&S take)?
- Which in turn would be relevant for understanding the external target phenomenon (T&S take)?

## Functionally Approximate Irrelevance

- variation in implementation does matters for the TML-target (how the intra-model inferences are drawn)
- but only in ways that approximately preserve relevant features of the target phenomenon
- i.e. variation in implementation is functionally approx. irrelevant for understanding certain aspects of how intra-model inferences are drawn
- Dilemma solved: Based on FAI we can gain understanding of intra-model inferences even with implementation black boxes
- impl. irrelevance: variation in implementation does not matter for understanding
- FAI: variation in implementation matters for the **TML target** (how the intra-model inferences are drawn), but not in ways relevant for understanding the external phenomenon as the variation in implementation is approx. irrelevant for modes of understanding using ML models such as IR understanding etc.
- two models come up with equivalent estimates of the actual distribution describing the external phenomenon's feature relationships (i.e. if they do output the same classification, predict the same disease)
- i.e. functionally approx. irrelevant variations in implementation imply that relevant feature relationships of the external phenomenon are approx. preserved in their model representation
- what happens when variations in implementation between models is NOT aprroximately irrelevant:then one cannot gain understanding of "relationships of features represented by the data" which enables correct predictions of the external target
- i.e. if the **variation in implementation is functionally approx. irrelevant for understanding the TML target,** one can still gain understanding of "real-world relationships of features found in the external phenomenon"  
- **functionally approx. irrelevant variations in implementation imply that relevant feature relationships of the external phenomenon are approx. preserved in their model representation**

## modes of understanding

- FAI-enabled?
- T&S identify modes of understanding that target different aspects of how intra-model inferences are drawn (TML-targets)
- IR: understanding how well the model can estimate target features given input data
- IF: understanding of which particular features of input data are important for correctly estimating target features
- LR: understanding how input data is transformed in learned representations to estimate target features
- Even highest-level black box compatible with understanding TML-targets!
- While the variation of implementation matters for how intra-model inferences are drawn, the variation does not matter for IR understanding
- The exact implementation of the intra-model inferences can be black boxed, but as they are "sufficiently reliable" they enable IR understanding
- **how invariant intrinsic properties of learned representations (e.g. relative angle or position among embeddings in embeddings space) allow for "direct engagement with hidden layer representations to gain LR understanding"**


## The problem with Sullivan's view on link uncertainty

- “We argue that focusing on precisely what features sampled data do and do not represent is paramount to evaluating ML model link uncertainty.”
- “In this section, we consider examples discussed by Sullivan to disambiguate two kinds of link uncertainty that we submit are conflated in Sullivan (2022) so that the understanding gained from FI and LR can potentially be leveraged to prevent such uncertainty.”
- “The data used by an ML model must represent the targeted features of the phenomenon as intended. If not, a background of scientific evidence does not prevent misrepresentation uncertainty.”
- **Representation of the target phenomenon as intended must be established as well in order for there to be a link connecting model and target.**
- To remove empirical link uncertainty is not enough, to establish a link between model and target.
- Data-misrepresentation link uncertainty must be removed as well, i.e. a representational link must be established.
- Establishing an empirical link means that target features identified by the model are empirically validated as being some actual target features
- (in Sullivan's words that the possible causes that are being identified by the model are empirically validated as being the actual causes)
- Establishing a representational link means that target features must represent the actual target features and not some other unintended features
- **In addition to what Sullivan claims is needed for empirical link (background knowledge etc.) T&S claim additional criteria are needed to be truly able to establish a link**: appropriate sampling methodology and data preparation is necessary to make sure that all data that is used to train the model represent the target phenomenon as intended and do not include unintended features that cause unintended although veridical matches


## connection between TML targets and external target phenomenon
- as these modes of understanding target "relationships of features represented by the data" they give indication of "real-world relationships of features found in the external phenomenon"
- as these modes of understanding target "relationships of features represented by the data"
- they give indication of "real-world relationships of features found in the external phenomenon“
- by looking at hidden layers one can gain understanding of how intra-model inferences are drawn (i.e. how the ML model learns to organize raw input data to optimally estimate target features)
- and by understanding how intra-model inferences are drawn one can gain understanding of the external target phenomenon



## highest-level black box
- “With the ML model’s target clearly defined as the relationships of features represented by X and Y, the fact that [the different learned parameterizations] has approximate irrelevance becomes clear: approximates p(Y|X) well enough, so while the details matter to how the estimates are made, they can still be (approximately) irrelevant for the target of understanding. With the functionally approximate irrelevance of particular parameter details ensured, IR understanding even with “highest level” opacity is possible.”
- if the variation in implementation is functionally approx. irrelevant for understanding certain aspects of how intra-model inferences are drawn e.g. how well the model can estimate target features given input data (IR), one can gain still understanding of the external phen., even when the model implementation is opaque.
- **While the variation of implementation matters for how intra-model inferences are drawn, the variation does not matter for IR understanding.**
- The exact implementation of the intra-model inferences can be black boxed, but as they are "sufficiently reliable" they enable IR understanding.
- **Conclusion**: Highest-level implementation black boxes are compatible with understanding if variation of implementation is approx. irrelevant for understanding the TML target.




