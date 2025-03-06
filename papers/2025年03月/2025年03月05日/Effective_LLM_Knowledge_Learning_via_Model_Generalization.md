# 利用模型的泛化能力提升LLM知识学习效果

发布时间：2025年03月05日

`LLM理论` `人工智能`

> Effective LLM Knowledge Learning via Model Generalization

# 摘要

> 大型语言模型（LLMs）通过海量文档学习了丰富的世界知识，但目前我们对知识是如何通过自回归预训练获取的机制还知之甚少。这种理解上的不足严重阻碍了知识的有效学习，尤其是对最新信息进行持续预训练时，因为这些动态变化的信息通常缺乏像基础知识那样多样的重复。本文致力于深入理解并优化LLMs的知识学习机制。我们发现并验证了，LLMs的知识学习可以被视为隐藏在自回归预训练目标中的一个隐式监督任务。研究结果表明，针对监督任务设计的提升泛化能力的方法，同样适用于LLMs的知识学习。基于这一发现，我们提出了基于格式的数据增强方法，能够有效扩展分布内的样本，且不会像文本改写那样改变文档中的事实。同时，我们引入了感知锐度的最小化作为优化算法，以更好地提升模型的泛化能力。此外，我们的分析和方法可以轻松扩展到指令微调任务。通过大量实验结果验证，我们的方法在持续预训练和指令微调中均表现出显著有效性。本文为理解和设计有效的LLMs知识学习策略提供了全新的视角和深刻见解。

> Large language models (LLMs) are trained on enormous documents that contain extensive world knowledge. However, it is still not well-understood how knowledge is acquired via autoregressive pre-training. This lack of understanding greatly hinders effective knowledge learning, especially for continued pretraining on up-to-date information, as this evolving information often lacks diverse repetitions like foundational knowledge. In this paper, we focus on understanding and improving LLM knowledge learning. We found and verified that knowledge learning for LLMs can be deemed as an implicit supervised task hidden in the autoregressive pre-training objective. Our findings suggest that knowledge learning for LLMs would benefit from methods designed to improve generalization ability for supervised tasks. Based on our analysis, we propose the formatting-based data augmentation to grow in-distribution samples, which does not present the risk of altering the facts embedded in documents as text paraphrasing. We also introduce sharpness-aware minimization as an effective optimization algorithm to better improve generalization. Moreover, our analysis and method can be readily extended to instruction tuning. Extensive experiment results validate our findings and demonstrate our methods' effectiveness in both continued pre-training and instruction tuning. This paper offers new perspectives and insights to interpret and design effective strategies for LLM knowledge learning.

[Arxiv](https://arxiv.org/abs/2503.03705)