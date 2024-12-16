# MST-R：针对检索系统和指标评估的多阶段调优

发布时间：2024年12月13日

`RAG`

> MST-R: Multi-Stage Tuning for Retrieval Systems and Metric Evaluation

# 摘要

> 监管文件充满了微妙的术语和专业的语义。FRAG 系统，即利用预训练（或冻结）组件的冻结检索增强生成器，在检索器和回答性能上都面临后续挑战。我们推出了一个借助多阶段调整（MST）策略让检索器性能适配目标领域的系统。我们的检索方法 MST-R ：（a）首先通过硬负挖掘对向量存储中使用的编码器进行微调；（b）接着使用混合检索器，通过互反秩融合将稀疏和密集检索器相结合；（c）然后仅对前 k 个检索结果进行微调来适配交叉注意力编码器。我们在为 RIRAG 挑战发布的数据集（属于 COLING 2025 年 RegNLP 研讨会的一部分）上对系统性能进行了基准测试。我们取得了显著的性能提升，在 RegNLP 挑战排行榜上名列前茅。我们还发现，一种简单的回答方式在 RePASs 指标上超过了所有基线和预训练的 Llama 模型。分析这一异常现象，我们为未来的研究提供了重要的启示。

> Regulatory documents are rich in nuanced terminology and specialized semantics. FRAG systems: Frozen retrieval-augmented generators utilizing pre-trained (or, frozen) components face consequent challenges with both retriever and answering performance. We present a system that adapts the retriever performance to the target domain using a multi-stage tuning (MST) strategy. Our retrieval approach, called MST-R (a) first fine-tunes encoders used in vector stores using hard negative mining, (b) then uses a hybrid retriever, combining sparse and dense retrievers using reciprocal rank fusion, and then (c) adapts the cross-attention encoder by fine-tuning only the top-k retrieved results. We benchmark the system performance on the dataset released for the RIRAG challenge (as part of the RegNLP workshop at COLING 2025). We achieve significant performance gains obtaining a top rank on the RegNLP challenge leaderboard. We also show that a trivial answering approach games the RePASs metric outscoring all baselines and a pre-trained Llama model. Analyzing this anomaly, we present important takeaways for future research.

[Arxiv](https://arxiv.org/abs/2412.10313)