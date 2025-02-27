# 跨模态分析针对WESAD数据集的压力分类问题

发布时间：2025年02月25日

`其他

这篇论文主要探讨了深度学习在医疗健康领域的应用，特别是压力检测方面的研究。它利用了多模态生理数据和Transformer模型，但并未直接涉及大型语言模型（LLM）、智能体（Agent）或检索增强生成（RAG）的具体应用或理论。因此，它更符合“其他”类别的分类。` `医疗健康` `人工智能`

> Cross-Modality Investigation on WESAD Stress Classification

# 摘要

> 深度学习在医疗健康领域的广泛应用，借助AI与传感器技术的进步，显著提升了诊断、治疗和监测的效能。在移动医疗领域，AI工具实现了压力等健康状况的早期诊断和持续监测。可穿戴设备与多模态生理数据的应用，使压力检测变得日益可行，但模型效果仍受数据质量、数量和模态的制约。本研究基于WESAD数据集，开发了用于压力检测的Transformer模型，涵盖了心电图（ECG）、皮肤电活动（EDA）、肌电图（EMG）、呼吸速率（RESP）、温度（TEMP）和三轴加速度计（ACC）等多模态信号。实验结果表明，单模态Transformer模型在生理信号分析中表现出色，压力检测的准确率、精确率和召回率均达到【数学公式】的顶尖水平。此外，本研究不仅探索了跨模态性能，还通过二维嵌入空间的可视化和基于数据方差的定量分析，深入解释了模型的工作原理。尽管压力检测与监测领域已有大量研究，但不同模态下模型的鲁棒性和泛化能力尚未得到充分探索。这项研究是首次尝试通过解释嵌入空间来理解压力检测机制，为跨模态性能提供了宝贵的见解。

> Deep learning's growing prevalence has driven its widespread use in healthcare, where AI and sensor advancements enhance diagnosis, treatment, and monitoring. In mobile health, AI-powered tools enable early diagnosis and continuous monitoring of conditions like stress. Wearable technologies and multimodal physiological data have made stress detection increasingly viable, but model efficacy depends on data quality, quantity, and modality. This study develops transformer models for stress detection using the WESAD dataset, training on electrocardiograms (ECG), electrodermal activity (EDA), electromyography (EMG), respiration rate (RESP), temperature (TEMP), and 3-axis accelerometer (ACC) signals. The results demonstrate the effectiveness of single-modality transformers in analyzing physiological signals, achieving state-of-the-art performance with accuracy, precision and recall values in the range of $99.73\%$ to $99.95\%$ for stress detection. Furthermore, this study explores cross-modal performance and also explains the same using 2D visualization of the learned embedding space and quantitative analysis based on data variance. Despite the large body of work on stress detection and monitoring, the robustness and generalization of these models across different modalities has not been explored. This research represents one of the initial efforts to interpret embedding spaces for stress detection, providing valuable information on cross-modal performance.

[Arxiv](https://arxiv.org/abs/2502.18733)