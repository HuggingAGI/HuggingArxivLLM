# # 混合粒度奖励机制适配语言模型助力增强整页优化

发布时间：2025年06月10日

`LLM应用` `推荐系统`

> Enhanced Whole Page Optimization via Mixed-Grained Reward Mechanism-Adapted Language Models

# 摘要

> 优化搜索和推荐结果的展示对提升用户体验和互动至关重要。全页面优化（WPO）在这一过程中发挥着关键作用，因为它直接影响信息如何呈现给用户。尽管预训练大型语言模型（LLMs）在生成连贯且上下文相关的文本方面表现出色，但将其微调到复杂任务如WPO上仍面临挑战。具体来说，需要大量人工标注的数据来缓解幻觉现象和模型不稳定等问题，这在每天与数百万条商品互动的大规模系统中成本高昂。在这项研究中，我们利用用户反馈作为监督信号，解决了将LLMs微调到WPO任务上的难题。与手动标注的数据集不同，用户反馈往往带有噪声，精确度较低。为克服这一问题，我们提出了一种基于奖励的微调方法——PageLLM，该方法采用混合粒度奖励机制，结合了页面级和项目级奖励。页面级奖励评估整体质量和连贯性，而项目级奖励则关注关键推荐的准确性和相关性。这种双重奖励结构确保了整体展示和关键个体组件都能得到优化。我们在公共数据集和工业数据集上验证了PageLLM。在包含超过1000万用户的在线A/B测试中，PageLLM不仅超越了基线模型，还实现了0.44%的GMV增长，证明了其实际应用价值。

> Optimizing the presentation of search and recommendation results is crucial to enhancing user experience and engagement. Whole Page Optimization (WPO) plays a pivotal role in this process, as it directly influences how information is surfaced to users. While Pre-trained Large Language Models (LLMs) have demonstrated remarkable capabilities in generating coherent and contextually relevant content, fine-tuning these models for complex tasks like WPO presents challenges. Specifically, the need for extensive human-annotated data to mitigate issues such as hallucinations and model instability can be prohibitively expensive, especially in large-scale systems that interact with millions of items daily. In this work, we address the challenge of fine-tuning LLMs for WPO by using user feedback as the supervision. Unlike manually labeled datasets, user feedback is inherently noisy and less precise. To overcome this, we propose a reward-based fine-tuning approach, PageLLM, which employs a mixed-grained reward mechanism that combines page-level and item-level rewards. The page-level reward evaluates the overall quality and coherence, while the item-level reward focuses on the accuracy and relevance of key recommendations. This dual-reward structure ensures that both the holistic presentation and the critical individual components are optimized. We validate PageLLM on both public and industrial datasets. PageLLM outperforms baselines and achieves a 0.44\% GMV increase in an online A/B test with over 10 million users, demonstrating its real-world impact.

[Arxiv](https://arxiv.org/abs/2506.09084)