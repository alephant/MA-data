>[!note]
>“‘realism of the assumptions debate’ (see Knuuttila 2009 for a review)” (Regt, 2015, p. 3787) relevance for Scorzato's point on model assumptions?
### Reliability as condition for understanding from ML models
Scorzato investigates the reliability of ML models. Reliable predictions of a model are crucial for  models to enable understanding. As reliability requires reliable model assumptions, the capacity to enable understanding needs to be investigated in light of model assumptions.
==“Trustworthy predictions require trustworthy premises.” (Scorzato, 2024, p. 6)==

Model reliability is assessed by estimating the uncertainty of model predictions. He argues that a statistical error analysis of prediction error needs to be integrated with a deeper epistemological analysis. He emphasizes that DNN have special characteristics that set them apart from other ML or TS models. This has implications in how to assess DNN reliability.

### "The illusion of predictions without assumptions"
Scorzato argues that as there is no theory-free observation, the estimation of prediction error of a model, ==i.e. assessing model reliability cannot be done without considering model assumptions.==
Assessing reliability of models solely based on fit with data is fallacious.
This is due to the underdetermination thesis that argues that for any given set of data, multiple theories or models can provide a fitting explanation or prediction.
- “Data alone cannot enforce any conclusion.” (Scorzato, 2024, p. 4)
- ==How does the underdetermination of ML models affect link uncertainty?==

The UAT tells us that ML models, especially deep neural networks, have the capacity to approximate any continuous function given sufficient complexity and data. This makes ML models highly flexible to fit any set of data and is the theoretical basis for their high predictive power.
However, this makes ML models even more prone to underdetermination.
- “The predictions of the ML model hence depend not only on the data but also on the architecture of the ML model and, in the absence of evidence to the contrary, also on the algorithmic and initialisation details.” (Scorzato, 2024, p. 4)

This suggests that ML predictions are determined by more than just empirical aspects, but by model assumptions as well.
Model assumptions are non-empirical, language-independent, theory-laiden and cannot be made future-proof. i.e. assumptions cannot be tested to hold in unknown contexts. 
i.e. the scope of applicability of the model cannot be definitely defined.
- ==What does it mean to "link a DNN to its target phenomenon" when the link is established in reference to a difficult to define domain of applicability?==

### Prediction is not enough
Predictive power alone is not a good measure for model reliability. Model assumptions need to be reliable as well. i.e. empirical success is not enough, other non-empirical aspects are also important to confirm reliability.
The reliability of model assumptions cannot be directly assessed. Scorzato proposes the measure of the simplicity of model assumptions as a surrogate to assess their reliability.
The simplicity of assumptions is closely related to the interpretability of the model.
- “the reliability of a model necessarily depends on the reliability of all its model assumptions, which are never self-justifying.” (Scorzato, 2024, p. 7)
- “In fact, predictions alone—no matter how impressive—are never sufficient to warrant trust in a model (Barnes, 2022; Votsis et al., 2014).” (Scorzato, 2024, p. 6)
- “Trustworthy predictions require trustworthy premises.” (Scorzato, 2024, p. 6)
- “This confirms that also DNN predictions are only valuable when they stem from a valuable model.” (Scorzato, 2024, p. 7)


### Model assumptions
“Any model, whether TS or ML is essentially characterised by all its assumptions and its accuracy with respect to the existing empirical data.” (Scorzato, 2024, p. 7)
- all those that are necessary to reproduce the outcome of the model
- ==“including the comparison with the empirical evidence”: related to Sullivan's external link view?==
- ==“expression of the input data”: related to T&S' model-internal data representation view?==
- “training data themselves are not part of the model assumptions”

**Assumptions from background science: TS vs ML models**
TS rely on model specific assumptions and assumptions that come from background sciences. TS' assumptions restrict their domain of applicability. TS model parameters are set up in advance, inherited from background science and are consistent with a broad range of empirical evidence. i.e. TS' assumptions are transparent.

