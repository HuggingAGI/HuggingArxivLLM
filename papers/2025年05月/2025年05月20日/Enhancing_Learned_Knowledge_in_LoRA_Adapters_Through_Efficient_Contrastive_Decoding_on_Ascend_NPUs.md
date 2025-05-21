# 高效对比解码提升 LoRA 适配器中的学习知识，使用 Ascend NPUs 实现

发布时间：2025年05月20日

`LLM应用` `云计算`

> Enhancing Learned Knowledge in LoRA Adapters Through Efficient Contrastive Decoding on Ascend NPUs

# 摘要

> 华为云用户通过LoRA（低秩适配）这一高效可扩展的方法，对大型语言模型（LLMs）进行微调和定制，以满足特定应用场景的需求。然而，当使用典型解码方法（如贪婪搜索或束搜索）时，复杂推理或深度上下文理解任务常受限于基础模型的偏见或干扰。这些偏见可能导致模型生成通用或与任务无关的响应，而非充分利用LoRA的适配能力。本文提出了一种新型解码框架——对比式LoRA解码（CoLD），旨在最大化利用LoRA适配模型中的任务特定知识，从而提升下游性能。CoLD通过对比解码方式，基于LoRA适配专家模型与对应基础模型的概率分布差异，对候选令牌进行评分。这种方法优先选择与LoRA学习表示更一致的令牌，从而增强专用任务的性能。尽管有效，但CoLD的朴素实现计算开销较大，因为每个解码步骤需要在两个模型上评估多个令牌候选。为解决这一问题，我们为华为昇腾NPU开发了一种优化内核。与贪婪解码相比，CoLD实现了任务准确率最高5.54%的提升，并将端到端延迟降低了28%。这项研究为资源受限环境下的微调LLMs提供了实用且高效的解码策略，并对云和本地环境中的应用数据科学具有广泛影响。

> Huawei Cloud users leverage LoRA (Low-Rank Adaptation) as an efficient and scalable method to fine-tune and customize large language models (LLMs) for application-specific needs. However, tasks that require complex reasoning or deep contextual understanding are often hindered by biases or interference from the base model when using typical decoding methods like greedy or beam search. These biases can lead to generic or task-agnostic responses from the base model instead of leveraging the LoRA-specific adaptations. In this paper, we introduce Contrastive LoRA Decoding (CoLD), a novel decoding framework designed to maximize the use of task-specific knowledge in LoRA-adapted models, resulting in better downstream performance. CoLD uses contrastive decoding by scoring candidate tokens based on the divergence between the probability distributions of a LoRA-adapted expert model and the corresponding base model. This approach prioritizes tokens that better align with the LoRA's learned representations, enhancing performance for specialized tasks. While effective, a naive implementation of CoLD is computationally expensive because each decoding step requires evaluating multiple token candidates across both models. To address this, we developed an optimized kernel for Huawei's Ascend NPU. CoLD achieves up to a 5.54% increase in task accuracy while reducing end-to-end latency by 28% compared to greedy decoding. This work provides practical and efficient decoding strategies for fine-tuned LLMs in resource-constrained environments and has broad implications for applied data science in both cloud and on-premises settings.

[Arxiv](https://arxiv.org/abs/2505.14620)