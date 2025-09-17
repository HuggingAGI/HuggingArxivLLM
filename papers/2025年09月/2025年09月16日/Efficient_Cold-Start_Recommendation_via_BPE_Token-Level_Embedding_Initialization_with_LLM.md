# 基于LLM的BPE令牌级嵌入初始化：高效冷启动推荐方法

发布时间：2025年09月16日

`LLM应用` `零售与电商`

> Efficient Cold-Start Recommendation via BPE Token-Level Embedding Initialization with LLM

# 摘要

> 冷启动问题一直是推荐系统的棘手难题，尤其当新用户或新物品缺乏历史交互数据时。传统方法多采用基于内容的特征或混合方案，但这些方法仅在元数据稀疏、模式简单的场景下有效。本文提出了一种高效冷启动推荐策略，其核心是在初始化阶段通过字节对编码（BPE）分词和预训练大型语言模型（LLM）嵌入，构建子词级表示。不同于传统的粗粒度句子嵌入，我们得到了与BPE词汇表对齐的细粒度令牌级向量。这些令牌嵌入可共同作为未见过实体的密集语义先验，无需用户-物品交互历史即可实现即时推荐。我们将该机制与协同过滤系统对比，并在严格冷启动假设的基准数据集上开展实验。结果显示，所提BPE-LLM方法在Recall@k、NDCG@k和命中率指标上均优于标准基线，同时保持了良好的计算性能。此外，子词感知嵌入还具有更强的泛化能力和可解释性，在多语言及稀疏输入场景下表现尤为突出。研究表明，令牌级语义初始化可作为轻量级却高效的扩展模块，应用于零样本场景下的现代推荐系统。

> The cold-start issue is the challenge when we talk about recommender systems, especially in the case when we do not have the past interaction data of new users or new items. Content-based features or hybrid solutions are common as conventional solutions, but they can only work in a sparse metadata environment with shallow patterns. In this paper, the efficient cold-start recommendation strategy is presented, which is based on the sub word-level representations by applying Byte Pair Encoding (BPE) tokenization and pre-trained Large Language Model (LLM) embedding in the initialization procedure. We obtain fine-grained token-level vectors that are aligned with the BPE vocabulary as opposed to using coarse-grained sentence embeddings. Together, these token embeddings can be used as dense semantic priors on unseen entities, making immediate recommendation performance possible without user-item interaction history. Our mechanism can be compared to collaborative filtering systems and tested over benchmark datasets with stringent cold-start assumptions. Experimental findings show that the given BPE-LLM method achieves higher Recall@k, NDCG@k, and Hit Rate measurements compared to the standard baseline and displays the same capability of sufficient computational performance. Furthermore, we demonstrate that using subword-aware embeddings yields better generalizability and is more interpretable, especially within a multilingual and sparse input setting. The practical application of token-level semantic initialization as a lightweight, but nevertheless effective extension to modern recommender systems in the zero-shot setting is indicated within this work.

[Arxiv](https://arxiv.org/abs/2509.13179)