DNN models do not rely on many assumptions from background science. They are very generic. Ideally, DNN model outcome is defined by their model architecture and their training domain. However, this is not realistic. Their training domain is hard to define, even with respect to known features. DNN training depends on many subtle details, e.g. on weight initialisation and pre-training techniques. DNN training does not depend on a simple set of rules. i.e. DNN model outcome is highly sensitive to details of the training process.
This makes it necessary to include assumptions that are hard to track.
- ==“Instead, the lack of understanding of the training dynamics enforces the inclusion of the full specification of the DNN (initial) parameters and training data as part of the assumptions.” (Scorzato, 2024, p. 8)==

Ideally, model outcome depends on a simple set of rules and is independent of minute model details. Then no further assumptions are needed. But no simple set of rules was found for DNN. Probably, DNN are not compatible with a simple set of rules that make their predictions independent of considering any further model details.

### How does this relate to the problem of opacity?
So, Scortazo established that DNN predictions are highly sensitive to details. But it is very difficult (impossible?) to identify which exact details are driving DNN predictions. The underlying model assumptions that determine model outcome are opaque. So we do not understand how the DNN came to its prediction:
- ==“High sensitivity to details is the key aspect of the so-called black-box problem (Desai et al., 2022) of some ML methods: lack of understanding is a serious limitation to the extent that we cannot tell which details actually matter for a conclusion.” (Scorzato, 2024, p. 8)==

As TS are applied to different data and domains, their paramterization is kept consistent.
DNN parameterization is not kept consistent. As DNN are applied to new domains, their parameterization changes, i.e. the underlying assumptions of the DNN change. 

Which features a model tracks define its domain of applicability.
For TS measurable features define its domain. This makes it possible to dismiss unwanted features by restricting out-of-domain data to enter into the model. 

The idea with DNN is that they learn to track the most relevant features through training and have no features defined in advance. i.e. their domain of applicability is not defined in terms of relevant features. But the training data needs to contain the relevant features. However, it is difficult to tell which features a DNN learns to track as model details are opaque. Thus for DNN, it is difficult to define their domain of applicability. 
If we cannot restrict the DNN domain, we have to test its performance across all domains.



### How this relates to Sullivan
Sullivan argues that understanding model details is irrelevant for understanding phenomena. She argues “Simply having a highly predictive model, and knowing the high-level emerging properties of the model, uncovers that it is possible to use a machine learning representation for disease prediction.” (Sullivan, 2022, p. 20).

"High-level emerging properties of the model" imply that for Sullivan, these properties determine the outcome of the DNN and enable us to understand. Model details are irrelevant for understanding. Model details can be opaque without necessarily impeding understanding. However, DNN model outcome is highly sensitive to model details, i.e. high-level properties are not the sole cause for model outcome.

If DNN rely on many assumptions, e.g. relating to details of their training, what happened to these assumptions according to Sullivan?

So it seems like Sullivan cannot simply state that “it is not necessary to look inside the implementation black box to answer these types of how-possibly questions. All that is needed is the higher-level understanding of how the system is able to identify high-level patterns within data.” (Sullivan, 2022, p. 20)

Higher-level understanding of higher-level properties alone is not sufficient to use DNN model outcome to generate understanding. More is needed. 

It sounds like Sullivan takes model assumptions into account, but in such a way to dismiss other assumptions. She considers background knowledge of the model and knowledge of higher-level functioning of the model, in such a way to dismiss the importance of model details. 

For Scorzato, model assumptions are insofar relevant that understanding model details becomes necessary to assess model reliability. As model reliability is crucial for a model to enable understanding, model assumptions also need to be considered when looking at understanding from models.

Sullivan only considers a subset of model assumptions. Thus, she can dimiss the need for transparency that would be needed to consider all model assumptions. For Scorzato, considering the all model assumptions makes transparency important.




### Sullivan: DNN are just like other models, but more complex
Sullivan treats DNN just like any other model. She argues for what is true for simple models is also true for complex models. And DNN are nothing else than a complex model with increased levels of opacity. They can be understood analogous to other classes of models.
Scorzato stresses crucial differences between TS and DNN models concerning domain of applicability, approach to parameterization (transparent in TS), parameter fitting (consistency with empirical findings of background scientific domains in TS). DNN models are even qualitatively different to other ML models due to their inherent flexibility.
