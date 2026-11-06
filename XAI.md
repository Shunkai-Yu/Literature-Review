# XAI Literature

## 2023

| Topic                       | Paper                                                                                                                     | Venue                                      | Code | Description                                                                                                                                                                                                 | Status |
| --------------------------- | ------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------ | ---- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------ |
| Statistical Association     | [Explaining Classifiers with Measures of Statistical Association](https://doi.org/10.1016/j.csda.2023.107701)            | Computational Statistics and Data Analysis | -    | Introduces the Xi-method, which measures feature importance through statistical dependence between features and class labels or model predictions, and compares these pre-hoc and post-hoc dependence structures. | Core   |
| Concept-based Explanation | [CRAFT: Concept Recursive Activation FacTorization for Explainability](https://arxiv.org/abs/2211.10154) | CVPR 2023 | [GitHub](https://github.com/deel-ai/Craft) | Introduces CRAFT, a concept-based explanation framework that uses Non-negative Matrix Factorization (NMF) to extract visual concepts from neural network activations. Proposes recursive concept decomposition, Sobol indices to quantify concept importance, and Concept Attribution Maps to visualize where concepts contribute to model predictions. | Core |

## 2020

| Topic | Paper | Venue | Code | Description | Status |
| --- | --- | --- | --- | --- | --- |
| Game-theoretic Attribution | [Neuron Shapley: Discovering the Responsible Neurons](https://arxiv.org/abs/2002.09815) | NeurIPS 2020 | [GitHub](https://github.com/amiratag/neuronshapley) | Introduces Neuron Shapley, which uses Shapley values to quantify individual neurons' contributions to model predictions and performance by evaluating their marginal effects across neuron subsets. Proposes an efficient multi-armed bandit algorithm to identify the most influential neurons while accounting for interactions between neurons. | Core |

## 2017

| Topic                      | Paper                                                                                                      | Venue        | Code                                    | Description                                                                                                                                                                        | Status |
| -------------------------- | ---------------------------------------------------------------------------------------------------------- | ------------ | --------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------ |
| Gradient-based Attribution | [Grad-CAM: Visual Explanations from Deep Networks via Gradient-based Localization](https://arxiv.org/abs/1610.02391) | ICCV 2017    | [GitHub](https://github.com/ramprs/grad-cam) | Uses gradients of a target output with respect to convolutional feature maps to compute channel weights and generate a class-specific localization heatmap.                       | Core   |
| Game-theoretic Attribution | [A Unified Approach to Interpreting Model Predictions](https://arxiv.org/abs/1705.07874)                   | NeurIPS 2017 | [GitHub](https://github.com/shap/shap) | Introduces SHAP, a unified additive feature-attribution framework based on Shapley values, assigning each feature its average marginal contribution across feature coalitions while satisfying local accuracy, missingness, and consistency. | Core   |

## 2016

| Topic                      | Paper                                                                                       | Venue     | Code                                        | Description                                                                                                                                                 | Status |
| -------------------------- | ------------------------------------------------------------------------------------------- | --------- | ------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------- | ------ |
| Gradient-based Attribution | [Learning Deep Features for Discriminative Localization](https://arxiv.org/abs/1512.04150) | CVPR 2016 | [GitHub](https://github.com/zhoubolei/CAM) | Introduces Class Activation Mapping (CAM), using class-specific weights on globally averaged convolutional feature maps to produce class-discriminative localization heatmaps. | Core   |
