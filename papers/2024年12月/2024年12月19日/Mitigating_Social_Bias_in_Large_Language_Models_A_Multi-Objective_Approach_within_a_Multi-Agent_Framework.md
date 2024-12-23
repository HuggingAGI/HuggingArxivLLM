# 减轻大型语言模型中的社会偏见：于多智能体框架内的多目标之法

发布时间：2024年12月19日

`Agent` `多智能体框架`

> Mitigating Social Bias in Large Language Models: A Multi-Objective Approach within a Multi-Agent Framework

# 摘要

> 自然语言处理（NLP）因大型语言模型（LLMs）的发展而取得显著进步。然而，LLMs 常产生带有社会偏见的输出。近期研究主要通过引导 LLMs 遵循道德规范来解决此问题，可这种方式却造成了难以接受的性能降低。本文在多智能体框架（MOMA）内提出一种多目标方法，用于减轻 LLMs 中的社会偏见，且不会明显损害其性能。MOMA 的核心思路是部署多个智能体对输入问题中与偏见相关的内容进行因果干预，切断这些内容与对应答案间的捷径连接。与导致性能下降的传统去偏技术不同，MOMA 在大幅减少偏见的同时，保持了下游任务的准确性。我们在两个数据集和两个模型上开展的实验显示，MOMA 在 BBQ 数据集中能将偏见分数降低多达 87.7%，性能最多仅下降 6.8%。此外，它在 StereoSet 数据集中使多目标指标 icat 显著提升多达 58.1%。代码将在 https://github.com/Cortantse/MOMA 上提供。

> Natural language processing (NLP) has seen remarkable advancements with the development of large language models (LLMs). Despite these advancements, LLMs often produce socially biased outputs. Recent studies have mainly addressed this problem by prompting LLMs to behave ethically, but this approach results in unacceptable performance degradation. In this paper, we propose a multi-objective approach within a multi-agent framework (MOMA) to mitigate social bias in LLMs without significantly compromising their performance. The key idea of MOMA involves deploying multiple agents to perform causal interventions on bias-related contents of the input questions, breaking the shortcut connection between these contents and the corresponding answers. Unlike traditional debiasing techniques leading to performance degradation, MOMA substantially reduces bias while maintaining accuracy in downstream tasks. Our experiments conducted on two datasets and two models demonstrate that MOMA reduces bias scores by up to 87.7%, with only a marginal performance degradation of up to 6.8% in the BBQ dataset. Additionally, it significantly enhances the multi-objective metric icat in the StereoSet dataset by up to 58.1%. Code will be made available at https://github.com/Cortantse/MOMA.

[Arxiv](https://arxiv.org/abs/2412.15504)