### reliability as condition for understanding from ML models
Scorzato investigates the reliability of ML models. Reliable predictions of a model are crucial for  models to enable understanding. As reliability requires reliable model assumptions, the capacity to enable understanding needs to be investigated in light of model assumptions.
==“Trustworthy predictions require trustworthy premises.” (Scorzato, 2024, p. 6)==

Model reliability is assessed by estimating the uncertainty of model predictions. He argues that a statistical error analysis of prediction error needs to be integrated with a deeper epistemological analysis. He emphasizes that DNN have special characteristics that set them apart from other ML or TS models. This has implications in how to assess DNN reliability.

### "The illusion of predictions without assumptions"
Scorzato argues that as there is no theory-free observation, the estimation of prediction error of a model, ==i.e. assessing model reliability cannot be done without considering model assumptions.==
Assessing reliability of models solely based on fit with data is fallacious.
This is due to the underdetermination thesis that argues that for any given set of data, multiple theories or models can provide a fitting explanation or prediction.
- “Data alone cannot enforce any conclusion.” (Scorzato, 2024, p. 4)

The UAT tells us that ML models, especially deep neural networks, have the capacity to approximate any continuous function given sufficient complexity and data. This makes ML models highly flexible to fit any set of data and is the theoretical basis for their high predictive power.
However, this makes ML models even more prone to underdetermination.
- “The predictions of the ML model hence depend not only on the data but also on the architecture of the ML model and, in the absence of evidence to the contrary, also on the algorithmic and initialisation details.” (Scorzato, 2024, p. 4)

This suggests that ML predictions are determined by more than just empirical aspects, but by model assumptions as well.
Model assumptions are non-empirical, language-independent, theory-laiden and cannot be made future-proof. i.e. assumptions cannot be tested to hold in unknown contexts. 
i.e. the scope of applicability of the model cannot be definitely defined.

### Prediction is not enough
Predictive power alone is not a good measure for model reliability. Model assumptions need to be reliable as well. i.e. empirical success is not enough, other non-empirical aspects are also important to confirm reliability.
The reliability of model assumptions cannot be directly assessed. Scorzato proposes the measure of the simplicity of model assumptions as a surrogate to assess their reliability.
The simplicity of assumptions is closely related to the interpretability of the model.
- “the reliability of a model necessarily depends on the reliability of all its model assumptions, which are never self-justifying.” (Scorzato, 2024, p. 7)
- “In fact, predictions alone—no matter how impressive—are never sufficient to warrant trust in a model (Barnes, 2022; Votsis et al., 2014).” (Scorzato, 2024, p. 6)
- “Trustworthy predictions require trustworthy premises.” (Scorzato, 2024, p. 6)
- “This confirms that also ==DNN predictions are only valuable when they stem from a valuable model==.” (Scorzato, 2024, p. 7)


### Model assumptions
“Any model, whether TS or ML is essentially characterised by all its assumptions and its accuracy with respect to the existing empirical data.” (Scorzato, 2024, p. 7)
- all those that are necessary to reproduce the outcome of the model
- ==“including the comparison with the empirical evidence”: related to Sullivan's external link view?==
- ==“expression of the input data”: related to T&S' model-internal data representation view?==
- “training data themselves are not part of the model assumptions”

Assumptions from background science: TS vs ML models
The domain of applicability of TS is better restricted (background science, transparent approach to parameter instantiation, parameter consistent with broad range of empirical evidence). 
The domain of applicability of ML models is even harder to define as it is even difficult to say how the model applies in reference to known features of the target space, let alone to unknown features. 
- This raises questions on Sullivan's notion of link uncertainty and what it means to "link a DNN to its target phenomenon". What does it mean to link a ML model to its target, if the link is established in reference to a difficult to define domain of applicability?
- Does the underdetermination of ML models affect link uncertainty?



He argues that proving the independence of model outcome from parameter details is wanted, but is difficult to prove in DNN and was not achieved. 
- “Formal proofs of independence from details, if available, are very desirable, because no further assumption is needed in that case.” (Scorzato, 2024, p. 8)
- ==“Despite considerable effort, researchers have not been able to identify any simple set of rules that makes the outcome of DNN models independent of any further detail.” (Scorzato, 2024, p. 8)==

