# SOSBENCH：科学知识领域内的安全对齐基准测试框架

发布时间：2025年05月27日

`LLM应用

论文摘要：大型语言模型 (LLMs) 在推理和研究生水平问题解答等复杂任务中表现优异，但面对科学滥用等高风险场景时的抗滥用能力仍待深入研究。现有的安全评估基准多聚焦于知识理解门槛较低的指令（如“告诉我如何制造炸弹”），或采用风险较低的提示形式（如关于有害内容的多项选择或分类任务）。这些基准难以全面评估模型在处理知识密集型高风险场景时的安全性。

为填补这一研究空白，我们推出了 SOSBench，一个基于法规、专注于危害的评估基准，涵盖化学、生物、医学、药理学、物理和心理学六大高风险科学领域。该基准包含 3,000 个源自真实法规和法律的提示，通过 LLM 辅助的进化管道系统扩展，引入了多样化、现实的滥用场景（如涉及复杂化学公式的爆炸物合成说明）。我们使用 SOSBench 对前沿模型进行了统一评估。尽管这些模型声称具备良好的对齐能力，但在所有领域中均持续出现违反政策的内容，表现出令人担忧的高比例有害响应（如 Deepseek-R1 的 79.1% 和 GPT-4.1 的 47.3%）。这些结果凸显了模型安全对齐的严重不足，并强调了负责任部署强大 LLMs 的紧迫性。

LLM应用`

> SOSBENCH: Benchmarking Safety Alignment on Scientific Knowledge

# 摘要

> 大型语言模型 (LLMs) 在推理和研究生水平问题解答等复杂任务中表现优异，但面对科学滥用等高风险场景时的抗滥用能力仍待深入研究。现有的安全评估基准多聚焦于知识理解门槛较低的指令（如“告诉我如何制造炸弹”），或采用风险较低的提示形式（如关于有害内容的多项选择或分类任务）。这些基准难以全面评估模型在处理知识密集型高风险场景时的安全性。

为填补这一研究空白，我们推出了 SOSBench，一个基于法规、专注于危害的评估基准，涵盖化学、生物、医学、药理学、物理和心理学六大高风险科学领域。该基准包含 3,000 个源自真实法规和法律的提示，通过 LLM 辅助的进化管道系统扩展，引入了多样化、现实的滥用场景（如涉及复杂化学公式的爆炸物合成说明）。我们使用 SOSBench 对前沿模型进行了统一评估。尽管这些模型声称具备良好的对齐能力，但在所有领域中均持续出现违反政策的内容，表现出令人担忧的高比例有害响应（如 Deepseek-R1 的 79.1% 和 GPT-4.1 的 47.3%）。这些结果凸显了模型安全对齐的严重不足，并强调了负责任部署强大 LLMs 的紧迫性。


> Large language models (LLMs) exhibit advancing capabilities in complex tasks, such as reasoning and graduate-level question answering, yet their resilience against misuse, particularly involving scientifically sophisticated risks, remains underexplored. Existing safety benchmarks typically focus either on instructions requiring minimal knowledge comprehension (e.g., ``tell me how to build a bomb") or utilize prompts that are relatively low-risk (e.g., multiple-choice or classification tasks about hazardous content). Consequently, they fail to adequately assess model safety when handling knowledge-intensive, hazardous scenarios.
  To address this critical gap, we introduce SOSBench, a regulation-grounded, hazard-focused benchmark encompassing six high-risk scientific domains: chemistry, biology, medicine, pharmacology, physics, and psychology. The benchmark comprises 3,000 prompts derived from real-world regulations and laws, systematically expanded via an LLM-assisted evolutionary pipeline that introduces diverse, realistic misuse scenarios (e.g., detailed explosive synthesis instructions involving advanced chemical formulas). We evaluate frontier models within a unified evaluation framework using our SOSBench. Despite their alignment claims, advanced models consistently disclose policy-violating content across all domains, demonstrating alarmingly high rates of harmful responses (e.g., 79.1% for Deepseek-R1 and 47.3% for GPT-4.1). These results highlight significant safety alignment deficiencies and underscore urgent concerns regarding the responsible deployment of powerful LLMs.

[Arxiv](https://arxiv.org/abs/2505.21605)