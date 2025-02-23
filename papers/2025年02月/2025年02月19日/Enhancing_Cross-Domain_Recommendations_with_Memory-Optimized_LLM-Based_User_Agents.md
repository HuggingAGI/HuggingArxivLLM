# 利用内存优化设计的LLM用户代理，提升跨领域推荐效果

发布时间：2025年02月19日

`LLM应用` `推荐系统` `电子商务`

> Enhancing Cross-Domain Recommendations with Memory-Optimized LLM-Based User Agents

# 摘要

> 基于大型语言模型（LLM）的用户代理已成为提升推荐系统性能的强大工具，通过模拟用户交互实现更精准的推荐。然而，现有方法在跨领域场景中表现不佳，主要由于内存结构效率低下，导致不相关信息的保留以及对流行度等社会影响因素的忽视。为了解决这些问题，我们提出了AgentCF++，这是一个创新性框架，通过双层内存架构和两步融合机制，能够有效过滤特定领域的偏好。此外，我们还引入了具有共享内存的兴趣组，使模型能够捕捉流行趋势对具有相似兴趣的用户的影响。通过在多个跨领域数据集上的广泛实验，AgentCF++在基线模型中表现出色，突显了其在细化推荐系统中用户行为模拟方面的有效性。我们的代码可在https://anonymous.4open.science/r/AgentCF-plus获取。

> Large Language Model (LLM)-based user agents have emerged as a powerful tool for improving recommender systems by simulating user interactions. However, existing methods struggle with cross-domain scenarios due to inefficient memory structures, leading to irrelevant information retention and failure to account for social influence factors such as popularity. To address these limitations, we introduce AgentCF++, a novel framework featuring a dual-layer memory architecture and a two-step fusion mechanism to filter domain-specific preferences effectively. Additionally, we propose interest groups with shared memory, allowing the model to capture the impact of popularity trends on users with similar interests. Through extensive experiments on multiple cross-domain datasets, AgentCF++ demonstrates superior performance over baseline models, highlighting its effectiveness in refining user behavior simulation for recommender systems. Our code is available at https://anonymous.4open.science/r/AgentCF-plus.

[Arxiv](https://arxiv.org/abs/2502.13843)