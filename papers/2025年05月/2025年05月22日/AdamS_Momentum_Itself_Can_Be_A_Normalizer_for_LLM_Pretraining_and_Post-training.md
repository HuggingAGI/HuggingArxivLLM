# AdamS：动量本身可以作为归一化器，在LLM的预训练和微调中发挥作用。

发布时间：2025年05月22日

`LLM理论` `机器学习`

> AdamS: Momentum Itself Can Be A Normalizer for LLM Pretraining and Post-training

# 摘要

> 我们提出了一种简单而有效的Adam替代方案——AdamS，专门用于大型语言模型（LLM）的预训练和微调。通过引入一种创新的分母设计，即动量和当前梯度平方和的平方根，AdamS成功避免了对二阶矩估计的需求。因此，AdamS不仅效率出众，其内存和计算资源的使用与动量优化器（SGD with momentum）相当，同时在优化性能上更胜一筹。此外，AdamS的采用极为简便：它可以直接沿用AdamW的超参数，并且完全与模型架构无关，能够无缝融入现有工作流程，无需对优化器API或模型结构进行任何修改。AdamS的灵感源自Transformer目标函数中观察到的$(L_0, L_1)$平滑性特性，其中局部平滑性由梯度幅度决定，而这一幅度又可以通过动量幅度进行近似。我们不仅提供了严格的理论收敛性证明，还给出了实用的超参数选择指南。实证研究表明，AdamS在多种任务中表现优异，包括GPT-2和Llama2（多达130亿参数）的预训练，以及微调阶段的强化学习。凭借其高效性、简洁性和坚实的理论基础，AdamS成为现有优化器的理想替代方案。

> We introduce AdamS, a simple yet effective alternative to Adam for large language model (LLM) pretraining and post-training. By leveraging a novel denominator, i.e., the root of weighted sum of squares of the momentum and the current gradient, AdamS eliminates the need for second-moment estimates. Hence, AdamS is efficient, matching the memory and compute footprint of SGD with momentum while delivering superior optimization performance. Moreover, AdamS is easy to adopt: it can directly inherit hyperparameters of AdamW, and is entirely model-agnostic, integrating seamlessly into existing pipelines without modifications to optimizer APIs or architectures. The motivation behind AdamS stems from the observed $(L_0, L_1)$ smoothness properties in transformer objectives, where local smoothness is governed by gradient magnitudes that can be further approximated by momentum magnitudes. We establish rigorous theoretical convergence guarantees and provide practical guidelines for hyperparameter selection. Empirically, AdamS demonstrates strong performance in various tasks, including pre-training runs on GPT-2 and Llama2 (up to 13B parameters) and reinforcement learning in post-training regimes. With its efficiency, simplicity, and theoretical grounding, AdamS stands as a compelling alternative to existing optimizers.

[Arxiv](https://arxiv.org/abs/2505.16363)