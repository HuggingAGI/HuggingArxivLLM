# 隐私保护的联邦嵌入式学习，助力本地化检索增强生成

发布时间：2025年04月27日

`RAG` `问答系统` `数据隐私`

> Privacy-Preserving Federated Embedding Learning for Localized Retrieval-Augmented Generation

# 摘要

> 检索增强生成（RAG）作为一种有前景的解决方案，最近在提升大型语言模型（LLM）的准确性和可信度方面取得了显著进展，尤其是在问答任务中。这一方法通过整合来自集成数据库的专有和私有数据实现。然而，私有RAG系统面临重大挑战，主要是由于私有领域数据的匮乏以及关键的数据隐私问题。这些障碍阻碍了私有RAG系统的部署，因为开发隐私保护的RAG系统需要在数据安全和数据可用性之间取得微妙的平衡。为了解决这些挑战，我们将联邦学习（FL）视为一种极具潜力的技术，用于实现隐私保护的RAG服务。我们提出了一种名为联邦检索增强生成（FedE4RAG）的创新框架。该框架支持客户端RAG检索模型的协作训练。模型参数在中央服务器上进行聚合和分发，确保数据隐私的同时无需直接共享原始数据。在FedE4RAG中，我们采用知识蒸馏技术实现服务器与客户端模型之间的通信。这种方法在联邦学习过程中提高了本地RAG检索器的泛化能力。此外，我们在联邦学习中应用同态加密技术，保护模型参数并缓解数据泄露相关担忧。在真实世界数据集上进行的广泛实验验证了FedE4RAG的有效性。实验结果表明，我们的框架能够显著提升私有RAG系统的性能，同时保持强大的数据隐私保护能力。

> Retrieval-Augmented Generation (RAG) has recently emerged as a promising solution for enhancing the accuracy and credibility of Large Language Models (LLMs), particularly in Question & Answer tasks. This is achieved by incorporating proprietary and private data from integrated databases. However, private RAG systems face significant challenges due to the scarcity of private domain data and critical data privacy issues. These obstacles impede the deployment of private RAG systems, as developing privacy-preserving RAG systems requires a delicate balance between data security and data availability. To address these challenges, we regard federated learning (FL) as a highly promising technology for privacy-preserving RAG services. We propose a novel framework called Federated Retrieval-Augmented Generation (FedE4RAG). This framework facilitates collaborative training of client-side RAG retrieval models. The parameters of these models are aggregated and distributed on a central-server, ensuring data privacy without direct sharing of raw data. In FedE4RAG, knowledge distillation is employed for communication between the server and client models. This technique improves the generalization of local RAG retrievers during the federated learning process. Additionally, we apply homomorphic encryption within federated learning to safeguard model parameters and mitigate concerns related to data leakage. Extensive experiments conducted on the real-world dataset have validated the effectiveness of FedE4RAG. The results demonstrate that our proposed framework can markedly enhance the performance of private RAG systems while maintaining robust data privacy protection.

[Arxiv](https://arxiv.org/abs/2504.19101)