# SafeChain：具备长链式推理能力的语言模型安全性研究

发布时间：2025年02月17日

`LLM应用` `模型安全` `推理模型`

> SafeChain: Safety of Language Models with Long Chain-of-Thought Reasoning Capabilities

# 摘要

> 新兴的大型推理模型（LRMs），例如DeepSeek-R1系列模型，通过运用长链式推理（CoT）生成结构化的中间步骤，显著提升了其推理能力。然而，长链式推理本身并不能确保输出的安全性，可能引发诸如代码中引入安全漏洞或传播虚假信息等严重后果。当前针对大型语言模型（LLM）安全性的研究大多聚焦于简短的回答式输出，而忽视了LRMs特有的长链式推理输出。为了填补这一研究空白，我们开展了一项系统性的LRM安全性研究。

首先，我们开发并验证了基于人工标注的安全评估器。借助新设计的评估指标，我们对12款先进的LRMs在StrongReject与WildJailbreak数据集上的安全性进行了全面评估。研究结果显示，尽管LRMs在推理能力上取得了显著进展，但其安全性仍不容乐观。进一步，我们对推理轨迹与最终答案进行了细致入微的分析。结果发现，三种解码策略——ZeroThink、LessThink和MoreThink——能够在不增加额外训练负担的前提下提升模型安全性。然而，这些策略要么依赖受限的推理轨迹，要么导致高昂的推理成本。

为了更有效地强化LRM的安全性，我们首次提出了专为链式推理设计的安全训练数据集SafeChain。通过在两个LRM上进行微调实验，我们证实SafeChain不仅显著提升了模型的安全性，还保持了其在6项推理基准测试中的性能水平。

> Emerging large reasoning models (LRMs), such as DeepSeek-R1 models, leverage long chain-of-thought (CoT) reasoning to generate structured intermediate steps, enhancing their reasoning capabilities. However, long CoT does not inherently guarantee safe outputs, potentially leading to harmful consequences such as the introduction of security vulnerabilities in code or the spread of misinformation. Current research on large language model (LLM) safety usually focuses on short-answer responses, overlooking the long CoT style outputs of LRMs. To bridge this gap, we conduct a systematic study of LRM safety. First, we investigate safety evaluators calibrated against human annotations. Using our newly developed metrics, we thoroughly assess the safety of 12 state-of-the-art LRMs on StrongReject and WildJailbreak datasets. Our results show that LRMs are not safe compared to their reasoning advance. Further, we perform a fine-grained analysis of the reasoning trace and final answer. We find that three decoding strategies-ZeroThink, LessThink, and MoreThink-can improve model safety without additional training. However, these strategies either use constrained reasoning traces or incur high inference costs. To better strengthen LRM safety, we introduce SafeChain, the first-of-its-kind safety training dataset in CoT style. We fine-tune two LRMs with SafeChain, showing that it not only enhances model safety but also preserves performance across 6 reasoning benchmarks.

[Arxiv](https://arxiv.org/abs/2502.12025)