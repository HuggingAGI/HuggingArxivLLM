# # 解决特定领域数据选择中的知识冲突：以医学指令微调为例

发布时间：2025年05月28日

`LLM应用`

> Resolving Knowledge Conflicts in Domain-specific Data Selection: A Case Study on Medical Instruction-tuning

# 摘要

> 领域特定指令微调已成为提升大型语言模型（LLMs）在专业应用（如医疗问答）性能的事实上的标准。然而，由于指令微调数据集可能包含冗余或低质量数据，通常需要进行数据选择（DS）以最大化数据效率。尽管在通用领域取得了成功，但当前的DS方法在为领域特定指令微调选择所需数据时常常遇到困难。主要原因之一是它们忽视了知识冲突的影响，即LLMs预训练知识与指令数据上下文知识之间的差异，这可能损害LLMs的先验能力并导致幻觉。为此，我们提出了一种简单而有效的知识感知数据选择（KDS）框架，用于选择符合LLMs实际需求的领域特定指令微调数据。KDS的核心是利用两个知识感知指标，从上下文-记忆知识对齐和内存知识一致性两个方面定量测量知识冲突。通过过滤知识冲突较大的数据并采样高质量和多样化的数据，KDS可以有效激发LLMs的能力并实现更好的领域特定性能。以医疗领域为实验床，我们进行了广泛实验，实证证明KDS超越其他基线，并在所有LLMs中带来显著且一致的性能提升。更令人鼓舞的是，KDS有效提高了模型的泛化能力并缓解了幻觉问题。

> Domain-specific instruction-tuning has become the defacto standard for improving the performance of large language models (LLMs) in specialized applications, e.g., medical question answering. Since the instruction-tuning dataset might contain redundant or low-quality data, data selection (DS) is usually required to maximize the data efficiency. Despite the successes in the general domain, current DS methods often struggle to select the desired data for domain-specific instruction-tuning. One of the main reasons is that they neglect the impact of knowledge conflicts, i.e., the discrepancy between LLMs' pretrained knowledge and context knowledge of instruction data, which could damage LLMs' prior abilities and lead to hallucination. To this end, we propose a simple-yet-effective Knowledge-aware Data Selection (namely KDS) framework to select the domain-specific instruction-tuning data that meets LLMs' actual needs. The core of KDS is to leverage two knowledge-aware metrics for quantitatively measuring knowledge conflicts from two aspects: context-memory knowledge alignment and intra-memory knowledge consistency. By filtering the data with large knowledge conflicts and sampling the high-quality and diverse data, KDS can effectively stimulate the LLMs' abilities and achieve better domain-specific performance. Taking the medical domain as the testbed, we conduct extensive experiments and empirically prove that KDS surpasses the other baselines and brings significant and consistent performance gains among all LLMs. More encouragingly, KDS effectively improves the model generalization and alleviates the hallucination problem.

[Arxiv](https://arxiv.org/abs/2505.21958)