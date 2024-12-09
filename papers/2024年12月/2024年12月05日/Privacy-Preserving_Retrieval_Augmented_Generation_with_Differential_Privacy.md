# 具有差分隐私的隐私保护检索增强生成

发布时间：2024年12月05日

`RAG` `数据隐私` `语言模型`

> Privacy-Preserving Retrieval Augmented Generation with Differential Privacy

# 摘要

> 随着大型语言模型（LLMs）近来取得显著进步，在其训练数据之外存在高度敏感数据的领域中利用它们的兴趣愈发浓厚。为此，检索增强生成（RAG）颇为有效——它能直接从外部知识源提供相关信息来辅助 LLMs。然而，若没有额外的隐私保护手段，RAG 的输出存在泄露外部数据源中敏感信息的风险。在本项工作中，我们在差分隐私（DP）的框架下对 RAG 展开探索，这是对数据隐私的正式保障。差分隐私下 RAG 的主要难题在于如何在适度的隐私预算内生成准确且较长的答案。我们通过提出一种算法来应对此问题，该算法仅为需要敏感信息的标记合理地分配隐私预算，而其他标记则使用非私有 LLMs。我们大量的实证评估显示，在合理的隐私预算$εpprox 10$下，我们的算法在不同模型和数据集中的表现均优于非 RAG 基线。

> With the recent remarkable advancement of large language models (LLMs), there has been a growing interest in utilizing them in the domains with highly sensitive data that lies outside their training data. For this purpose, retrieval augmented generation (RAG) is particularly effective -- it assists LLMs by directly providing relevant information from the external knowledge sources. However, without extra privacy safeguards, RAG outputs risk leaking sensitive information from the external data source. In this work, we explore RAG under differential privacy (DP), a formal guarantee of data privacy. The main challenge with differentially private RAG is how to generate long accurate answers within a moderate privacy budget. We address this by proposing an algorithm that smartly spends privacy budget only for the tokens that require the sensitive information and uses the non-private LLM for other tokens. Our extensive empirical evaluations reveal that our algorithm outperforms the non-RAG baseline under a reasonable privacy budget of $ε\approx 10$ across different models and datasets.

[Arxiv](https://arxiv.org/abs/2412.04697)