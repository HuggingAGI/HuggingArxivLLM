# # FedOne：高效查询的黑盒离散提示联邦学习方法

发布时间：2025年06月17日

`LLM应用` `人工智能`

> FedOne: Query-Efficient Federated Learning for Black-box Discrete Prompt Learning

# 摘要

> 黑箱离散提示学习（Black-Box Discrete Prompt Learning，BDPL）是一种无需访问模型参数或梯度的提示微调方法，使得在云端大型语言模型（LLM）上进行提示微调成为可能。将联邦学习（federated learning）应用于BDPL，能够通过利用多源数据进一步提升提示微调的性能。然而，此前所有关于联邦黑箱提示微调的研究均忽视了云端LLM服务中与之相关的巨大查询成本。为填补这一空白，我们针对联邦黑箱提示微调背景下的查询效率进行了理论分析。研究发现，将FedAvg降级为每轮仅激活一个客户端的策略，即我们所称的	extit{FedOne}，能够在联邦黑箱提示学习中实现最优的查询效率。基于这一发现，我们提出了FedOne框架，这是一种旨在与云端LLM交互时最大化查询效率的联邦黑箱离散提示学习方法。我们对框架的各个方面进行了数值实验，结果表明查询效率有了显著提升，这与我们的理论结果一致。

> Black-Box Discrete Prompt Learning is a prompt-tuning method that optimizes discrete prompts without accessing model parameters or gradients, making the prompt tuning on a cloud-based Large Language Model (LLM) feasible. Adapting federated learning to BDPL could further enhance prompt tuning performance by leveraging data from diverse sources. However, all previous research on federated black-box prompt tuning had neglected the substantial query cost associated with the cloud-based LLM service. To address this gap, we conducted a theoretical analysis of query efficiency within the context of federated black-box prompt tuning. Our findings revealed that degrading FedAvg to activate only one client per round, a strategy we called \textit{FedOne}, enabled optimal query efficiency in federated black-box prompt learning. Building on this insight, we proposed the FedOne framework, a federated black-box discrete prompt learning method designed to maximize query efficiency when interacting with cloud-based LLMs. We conducted numerical experiments on various aspects of our framework, demonstrating a significant improvement in query efficiency, which aligns with our theoretical results.

[Arxiv](https://arxiv.org/abs/2506.14929)