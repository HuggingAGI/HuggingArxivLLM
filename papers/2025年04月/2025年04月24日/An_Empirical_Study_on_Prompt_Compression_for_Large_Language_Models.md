# # An Empirical Study on Prompt Compression for Large Language Models
# 针对大型语言模型的提示压缩进行的经验研究

发布时间：2025年04月24日

`LLM应用` `人工智能`

> An Empirical Study on Prompt Compression for Large Language Models

# 摘要

> 提示工程让大型语言模型（LLMs）能够执行多种任务，但冗长的提示会显著增加计算复杂度和经济成本。为了解决这一问题，我们研究了六种针对LLMs的提示压缩方法，旨在在保持模型响应质量的同时减少提示长度。本文对这些方法进行了全面分析，涵盖生成性能、模型幻觉、多模态任务有效性、词汇遗漏分析等多个方面。我们在13个数据集上评估了这些方法，包括新闻、科学文章、常识问答、数学问答、长上下文问答和视觉问答数据集。实验结果显示，与短上下文相比，提示压缩对长上下文中的LLM性能影响更大。在Longbench评估中，适度的压缩甚至提升了LLM的性能。我们的代码和数据可在GitHub上获取，链接为https://github.com/3DAgentWorld/Toolkit-for-Prompt-Compression。

> Prompt engineering enables Large Language Models (LLMs) to perform a variety of tasks. However, lengthy prompts significantly increase computational complexity and economic costs. To address this issue, we study six prompt compression methods for LLMs, aiming to reduce prompt length while maintaining LLM response quality. In this paper, we present a comprehensive analysis covering aspects such as generation performance, model hallucinations, efficacy in multimodal tasks, word omission analysis, and more. We evaluate these methods across 13 datasets, including news, scientific articles, commonsense QA, math QA, long-context QA, and VQA datasets. Our experiments reveal that prompt compression has a greater impact on LLM performance in long contexts compared to short ones. In the Longbench evaluation, moderate compression even enhances LLM performance. Our code and data is available at https://github.com/3DAgentWorld/Toolkit-for-Prompt-Compression.

[Arxiv](https://arxiv.org/abs/2505.00019)