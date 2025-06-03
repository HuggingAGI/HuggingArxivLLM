# GLoSS：结合语义搜索的生成式语言模型，专为序列推荐而设计

发布时间：2025年06月02日

`LLM应用

理由：这篇论文主要探讨了如何将大型语言模型（LLM）应用于推荐系统中，特别是通过结合语义检索来提升推荐的性能。论文提出了一种生成推荐框架GLoSS，并详细描述了其在亚马逊数据集上的实验结果，展示了其在推荐任务中的优势。因此，这篇论文属于LLM应用类别。` `电子商务` `推荐系统`

> GLoSS: Generative Language Models with Semantic Search for Sequential Recommendation

# 摘要

> 我们提出了一种结合大型语言模型与稠密检索的生成推荐框架——生成式低秩语义检索语言模型（Generative Low-rank language model with Semantic Search，GLoSS），用于序列推荐任务。与依赖BM25进行词汇匹配的传统方法如GPT4Rec不同，GLoSS采用了语义检索，能够检索出超越单纯词汇匹配的相关项。在查询生成方面，我们采用了经过低秩自适应（LoRA）微调的4位量化LlaMA-3模型，这使得训练和推理可以在普通硬件上高效进行。我们在三个真实的亚马逊评论数据集（Beauty、Toys和Sports）上对GLoSS进行了评估，发现它达到了目前最优的性能表现。与传统的基于ID的基准方法相比，GLoSS在各项指标上分别提升了33.3%、52.8%和15.2%的Recall@5，以及30.0%、42.6%和16.1%的NDCG@5。它还超越了基于LLM的推荐器如P5、GPT4Rec、LlamaRec和E4SRec，在Recall@5上分别提高了4.3%、22.8%和29.5%。此外，用户分群评估显示，GLoSS在亚马逊Toys和Sports数据集中的冷启动用户群体中表现尤为出色，并且在亚马逊Beauty数据集中受益于更长的用户历史记录，展现出在不同交互长度水平下的鲁棒性。

> We propose Generative Low-rank language model with Semantic Search (GLoSS), a generative recommendation framework that combines large language models with dense retrieval for sequential recommendation. Unlike prior methods such as GPT4Rec, which rely on lexical matching via BM25, GLoSS uses semantic search to retrieve relevant items beyond lexical matching. For query generation, we employ 4-bit quantized LlaMA-3 models fine-tuned with low-rank adaptation (LoRA), enabling efficient training and inference on modest hardware. We evaluate GLoSS on three real-world Amazon review datasets: Beauty, Toys, and Sports, and find that it achieves state-of-the-art performance. Compared to traditional ID-based baselines, GLoSS improves Recall@5 by 33.3%, 52.8%, and 15.2%, and NDCG@5 by 30.0%, 42.6%, and 16.1%, respectively. It also outperforms LLM-based recommenders such as P5, GPT4Rec, LlamaRec and E4SRec with Recall@5 gains of 4.3%, 22.8%, and 29.5%. Additionally, user segment evaluations show that GLoSS performs particularly well for cold-start users in the Amazon Toys and Sports datasets, and benefits from longer user histories in Amazon Beauty dataset, demonstrating robustness across different levels of interaction lengths.

[Arxiv](https://arxiv.org/abs/2506.01910)