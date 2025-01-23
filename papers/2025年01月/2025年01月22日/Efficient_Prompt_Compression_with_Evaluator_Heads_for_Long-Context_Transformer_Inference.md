# 长上下文Transformer推理中的高效提示压缩与评估器头部

发布时间：2025年01月22日

`LLM应用

**解释**：这篇论文主要讨论了一种无需训练的高效提示压缩方法（EHPC），旨在提高大型语言模型（LLMs）在处理长上下文输入时的效率。该方法通过筛选出对推理最重要的标记来压缩提示，从而降低计算成本和提升性能。这属于对LLMs在实际应用中的优化和改进，因此归类为“LLM应用”。` `计算优化`

> Efficient Prompt Compression with Evaluator Heads for Long-Context Transformer Inference

# 摘要

> 尽管长上下文输入对LLMs的高效利用至关重要，但它也带来了计算成本上升和性能下降的问题。为此，我们提出了一种无需训练的高效提示压缩方法，能在压缩提示中保留关键信息。我们在基于Transformer的LLMs中发现了特定的注意力头——评估头，它们能筛选出长输入中对推理最重要的标记。基于此，我们开发了EHPC（基于评估头的提示压缩方法），使LLMs在预填充阶段仅通过前几层的评估头快速“浏览”输入提示，随后仅传递重要标记进行推理。EHPC在提示压缩和长上下文推理加速两大基准测试中表现卓越，显著降低了商业API调用的复杂性和成本。此外，EHPC在与基于键值缓存的加速方法对比中表现优异，展现了其在提升LLMs长上下文任务效率方面的巨大潜力。

> Although applications involving long-context inputs are crucial for the effective utilization of large language models (LLMs), they also result in increased computational costs and reduced performance. To address this challenge, we propose an efficient, training-free prompt compression method that retains key information within compressed prompts. We identify specific attention heads in transformer-based LLMs, which we designate as evaluator heads, that are capable of selecting tokens in long inputs that are most significant for inference. Building on this discovery, we develop EHPC, an Evaluator Head-based Prompt Compression method, which enables LLMs to rapidly "skim through" input prompts by leveraging only the first few layers with evaluator heads during the pre-filling stage, subsequently passing only the important tokens to the model for inference. EHPC achieves state-of-the-art results across two mainstream benchmarks: prompt compression and long-context inference acceleration. Consequently, it effectively reduces the complexity and costs associated with commercial API calls. We further demonstrate that EHPC attains competitive results compared to key-value cache-based acceleration methods, thereby highlighting its potential to enhance the efficiency of LLMs for long-context tasks.

[Arxiv](https://arxiv.org/abs/2501.12959)