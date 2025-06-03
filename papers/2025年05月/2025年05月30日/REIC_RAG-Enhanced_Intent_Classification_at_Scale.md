# REIC：基于RAG的大规模意图分类方法

发布时间：2025年05月30日

`RAG`

> REIC: RAG-Enhanced Intent Classification at Scale

# 摘要

> 精准的意图分类是客服高效路由的核心，它不仅帮助客户快速连接到最合适的客服代表，还能显著降低处理时间和运营成本。然而，随着企业产品线的不断扩展，意图分类面临着严峻的可扩展性挑战——日益增长的意图数量以及不同垂直领域分类法的差异让问题更加复杂。本文中，我们提出了REIC（检索增强生成增强意图分类）方法，它能够有效应对这些挑战。REIC利用检索增强生成（RAG）技术，动态融入相关知识，实现精准分类，而无需频繁重新训练。通过在真实世界数据集上的广泛实验，我们证明了在大规模客服场景下，REIC的表现显著优于传统的微调、零样本和少样本方法。我们的结果表明，REIC在领域内和领域外场景中均表现出色，充分展示了其在自适应和大规模意图分类系统中实现实际部署的潜力。

> Accurate intent classification is critical for efficient routing in customer service, ensuring customers are connected with the most suitable agents while reducing handling times and operational costs. However, as companies expand their product lines, intent classification faces scalability challenges due to the increasing number of intents and variations in taxonomy across different verticals. In this paper, we introduce REIC, a Retrieval-augmented generation Enhanced Intent Classification approach, which addresses these challenges effectively. REIC leverages retrieval-augmented generation (RAG) to dynamically incorporate relevant knowledge, enabling precise classification without the need for frequent retraining. Through extensive experiments on real-world datasets, we demonstrate that REIC outperforms traditional fine-tuning, zero-shot, and few-shot methods in large-scale customer service settings. Our results highlight its effectiveness in both in-domain and out-of-domain scenarios, demonstrating its potential for real-world deployment in adaptive and large-scale intent classification systems.

[Arxiv](https://arxiv.org/abs/2506.00210)