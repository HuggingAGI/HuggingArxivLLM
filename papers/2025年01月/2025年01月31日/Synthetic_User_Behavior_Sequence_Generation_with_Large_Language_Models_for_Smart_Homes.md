# 基于大型语言模型的智能家居合成用户行为序列生成

发布时间：2025年01月31日

`LLM应用

理由：这篇论文主要讨论了如何利用大型语言模型（LLMs）来生成合成数据集，以提升智能家居模型的泛化能力。虽然涉及了智能家居系统的安全问题，但核心内容是利用LLMs进行数据生成和模型训练，属于LLM在实际应用中的具体应用场景。因此，将其分类为“LLM应用”是合适的。` `智能家居` `物联网`

> Synthetic User Behavior Sequence Generation with Large Language Models for Smart Homes

# 摘要

> 近年来，随着智能家居系统的普及，其安全问题日益凸显。目前，大多数智能家居安全解决方案（如异常检测和行为预测模型）依赖于预先收集的固定数据集进行训练。然而，数据集收集过程耗时且缺乏灵活性，难以适应不断变化的智能家居环境。此外，个人数据的收集也引发了严重的隐私问题。最近，大型语言模型（LLMs）凭借其在自然语言处理、推理和问题解决方面的强大能力，成为跨领域任务的利器。本文提出了一种基于LLM的合成数据集生成框架IoTGen，旨在提升下游智能家居模型的泛化能力。通过生成反映环境变化的新合成数据集，智能家居模型得以重新训练，克服固定和过时数据的局限，更好地适应现实家庭环境的动态变化。具体而言，我们首先提出了一种针对物联网行为数据的结构模式感知压缩（SPPC）方法，在保留关键信息的同时大幅减少token消耗。随后，我们设计了一套系统化的提示生成和数据生成方法，自动生成规范且合理的物联网合成数据，助力任务模型进行自适应训练，提升其泛化能力和实际表现。

> In recent years, as smart home systems have become more widespread, security concerns within these environments have become a growing threat. Currently, most smart home security solutions, such as anomaly detection and behavior prediction models, are trained using fixed datasets that are precollected. However, the process of dataset collection is time-consuming and lacks the flexibility needed to adapt to the constantly evolving smart home environment. Additionally, the collection of personal data raises significant privacy concerns for users. Lately, large language models (LLMs) have emerged as a powerful tool for a wide range of tasks across diverse application domains, thanks to their strong capabilities in natural language processing, reasoning, and problem-solving. In this paper, we propose an LLM-based synthetic dataset generation IoTGen framework to enhance the generalization of downstream smart home intelligent models. By generating new synthetic datasets that reflect changes in the environment, smart home intelligent models can be retrained to overcome the limitations of fixed and outdated data, allowing them to better align with the dynamic nature of real-world home environments. Specifically, we first propose a Structure Pattern Perception Compression (SPPC) method tailored for IoT behavior data, which preserves the most informative content in the data while significantly reducing token consumption. Then, we propose a systematic approach to create prompts and implement data generation to automatically generate IoT synthetic data with normative and reasonable properties, assisting task models in adaptive training to improve generalization and real-world performance.

[Arxiv](https://arxiv.org/abs/2501.19298)