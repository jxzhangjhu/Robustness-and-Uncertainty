# Robustness and Uncertainty in NLP
Robustness, uncertainty, safety and trustworthiness in deep learning, e.g., NLP, CV, multimodality


### NLP important papers 


| Read | Year | Name                                                         | Brief introduction                | Citation |   PDF link |
| ------ | ---- | ------------------------------------------------------------ | ----------------------------- | ------------------------------------------------------------ |  ------- |
| ✅ | 2017 | Transformer | Attentaion is all you need   | NeurIPS 2017 | [PDF](https://github.com/jxzhangjhu/Robustness-and-Uncertainty-in-NLP/blob/main/pdf/1706.03762.pdf) |  



### NLP tutorial 




### UQ in Text classification 

1. (KDD 2021) **Uncertainty-Aware Reliable Text Classification** [PDF](https://github.com/jxzhangjhu/Robustness-and-Uncertainty-in-NLP/blob/main/pdf/KDD2021.pdf)
	> first apply evidential uncertainty (ENN) to text classification task; solve OOD detection tasks leveraging the OE method; three datasets (OE) are used as the benchmark; design adversarial examples


1. (AAAI 2020) **Uncertainty-aware deep classifiers using generative models** [PDF]


1. (NeurIPS 2019) **Can you trust your model's uncertainty? evaluating predictive uncertainty under dataset shift** [PDF]


1. (ICML 2020 UDL workshop) **Predictive uncertainty for probabilistic novelty detection in text classification** [PDF]


1. (AAAI 2019) **Quantifying uncertainties in natural language processing tasks** [PDF] 

1. (COLING 2020) **Word-Level Uncertainty Estimation for Black-Box Text Classifiers using RNNs**

1. (ACL 2020) **Uncertainty-aware curriculum learning for neural machine translation**

1. (ACL 2022) **Uncertainty Estimation of Transformer Predictions for Misclassification Detection** 


### Active learning (MC dropout) 

1. (2017, Arxiv) **Deep active learning for named entity recognition**


1. (2018, Arxiv) **Deep bayesian active learning for natural language processing: Results of a large-scale empirical study**


### UQ method 


1. (NeurIPS 2018) **Evidential deep learning to quantify classification uncertainty** [PDF](https://github.com/jxzhangjhu/Robustness-and-Uncertainty-in-NLP/blob/main/pdf/NeurIPS-2018-evidential-deep-learning-to-quantify-classification-uncertainty-Paper.pdf)



### Confidence score

> 09-15-2022 update from Kumar's literture review 

1. [NeurIPS 2017] Deep ensemble - **Simple and Scalable Predictive Uncertainty Estimation using Deep Ensembles** [pdf](https://arxiv.org/abs/1612.01474)
2. [NeurIPS 2019] - **Addressing Failure Prediction by Learning Model Confidence** - [pdf](https://proceedings.neurips.cc/paper/2019/file/757f843a169cc678064d9530d12a1881-Paper.pdf)
3. [Arxiv] - **Learning Confidence for Out-of-Distribution Detection in Neural Networks** [pdf](https://arxiv.org/pdf/1802.04865.pdf) -[code](https://github.com/uoguelph-mlrg/confidence_estimation) 

> 被引了366+ 有code， 好像是ICML，但是没过，挺有意思的paper 

4. [NeurIPS 2020] **Simple and Principled Uncertainty Estimation with Deterministic Deep Learning via Distance Awareness** - [pdf](https://papers.nips.cc/paper/2020/file/543e83748234f7cbab21aa0ade66565f-Paper.pdf) 

> Google的工作，distance awareness 的

5. [ICLR 2020] **Towards neural networks that provably know when they don't know** -[pdf](https://openreview.net/attachment?id=ByxGkySKwH&name=original_pdf), -[code](https://github.com/AlexMeinke/certified-certain-uncertainty)


6. [ICLR 2017] **A BASELINE FOR DETECTING MISCLASSIFIED AND OUT-OF-DISTRIBUTION EXAMPLES IN NEURAL NETWORKS** [pdf](https://arxiv.org/pdf/1610.02136.pdf), [code](https://github.com/hendrycks/error-detection)


7. [ICML 2015] **Probabilistic Backpropagation for Scalable Learning of Bayesian Neural Networks** [pdf](https://arxiv.org/pdf/1502.05336.pdf) 

8. [NeurIPS 2018] **Evidential Deep Learning to Quantify Classification Uncertainty** [pdf](https://proceedings.neurips.cc/paper/2018/file/a981f2b708044d6fb4a71a1463242520-Paper.pdf)

9. [arxiv] **The Case for Bayesian Deep Learning** [pdf](https://arxiv.org/pdf/2001.10995.pdf) 

10. [IBM UQ] **Uncertainty Quantification 360: A Holistic Toolkit for Quantifying and Communicating the Uncertainty of AI** - [pdf](https://arxiv.org/pdf/2106.01410.pdf)


### Confidence score + UQ + OOD + Generalization - SOTA work summary 

1. [Docuemnt AI application] - [HYCEDIS: HYbrid Confidence Engine for Deep DocumentIntelligence System](https://document-intelligence.github.io/DI-2021/files/di-2021_final_8.pdf)

> 看上去挺有意思的，关于document AI 的workshop best paper 


#### Workshops 

<!-- 1. [NeurIPS 2021] - [Bayesian Deep Learning](http://bayesiandeeplearning.org/)
2. [NeurIPS 2021] - [Out-of-distribution generalization and adaptation in natural and artificial intelligence](https://docs.neurodata.io/ood-workshop/)
3. [NeurIPS 2021] - [Distribution shifts: connecting methods and applications (DistShift)](https://neurips.cc/Conferences/2021/Schedule?showEvent=21859)
4. [NeurIPS 2021] - [Your Model is Wrong: Robustness and misspecification in probabilistic modeling](https://neurips.cc/Conferences/2021/Schedule?showEvent=21872)
5. [ICML 2022] - [Beyond Bayes: Paths Towards Universal Reasoning Systems](https://beyond-bayes.github.io/)
6. [ICML 2022] - [Workshop on Distribution-Free Uncertainty Quantification](https://icml.cc/Conferences/2022/Schedule?showEvent=13460)
7. [ICML 2022] - [Principles of Distribution Shift (PODS)](https://sites.google.com/view/icml-2022-pods) -->


1. [NeurIPS 2021] - [Bayesian Deep Learning](http://bayesiandeeplearning.org/)
- UncertaINR: Uncertainty Quantification of End-to-End Implicit Neural Representations for Computed Tomography [pdf](https://arxiv.org/pdf/2202.10847.pdf) 
> this is very new work from Oxford group.  INR can be leveraged a little more? 




2. [NeurIPS 2021] - [Out-of-distribution generalization and adaptation in natural and artificial intelligence](https://docs.neurodata.io/ood-workshop/)
3. [NeurIPS 2021] - [Distribution shifts: connecting methods and applications (DistShift)](https://neurips.cc/Conferences/2021/Schedule?showEvent=21859)
4. [NeurIPS 2021] - [Your Model is Wrong: Robustness and misspecification in probabilistic modeling](https://neurips.cc/Conferences/2021/Schedule?showEvent=21872)
5. [ICML 2022] - [Beyond Bayes: Paths Towards Universal Reasoning Systems](https://beyond-bayes.github.io/)
6. [ICML 2022] - [Workshop on Distribution-Free Uncertainty Quantification](https://icml.cc/Conferences/2022/Schedule?showEvent=13460)
7. [ICML 2022] - [Principles of Distribution Shift (PODS)](https://sites.google.com/view/icml-2022-pods)





