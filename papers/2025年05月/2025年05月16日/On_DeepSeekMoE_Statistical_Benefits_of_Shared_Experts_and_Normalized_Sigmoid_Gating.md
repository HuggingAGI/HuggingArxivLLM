# # 探讨 DeepSeekMoE：共享专家机制与归一化 Sigmoid 门控的统计优势

发布时间：2025年05月16日

`LLM理论` `大型语言模型` `视觉语言建模`

> On DeepSeekMoE: Statistical Benefits of Shared Experts and Normalized Sigmoid Gating

# 摘要

> 专家混合（MoE）方法是大型语言模型架构中的关键要素，包括近期的DeepSeek模型系列。与其它MoE实现方式相比，DeepSeekMoE凭借两大独特特征脱颖而出：共享专家策略和归一化sigmoid门控机制。尽管DeepSeekMoE在DeepSeek系列模型的成功中发挥了重要作用，但目前仅有少数尝试从理论上论证共享专家策略的价值，而其归一化sigmoid门控机制仍未得到探索。为填补这一研究空白，我们从统计学视角对DeepSeekMoE的两大特征展开了全面的理论研究。通过对专家估计任务的收敛性分析，我们揭示了共享专家策略和归一化sigmoid门控在样本效率上的提升，为专家和门控结构的设计提供了有价值的见解。为通过实证验证我们的理论发现，我们在合成数据和真实世界数据集上进行了针对（视觉）语言建模任务的多项实验。最后，我们对路由器行为进行了全面的实证分析，涵盖路由器饱和度、路由器变化率以及专家利用率等多个方面。

> Mixture of experts (MoE) methods are a key component in most large language model architectures, including the recent series of DeepSeek models. Compared to other MoE implementations, DeepSeekMoE stands out because of two unique features: the deployment of a shared expert strategy and of the normalized sigmoid gating mechanism. Despite the prominent role of DeepSeekMoE in the success of the DeepSeek series of models, there have been only a few attempts to justify theoretically the value of the shared expert strategy, while its normalized sigmoid gating has remained unexplored. To bridge this gap, we undertake a comprehensive theoretical study of these two features of DeepSeekMoE from a statistical perspective. We perform a convergence analysis of the expert estimation task to highlight the gains in sample efficiency for both the shared expert strategy and the normalized sigmoid gating, offering useful insights into the design of expert and gating structures. To verify empirically our theoretical findings, we carry out several experiments on both synthetic data and real-world datasets for (vision) language modeling tasks. Finally, we conduct an extensive empirical analysis of the router behaviors, ranging from router saturation, router change rate, to expert utilization.

[Arxiv](https://arxiv.org/abs/2505.10860)