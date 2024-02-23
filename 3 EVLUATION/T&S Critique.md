## which target phenomenon?
- “real world relationships between features implied by the description that are the target phenomenon not itself.”
- **really irritating: they mean to say "real world relationships between features described by the actual distribution estimated by the model based on relationships of features represented by the data"**
- “we show how direct analysis of an estimator’s learned transformations (specifically, the hidden layers of a deep learning model) can improve understanding of the target phenomenon and reveal how the model organizes relevant information”
- „In order to study trained ML models, especially complex DL models, for insight into external targets, we must first clarify how a link from ML models to TML targets (horizontal bottom side of a C-schema) may work.”
- "FI understanding of the phenomenon": FI understanding of TML target to enable understanding the external phenomenon?
- “features of the target phenomenon”
- **lack of selectivity**: here they mean external target phen!
- “are predictive of the target”
- **understanding vs predicting**: "understanding external targets using ML models" or "predicting external targets using ML models? Isnt this a big difference?
- OR FI understanding IS understanding the external phenomenon by means of understanding the TML target? (yes?...)


## FAI?

- “but they are varied only in ways that approximately preserve the relevant aspects of the phenomenon to be understood”
- **attack**: what does it mean "but only in ways that approx. preserve the relevant aspects of the external phenomenon"? who or what decides what is relevant or not?
- preserving the aspects of the (external) phenomenon means that the relevant "real-world relationships of features found in the external phenomenon" are preserved in the ML model representations
- **criticism**: we could know that there is a similarity relationship in the general characteristics of the model-internal data relationships, but we could not say how these data relationships would look like, right?


