# LR-IAD：基于逻辑推理的无遮罩工业异常检测。

发布时间：2025年04月28日

`LLM应用` `制造业` `工业检测`

> LR-IAD:Mask-Free Industrial Anomaly Detection with Logical Reasoning

# 摘要

> 工业异常检测（IAD）在保障产品质量方面发挥着关键作用，它通过识别产品缺陷来实现这一目标。然而，传统的特征嵌入和基于重建的方法存在依赖大量数据和扩展性不足的局限。现有的视觉-语言模型（VLMs）和多模态大型语言模型（MLLMs）虽然弥补了一些不足，但它们需要掩码标注，这不仅增加了实施成本，还容易导致误报。此外，工业数据集如MVTec-AD和VisA面临着严重的类别不平衡问题，缺陷样本分别仅占总数据的23.8%和11.1%。针对这些问题，我们提出了一种动态奖励函数，能够在训练过程中优先处理罕见缺陷模式，有效缓解类别不平衡问题。我们还创新性地引入了一个无掩码推理框架，结合链式思维（CoT）和组相对策略优化（GRPO）机制，实现了直接从原始图像进行异常检测，无需依赖标注掩码。该框架不仅能准确定位缺陷，还能生成清晰的分步解释说明。实验结果表明，我们的方法在MVTec-AD和VisA数据集上分别比现有方法提升了36%和16%的准确率，达到了当前最优水平。通过消除对掩码标注的依赖、降低实施成本并提供可解释的检测结果，这项研究不仅推动了工业异常检测技术的发展，还为制造业实现大规模质量控制提供了有力支持。如需复现实验，代码已开源在https://github.com/LilaKen/LR-IAD。

> Industrial Anomaly Detection (IAD) is critical for ensuring product quality by identifying defects. Traditional methods such as feature embedding and reconstruction-based approaches require large datasets and struggle with scalability. Existing vision-language models (VLMs) and Multimodal Large Language Models (MLLMs) address some limitations but rely on mask annotations, leading to high implementation costs and false positives. Additionally, industrial datasets like MVTec-AD and VisA suffer from severe class imbalance, with defect samples constituting only 23.8% and 11.1% of total data respectively. To address these challenges, we propose a reward function that dynamically prioritizes rare defect patterns during training to handle class imbalance. We also introduce a mask-free reasoning framework using Chain of Thought (CoT) and Group Relative Policy Optimization (GRPO) mechanisms, enabling anomaly detection directly from raw images without annotated masks. This approach generates interpretable step-by-step explanations for defect localization. Our method achieves state-of-the-art performance, outperforming prior approaches by 36% in accuracy on MVTec-AD and 16% on VisA. By eliminating mask dependency and reducing costs while providing explainable outputs, this work advances industrial anomaly detection and supports scalable quality control in manufacturing. Code to reproduce the experiment is available at https://github.com/LilaKen/LR-IAD.

[Arxiv](https://arxiv.org/abs/2504.19524)