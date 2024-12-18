# 跨方言信息检索：在低资源和高方差语言中的信息获取

发布时间：2024年12月17日

`LLM应用` `信息检索` `语言处理`

> Cross-Dialect Information Retrieval: Information Access in Low-Resource and High-Variance Languages

# 摘要

> 大量本地及特定文化的知识（比如人物、传统、美食）唯有在方言书写的文档中方可获取。尽管跨语言信息检索（CLIR）领域已开展了广泛研究，然而跨方言检索（CDIR）领域却鲜有关注。由于训练检索模型的资源有限，加上非标准化语言的高度多变性，方言检索面临着独特挑战。我们以德语方言为例对这些挑战展开研究，并推出了首个德语方言检索数据集，名为 WikiDIR，它由从维基百科中提取的七种德语方言构成。通过 WikiDIR，我们揭示了词汇方法在应对方言中的高词汇变化时的不足。我们还进一步表明，带有多语言编码器的常用零样本跨语言迁移方法在极低资源配置下迁移效果欠佳，这就促使我们需要资源精简且针对特定方言的检索模型。最后我们证明，（文档）翻译是缩小 CDIR 中方言差距的有效途径。

> A large amount of local and culture-specific knowledge (e.g., people, traditions, food) can only be found in documents written in dialects. While there has been extensive research conducted on cross-lingual information retrieval (CLIR), the field of cross-dialect retrieval (CDIR) has received limited attention. Dialect retrieval poses unique challenges due to the limited availability of resources to train retrieval models and the high variability in non-standardized languages. We study these challenges on the example of German dialects and introduce the first German dialect retrieval dataset, dubbed WikiDIR, which consists of seven German dialects extracted from Wikipedia. Using WikiDIR, we demonstrate the weakness of lexical methods in dealing with high lexical variation in dialects. We further show that commonly used zero-shot cross-lingual transfer approach with multilingual encoders do not transfer well to extremely low-resource setups, motivating the need for resource-lean and dialect-specific retrieval models. We finally demonstrate that (document) translation is an effective way to reduce the dialect gap in CDIR.

[Arxiv](https://arxiv.org/abs/2412.12806)