# # 直接检索增强优化：融合知识选择与语言模型

发布时间：2025年05月05日

`RAG` `问答系统` `信息检索`

> Direct Retrieval-augmented Optimization: Synergizing Knowledge Selection and Language Models

# 摘要

> 检索增强生成（RAG）通过结合大型语言模型（LLMs）与检索器，赋予模型访问外部知识的能力，从而在知识导向的任务中显著提升了生成内容的事实准确性。尽管如此，现有方法在优化 RAG 性能时仍存在明显局限：早期研究或通过微调检索器以适配固定 LLM，或训练 LLM 使用现成检索器获取的文档，但这些方法均缺乏端到端的训练监督。近期研究虽尝试同时优化这两个组件，但其假设文档间完全独立的简化条件受到质疑，被认为难以贴近实际应用场景。因此，如何有效提升整体 RAG 性能仍是亟待解决的关键问题。
    
    为应对这一挑战，我们提出了一种名为 DRO 的直接检索增强优化框架，实现了生成式知识选择模型与 LLM 生成器的端到端联合优化。DRO 通过变分方法在两个阶段之间交替优化：(i) 文档排列估计和 (ii) 重新加权最大化，逐步提升 RAG 组件的性能。在估计阶段，我们将文档排列视为潜在变量，并通过重要性采样策略直接从选择模型中估计其分布。在最大化阶段，我们利用重要性权重校准优化期望，并同时训练选择模型和 LLM 生成器。理论分析表明，DRO 与强化学习中的策略梯度方法具有相似性。在五个数据集上进行的广泛实验表明，与最佳基线相比，DRO 在 EM 和 F1 指标上提升了 5%-15%。我们还提供了深入的实验分析，从定性角度探讨了 DRO 的稳定性、收敛性和方差。

> Retrieval-augmented generation (RAG) integrates large language models ( LLM s) with retrievers to access external knowledge, improving the factuality of LLM generation in knowledge-grounded tasks. To optimize the RAG performance, most previous work independently fine-tunes the retriever to adapt to frozen LLM s or trains the LLMs to use documents retrieved by off-the-shelf retrievers, lacking end-to-end training supervision. Recent work addresses this limitation by jointly training these two components but relies on overly simplifying assumptions of document independence, which has been criticized for being far from real-world scenarios. Thus, effectively optimizing the overall RAG performance remains a critical challenge.
  We propose a direct retrieval-augmented optimization framework, named DRO, that enables end-to-end training of two key components: (i) a generative knowledge selection model and (ii) an LLM generator. DRO alternates between two phases: (i) document permutation estimation and (ii) re-weighted maximization, progressively improving RAG components through a variational approach. In the estimation step, we treat document permutation as a latent variable and directly estimate its distribution from the selection model by applying an importance sampling strategy. In the maximization step, we calibrate the optimization expectation using importance weights and jointly train the selection model and LLM generator. Our theoretical analysis reveals that DRO is analogous to policy-gradient methods in reinforcement learning. Extensive experiments conducted on five datasets illustrate that DRO outperforms the best baseline with 5%-15% improvements in EM and F1. We also provide in-depth experiments to qualitatively analyze the stability, convergence, and variance of DRO.

[Arxiv](https://arxiv.org/abs/2505.03075)