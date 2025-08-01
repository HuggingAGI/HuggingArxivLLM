# # DiffLoRA：专为大型语言模型设计的差分低秩适配器

发布时间：2025年07月31日

`LLM理论` `参数高效微调`

> DiffLoRA: Differential Low-Rank Adapters for Large Language Models

# 摘要

> 差分Transformer近期被提出，通过引入去噪注意力机制来消除噪声，从而提升Transformer模型的性能。在本研究中，我们提出了DiffLoRA——一种对差分注意力机制的参数高效适配方法，它在正负注意力项上均采用了低秩适配器。这种方法不仅保留了LoRA的高效性，还旨在从差分注意力带来的性能提升中获益。我们对DiffLoRA进行了全面评估，涵盖通用基准测试、多示例上下文学习、RAG和长上下文测试等多种NLP任务。结果显示，尽管DiffLoRA在大多数任务中尚未超越其他参数高效的微调方法，但在某些领域却展现了显著优势（HumanEval任务上较LoRA提升了11分）。我们进一步分析了微调后的注意力模式，以探究其独特表现背后的原因。

> Differential Transformer has recently been proposed to improve performance in Transformer models by canceling out noise through a denoiser attention mechanism. In this work, we introduce DiffLoRA, a parameter-efficient adaptation of the differential attention mechanism, with low-rank adapters on both positive and negative attention terms. This approach retains the efficiency of LoRA while aiming to benefit from the performance gains of differential attention. We evaluate DiffLoRA across a broad range of NLP tasks, including general benchmarks, many-shot in-context learning, RAG, and long-context tests. We observe that, although DiffLoRA falls short of other parameter-efficient fine-tuning methods in most evaluation tasks, it shows interesting results in certain domains (+11 pts on LoRA for HumanEval). We analyze the attention patterns post-finetuning to identify the reasons for this behavior.

[Arxiv](https://arxiv.org/abs/2507.23588)