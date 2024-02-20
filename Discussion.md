- philosophy of science's emphasis on empirical validation and the iterative process of theory refinement
- practical and theoretical challenges due to ==underdetermination of a theory by the data== and model selection
- reliable predicition are crucial for understanding; reliable predicition however require the consideration of more than just the data, but of ==non-empirical model assumptions== as well
	- “The predictions of the ML model hence depend not only on the data but also on the architecture of the ML model and, in the absence of evidence to the contrary, also on the algorithmic and initialisation details.” (Scorzato, 2024, p. 4) 
	- i.e. detail implementations & model assumptions are relevant for understanding from ML models?
	- it seems like Sullivan does take "model assumptions" into consideration when she is talking about background knowledge of the model; but for her, these assumption work in her favor and enable her to wave away opacity as a problem; whereas for Scorzato, the model assumption are insofar relevant that understanding model implementation becomes necessary for estimating reliability of predicition, and thus, need to be considered for understanding from ML models as well (Sullivan: model assumptions wave away opacity; Scorzato: model assumptions make transparency important)

## on "simply having a highly predictive model"
- “The fact that some successful DNN architectures keep being successful over time is certainly convincing evidence that they can learn something valuable. However, also in those cases, we cannot exclude that the DNNs have actually learned unwanted features that happened to have a strong spurious correlation with the labels (see, e.g., Xiao et al. (2021) for an example of this phenomenon).” (Scorzato, 2024, p. 7)
- “This confirms that also DNN predictions are only valuable ==when they stem from a valuable model==.” (Scorzato, 2024, p. 7)

## on link uncertainty
- “But for DNNs the problem is somewhat harder because the ==domain of applicability is difficult to define== also with reference to features that we do know.” (Scorzato, 2024, p. 6)
- 