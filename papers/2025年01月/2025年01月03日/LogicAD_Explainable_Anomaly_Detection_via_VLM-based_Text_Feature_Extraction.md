# LogicAD: 基于VLM文本特征提取的可解释异常检测

发布时间：2025年01月03日

`LLM应用

**理由**：该论文探讨了自回归多模态视觉语言模型（AVLMs）在逻辑异常检测（AD）中的应用，并展示了其在工业检测等场景中的潜力。虽然涉及多模态模型，但其核心是应用这些模型来解决实际问题（逻辑AD），因此归类为“LLM应用”。` `工业检测` `异常检测`

> LogicAD: Explainable Anomaly Detection via VLM-based Text Feature Extraction

# 摘要

> # 逻辑图像理解
逻辑图像理解是指对图像中视觉内容的关系和一致性进行解释和推理。这种能力在工业检测等场景中尤为重要，因为逻辑异常检测是确保高质量标准和减少昂贵召回的关键。以往的异常检测（AD）研究通常依赖先验知识设计算法，需要大量手动标注、计算资源和训练数据。自回归多模态视觉语言模型（AVLMs）因其在跨领域视觉推理中的卓越表现，成为了一种有潜力的替代方案。然而，它们在逻辑AD中的应用尚未被充分探索。本研究探讨了AVLMs在逻辑AD中的应用，并证明其非常适合这一任务。通过结合格式嵌入和逻辑推理器，我们在MVTec LOCO AD基准上取得了SOTA性能，AUROC达到86.0%，F1-max为83.7%，同时提供了异常解释，显著超越了现有SOTA方法。

> Logical image understanding involves interpreting and reasoning about the relationships and consistency within an image's visual content. This capability is essential in applications such as industrial inspection, where logical anomaly detection is critical for maintaining high-quality standards and minimizing costly recalls. Previous research in anomaly detection (AD) has relied on prior knowledge for designing algorithms, which often requires extensive manual annotations, significant computing power, and large amounts of data for training. Autoregressive, multimodal Vision Language Models (AVLMs) offer a promising alternative due to their exceptional performance in visual reasoning across various domains. Despite this, their application to logical AD remains unexplored. In this work, we investigate using AVLMs for logical AD and demonstrate that they are well-suited to the task. Combining AVLMs with format embedding and a logic reasoner, we achieve SOTA performance on public benchmarks, MVTec LOCO AD, with an AUROC of 86.0% and F1-max of 83.7%, along with explanations of anomalies. This significantly outperforms the existing SOTA method by a large margin.

[Arxiv](https://arxiv.org/abs/2501.01767)