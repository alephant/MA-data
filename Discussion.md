- philosophy of science's emphasis on empirical validation and the iterative process of theory refinement
- practical and theoretical challenges due to ==underdetermination of a theory by the data== and model selection

## criticism based on model assumption
- reliable predicition are crucial for understanding; reliable predicition however require the consideration of more than just the data, but of ==non-empirical model assumptions== as well
	- “The predictions of the ML model hence depend not only on the data but also on the architecture of the ML model and, in the absence of evidence to the contrary, also on the algorithmic and initialisation details.” (Scorzato, 2024, p. 4) 
	- i.e. detail implementations & model assumptions are relevant for understanding from ML models?
	- it seems like Sullivan does take "model assumptions" into consideration when she is talking about background knowledge of the model; but for her, these assumption work in her favor and enable her to wave away opacity as a problem; whereas for Scorzato, the model assumption are insofar relevant that understanding model implementation becomes necessary for estimating reliability of predicition, and thus, need to be considered for understanding from ML models as well (Sullivan: model assumptions wave away opacity; Scorzato: model assumptions make transparency important)
- “Ideally, the specific values of all those parameters are not essential to determine a prediction, which should depend only on the training domain. However, the training domain is difficult to define and the outcome may depend also on subtle details of the training process. In fact, weight initialisation and pre-training techniques are key design choices when training and deploying a DNN model (Narkhede et al., 2022; Glorot and Bengio, 2010). Adversarials (Szegedy et al., 2014) are also evidence of high sensitivity to details.” (Scorzato, 2024, p. 7) 
	- this shoots down "model decision driven by high-level properties" as not the exact parameterization is relevant but model decision is highly sensitive to details of the training process (weight initialization, pre-training, adversarials as evidence for sensitivity)
	- as ML predictions are determined by model assumptions: Sullivan's post-training ML model decisions are predominantly driven by "high-level properties", whereas pre-training there must have been many more underlying assumptions that made training possible? it sounds like a weird decrease in model assumptions before and after training? can it be even the same model, when the model assumption change so drastically?
- “Instead, the lack of understanding of the training dynamics enforces the inclusion of the full specification of the DNN (initial) parameters and training data as part of the assumptions.” (Scorzato, 2024, p. 8) 
	- the increase in complexity leads to the inclusion of more detailed model assumptions
- “Formal proofs of independence from details, if available, are very desirable, because no further assumption is needed in that case.” (Scorzato, 2024, p. 8) 
	- this sounds like what Sullivan tries to achieve with "only predictive model and high-level properties needed": make DNN decision independent of any further assumptions that take detail implementation into consideration
	- “Despite considerable effort, researchers have not been able to identify any simple set of rules that makes the outcome of DNN models independent of any further detail.” (Scorzato, 2024, p. 8)
- “Moreover, this difficulty might actually be an intrinsic price to pay for the great flexibility of DNN models (see also Hartmann and Richter (2023).” (Scorzato, 2024, p. 8) 
	- strong indication that "Predictions are certainly determined by the entire set of DNN parameters" is true as flexibly parameterized DNN do in fact inform different model decisions
	- probably the UAT-enabled flexibility of DNN is not compatible with a simple set of rules that make model decision independent of any further detail
	- Sullivan tries to achieve some de-correlation between detail parameterization and "high-level properties" whereas in fact detail parameterization is highly correlated with model outcome
- ==“High sensitivity to details is the key aspect of the so-called black-box problem (Desai et al., 2022) of some ML methods: lack of understanding is a serious limitation to the extent that we cannot tell which details actually matter for a conclusion.” (Scorzato, 2024, p. 8)==
	- model outcome is sensitive to details in training; it is very difficult (impossible?) to identify which exact details are driving model outcome; underlying DNN model assumptions that determine model outcome are thus opaque; so we do not understand which model details actually determined model outcome in DNN

## on "simply having a highly predictive model"
- “The fact that some successful DNN architectures keep being successful over time is certainly convincing evidence that they can learn something valuable. However, also in those cases, we cannot exclude that the DNNs have actually learned unwanted features that happened to have a strong spurious correlation with the labels (see, e.g., Xiao et al. (2021) for an example of this phenomenon).” (Scorzato, 2024, p. 7)
- “This confirms that also DNN predictions are only valuable ==when they stem from a valuable model==.” (Scorzato, 2024, p. 7)

## Sullivan: DNN are just like other models, but more complex
- crucial difference between TS and DNN in respect to assumptions that restrict the domain of applicability, approach to parameterization (transparent in TS), parameter fitting (consistency with empirical findings of background scientific domains in TS)
## on link uncertainty
- “But for DNNs the problem is somewhat harder because the ==domain of applicability is difficult to define== also with reference to features that we do know.” (Scorzato, 2024, p. 6)
- 