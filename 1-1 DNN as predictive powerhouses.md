- general motivation of my thesis
- predictive strength of DNN
- DNN already used as models
- criteria 



ML models in general and DNN in particular are predictive powerhouses and their predictive power will never be any worse than today. Among many more examples, ML algorithms have achieved human-level accuracy in visual recognition tasks (Russakovsky_2015), disease classification (Esteva_2017), similary judgements (Peterson_2016), high performance on complex tasks (Mnih_2015), natural-sounding audio generation (Oord_2016) or the prediction and modelling of neural activity (Cadena_2018, Yamins_2014, Yamins_2016, Khaligh-Razavi_2014).
However, the use of DNN as scientific models is controversial. DNN are highly complex, state-of-the-art archictectures contain billions of parameters, their functioning is difficult to understand and control for the modeler. Thus, DNN are labelled black boxes. Black boxes somehow do what they are supposed to do, but one does not fully understand how they do. As DNN lack transparency and simplicity, critics dismiss their capacity to enable scientific understanding. At the same time, the use of DNN as scientific models is continously expanding. Especially data-driven sciences such as genomics are transformed by the use of DNN as they are highly capable to learn complex patterns (Eraslan_2019). But worries remain - do scientists sacrifice scientific understanding by ML models compared to traditional scientific models?
“One might argue that a machine-learning approach to determine the non-linear response from varying parameter settings is a rather black-box approach that goes against the traditional approach to spectra: based on scientific understanding and physics.” (Agarwal et al., 2012, p. 1410)

Are ML models incapable of providing understanding? Does their black box nature prevent DNN to provide scientific understanding?

To answer these questions, I first give a lay of the land and introduce DNN in their structure and  modelling process, clarify the use of DNN as scientific models and the black box problem of DNN. Then I compare two views on understanding from ML models: the first introduced by Sullivan that dismisses ML opacity as an in-principle problem for understanding, and second by T&S introduced as a refined of Sullivan's view that narrows the scope of understanding. I critically evaluate both in respect to key concepts and conclusions: I reject Sullivan's thesis on ML opacity being no problem, accept her external link view in principle, reject T&S' view on the relevance of ML implementation details and embrace their narrow view of understanding in principle. Then I present my own view: while opacity cannot be easily dismissed, understanding from ML models can be achieved in scientifically meaningful ways by combining an external link view with a narrow scope of understanding (understanding TML targets).



A classical approach to scientific modelling is that relevant model features are measurable and specified, parameter values remain largely consistent across domains of application and model assumptions are few. On the other hand, the idea of DNN models is that their relevant model features are initially unspecified and are acquired through training. However, due to their high level of opacity, it proves to be difficult to determine which features a DNN model tracks and what the parameter values are. When DNN models are applied to new domains, their parameterization usually changes drastically (Scorzato_2024).





