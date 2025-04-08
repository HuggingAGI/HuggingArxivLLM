# 通用项目分词方法助力可迁移的生成推荐系统

发布时间：2025年04月06日

`LLM应用` `推荐系统`

> Universal Item Tokenization for Transferable Generative Recommendation

# 摘要

> 最近，生成推荐作为一种有前途的范式，吸引了大量的研究关注。其基本框架包括一个物品编码器，它将每个物品表示为一组作为其标识符的代码序列，以及一个生成推荐器，通过自回归生成目标物品标识符来预测下一个物品。然而，在现有方法中，编码器和推荐器通常是特定于某个领域的，这限制了它们在不同领域之间有效转移或适应的能力。为此，我们提出了UTGRec，一种用于可迁移生成推荐的通用物品编码方法。具体来说，我们设计了一个通用的物品编码器，通过适应多模态大型语言模型（MLLM）来编码丰富的物品语义。通过设计树形结构代码本，我们将内容表示离散化为相应的代码，以实现物品编码。为了在多个领域上有效学习通用物品编码器，我们在方法中引入了两种关键技术。对于原始内容的重建，我们采用了双轻量级解码器，从离散表示中重建物品文本和图像，以捕捉内容中嵌入的通用知识。对于协作知识的整合，我们假设共现的物品是相似的，并通过共现对齐和重建来整合协作信号。最后，我们提出了一种联合学习框架，用于跨多个领域的可迁移生成推荐器的预训练和适应。在四个公共数据集上的广泛实验表明，UTGRec相较于传统和生成推荐的基线方法具有优越性。

> Recently, generative recommendation has emerged as a promising paradigm, attracting significant research attention. The basic framework involves an item tokenizer, which represents each item as a sequence of codes serving as its identifier, and a generative recommender that predicts the next item by autoregressively generating the target item identifier. However, in existing methods, both the tokenizer and the recommender are typically domain-specific, limiting their ability for effective transfer or adaptation to new domains. To this end, we propose UTGRec, a Universal item Tokenization approach for transferable Generative Recommendation. Specifically, we design a universal item tokenizer for encoding rich item semantics by adapting a multimodal large language model (MLLM). By devising tree-structured codebooks, we discretize content representations into corresponding codes for item tokenization. To effectively learn the universal item tokenizer on multiple domains, we introduce two key techniques in our approach. For raw content reconstruction, we employ dual lightweight decoders to reconstruct item text and images from discrete representations to capture general knowledge embedded in the content. For collaborative knowledge integration, we assume that co-occurring items are similar and integrate collaborative signals through co-occurrence alignment and reconstruction. Finally, we present a joint learning framework to pre-train and adapt the transferable generative recommender across multiple domains. Extensive experiments on four public datasets demonstrate the superiority of UTGRec compared to both traditional and generative recommendation baselines.

[Arxiv](https://arxiv.org/abs/2504.04405)