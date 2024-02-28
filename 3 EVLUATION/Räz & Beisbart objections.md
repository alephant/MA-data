### Objections against Sullivan
1. **==auxiliary: DNN are not harmless implementation black boxes==** (DNN implementation is significantly different and cannot be known analogous to factorials, is not transparent analogous to the Schelling model)
2. **==auxiliary: DNN's higher-level properties are not known==** (saliency maps do not enable epistemic access)
3. **==main: Understanding DNN implementation is relevant for understanding phenomena, i.e. DNN opacity is an in-principle problem for understanding==**
	1. DNN's epistemic achievements are not enough for explanatory understanding: a strong reading of Sullivan's thesis fails (DNN do not and cannot enable explanatory understanding), a weak reading is trivial or plausible (DNN can enable objectual understanding)
	2. As we do not understand DNN properties that make DNN predictively successful, we cannot use them for understanding

***==How do these objections also argue against T&S approach?==***
- could their approach help to gain epistemic access to higher-level properties like generalization?
- is T&S approach not in fact about understanding DNN implementation?

### What transpareny is needed to gain understanding of DNN implementation?

**Creel:**
**==functional vs structural transparency==**: knowing which vs knowing how a particular algorithm is instantiated?

Probably, acc. to R&B accomplishing understanding DNN implementation would need **==structural transparency==**: “to understand how the code as written brings about the result of the program.” (Creel, 2020, p. 13)
	- Creel argues that Humphreys’s process decomposition and Lipton's improvement on it d not define structural transparency

**Creel argues that the knowledge of relations between subcomponents defines a system's structural transparency:** 
this sounds a lot like T&S approach based on intra-model inferences on data representations that let us understand the relationships of features (in the abstraction of T)

### Objections in detail
Objection 1: 
R&B challenge the arguments from analogy that Sullivan makes. We do not know what function a DNN implements in the same way we know what function an algorithm implements that computes factorials. In the case of the factorials we can give a description of the function that governs the input-output relation. For each input number the function computes its factorial. This description does not change when the computational implementation of the function changes.
Knowing the classifier function that governs the input-output relation of a DNN is not possible. 

R&B challenge the analogy between the Schelling model and DNN with which Sullivan argues that in both cases understanding model implementation is irrelevant for understanding phenomena using the models. R&B argues that the Schelling model implements "rules of transition" that are predetermined by the modeler, and thus, known, whereas the "rules of transition" in the case of a DNN are not known by the modeler. The overall "story" that the Schelling model implements makes the model behavior accessible to reason, whereas a DNN cannot be reasoned with.
R&B argue that the fundamental problem is that “we know little about what function is computed by an DNN.” (Räz and Beisbart, 2022, p. 8)

Objection 2: 
R&B challenges the assumption that an understanding of the higher-level functioning of DNN is enabled through indirect means such as saliency maps. Sullivan introduces these indirect means as a way “to satisfy our need to know the high level details of how the model works to open the door to understanding the phenomenon the model bears on” (Sullivan, 2022, p. 18) However, if these means do not enable epistemic access to the higher-level functioning of DNN, then understanding of phenomena - in the sense that Sullivan is argueing for, i.e. explanatory understanding - cannot be gained from black-boxed DNN. R&B directly attack the claim that 
- “Simply having a highly predictive model, and knowing the high-level emerging properties of the model, uncovers that it is possible to use a machine learning representation for disease prediction.” (Sullivan, 2022, p. 20)

Objection 3: 
Objection against Sullivan's notion of understanding:
Sullivan employs a strong notion of understanding (explanatory understanding) which she cannot reasonably back up.
However, employing a weak notion would not do her a favour as it has nothing to do with true understanding for which she wants to argue (objectional understanding; heuristics; exploration)
Sullivan argues that ML can provide explanatory understanding; her reasons are not sufficient; in fact there are fundamental reasons why DNN cannot provide explanatory understanding; however, a weak sense of understanding provided by DNN (e.g. heuristics) trivial as DNN certainly provide this sense of understanding already

DNN do not enable explanatory understanding as DNN achieve conditions for expl. understanding only to some degree:
	- predicitive power is not explanatory power
	- how-possibly explanations do not provide explanatory understanding
	- DNN do not even provide how-possibly explanations

### Lack of Understanding of DNNs Impedes Understanding With DNNs
When R&B speak of "understanding the DNN model itself", they do not mean to understand the DNN in respect to a particular dataset , **==but how DNN work in general.==**

There are high-level properties that we currently do not understand. 
e.g. we do not properly understand DNN generalizations. We also do not understand whether a DNN is truly optimized (see stochastic gradient descent).
DNN high-level properties are the reason that they are predictively successful.
It is possible that DNN predict well, without enabling true understanding.
Their predictions might be based upon spurious correlations, unstable features, artifacts etc. that have nothing to with relevant features that actually explain the target system.

Thus, the lack of understanding of DNN impedes our ability to use DNN to obtain how-actually explanations and to gain understanding of phenomena.

**==The case of spurious correlations underlying prediction illustrates why predictive power is not necessarily indicative of explanatory power.==**


**==A better understanding DNN properties might help to use DNN more confidently to gain understanding.==**
e.g. research how well DNN perform in worst cases. 

Do we have to know why DNN are predictively successful to be able to gain expl. understanding from them?

### Link uncertainty is connected to understanding model implementation
R&B argue that Sullivan is misguided in the idea that link uncertainty and understanding the model are independent from each other.
***==R&B argue, when link uncertainty is true (M must be linked to T to enable understanding), then implementation irrelevance cannot be true as well (understanding how M works is irrelevant to understand T using M).==***

If M is linked to T, M will be understood better.
If M is better understood, a link between M and T is easier to establish. 