# 基于定量皮肤属性的多模态大语言模型锚定：检索研究

发布时间：2025年08月27日

`LLM应用` `医疗健康`

> Grounding Multimodal Large Language Models with Quantitative Skin Attributes: A Retrieval Study

# 摘要

> 人工智能模型在诊断包括癌症在内的皮肤疾病上成效显著，有望辅助临床医生进行病情分析。然而，要投入实际应用，模型预测的可解释性亟待大幅提升。为此，我们探索结合两种极具潜力的方法：多模态大型语言模型（MLLMs）与定量属性应用。MLLMs有望提升可解释性，其能通过交互式形式，以自然语言给出诊断推理过程。此外，近期研究发现，诸多与病变外观相关的定量属性（如病变面积）能以极高准确率预测恶性肿瘤。将预测结果建立在这些属性概念的函数关系上，有助于增强模型的可解释性。我们的研究证实，通过微调模型以从图像中预测这些属性值，MLLM的嵌入空间能够与这些属性建立关联。具体而言，我们利用SLICE-3D数据集，通过特定于属性的基于内容的图像检索案例研究，对嵌入空间中的这种关联进行了评估。

> Artificial Intelligence models have demonstrated significant success in diagnosing skin diseases, including cancer, showing the potential to assist clinicians in their analysis. However, the interpretability of model predictions must be significantly improved before they can be used in practice. To this end, we explore the combination of two promising approaches: Multimodal Large Language Models (MLLMs) and quantitative attribute usage. MLLMs offer a potential avenue for increased interpretability, providing reasoning for diagnosis in natural language through an interactive format. Separately, a number of quantitative attributes that are related to lesion appearance (e.g., lesion area) have recently been found predictive of malignancy with high accuracy. Predictions grounded as a function of such concepts have the potential for improved interpretability. We provide evidence that MLLM embedding spaces can be grounded in such attributes, through fine-tuning to predict their values from images. Concretely, we evaluate this grounding in the embedding space through an attribute-specific content-based image retrieval case study using the SLICE-3D dataset.

[Arxiv](https://arxiv.org/abs/2508.20188)