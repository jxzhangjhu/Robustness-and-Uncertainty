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
- 2022 - Francisca Vasconcelos, Bobby He, Nalini Singh, Yee Whye Teh. UncertaINR: Uncertainty Quantification of End-to-End Implicit Neural Representations for Computed Tomography - [pdf](https://arxiv.org/pdf/2202.10847.pdf) 
> this is very new work from Oxford group.  INR can be leveraged a little more?  no code 

- [NeurIPS 2021] - Sheheryar Zaidi*, Arber Zela*, Thomas Elsken, Chris Holmes, Frank Hutter and Yee Whye Teh.  Neural Ensemble Search for Uncertainty Estimation and Dataset Shift - [pdf](https://arxiv.org/abs/2006.08573), -[code](https://github.com/automl/nes)




2. [NeurIPS 2021] - [Out-of-distribution generalization and adaptation in natural and artificial intelligence](https://docs.neurodata.io/ood-workshop/)
3. [NeurIPS 2021] - [Distribution shifts: connecting methods and applications (DistShift)](https://neurips.cc/Conferences/2021/Schedule?showEvent=21859)
4. [NeurIPS 2021] - [Your Model is Wrong: Robustness and misspecification in probabilistic modeling](https://neurips.cc/Conferences/2021/Schedule?showEvent=21872)
5. [ICML 2022] - [Beyond Bayes: Paths Towards Universal Reasoning Systems](https://beyond-bayes.github.io/)
6. [ICML 2022] - [Workshop on Distribution-Free Uncertainty Quantification](https://icml.cc/Conferences/2022/Schedule?showEvent=13460)
7. [ICML 2022] - [Principles of Distribution Shift (PODS)](https://sites.google.com/view/icml-2022-pods)




### New topics 

1. Implicit neural representations [awesome github](https://github.com/jxzhangjhu/awesome-implicit-representations)

> - **What are implicit neural representations?**
Implicit Neural Representations (sometimes also referred to as coordinate-based representations) are a novel way to parameterize signals of all kinds. Conventional signal representations are usually discrete - for instance, images are discrete grids of pixels, audio signals are discrete samples of amplitudes, and 3D shapes are usually parameterized as grids of voxels, point clouds, or meshes. In contrast, Implicit Neural Representations parameterize a signal as a continuous function that maps the domain of the signal (i.e., a coordinate, such as a pixel coordinate for an image) to whatever is at that coordinate (for an image, an R,G,B color). Of course, these functions are usually not analytically tractable - it is impossible to "write down" the function that parameterizes a natural image as a mathematical formula. Implicit Neural Representations thus approximate that function via a neural network.

- **Why are they interesting?**
Implicit Neural Representations have several benefits: First, they are not coupled to spatial resolution anymore, the way, for instance, an image is coupled to the number of pixels. This is because they are continuous functions! Thus, the memory required to parameterize the signal is independent of spatial resolution, and only scales with the complexity of the underyling signal. Another corollary of this is that implicit representations have "infinite resolution" - they can be sampled at arbitrary spatial resolutions.

This is immediately useful for a number of applications, such as super-resolution, or in parameterizing signals in 3D and higher dimensions, where memory requirements grow intractably fast with spatial resolution. Further, generalizing across neural implicit representations amounts to learning a prior over a space of functions, implemented via learning a prior over the weights of neural networks - this is commonly referred to as meta-learning and is an extremely exciting intersection of two very active research areas! Another exciting overlap is between neural implicit representations and the study of symmetries in neural network architectures - for intance, creating a neural network architecture that is 3D rotation-equivariant immediately yields a viable path to rotation-equivariant generative models via neural implicit representations.

Another key promise of implicit neural representations lie in algorithms that directly operate in the space of these representations. In other words: What's the "convolutional neural network" equivalent of a neural network operating on images represented by implicit representations?


### UQ people 

1. Yee Whye Teh  [google scholar](https://scholar.google.com/citations?hl=en&user=y-nUzMwAAAAJ&view_op=list_works&sortby=pubdate)


