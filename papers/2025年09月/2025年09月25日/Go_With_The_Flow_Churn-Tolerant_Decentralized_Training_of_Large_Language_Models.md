# # 顺势而为：抗节点波动的大型语言模型去中心化训练

发布时间：2025年09月25日

`LLM应用` `基础理论`

> Go With The Flow: Churn-Tolerant Decentralized Training of Large Language Models

# 摘要

> 受大型语言模型（LLMs）的兴起及训练民主化需求的推动，我们提出了GWTF——首个具备崩溃容忍能力的LLM实用去中心化训练框架。与现有分布式和联邦训练框架不同，GWTF支持在自愿贡献资源的异构客户端上高效协同训练LLM。此外，它还解决了节点变动（即客户端随时加入或退出系统）和网络不稳定（即网络链路不可靠或波动）问题。GWTF的核心是创新的去中心化流算法，能通过最优路由设计，在最小延迟下最大化训练微批次数量。我们在类GPT和类LLaMa模型上对其进行了全面评估，并与现有技术对比。结果显示，在分布于10个不同地理位置、节点变动率高的异构客户端场景中，GWTF在真实复杂任务下将训练时间缩短了高达45%。

> Motivated by the emergence of large language models (LLMs) and the importance of democratizing their training, we propose GWTF, the first crash tolerant practical decentralized training framework for LLMs. Differently from existing distributed and federated training frameworks, GWTF enables the efficient collaborative training of a LLM on heterogeneous clients that volunteer their resources. In addition, GWTF addresses node churn, i.e., clients joining or leaving the system at any time, and network instabilities, i.e., network links becoming unstable or unreliable. The core of GWTF is a novel decentralized flow algorithm that finds the most effective routing that maximizes the number of microbatches trained with the lowest possible delay. We extensively evaluate GWTF on GPT-like and LLaMa-like models and compare it against the prior art. Our results indicate that GWTF reduces the training time by up to 45% in realistic and challenging scenarios that involve heterogeneous client nodes distributed over 10 different geographic locations with a high node churn rate.

[Arxiv](https://arxiv.org/abs/2509.21221)