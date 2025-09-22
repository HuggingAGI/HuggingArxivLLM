# 相关性与实用性：面向RAG的过程监督重写

发布时间：2025年09月19日

`RAG` `基础理论`

> Relevance to Utility: Process-Supervised Rewrite for RAG

# 摘要

> 检索增强生成系统常存在检索相关性优化与生成实用性脱节的问题：检索到的文档虽主题相关，却可能缺少生成时有效推理所需的内容。现有“桥接”模块虽尝试重写检索文本以提升生成效果，我们却发现它们无法真正捕捉文档的实用价值。为此，我们提出R2U方法，其核心创新在于通过过程监督直接优化，以最大化生成正确答案的概率。鉴于直接观察成本高昂，我们进一步提出通过扩展大型语言模型的监督信号，来近似高效的蒸馏流程，从而帮助更小的重写器模型实现更好的泛化。我们在多个开放域问答基准上对该方法进行了评估，实验结果显示，相较于强大的桥接基线模型，我们的方法性能持续提升。

> Retrieval-Augmented Generation systems often suffer from a gap between optimizing retrieval relevance and generative utility: retrieved documents may be topically relevant but still lack the content needed for effective reasoning during generation. While existing "bridge" modules attempt to rewrite the retrieved text for better generation, we show how they fail to capture true document utility. In this work, we propose R2U, with a key distinction of directly optimizing to maximize the probability of generating a correct answer through process supervision. As such direct observation is expensive, we also propose approximating an efficient distillation pipeline by scaling the supervision from LLMs, which helps the smaller rewriter model generalize better. We evaluate our method across multiple open-domain question-answering benchmarks. The empirical results demonstrate consistent improvements over strong bridging baselines.

[Arxiv](https://arxiv.org/abs/2509.15577)