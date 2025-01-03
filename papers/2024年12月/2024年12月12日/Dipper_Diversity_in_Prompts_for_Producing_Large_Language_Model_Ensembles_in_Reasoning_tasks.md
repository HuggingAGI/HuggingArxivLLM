# Dipper: 提示多样性助力推理任务中的大型语言模型集成

发布时间：2024年12月12日

`LLM应用

理由：这篇论文主要讨论了如何通过并行输入一组优化的、多样化的提示来提升大型语言模型（LLM）在推理任务中的性能。这种方法属于LLM在实际应用中的优化和改进，因此应归类为LLM应用。` `人工智能` `数学推理`

> Dipper: Diversity in Prompts for Producing Large Language Model Ensembles in Reasoning tasks

# 摘要

> 大型语言模型在推理任务中仍面临巨大挑战，尤其是资源受限的用户只能使用较小的模型。过去的研究表明，通过提示方法在推理时提升LLM性能是有效的，但这些方法主要依赖顺序查询。集成方法由多个并行运行的模型组成，是一种有前景的解决方案，特别是在LLM批量推理速度显著提升的背景下。我们提出了一种无需训练的LLM集成框架，通过并行输入一组优化的、多样化的提示，在推理时实现性能提升。实验证明，我们的方法在数学推理任务中表现优异，例如在MATH数据集上，几个小模型（如三个Qwen2-MATH-1.5B-it模型）的集成可以超越更大的模型（如Qwen2-MATH-7B-it）。

> Large Language Models still encounter substantial challenges in reasoning tasks, especially for smaller models, which many users may be restricted to due to resource constraints (e.g. GPU memory restrictions). Inference-time methods to boost LLM performance, such as prompting methods to invoke certain reasoning pathways in responses, have been shown effective in past works, though they largely rely on sequential queries. The ensemble method, which consists of multiple constituent models running in parallel, is a promising approach to achieving better inference-time performance, especially given recent developments that enabled significant speed-ups in LLM batch inference. In this work, we propose a novel, training-free LLM ensemble framework where a single LLM model is fed an optimized, diverse set of prompts in parallel, effectively producing an ensemble at inference time to achieve performance improvement in reasoning tasks. We empirically demonstrate that our method leads to significant gains on math reasoning tasks, e.g., on MATH, where our ensemble consisting of a few small models (e.g., three Qwen2-MATH-1.5B-it models) can outperform a larger model (e.g., Qwen2-MATH-7B-it).

[Arxiv](https://arxiv.org/abs/2412.15238)