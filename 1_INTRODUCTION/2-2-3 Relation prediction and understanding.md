**Scientific explanations are expected to have predictive accuracy**
“Now following Douglas (2009, p. 458), we can hold predictive accuracy to also be a key marker of scientific explanations: A scientific explanation will be expected to produce new, generally successful predictions. An explanation that is not in fact used to generate predictions, or whose predictions quickly and obviously fail, would be scientifically suspect.” (Boge, 2022, p. 48) 

**What provides DNN their predictive power? Parameterized input-output mapping powered by SGD**
“It is exactly this mapping, established during the training phase, that provides DNNs with their predictive capabilities. To see this, recall that “[n]early all of deep learning is powered by [...] stochastic gradient descent” (Goodfellow et al., 2016, p. 147), which means the iterative minimization of a ‘loss function’ through several rounds of training (also called ‘epochs’).” (Boge, 2022, p. 46) 


==Predictive success of DNN is relevant for DNN to provide understanding, but it is not necessarily indicative that DNN can in fact provide understanding.==

**The case of spurious correlations underlying prediction illustrates why predictive power is not necessarily indicative of explanatory power.**
“Spurious correlations are misleading about the causal relations underlying a prediction. If a model is based on spurious correlations, the model’s predictive accuracy may be bad for a relevant subset of data, namely the subset where the difference between mere correlation and causal relation makes an observable difference. Caruana et al. (2015) provide a notorious example of a model for hospital admission triage that is (at least to a large extent) predictively successful, but makes wrong and harmful predictions for a subset of cases. However, a model that is to a large extent predictively successful, but that may still be systematically wrong about a target system given the knowledge of the researchers, is not a good tool for yielding understanding about the target system.” (Räz and Beisbart, 2022, p. 14)

**High-level properties of DNN underlying their predictive success not well understood**
generalization: “However, the reasons why these DNNs generalize well is only insufficiently understood (Zhang et al., 2017; Shwartz-Ziv & Tishby, 2017; Alain & Bengio, 2016; Zhang et al., 2021; Berner et al., 2021).” (Räz and Beisbart, 2022, p. 13)

optimization: “One important example concerns the optimization properties of DNNs: It is not known whether stochastic gradient descent (SGD) finds the best approximation ̂ f of a function f of interest.” (Räz and Beisbart, 2022, p. 15)

