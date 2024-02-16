[Go to annotation](zotero://open-pdf/library/items/JF9MCQ3U?page=1&annotation=LEZ9CYN5) “Are scientists trading understanding for some other epistemic or pragmatic good when they choose a machine learning model? Or are the assumptions behind why minimal models provide understanding misguided?” ([Sullivan, 2022, p. 1](zotero://select/library/items/GQGEYW5N)) Sullivan's research question: scientist use models to gain understanding; complex models seem to provide less understanding; model complexity and understanding seem to be connected; is this true? is there less potential for understanding when using a ML model? if it is not model complexity that decides potential for understanding, what is it then?

[Go to annotation](zotero://open-pdf/library/items/JF9MCQ3U?page=2&annotation=JE6FNEW8) “I argue that model simplicity and transparency are not needed for understanding phenomena.” ([Sullivan, 2022, p. 2](zotero://select/library/items/GQGEYW5N)) introduce argument part 1 "transparency and simplicity are not relevant for understanding"

[Go to annotation](zotero://open-pdf/library/items/JF9MCQ3U?page=2&annotation=FGXRX2I3) “Instead, it is the level of link uncertainty present—that is, the extent to which the model fails to be empirically supported and adequately linked to the target phenomena—that prohibits understanding.” ([Sullivan, 2022, p. 2](zotero://select/library/items/GQGEYW5N)) introduce argument part 2 "link uncertainty is relevant for understanding"

[Go to annotation](zotero://open-pdf/library/items/JF9MCQ3U?page=4&annotation=L4435529) “My arguments do not so much trade on any positive notion of what understanding or explanation is, but on whether, given a lack of information, it is still possible to gain insight about a phenomenon.” ([Sullivan, 2022, p. 4](zotero://select/library/items/GQGEYW5N)) clarify argumentation "I do not say anything about what model explanation and understanding from ML models is - all I say is whether understanding is possible even though ML models are opaque"  
**point of attack** "is it possible to argue for the possibility of understanding from ML models without saying anything about what this understanding is?"

[Go to annotation](zotero://open-pdf/library/items/JF9MCQ3U?page=5&annotation=XTZMXI4S) “The question of this paper, on the other hand, is to what extent understanding the model is necessary for gaining understanding of the phenomenon that the model explains.” ([Sullivan, 2022, p. 5](zotero://select/library/items/GQGEYW5N)) research question in light of "narrow vs broad sense of understanding": "how much do I need to understand the model in order to understand the phenomenon?" (degree of model transparency needed)  
  
"are opaque and complex ML models that do explaining unable to provide understanding, because they are opaque and complex - or because of something else?" (model transparency in principle needed)  
  
**point of attack**: Sullivan claims that "narrow vs broad sense of understanding" in relation to ML models is distinct - but how distinct are they really?  
  
  
**all below Sullivan argues that model opacity should not be the sole focus when deciding whether understanding from ML models is prevented or not and she introduces link uncertainty as a critical factor whether opaque ML models are unable to provide understanding or not**

[Go to annotation](zotero://open-pdf/library/items/JF9MCQ3U?page=8&annotation=UV8FWDAV) “the implementation is either unknown or illegible to the modeler, the explainer, or the understander.” ([Sullivan, 2022, p. 8](zotero://select/library/items/GQGEYW5N)) introduce idea of "black boxed implementation" relating it to lack of intelligibility

[Go to annotation](zotero://open-pdf/library/items/JF9MCQ3U?page=9&annotation=IC4YSR9Y) “Thus, implementation black boxing in itself does not undermine our ability to explain or understand phenomena.” ([Sullivan, 2022, p. 9](zotero://select/library/items/GQGEYW5N)) intermediate conclusion: while it is possible for implementation black boxing to impede understanding a phenomenon, it is not in principle relevant for understanding a phenomenon  
  
i.e. model opacity is not in principle relevant  
i.e. intelligibility of model implementation is not in principle relevant

[Go to annotation](zotero://open-pdf/library/items/JF9MCQ3U?page=10&annotation=8AAFL4LF) “3.2 Levels of implementation black boxes” ([Sullivan, 2022, p. 10](zotero://select/library/items/GQGEYW5N)) investigate the impact of model opacity on the possibility for understanding by introducing concepts of "depth of black box" and "different types of implementation black boxes" and looking at how they impact the possibility for understanding for algorithmic and simple models:  
  
"different types of implementation black boxes":  
1. basic implementation black boxing in function calls (e.g. sig() )  
2. impl. black boxing by in principle unpredictable algorithms  
3. impl. black boxing by regularization methods to make model generalizable (see below)  
  
  
"depth of black box":  
whether or not a model is a highest-level black box depends on various factors  
if it is not a highest-level black box it is compatible with understanding  
  
if it is a highest-level black box it is very plausible that it is not compatible with understanding

[Go to annotation](zotero://open-pdf/library/items/JF9MCQ3U?page=11&annotation=SQ65MMVS) “In order to gain understanding of segregation using Schelling’s model, you do not need to peer inside and see the implementation here. We have the same level of understanding of the mechanisms of segregation whether or not the implementation black box is removed.” ([Sullivan, 2022, p. 11](zotero://select/library/items/GQGEYW5N)) prepare "what is true for simple models is also true for complex models"  
Sullivan makes her case starting with simple models and than applies what is true for simple models to complex models

[Go to annotation](zotero://open-pdf/library/items/JF9MCQ3U?page=12&annotation=IHVE47FJ) “we need to ask whether we have the highest level of implementation black boxing” ([Sullivan, 2022, p. 12](zotero://select/library/items/GQGEYW5N)) relate "depth of black box" with DNN:  
as it seems relevant for understanding whether we have a highest-level implementation black box or not, let's see if DNN are highest-level black boxes

[Go to annotation](zotero://open-pdf/library/items/JF9MCQ3U?page=12&annotation=3TVUGIVV) “As I have been arguing, in order to consider how opacity limits understanding, we need to isolate the explanatory question of interest, the level of link uncertainty present, and determine the depth of the black boxes” ([Sullivan, 2022, p. 12](zotero://select/library/items/GQGEYW5N)) argument layout of how to show whether or not opacity is the limiting factor for understanding from DNN:  
  
- "determine depth of the black boxes":DNN are not black boxed at the highest level  
  
- "isolate expl. question": deep patient DNN provides us with how-possibly explanations, ie. it allows for understanding of possibilities; it requires empirical evidence to establish link between DNN and its target phenomenon to allow for understanding actual causes  
  
- "isolate level of link uncertainty": DNN's level of link uncertainty reduced/ resolved by empirical evidence  
  
thus, whether or not opacity is relevant for understanding needs to be considered in relation to the depth of the implementation black boxes, the expl. questions asked and the degree of link uncertainty  
  
and this consideration leads us to conclude that opacity is not relevant for understanding phen.  
it is relevant for understanding how the model works though  
  
  
?: aren't all these aspects (type of expl. question, degree of link uncertainty, background knowledge of model and phenomenon) contained in the question how deep the black box is?

[Go to annotation](zotero://open-pdf/library/items/JF9MCQ3U?page=18&annotation=BM6KQ375) “So, while the modeler does not have direct control over the modelling process, a contrast case with Schelling’s model, still the process is not black boxed at the highest level, such that it would prevent understanding of the phenomenon the resulting model aims to capture.” ([Sullivan, 2022, p. 18](zotero://select/library/items/GQGEYW5N)) premise: models that are black boxed at the highest level impede all understanding that can be gained from them  
  
premise: background knowledge of a model reduces level of black box  
premise: modelers have background knowledge of DNN  
  
  
conclusion: black boxed implementation of DNN does not prevent understanding as they are not black boxed at the highest level as modelers have background knowledge of the modelling process (training, validation and testing)

[Go to annotation](zotero://open-pdf/library/items/JF9MCQ3U?page=18&annotation=AIHR87HF) “However, different types of saliency testing are enough to satisfy our need to know the high level details of how the model works to open the door to understanding the phenomenon the model bears on” ([Sullivan, 2022, p. 18](zotero://select/library/items/GQGEYW5N)) support intermediate claim "black boxed implementation of DNN does not prevent understanding as they are not black boxed at the highest level" by adding indirect means (saliency maps) that enable us to validate whether the high-level goals of the model (determined by the modeler) are satisfied or not, thus, enabling understanding

[Go to annotation](zotero://open-pdf/library/items/JF9MCQ3U?page=19&annotation=FQK262I3) “Thus, there is a lingering concern that even though black boxes of DNN models are not at the highest level, still the understanding we gain from these models is limited because of the lower level opacity in the DNN model itself.” ([Sullivan, 2022, p. 19](zotero://select/library/items/GQGEYW5N)) building up "even DNN that are not black boxed at the highest level, but on a lower level still impede understanding" as counter-argument to own "DNN are not black boxed at the highest level" in order to dismiss it and introduce link uncertainty as the relevant criteria for understanding

[Go to annotation](zotero://open-pdf/library/items/JF9MCQ3U?page=20&annotation=J8VGALDE) “It is my contention that the same is true with DNNs” ([Sullivan, 2022, p. 20](zotero://select/library/items/GQGEYW5N)) showing what is true for simple models is also true for complex models:  
initial question: how much understanding of how the model works is necessary for gaining understanding of the phenomenon the model bears on?  
recap example of simple model: The mid-level updating algo is black boxed; the high-level algo stays intact; revealing the mid-level implementation black box around the updating algo does not change the level of understanding on the phenomenon gained from the model  
  
ie. it is true for simple models that understanding more how the model works does not change the amount of understanding gained about the phenomenon

[Go to annotation](zotero://open-pdf/library/items/JF9MCQ3U?page=21&annotation=XCL97Z9M) “While it is tempting to attribute this gap in understanding to the implementation black box of the deep patient model, we should not take the bait.” ([Sullivan, 2022, p. 21](zotero://select/library/items/GQGEYW5N)) relate what is true for simple models is also true for complex models, i.e.  
"implementation black boxes that prevent understanding how the simple OR complex model works DO NOT prevent understanding of the phenomenon"  
  
it is true for simple models that understanding more how the model works being prevented by implementation black box does not change the amount of understanding gained about the phenomenon  
it is true for simple models that understanding more how the model works (ie. revealing the mid-level implementation black box around the updating algo) does not change the amount of understanding gained about the phenomenon  
thus, not being able to answer "How is schizo actually predicted using the model?" is NOT due to implementation black box, but due to link uncertainty

[Go to annotation](zotero://open-pdf/library/items/JF9MCQ3U?page=21&annotation=FI8W7B3U) “DNNs and link uncertainty” ([Sullivan, 2022, p. 21](zotero://select/library/items/GQGEYW5N)) give reasons why there is link uncertainty in DNN, what explanatory questions it can still answer, how to reduce link uncertainty in DNN by empirical and scientific evidence, model is still useful even after link uncertainty is resolved

[Go to annotation](zotero://open-pdf/library/items/JF9MCQ3U?page=26&annotation=8EMYBWIC) “The level of implementation black boxing is the same in the deep patient case, the melanoma case, and sexual orientation case” ([Sullivan, 2022, p. 26](zotero://select/library/items/GQGEYW5N)) argumentation from different amount of understanding gained from DNN with same level of implementation black boxing but different level of link uncertainty:  
level of impl. black boxing influences understanding  
level of link uncertainty influences understanding  
level of impl. black boxing is the same  
level of link uncertainty is different  
thus, difference in understanding can only be due to difference in level of link uncertainty

[Go to annotation](zotero://open-pdf/library/items/JF9MCQ3U?page=27&annotation=9MGENTDA) “This general claim about the importance of removing link uncertainty in order to gain understanding stretches beyond the cases of minimal and complex models.” ([Sullivan, 2022, p. 27](zotero://select/library/items/GQGEYW5N)) example why link uncertainty and the question of how it can be removed is relevant for other scientific questions too

