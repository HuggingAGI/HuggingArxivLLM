# 设计模型到代码转换解决方案：LOCOFY 大型设计模型

发布时间：2025年07月21日

`LLM应用

理由：这篇论文讨论了大型语言模型（LLMs）在设计到代码转换中的应用，并提出了专门针对这一任务的大型设计模型（LDMs）。论文详细描述了训练和推理 pipeline，包括设计优化器、标签和特征检测、自动组件提取等组件，旨在提高转换的准确性和可重复性。因此，它属于LLM应用类别，因为它专注于LLMs在特定任务中的实际应用和优化。` `网页开发`

> LOCOFY Large Design Models -- Design to code conversion solution

# 摘要

> 尽管大型语言模型和多模态大型语言模型（LLMs）在设计到代码转换应用中取得了进展，但仍面临诸多挑战，包括可解释性、可扩展性、资源需求和可重复性。为应对这些挑战，我们提出了大型设计模型（LDMs），专门针对设计和网页进行训练，以实现设计到代码的无缝转换。我们开发了一套整合数据工程和模型架构优化的训练与推理 pipeline。训练 pipeline 包括三个关键组件：1）设计优化器：基于专有真实数据集，优化设计中的不足；2）标签和特征检测：通过预训练和微调模型，精准识别和分类 UI 元素；3）自动组件提取：将重复的 UI 结构转化为可复用组件，生成模块化代码，减少冗余并提升代码复用性。推理 pipeline 则处理真实设计，生成精确且可解释的代码生成指令，确保转换的可靠性。实验结果表明，LDMs 在节点定位准确性、响应性和可重复性方面优于 LLMs。此外，我们的自定义标签和特征检测模型在广泛测试样本中展现了对 UI 元素的高精度识别能力。因此，LDMs 是一个可靠且优越的解决方案，能够深入理解设计并生成高效可靠的生产就绪代码。

> Despite rapid advances in Large Language Models and Multimodal Large Language Models (LLMs), numerous challenges related to interpretability, scalability, resource requirements and repeatability remain, related to their application in the design-to-code space. To address this, we introduce the Large Design Models (LDMs) paradigm specifically trained on designs and webpages to enable seamless conversion from design-to-code. We have developed a training and inference pipeline by incorporating data engineering and appropriate model architecture modification. The training pipeline consists of the following: 1)Design Optimiser: developed using a proprietary ground truth dataset and addresses sub-optimal designs; 2)Tagging and feature detection: using pre-trained and fine-tuned models, this enables the accurate detection and classification of UI elements; and 3)Auto Components: extracts repeated UI structures into reusable components to enable creation of modular code, thus reducing redundancy while enhancing code reusability. In this manner, each model addresses distinct but key issues for design-to-code conversion. Separately, our inference pipeline processes real-world designs to produce precise and interpretable instructions for code generation and ensures reliability. Additionally, our models illustrated exceptional end-to-end design-to-code conversion accuracy using a novel preview match score metric. Comparative experiments indicated superior performance of LDMs against LLMs on accuracy of node positioning, responsiveness and reproducibility. Moreover, our custom-trained tagging and feature detection model demonstrated high precision and consistency in identifying UI elements across a wide sample of test designs. Thus, our proposed LDMs are a reliable and superior solution to understanding designs that subsequently enable the generation of efficient and reliable production-ready code.

[Arxiv](https://arxiv.org/abs/2507.16208)