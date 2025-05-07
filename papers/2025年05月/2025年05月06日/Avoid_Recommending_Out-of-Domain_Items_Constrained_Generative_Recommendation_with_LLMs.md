# 避免推荐域外项目：基于LLMs的受限生成推荐

发布时间：2025年05月06日

`LLM应用` `推荐系统` `信息检索`

> Avoid Recommending Out-of-Domain Items: Constrained Generative Recommendation with LLMs

# 摘要

> 大型语言模型（LLMs）在生成式推荐系统中展现出巨大的潜力，但如何避免推荐域外（OOD）项目仍是一个挑战。我们提出了两种方法来解决这一问题：基于检索的RecLM-ret和受约束生成的RecLM-cgen。这两种方法均可与现有LLMs无缝集成，确保推荐内容在域内。在三个推荐数据集上的实验表明，RecLM-cgen不仅在准确性上超越了RecLM-ret和现有基于LLM的推荐模型，还成功消除了域外推荐，成为更优的选择。此外，RecLM-cgen具备强大的通用能力，并且作为一个轻量级的即插即用模块，便于集成到LLMs中，为实际应用提供了重要价值。源代码已开源，地址为https://github.com/microsoft/RecAI

> Large Language Models (LLMs) have shown promise for generative recommender systems due to their transformative capabilities in user interaction. However, ensuring they do not recommend out-of-domain (OOD) items remains a challenge. We study two distinct methods to address this issue: RecLM-ret, a retrieval-based method, and RecLM-cgen, a constrained generation method. Both methods integrate seamlessly with existing LLMs to ensure in-domain recommendations. Comprehensive experiments on three recommendation datasets demonstrate that RecLM-cgen consistently outperforms RecLM-ret and existing LLM-based recommender models in accuracy while eliminating OOD recommendations, making it the preferred method for adoption. Additionally, RecLM-cgen maintains strong generalist capabilities and is a lightweight plug-and-play module for easy integration into LLMs, offering valuable practical benefits for the community. Source code is available at https://github.com/microsoft/RecAI

[Arxiv](https://arxiv.org/abs/2505.03336)