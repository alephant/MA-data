**Can post-hoc explanations illuminate why DNN are predictively successful and tell us anything about their unique properties such as generalization?**
“Nevertheless, such outside in, post-hoc explanation generation increases a type of functional transparency: it provides access to the decision space most relevant to the token classification. In the language of functional transparency, it thus succeeds in explaining the functioning of the algorithm on ==that particular decision==, albeit in coarsegrain, human-interpretable terms.” (Creel, 2020, p. 27)

It sounds like LIME provides local explanations and does not help understanding global properties of DNN.

**Visualization?**
“By supporting a high-level understanding of which features the algorithm is using to decide whether an image should be classified with a label, visualization delivers the capacity to detect artifacts.” (Creel, 2020, p. 31)
“Visualization provides knowledge of features of the initial training data and subsequent trained algorithm that would otherwise be difficult to access merely from the output.” (Creel, 2020, p. 32)

---

**Post-hoc explanations like LIME do not give insight how the DNN actually came to its decision**
“But the decision-making process implied by LIME’s list of symptoms is not the way that the original system decides. At no point in the original machine learning system’s decision making does it build a sparse linear model that provides discrete symptoms. The linear model used by LIME accurately characterizes the relevant space for that decision, but it would not be of much use in detecting problems with the functioning of the original system. Nor does it open the “steps in the process” to “direct inspection and verification” (Humphreys 2004, 148)” (Creel, 2020, p. 28)

**Visualization does not tell us which DNN sub-component tracks which target features is**
“However, it does not localize the detected artifact to a particular submodel. Each of the artificial neurons that (metaphorically) fire differentially when presented with the image of the dumbbell is looking for slightly different sub-components or aspects of the definition of dumbbell. Although we can know which neurons are firing when presented with an arm, a dumbbell, and an arm with a dumbbell, teasing apart which “subcomponent” should be modified to fix the artifact is difficult due to the fuzzy modularity of neuron groups.” (Creel, 2020, p. 32)

---

**Post-hoc explanantions could prove to be a step towards understanding DNN's predictive success and their unique properties**
“Nevertheless, LIME does increase transparency. It provides faithful access to high-level features of the decision making process that are useful in aiding artifact detection and explanation.” (Creel, 2020, p. 29)

---

**R&B: How to increase understanding of DNN high-level properties**
“One way to understand generalization properties better is to prove an upper bound on the so-called generalization error (a measure of how well a DNN performs in the worst case), given assumptions about the data distribution, features of the model and of the learning algorithm.” (Räz and Beisbart, 2022, p. 14)




**Can structural transparency help?**
“to understand how the code as written brings about the result of the program.” (Creel, 2020, p. 13)


**Acc. to Creel structural transparency can be best defined as knowledge of relations between subcomponents** 
“Without such knowledge of the sub-components and their relations, it would be difficult to successfully trace the path between every possible input and its output. Since there are an infinite number of possible inputs, the possibility of predicting the behavior of the system, and especially of identifying the sources of unexpected behavior in the code, requires a model of the system and how it will treat inputs. ==Therefore the more complete form of analysis is the knowledge of relations between the subcomponents, not the sum of the ability to traverse all possible paths.==” (Creel, 2020, p. 17)

Defining input-output paths fails.
Can T&S approach provide knowledge of relations between subcomponents?

T&S approach: intra-model inferences on data representations that let us understand the relationships of features (in the abstraction of T).


**Humphreys: Structural transparency could provide functional transparency**
“This independence conflicts with existing philosophical accounts, according to which possession of one type of transparency necessarily affords another (Humphreys 2004; Lenhard and Winsberg 2010). On Humphreys’ view, possessing structural transparency provides high-level algorithmic, functional transparency.” (Creel, 2020, p. 23) 

Humphrey argues in favor of a correlation between types of transparency.
This implies that methods that provide structural transparency also provide functional transparency.
==Humphrey's account fits the thesis that lack of understanding of DNNs (due to structural opacity) impedes understanding with DNNs (due to functional opacity).==
Can T&S approach provide structural transparency?

- **Creel objects “Humphreys does not get two transparencies for the price of one.” (Creel, 2020, p. 24)**
- Modular decomposition granting a partial form of Creel's structural transparency does not grant functional transparency.

**Creel: Localizing subcomponents that drive model outcome does not provide understanding of the higher-level emergent properties of a model**
“The economy-reelection correlation localizes the prediction’s success or failure to one particular component of a complex model of factors that affect elections, as Lenhard and Winsberg would desire. However, it merely presents a predictive correlation useful for localizing success or failure but useless for a high-level algorithmic understanding of the effect.” (Creel, 2020, p. 25)

Lenhard and Winsberg approach do not explain how the component is related to the phenomenon.