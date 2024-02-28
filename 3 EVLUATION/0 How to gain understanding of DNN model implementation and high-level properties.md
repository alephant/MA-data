**Do post-hoc explanations help?**
“Nevertheless, such outside in, post-hoc explanation generation increases a type of functional transparency: it provides access to the decision space most relevant to the token classification. In the language of functional transparency, it thus succeeds in explaining the functioning of the algorithm on ==that particular decision==, albeit in coarsegrain, human-interpretable terms.” (Creel, 2020, p. 27)

It sounds like LIME provides local explanations and does not help understanding global properties of DNN.

**Post-hoc explanations like LIME do not give insight how the DNN actually came to its decision**
“But the decision-making process implied by LIME’s list of symptoms is not the way that the original system decides. At no point in the original machine learning system’s decision making does it build a sparse linear model that provides discrete symptoms. The linear model used by LIME accurately characterizes the relevant space for that decision, but it would not be of much use in detecting problems with the functioning of the original system. Nor does it open the “steps in the process” to “direct inspection and verification” (Humphreys 2004, 148)” (Creel, 2020, p. 28)

==Can post-hoc explanations illuminate why DNN are predictively successful and tell us anything about their unique properties such as generalization? If not, then they are not helpful.==



**What are R&B argue is necessary to understand model implementation?**


**Can structural transparency help?**
“to understand how the code as written brings about the result of the program.” (Creel, 2020, p. 13)


**Acc. to Creel structural transparency can be best defined as knowledge of relations between subcomponents** 
“Without such knowledge of the sub-components and their relations, it would be difficult to successfully trace the path between every possible input and its output. Since there are an infinite number of possible inputs, the possibility of predicting the behavior of the system, and especially of identifying the sources of unexpected behavior in the code, requires a model of the system and how it will treat inputs. ==Therefore the more complete form of analysis is the knowledge of relations between the subcomponents, not the sum of the ability to traverse all possible paths.==” (Creel, 2020, p. 17)

Defining input-output paths fails.
Can T&S approach provide knowledge of relations between subcomponents?

T&S approach: intra-model inferences on data representations that let us understand the relationships of features (in the abstraction of T).


**Humphrey: Structural transparency could provide functional transparency**
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