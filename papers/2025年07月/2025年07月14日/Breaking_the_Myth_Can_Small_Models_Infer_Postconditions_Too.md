# 打破迷思：小型模型也能推断后置条件吗？

发布时间：2025年07月14日

`LLM应用` `软件工程` `规范生成`

> Breaking the Myth: Can Small Models Infer Postconditions Too?

# 摘要

> 形式化规范是确保软件正确性的基石，但手动编写它们不仅耗时，还容易出错。大型语言模型（LLMs）在从自然语言意图生成规范方面展现出潜力，但面对模型规模和计算成本的挑战，我们不禁要问：完成这一任务真的需要大型模型吗？在本文中，我们发现，经过微调的小型语言模型不仅能够生成高质量的后置条件，还能以更低的计算成本实现目标。我们构建了一个包含提示、推理日志和后置条件的专用数据集，并监督微调了一个70亿参数的代码模型。我们的方法能够处理真实世界的仓库依赖关系，并保留前置状态信息，从而生成表达丰富且准确的规范。我们在真实世界Java漏洞基准测试（Defects4J）上评估了该模型，并将其与专有巨头模型（如GPT-4o）和开源大型模型进行了对比。实证结果表明，我们的紧凑型模型在语法正确性、语义正确性和缺陷区分能力方面，与规模大得多的模型相比，能够匹敌甚至超越。这些发现表明，通过在适度规模的数据集上进行针对性微调，小型模型能够实现以往仅在资源消耗巨大的大规模LLMs中才能看到的成果，为自动化规范生成技术在现实世界的实际应用提供了切实可行且高效的解决方案。


> Formal specifications are essential for ensuring software correctness, yet manually writing them is tedious and error-prone. Large Language Models (LLMs) have shown promise in generating such specifications from natural language intents, but the giant model size and high computational demands raise a fundamental question: Do we really need large models for this task? In this paper, we show that a small, fine-tuned language model can achieve high-quality postcondition generation with much lower computational costs. We construct a specialized dataset of prompts, reasoning logs, and postconditions, then supervise the fine-tuning of a $7$B-parameter code model. Our approach tackles real-world repository dependencies and preserves pre-state information, allowing for expressive and accurate specifications. We evaluate the model on a benchmark of real-world Java bugs (Defects4J) and compare against both proprietary giants (e.g., GPT-4o) and open-source large models. Empirical results demonstrate that our compact model matches or outperforms significantly larger counterparts in syntax correctness, semantic correctness, and bug-distinguishing capability. These findings highlight that targeted fine-tuning on a modest dataset can enable small models to achieve results formerly seen only in massive, resource-heavy LLMs, offering a practical and efficient path for the real-world adoption of automated specification generation.

[Arxiv](https://arxiv.org/abs/2507.10182)