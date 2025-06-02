# R3-RAG：基于强化学习实现大型语言模型的逐步推理与检索能力的学习

发布时间：2025年05月26日

`RAG` `问答系统` `信息检索`

> R3-RAG: Learning Step-by-Step Reasoning and Retrieval for LLMs via Reinforcement Learning

# 摘要

> 检索增强生成（RAG）通过结合外部知识与大型语言模型（LLMs），有效提升了事实准确性并降低了幻觉风险。然而，密集检索器因参数量远不及LLMs且无法进行逐步推理，往往成为RAG系统的瓶颈。虽然基于提示的迭代式RAG尝试解决这些问题，但其仍受限于人工设计的工作流。为突破这些限制，我们提出了$	extbf{R3-RAG}$，该方法借助$	extbf{R}$强化学习，使LLM掌握逐步推理和检索的技巧，从而全面获取外部知识并得出正确答案。R3-RAG分为两个阶段：首先通过冷启动让模型学习迭代式交替推理与检索的模式；随后运用强化学习进一步提升其探索外部检索环境的能力。具体而言，我们为R3-RAG设计了两种奖励机制：1）答案正确性作为结果奖励，判断推理轨迹是否导向正确答案；2）基于相关性的文档验证作为过程奖励，鼓励模型检索与用户问题相关的文档。通过这种方式，模型得以学习如何迭代式推理并检索相关文档，最终获得正确答案。实验结果表明，R3-RAG显著优于现有基线模型，并且能够很好地适应不同检索器。我们已在GitHub（https://github.com/Yuan-Li-FNLP/R3-RAG）发布了R3-RAG的代码和资源。

> Retrieval-Augmented Generation (RAG) integrates external knowledge with Large Language Models (LLMs) to enhance factual correctness and mitigate hallucination. However, dense retrievers often become the bottleneck of RAG systems due to their limited parameters compared to LLMs and their inability to perform step-by-step reasoning. While prompt-based iterative RAG attempts to address these limitations, it is constrained by human-designed workflows. To address these limitations, we propose $\textbf{R3-RAG}$, which uses $\textbf{R}$einforcement learning to make the LLM learn how to $\textbf{R}$eason and $\textbf{R}$etrieve step by step, thus retrieving comprehensive external knowledge and leading to correct answers. R3-RAG is divided into two stages. We first use cold start to make the model learn the manner of iteratively interleaving reasoning and retrieval. Then we use reinforcement learning to further harness its ability to better explore the external retrieval environment. Specifically, we propose two rewards for R3-RAG: 1) answer correctness for outcome reward, which judges whether the trajectory leads to a correct answer; 2) relevance-based document verification for process reward, encouraging the model to retrieve documents that are relevant to the user question, through which we can let the model learn how to iteratively reason and retrieve relevant documents to get the correct answer. Experimental results show that R3-RAG significantly outperforms baselines and can transfer well to different retrievers. We release R3-RAG at https://github.com/Yuan-Li-FNLP/R3-RAG.

[Arxiv](https://arxiv.org/abs/2505.23794)