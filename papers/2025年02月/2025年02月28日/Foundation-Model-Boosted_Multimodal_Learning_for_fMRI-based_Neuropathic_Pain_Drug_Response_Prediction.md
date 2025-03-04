# # 基于基础模型的增强式多模态学习，用于基于fMRI的神经病理性疼痛药物反应预测

发布时间：2025年02月28日

`LLM应用` `疼痛管理`

> Foundation-Model-Boosted Multimodal Learning for fMRI-based Neuropathic Pain Drug Response Prediction

# 摘要

> 神经性疼痛影响着高达10%的成年人，由于治疗效果有限且耐受性不佳，治疗仍然具有挑战性。尽管静息态功能磁共振成像（rs-fMRI）是一种有前景的非侵入性脑生物标志物测量方法，可用于预测药物反应，但fMRI的复杂性要求机器学习模型具备强大的容量。然而，神经性疼痛研究中的极端数据稀缺性限制了高容量模型的应用。为了解决这一难题，我们提出了FMM$_{TC}$，一种基于fMRI的神经性疼痛药物反应预测的Foundation-Model增强的多模态学习框架，该框架巧妙地结合了疼痛特异性数据中的内部多模态信息以及来自大型疼痛不可知数据的外部知识。具体而言，为了充分利用有限的疼痛特异性数据，FMM$_{TC}$整合了两种rs-fMRI模态的互补信息：时间序列和功能连接。FMM$_{TC}$还通过一个fMRI基础模型得到了进一步增强，该模型从广泛的疼痛不可知fMRI数据集中获取外部知识，从而丰富了有限的疼痛特异性信息。使用内部数据集和来自OpenNeuro的公共数据集进行的评估表明，与仅考虑一种rs-fMRI模态的现有单模态fMRI模型相比，FMM$_{TC}$在表示能力、泛化能力和跨数据集适应性方面表现出色。消融研究验证了FMM$_{TC}$中多模态学习和基于基础模型的外部知识转移的有效性。通过集成梯度解释研究，我们进一步解释了FMM$_{TC}$如何通过跨数据集动态行为增强其适应性。总之，FMM$_{TC}$通过准确预测药物反应，提高了神经性疼痛治疗开发中的受试者分层效率，从而推动了临床试验的发展。

> Neuropathic pain, affecting up to 10% of adults, remains difficult to treat due to limited therapeutic efficacy and tolerability. Although resting-state functional MRI (rs-fMRI) is a promising non-invasive measurement of brain biomarkers to predict drug response in therapeutic development, the complexity of fMRI demands machine learning models with substantial capacity. However, extreme data scarcity in neuropathic pain research limits the application of high-capacity models. To address the challenge of data scarcity, we propose FMM$_{TC}$, a Foundation-Model-boosted Multimodal learning framework for fMRI-based neuropathic pain drug response prediction, which leverages both internal multimodal information in pain-specific data and external knowledge from large pain-agnostic data. Specifically, to maximize the value of limited pain-specific data, FMM$_{TC}$ integrates complementary information from two rs-fMRI modalities: Time series and functional Connectivity. FMM$_{TC}$ is further boosted by an fMRI foundation model with its external knowledge from extensive pain-agnostic fMRI datasets enriching limited pain-specific information. Evaluations with an in-house dataset and a public dataset from OpenNeuro demonstrate FMM$_{TC}$'s superior representation ability, generalizability, and cross-dataset adaptability over existing unimodal fMRI models that only consider one of the rs-fMRI modalities. The ablation study validates the effectiveness of multimodal learning and foundation-model-powered external knowledge transfer in FMM$_{TC}$. An integrated gradient-based interpretation study explains how FMM$_{TC}$'s cross-dataset dynamic behaviors enhance its adaptability. In conclusion, FMM$_{TC}$ boosts clinical trials in neuropathic pain therapeutic development by accurately predicting drug responses to improve the participant stratification efficiency.

[Arxiv](https://arxiv.org/abs/2503.00210)