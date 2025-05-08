# 独立于LLM的自适应RAG：让问题为自己发声

发布时间：2025年05月07日

`RAG` `问答系统`

> LLM-Independent Adaptive RAG: Let the Question Speak for Itself

# 摘要

> 大型语言模型 (LLMs) 容易出现幻觉，而检索增强生成 (RAG) 虽然有所帮助，但代价是高计算成本并存在误导信息的风险。自适应检索旨在仅在必要时进行检索，但现有方法依赖于基于 LLM 的不确定性估计，这仍然效率低下且不切实际。本研究中，我们引入了基于外部信息的轻量级 LLM 独立自适应检索方法。我们研究了 27 个特征，分为 7 组，并评估了它们的混合组合。我们在 6 个问答数据集上对这些方法进行了评估，评估了问答性能和效率。结果表明，我们的方法在性能上与复杂的 LLM 基础方法相匹配，同时实现了显著的效率提升，证明了外部信息在自适应检索中的潜力。

> Large Language Models~(LLMs) are prone to hallucinations, and Retrieval-Augmented Generation (RAG) helps mitigate this, but at a high computational cost while risking misinformation. Adaptive retrieval aims to retrieve only when necessary, but existing approaches rely on LLM-based uncertainty estimation, which remain inefficient and impractical. In this study, we introduce lightweight LLM-independent adaptive retrieval methods based on external information. We investigated 27 features, organized into 7 groups, and their hybrid combinations. We evaluated these methods on 6 QA datasets, assessing the QA performance and efficiency. The results show that our approach matches the performance of complex LLM-based methods while achieving significant efficiency gains, demonstrating the potential of external information for adaptive retrieval.

[Arxiv](https://arxiv.org/abs/2505.04253)