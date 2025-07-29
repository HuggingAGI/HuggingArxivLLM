# 利用紧凑型多模态模型高效学习产品特性

发布时间：2025年07月25日

`LLM应用`

> Efficient Learning for Product Attributes with Compact Multimodal Models

# 摘要

> 基于图像的产品属性预测在电商领域具有广泛应用价值，但视觉语言模型（VLMs）的监督微调却面临标注成本高昂的挑战。本文针对20亿至30亿参数的紧凑型VLMs，提出了一种标签高效半监督微调策略，通过直接偏好优化（DPO）充分利用未标注数据。我们从一个小型API标注数据集出发，首先采用PEFT训练低秩适配器模块。随后，我们为每个未标注样本生成多个推理-答案链，并根据自洽性将这些链划分为偏好和非偏好两类。通过DPO损失进行微调后，模型性能显著提升。实验表明，仅利用未标注数据的DPO微调方法在涵盖十二个电商垂直领域的数据集上表现优异，且模型准确性随未标注数据量增加而提升，证明了未标注数据的巨大潜力。我们的方法结合PEFT与DPO，实现了高效收敛，计算开销极小，为VLMs在电商领域的应用提供了新的思路。

> Image-based product attribute prediction in e-commerce is a crucial task with numerous applications. The supervised fine-tuning of Vision Language Models (VLMs) faces significant scale challenges due to the cost of manual or API based annotation. In this paper, we investigate label-efficient semi-supervised fine-tuning strategies for compact VLMs (2B-3B parameters) that leverage unlabeled product listings through Direct Preference Optimization (DPO). Beginning with a small, API-based, annotated, and labeled set, we first employ PEFT to train low-rank adapter modules. To update the adapter weights with unlabeled data, we generate multiple reasoning-and-answer chains per unlabeled sample and segregate these chains into preferred and dispreferred based on self-consistency. We then fine-tune the model with DPO loss and use the updated model for the next iteration. By using PEFT fine-tuning with DPO, our method achieves efficient convergence with minimal compute overhead. On a dataset spanning twelve e-commerce verticals, DPO-based fine-tuning, which utilizes only unlabeled data, demonstrates a significant improvement over the supervised model. Moreover, experiments demonstrate that accuracy with DPO training improves with more unlabeled data, indicating that a large pool of unlabeled samples can be effectively leveraged to improve performance.

[Arxiv](https://arxiv.org/abs/2507.19679)