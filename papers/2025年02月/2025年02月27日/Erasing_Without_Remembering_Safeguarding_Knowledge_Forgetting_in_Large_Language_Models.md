# 遗忘不存痕：大型语言模型中的知识遗忘防护

发布时间：2025年02月27日

`LLM理论` `数据安全` `隐私保护`

> Erasing Without Remembering: Safeguarding Knowledge Forgetting in Large Language Models

# 摘要

> 本文从全新视角探索机器遗忘机制，专注于大型语言模型（LLMs）的模型遗忘保护。我们发现现有方法仅能清除目标知识的精确表达，而无法彻底消除其同义表达或相关知识。为此，我们提出了首个基准测试框架UGBench，专门用于评估13种先进方法的泛化性能。UGBench发现，遗忘后的模型仍能回忆起同义表达的答案，并在中间层保留目标事实。为解决这一问题，我们提出了基于扰动的PERMU方法，显著提升了LLM遗忘保护的泛化能力。实验结果表明，PERMU在实现模型遗忘的同时，还能带来高达50.13%的提升，同时保持43.53%的强健性泛化优势。我们的代码可在https://github.com/MaybeLizzy/UGBench获取。

> In this paper, we explore machine unlearning from a novel dimension, by studying how to safeguard model unlearning in large language models (LLMs). Our goal is to prevent unlearned models from recalling any related memory of the targeted knowledge.We begin by uncovering a surprisingly simple yet overlooked fact: existing methods typically erase only the exact expressions of the targeted knowledge, leaving paraphrased or related information intact. To rigorously measure such oversights, we introduce UGBench, the first benchmark tailored for evaluating the generalisation performance across 13 state-of-the-art methods.UGBench reveals that unlearned models can still recall paraphrased answers and retain target facts in intermediate layers. To address this, we propose PERMU, a perturbation-based method that significantly enhances the generalisation capabilities for safeguarding LLM unlearning.Experiments demonstrate that PERMU delivers up to a 50.13% improvement in unlearning while maintaining a 43.53% boost in robust generalisation. Our code can be found in https://github.com/MaybeLizzy/UGBench.

[Arxiv](https://arxiv.org/abs/2502.19982)