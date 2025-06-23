# 架构就是你需要的：揭示架构设计在提升LLM推荐系统性能中的关键作用

发布时间：2025年06月18日

`LLM应用` `推荐系统` `信息检索`

> Architecture is All You Need: Improving LLM Recommenders by Dropping the Text

# 摘要

> 近年来，大规模预训练语言模型（PLMs）在推荐系统中的应用引发了极大关注。研究表明，PLMs在常见基准数据集上表现出色，其优势包括灵活且可定制的提示机制、无限可推荐词汇量以及通过大规模文本语料库预训练获得的通用“世界知识”。然而，基于PLMs的推荐器在实际部署中面临挑战：模型体积庞大、计算成本高昂，且微调PLMs以提升协同信号的表现可能削弱其对世界知识的掌握和泛化能力。我们提出了一种基于LLMs架构的推荐模型，通过减少层数和维度，并用唯一表示单个内容项目的离散令牌替换典型LLM中的基于文本的子词分词，取得了显著优于传统序列推荐模型和基于PLM的推荐模型的效果。值得注意的是，我们的模型规模和计算复杂度仅为PLM基线模型的一小部分。研究结果表明，LLMs在推荐系统中的主要优势在于其架构设计，而非通过广泛预训练获得的世界知识。

> In recent years, there has been an explosion of interest in the applications of large pre-trained language models (PLMs) to recommender systems, with many studies showing strong performance of PLMs on common benchmark datasets. PLM-based recommender models benefit from flexible and customizable prompting, an unlimited vocabulary of recommendable items, and general ``world knowledge'' acquired through pre-training on massive text corpora. While PLM-based recommenders show promise in settings where data is limited, they are hard to implement in practice due to their large size and computational cost. Additionally, fine-tuning PLMs to improve performance on collaborative signals may degrade the model's capacity for world knowledge and generalizability. We propose a recommender model that uses the architecture of large language models (LLMs) while reducing layer count and dimensions and replacing the text-based subword tokenization of a typical LLM with discrete tokens that uniquely represent individual content items. We find that this simplified approach substantially outperforms both traditional sequential recommender models and PLM-based recommender models at a tiny fraction of the size and computational complexity of PLM-based models. Our results suggest that the principal benefit of LLMs in recommender systems is their architecture, rather than the world knowledge acquired during extensive pre-training.

[Arxiv](https://arxiv.org/abs/2506.15833)