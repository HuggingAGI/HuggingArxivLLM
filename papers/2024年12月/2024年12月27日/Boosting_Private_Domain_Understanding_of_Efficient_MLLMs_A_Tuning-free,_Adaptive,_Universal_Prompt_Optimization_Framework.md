# 增强高效 MLLMs 对私有领域的理解：一个无需调优、自适应且通用的提示优化框架

发布时间：2024年12月27日

`LLM应用` `数据隐私`

> Boosting Private Domain Understanding of Efficient MLLMs: A Tuning-free, Adaptive, Universal Prompt Optimization Framework

# 摘要

> 高效多模态大型语言模型（EMLLMs）和多模态大型语言模型（MLLMs）不同，它减小了模型规模和计算成本，常被部署在资源受限的设备上。然而，因数据隐私问题，现有的开源 EMLLMs 在预训练时很少能获取私有领域的特定数据，导致难以直接应用于特定设备领域，比如某些业务场景。为解决这一短板，本文聚焦于 EMLLMs 对私有领域的高效适配，主要在两个方面：1. 怎样降低数据需求；2. 如何避免参数微调。具体来说，我们提出了一种无需调优、自适应、通用的提示优化框架，简称为	extit{	extbf{\ourmethod{}}}，包含两个阶段：1. 预定义提示，基于强化搜索策略，生成提示优化策略树以获取优化先验；2. 提示反射，基于优化先验初始化提示，接着进行自我反思以进一步搜索和优化提示。如此一来，\ourmethod{} 巧妙地生成了处理私有领域特定数据的“理想提示”。要注意的是，我们的方法无需参数微调，仅需少量数据就能迅速适应私有数据的数据分布。在多个任务上开展的大量实验表明，我们提出的\ourmethod{} 与基线相比，在效率和性能上均有显著提升。

> Efficient multimodal large language models (EMLLMs), in contrast to multimodal large language models (MLLMs), reduce model size and computational costs and are often deployed on resource-constrained devices. However, due to data privacy concerns, existing open-source EMLLMs rarely have access to private domain-specific data during the pre-training process, making them difficult to directly apply in device-specific domains, such as certain business scenarios. To address this weakness, this paper focuses on the efficient adaptation of EMLLMs to private domains, specifically in two areas: 1) how to reduce data requirements, and 2) how to avoid parameter fine-tuning. Specifically, we propose a tun\textbf{underline{I}}ng-free, a\textbf{underline{D}}aptiv\textbf{underline{E}}, univers\textbf{underline{AL}} \textbf{underline{Prompt}} Optimization Framework, abbreviated as \textit{\textbf{\ourmethod{}}} which consists of two stages: 1) Predefined Prompt, based on the reinforcement searching strategy, generate a prompt optimization strategy tree to acquire optimization priors; 2) Prompt Reflection initializes the prompt based on optimization priors, followed by self-reflection to further search and refine the prompt. By doing so, \ourmethod{} elegantly generates the ``ideal prompts'' for processing private domain-specific data. Note that our method requires no parameter fine-tuning and only a small amount of data to quickly adapt to the data distribution of private data. Extensive experiments across multiple tasks demonstrate that our proposed \ourmethod{} significantly improves both efficiency and performance compared to baselines.

[Arxiv](https://arxiv.org/abs/2412.19684)