## misrepresentation link uncertainty?
- “the actual features represented by the data were not just the intended features”
- **attack misrepresentation uncertainty**: I dont think Sullivans link is concerned with which features of the data are intended or not, but with which features are empirically validated as being actual features of the external target?
- but arent confounding variables in the data just features that could not be empirically validated as being actual features of the external target, and thus, the differentiation in data-misrepresentation and link uncertainty is irrelevant? as link uncertainty already captures the aspects that misrepresentation wants to capture?
- “rendering the link with intended features, namely, unmarked skin and their dermatological state uncertain”
- **attack misrepresentation uncertainty**: this has nothing to do with the confounds being part of the actually sampled data, but with the confounds not being empirically validated as being actual features of the target.  
- when a ML model captures something that is not there, i.e. a confound cannot be empirically or scientifically validated as being an actual feature of the external target; it can in fact be empirically and scientifically validated as being a confound, i.e. not actually being present in the target
- well, the confound can in fact be actually present in the represented data, but the confound being present is not relevant for the explanatory question that is asked to the model
- [Go to annotation](zotero://open-pdf/library/items/ZTJ7YW79?page=16&annotation=5EWBAVPA) “in both directions” ([Shech and Tamir, 2022, p. 16](zotero://select/library/items/3X99RVG8)) why in both??
- “but in order to establish a link between the model and the target, more is needed”
- **attack misrepresentation uncertainty:** here it sounds as if a link can only then be established if empirical as well as representational link uncertainty is prevented!
- below they talk that complementary to an empirical link a representational link needs to be established to establish "clear horizontal links for understanding"

## relation between FAI and misrepresentation LU?
- key question: is FAI and the ways to fix misrepresentation LU that are proposed by T&S themselves compatible?
- If preventing data misrepresentation link uncertainty needs model transparency, then how can T&S reason for FAI for which model opacity is dismissed to be relevant?
- see “With the functionally approximate irrelevance of particular parameter details ensured, IR understanding even with “highest level” opacity is possible.” (Shech and Tamir, 2022, p. 11)
- **How can opacity be irrelevant for FI understanding of intra-model feature relationships while at the same time data misrepresentation has been identified as an additional factor contributing to link uncertainty?**
- This would reinstate opacity as a problem for linking the model to the target as opacity would impede the fixing of data misrepresentation LU

## really highest-level black box?
- is it even relevant when T&S claim of highest-level opacity falls? how would this impact their argumentation?
- “IR understanding even with “highest level” opacity is possible.”
- no background knowledge of the model implies no knowledge of different parameterization
- no background knowledge of the target implies no way to judge whether or not the models perform sufficiently and equivalently across different strata of the data
- and no possibility to gain any knowledge through the comparison of performance between two models
- Do Sullivan and T&S have the same understanding of “highest-level opacity” or T&S are in fact considering models with “highest-level opacity”?
- “significant parameter detail differences (i.e. ) are irrelevant”
- **attack T&S do not in fact operate on highest-level opacity:**  
  
T&S need the comparison between two models to be able to say that a difference in implementation between models is irrelevant to gain IR understanding of relationships between features represented by the data.  
Only through the comparison between ML models that "perform sufficiently and equivalently across different strata of the data", i.e. generalize the same way across new data, i.e. enable to draw the same inferences about the external target, T&S can say that even highest-level opacity is compatible with understanding.  
  
However, Sullivan's claim that highest-level opacity is not compatible with understanding the external target is derived only from observations of a singular ML model and implies that the modeler has no background knowledge about the model or the target, i.e. there is no way for the modeler to judge whether or not the model performs sufficiently and equivalently across different strata of the data AND the modeler can not gain any knowledge through comparison of performance between two models. i.e. the modeler is not able to state that he can gain the same inferences about the external target, nor has the modeler any knowledge that the models are implemented differently to make derive from the same performance of the models any meaning.  
  
**So there are 4 points that are different between how T&S and Sullivan understand highest-level opacity in relation to knowledge and implementation irrelevance:**  
1. no background knowledge of the model implies no knowledge of different parameterization  
2. no background knowledge of the target implies no way to judge whether or not the model performs sufficiently and equivalently across different strata of the data  
3. no possibility to gain any knowledge through the comparison of performance between two models  
4. Sullivan and T&S do operate with the same notion of implementation irrelevance  
  
It seems that T&S are not in fact considering models with highest-level opacity as knowledge is gained through the comparison of model performance between the models. This makes it possible for them to say that difference in implementation between both models are aprrox. irrelevant. Thus, the level of opacity T&S are considering is reduced for them to be able to say that understanding of the target phen. is possible through their postulated modes of understanding.  
  
"At minimum, the reliable generalizability of an ML model to similarly sampled data increases our understanding that there is some signal in the x-data useful for y-target estimation."  
Dont we need some knowledge into the external target to be able to judge whether or not the generalizability of a ML model is reliable or not?  
Doesnt this imply that we do not in fact on the basis of a highest level black box?  

Things I need to be sure:  
- are T&S postulating that the models have different parameterization? Sullivan says highest-level opacity means also no background knowledge of the model implementation - thus, do T&S  already NOT operate on the basis of highest-level opacity or is it okay for them to postulate knowledge of different parameterization while at the same time claim that they operate on the basis of a highest-level black box?  
- is it really a problem that T&S utlilize a comparison between models vs Sullivan only focuses on highest-level opacity in relation to a singular model? does this really imply gain of knowledge?  

“when we “open up the black box” to acquire this understanding” ([Shech and Tamir, 2022, p. 15](zotero://select/library/items/3X99RVG8)) WHAT? why would you open the black box, when you previously said that even a highest-level black box is compatible with understanding??  
dont you mean "when we do not open the black box"???
## contributing to the same discussion?
- “This paper places into context how the term model in machine learning (ML) contrasts with traditional usages of scientific models for understanding...”
- “Our hypothesis is that the appropriate target of understanding with ML models...”
- ... evaluating ML model link uncertainty.”
- T&S speak specifically on the case of ML models – does their approach actually contribute to the broader discussion on model opacity that Sullivan is interested in?
- Does their approach tell us anything about how ML model can be used as scientific models
- “to reconciling Sullivan’s contrast of DL models with idealized models”: **I dont know how Sullivan needs reconciling?** she didnt contrast ML and idealized models in a way that conclude that ML models are limited in the understanding they can provide compared to idealized models?? in fact, Sullivan sees ML and idealized models more as the same when looking at implementation black box and concludes for both that model opacity is not an in principle problem for understanding!
- “leverage these models for LR (FI and MI) understanding” 
- **can the difference in "target of ML model" between Sullivan and T&S be reconciled?** arent they arguing about something different??



