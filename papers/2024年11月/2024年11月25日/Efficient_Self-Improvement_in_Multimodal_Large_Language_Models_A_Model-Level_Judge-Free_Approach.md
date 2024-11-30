# 多模态大型语言模型的高效自我改进：一种无需模型级别评判的方法

发布时间：2024年11月25日

`LLM应用` `语言模型` `多模态`

> Efficient Self-Improvement in Multimodal Large Language Models: A Model-Level Judge-Free Approach

# 摘要

> 在多模态大型语言模型（MLLMs）中进行自我改进，对于增强其可靠性和鲁棒性极为关键。然而，当下的方法往往过度依赖 MLLMs 自身充当评判者，致使计算成本高昂，还可能出现诸如奖励破解和模型崩溃之类的隐患。此文引入了一种全新的、无需模型级别评判者的自我改进框架。我们的方法运用了受控反馈机制，同时在验证环节中不再需要 MLLMs 。我们借助可控的幻觉机制生成偏好学习对，并利用轻量级的对比语言 - 图像编码器，在必要时对其进行评估和反转，以优化数据质量。在公共基准以及我们新推出的旨在挑战幻觉控制的 IC 数据集上的评估显示，我们的模型胜过传统技术。我们在大幅降低计算需求的情况下，实现了更优的精度和召回率。这种方法为 MLLMs 的可扩展自我改进提供了高效路径，在性能提升与资源需求降低之间实现了平衡。

> Self-improvement in multimodal large language models (MLLMs) is crucial for enhancing their reliability and robustness. However, current methods often rely heavily on MLLMs themselves as judges, leading to high computational costs and potential pitfalls like reward hacking and model collapse. This paper introduces a novel, model-level judge-free self-improvement framework. Our approach employs a controlled feedback mechanism while eliminating the need for MLLMs in the verification loop. We generate preference learning pairs using a controllable hallucination mechanism and optimize data quality by leveraging lightweight, contrastive language-image encoders to evaluate and reverse pairs when necessary. Evaluations across public benchmarks and our newly introduced IC dataset designed to challenge hallucination control demonstrate that our model outperforms conventional techniques. We achieve superior precision and recall with significantly lower computational demands. This method offers an efficient pathway to scalable self-improvement in MLLMs, balancing performance gains with reduced resource requirements.

[Arxiv](https://arxiv.org/abs/2411.17760)