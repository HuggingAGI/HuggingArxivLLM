# 结构化推理助力大型语言模型能力提升

发布时间：2025年06月25日

`LLM理论` `自动决策`

> Enhancing Large Language Models through Structured Reasoning

# 摘要

> 近年来，大型语言模型（LLMs）在自然语言处理和自动决策方面取得了显著进展。然而，这些模型在处理涉及逻辑推理和系统规划的复杂任务时仍面临挑战，这主要源于它们依赖于隐式的统计关联，而缺乏结构化的知识表示。受认知科学和神经符号人工智能的启发，我们提出了一种通过显式结构化推理增强LLMs的新方法。首先，我们将非结构化数据通过显式标注推理步骤转化为结构化格式。随后，我们利用这个结构化数据集通过监督微调（SFT）对LLMs进行训练。此外，我们还通过组相对策略优化（GRPO）增强了LLMs的结构化推理能力，引入了两种创新算法——最大流（MAX-Flow）和最长公共子序列（LCS），这些算法显著提升了推理效果并降低了计算复杂度。通过对DeepSeek-R1-Distill-Qwen-1.5B模型进行微调的实验结果表明，该方法实现了简洁的推理能力，在各种场景下表现稳健，并且与优化技术的兼容性得到了提升，验证了结构化推理在LLMs中的有效性。

> Recent Large Language Models (LLMs) have significantly advanced natural language processing and automated decision-making. However, these models still encounter difficulties when performing complex reasoning tasks involving logical deduction and systematic planning, primarily due to their reliance on implicit statistical relationships without structured knowledge representation.Inspired by cognitive science and neurosymbolic AI, we introduce a novel approach to enhance LLMs through explicit structured reasoning. First, we convert unstructured data into structured formats by explicitly annotating reasoning steps. We then employ this structured dataset to train LLMs through Supervised Fine-Tuning (SFT). Additionally, we enhance the structured reasoning capabilities of LLMs using Group Relative Policy Optimization (GRPO), incorporating two innovative algorithms--MAX-Flow and Longest Common Subsequence (LCS)--which notably improve reasoning effectiveness and reduce computational complexity. Experimental results from fine-tuning a DeepSeek-R1-Distill-Qwen-1.5B model demonstrate concise reasoning, robust performance across various scenarios, and improved compatibility with optimization techniques, validating the efficacy of structured reasoning integration in LLMs.

[Arxiv](https://arxiv.org/abs/2506.20241)