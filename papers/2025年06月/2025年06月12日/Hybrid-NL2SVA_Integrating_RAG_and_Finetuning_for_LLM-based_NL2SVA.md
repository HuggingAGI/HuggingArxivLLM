# # 混合 NL2SVA：融合 RAG 和微调技术，实现基于 LLM 的 NL2SVA

发布时间：2025年06月12日

`RAG` `硬件设计验证` `电子设计自动化`

> Hybrid-NL2SVA: Integrating RAG and Finetuning for LLM-based NL2SVA

# 摘要

> SystemVerilog断言（SVAs）在硬件设计验证中至关重要，但将自然语言属性描述转化为SVAs（NL2SVA）仍是一项耗时且易出错的任务。大型语言模型（LLMs）的进步为这一过程的自动化带来了希望，然而现有模型在理解领域特定语法和语义方面仍显不足。为此，我们提出了一种定制的检索增强生成（RAG）框架和一个合成微调数据集，共同提升了LLM的性能。为了进一步优化轻量级模型在NL2SVA任务中的表现，我们的微调数据集提供了基于提示的解释，引导LLMs逐步构建并发SVAs，从而实现监督微调，显著提升了语法和功能准确性。为了全面评估LLMs在NL2SVA任务中的性能，我们构建了目前最大的评估数据集，包含40个Verilog设计和229个形式验证的SVAs，每个都附有详细注释。实验结果表明，我们的定制RAG框架使功能匹配的SVAs数量比GPT-4o-mini增加了58.42%，而结合HybridRetrieval并基于我们的微调数据集进行优化的Qwen2.5-Coder-7B-Instruct比基础Qwen模型提升了59.05%。

> SystemVerilog Assertions (SVAs) are critical for verifying the correctness of hardware designs, but manually writing them from natural language property descriptions, i.e., NL2SVA, remains a labor-intensive and error-prone task. Recent advances in large language models (LLMs) offer opportunities to automate this translation. However, existing models still struggle with understanding domain-specific syntax and semantics. To enhance LLM performance in NL2SVA, we propose a customized retrieval-augmented generation (RAG) framework and a synthetic fine-tuning dataset that together improve LLM's performance. To further improve lightweight models over NL2SVA, our fine-tuning dataset provides prompt-guided explanations that teach LLMs the layer-by-layer construction process of concurrent SVAs, enabling supervised fine-tuning that greatly improves syntax and functionality accuracy. To evaluate the performance of LLMs over NL2SVA, we construct the largest evaluation dataset for NL2SVA, comprising 40 Verilog designs and 229 formally verified SVAs with detailed annotations. Experimental results show that our customized RAG framework increases the number of functionality matched SVAs by 58.42% over GPT-4o-mini, while Qwen2.5-Coder-7B-Instruct fine-tuned on our fine-tuning dataset and integrated with HybridRetrieval achieves a 59.05% over the base Qwen model.

[Arxiv](https://arxiv.org/abs/2506.21569)