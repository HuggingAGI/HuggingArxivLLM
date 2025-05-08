# 推理能力超越模型规模：1.5B推理模型作为判别器击败13B大语言模型

发布时间：2025年04月30日

`LLM应用` `数据库` `人工智能`

> When Reasoning Beats Scale: A 1.5B Reasoning Model Outranks 13B LLMs as Discriminator

# 摘要

> 推理型大型语言模型（LLM）在提升规划框架中的候选方案评估方面展现出巨大潜力，但它们相对于传统非推理模型的相对性能仍未得到充分探索。本研究在生成器-判别器框架下，对比评估了蒸馏版15亿参数推理模型（DeepSeek-R1）与多个先进的非推理LLM在文本到SQL任务中的表现。为此，我们提出了一种从推理链（CoT）输出中提取软评分的新方法，从而实现对候选方案的精细排序。我们的核心假设是，推理模型作为判别器相较于非推理LLM更为有效。实验结果显示，尽管参数量远少于CodeLlama-7B和CodeLlama-13B，蒸馏版DeepSeek-R1-1.5B在F1值上提升了【数学公式】，判别准确度提高了【数学公式】，执行准确度也优于CodeLlama-13B。此外，我们发现推理模型的逻辑能力存在上限，仅仅增加上下文长度或计算预算无法显著提升其判别性能。最后，我们证明与非推理LLM不同，推理模型在生成任务上面临更大挑战，作为生成器的表现可能不如小型非推理模型。本研究凸显了推理模型在智能体框架中作为判别器的潜力，其价值远超作为生成器的能力，为LLM规划架构中推理模型的最佳角色定位提供了重要启示。

> Large Language Models (LLM) with reasoning capabilities offer a promising path for improving candidate evaluation in planning frameworks, but their relative performance against traditional non-reasoning models remains largely underexplored. In this study, we benchmark a distilled 1.5B parameter reasoning model (DeepSeek-R1) against several state-of-the-art non-reasoning LLMs within a generator-discriminator LLM planning framework for the text-to-SQL task. For this, we introduce a novel method for extracting soft scores from the chain-of-thought (CoT) outputs from reasoning that enables fine-grained ranking of candidates. Our central hypothesis is that reasoning models are more effective discriminators than non-reasoning LLMs. Our results show that distilled DeepSeek-R1-1.5B achieves up to $87\%$ higher F1 and $3.7\%$ better discrimination accuracy than CodeLlama-7B, as well as $3.7\%$ higher execution accuracy than CodeLlama-13B, despite having significantly fewer parameters. Furthermore, we find that there is a limit to the logical capabilities of reasoning models, and only providing more context or allowing more compute budget for reasoning is not enough to improve their discrimination performance. Finally, we demonstrate that, unlike non-reasoning LLMs, reasoning models find generation more challenging than discrimination and may underperform as generators compared to smaller non-reasoning LLMs. Our work highlights the potential of reasoning models as discriminators in agentic frameworks, far outweighing their capabilities as generators, offering insights into their optimal role within LLM planning infrastructures.

[Arxiv](https://arxiv.org/abs/2505.03786)