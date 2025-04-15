# 零样本自主显微镜实现二维材料的智能化、可扩展表征。

发布时间：2025年04月14日

`LLM应用

摘要中提到的系统ATOMIC结合了大型语言模型（如ChatGPT）来实现材料表征的自动化，展示了LLM在实际应用中的潜力，属于LLM应用类别。` `材料科学` `人工智能`

> Zero-shot Autonomous Microscopy for Scalable and Intelligent Characterization of 2D Materials

# 摘要

> 传统上，原子尺度材料的表征需要人类专家经过数月甚至数年的专业培训。即使是经验丰富的操作人员，在分析新发现的材料（如二维结构）时，仍面临诸多挑战。这一瓶颈催生了对完全自主实验系统的迫切需求，这些系统无需依赖大规模训练数据集即可理解研究目标。在此，我们推出了ATOMIC（自主光学显微镜与智能表征技术），这是一个集成基础模型的端到端框架，能够实现完全自主的零样本二维材料表征。我们的系统融合了视觉基础模型（Segment Anything Model）、大型语言模型（ChatGPT）、无监督聚类和拓扑分析，通过提示工程实现了显微镜控制、样品扫描、图像分割和智能分析的全流程自动化。在分析典型MoS2样品时，我们的方法在单层识别方面达到了99.7%的分割精度，与人类专家相当。此外，该系统能够检测人眼难以识别的晶界裂纹。更重要的是，即使面对散焦、色温波动和曝光变化等复杂条件，系统依然保持了卓越的准确性。它适用于广泛的二维材料，包括石墨烯、MoS2、WSe2、SnSe，无论这些材料是通过化学气相沉积还是机械剥离制备。这项工作展示了基础模型在实现自主分析方面的潜力，开创了一种可扩展且数据高效的表征范式，彻底革新了纳米尺度材料研究的方法论。

> Characterization of atomic-scale materials traditionally requires human experts with months to years of specialized training. Even for trained human operators, accurate and reliable characterization remains challenging when examining newly discovered materials such as two-dimensional (2D) structures. This bottleneck drives demand for fully autonomous experimentation systems capable of comprehending research objectives without requiring large training datasets. In this work, we present ATOMIC (Autonomous Technology for Optical Microscopy & Intelligent Characterization), an end-to-end framework that integrates foundation models to enable fully autonomous, zero-shot characterization of 2D materials. Our system integrates the vision foundation model (i.e., Segment Anything Model), large language models (i.e., ChatGPT), unsupervised clustering, and topological analysis to automate microscope control, sample scanning, image segmentation, and intelligent analysis through prompt engineering, eliminating the need for additional training. When analyzing typical MoS2 samples, our approach achieves 99.7% segmentation accuracy for single layer identification, which is equivalent to that of human experts. In addition, the integrated model is able to detect grain boundary slits that are challenging to identify with human eyes. Furthermore, the system retains robust accuracy despite variable conditions including defocus, color temperature fluctuations, and exposure variations. It is applicable to a broad spectrum of common 2D materials-including graphene, MoS2, WSe2, SnSe-regardless of whether they were fabricated via chemical vapor deposition or mechanical exfoliation. This work represents the implementation of foundation models to achieve autonomous analysis, establishing a scalable and data-efficient characterization paradigm that fundamentally transforms the approach to nanoscale materials research.

[Arxiv](https://arxiv.org/abs/2504.10281)