# 基于强化学习的上下文学习演示选择

发布时间：2024年12月05日

`LLM应用` `文本分类`

> Demonstration Selection for In-Context Learning via Reinforcement Learning

# 摘要

> 演示选择的多样性对提升模型的泛化能力极为关键，因其能更广泛地涵盖各种结构和概念。然而，构建合适的演示集始终是研究的重点。本文呈现了相关性 - 多样性增强选择（RDES）这一创新手段，它借助强化学习为运用大型语言模型（LLMs）的文本分类任务优化多样的参考演示选择，在少样本提示场景中尤为适用。RDES 运用 Q 学习框架，依据所选演示中的标签分布计算多样性得分，从而动态识别出兼顾多样性和与分类目标相关性最大的演示。此方法保证了参考数据的均衡呈现，进而提高了分类准确率。通过在四个基准数据集上开展大量实验，并涉及 12 个闭源和开源的 LLMs，我们表明与十个既定基线相比，RDES 显著提升了分类准确率。另外，我们探究了在推理过程中融入思维链（CoT）推理，这进一步增强了模型的预测性能。这些结果凸显了强化学习在推动自适应演示选择方面的潜力，也加深了对分类挑战的认识。

> Diversity in demonstration selection is crucial for enhancing model generalization, as it enables a broader coverage of structures and concepts. However, constructing an appropriate set of demonstrations has remained a focal point of research. This paper presents the Relevance-Diversity Enhanced Selection (RDES), an innovative approach that leverages reinforcement learning to optimize the selection of diverse reference demonstrations for text classification tasks using Large Language Models (LLMs), especially in few-shot prompting scenarios. RDES employs a Q-learning framework to dynamically identify demonstrations that maximize both diversity and relevance to the classification objective by calculating a diversity score based on label distribution among selected demonstrations. This method ensures a balanced representation of reference data, leading to improved classification accuracy. Through extensive experiments on four benchmark datasets and involving 12 closed-source and open-source LLMs, we demonstrate that RDES significantly enhances classification accuracy compared to ten established baselines. Furthermore, we investigate the incorporation of Chain-of-Thought (CoT) reasoning in the reasoning process, which further enhances the model's predictive performance. The results underscore the potential of reinforcement learning to facilitate adaptive demonstration selection and deepen the understanding of classification challenges.

[Arxiv](https://arxiv.org/abs/2412.03966)