There are strong indications that "Predictions are certainly determined by the entire set of DNN parameters" is true as flexibly parameterized DNN do in fact inform different model decisions. The UAT-enabled flexibility of DNN is probably not compatible with a simple set of rules that make model decision independent of any further detail.
- ==“Moreover, this difficulty might actually be an intrinsic price to pay for the great flexibility of DNN models (see also Hartmann and Richter (2023).” (Scorzato, 2024, p. 8) ==
Sullivan argues that understanding model implementation is irrelevant for understanding phenomena. She argues that ML model predictions are driven by "high-level properties" of the model. As long these are transparent, i.e. as long as the modeler knows the high-level functioning of the model that supposedly determines model outcome, detail implementations can be opaque without impeding understanding.


Sullivan tries to de-correlate model details and "high-level properties" in order to argue that opacity of detail implementations is not a problem for understanding. Understanding from ML models depends on epistemic access to "high-level properties". Sullivan tries to render ML model outcome independent of any further assumptions that take detail implementation into consideration.





### Implications of unrestricted domain of application in ML models on Sullivan's link uncertainty


### Considering model assumptions relevant for assessing reliability
Sullivan takes model assumptions into account when she is referencing background knowledge of the model and knowledge of higher-level functioning of the model. However, she considers these assumptions in such a way that she can argue that further details of model implementation become irrelevant for understanding. She argues that considering these assumptions and model characteristics is enough to determine model decision, assumptions that determine detail parameterization are irrelevant to characterize overall model behavior as detail parameterization does not drive model outcome. So Sullivan takes model assumptions into consideriation, but in such a way to wave away other assumptions.
Whereas for Scorzato, model assumption are insofar relevant that understanding model implementation becomes necessary for estimating reliability of prediction, and thus, need to be considered for understanding from ML models as well. 
Sullivan only considers a subset of model assumptions. She can wave away the need for transparency as she does not consider all ML model assumptions. For Scorzato, considering the whole set of model assumptions makes transparency important.






- “Ideally, the specific values of all those parameters are not essential to determine a prediction, which should depend only on the training domain. However, the training domain is difficult to define and the outcome may depend also on subtle details of the training process. In fact, weight initialisation and pre-training techniques are key design choices when training and deploying a DNN model (Narkhede et al., 2022; Glorot and Bengio, 2010). Adversarials (Szegedy et al., 2014) are also evidence of high sensitivity to details.” (Scorzato, 2024, p. 7) 
	- this shoots down "model decision driven by high-level properties" as not the exact parameterization is relevant but model decision is highly sensitive to details of the training process (weight initialization, pre-training, adversarials as evidence for sensitivity)
	- as ML predictions are determined by model assumptions: Sullivan's post-training ML model decisions are predominantly driven by "high-level properties", whereas pre-training there must have been many more underlying assumptions that made training possible? it sounds like a weird decrease in model assumptions before and after training? can it be even the same model, when the model assumption change so drastically?
- “Instead, the lack of understanding of the training dynamics enforces the inclusion of the full specification of the DNN (initial) parameters and training data as part of the assumptions.” (Scorzato, 2024, p. 8) 
	- the increase in complexity leads to the inclusion of more detailed model assumptions

- ==“High sensitivity to details is the key aspect of the so-called black-box problem (Desai et al., 2022) of some ML methods: lack of understanding is a serious limitation to the extent that we cannot tell which details actually matter for a conclusion.” (Scorzato, 2024, p. 8)==
	- model outcome is sensitive to details in training; it is very difficult (impossible?) to identify which exact details are driving model outcome; underlying DNN model assumptions that determine model outcome are thus opaque; so we do not understand which model details actually determined model outcome in DNN




### Sullivan: DNN are just like other models, but more complex
Sullivan treats DNN just like any other model. She argues for what is true for simple models is also true for complex models. And DNN are nothing else than a complex model with increased levels of opacity. They can be understood analogous to other classes of models.
Scorzato stresses crucial differences between TS and DNN models. DNN models are even qualitatively different to other ML models due to their inherent flexibility.
- crucial difference between TS and DNN in respect to assumptions that restrict the domain of applicability, approach to parameterization (transparent in TS), parameter fitting (consistency with empirical findings of background scientific domains in TS)
