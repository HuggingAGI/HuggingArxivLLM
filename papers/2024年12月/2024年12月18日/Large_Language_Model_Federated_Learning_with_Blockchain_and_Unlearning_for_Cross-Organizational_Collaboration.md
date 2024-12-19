# 大型语言模型的联邦学习结合区块链和遗忘技术，用于跨组织协作

发布时间：2024年12月18日

`Agent` `联邦学习` `区块链`

> Large Language Model Federated Learning with Blockchain and Unlearning for Cross-Organizational Collaboration

# 摘要

> 大型语言模型（LLMs）改变了计算机理解和处理人类语言的方式，然而在不同组织中有效运用它们仍颇具难度。当组织携手改进 LLMs 时，面临着几大主要挑战。其一，组织不愿与他人分享宝贵数据。其二，组织间的竞争在合作时引发信任问题。其三，新的隐私法规定，组织在被要求时需能删除特定数据，这在多个组织从共享数据中学习的情况下尤为棘手。传统的联邦学习方法未能解决这些相互关联的挑战，特别是在参与者无法完全信任彼此或中央聚合器的情形下。为突破这些限制，我们提出了一个基于混合区块链的联邦学习框架，它独特地将公共和私有区块链架构与多智能体强化学习相结合。我们的框架借助公共区块链实现模型更新的透明共享，同时在私有链中保护敏感计算。每个组织作为智能代理运行，运用 Q 学习优化其参与策略和资源分配，从而使个人激励与集体目标相契合。值得注意的是，我们引入了基于低秩适应（LoRA）的高效遗忘机制，能够有选择地删除特定数据贡献，且不影响模型的整体性能。通过在真实世界数据集上的大量实验，我们证明了我们的框架在维持高模型性能的同时，有效地平衡了隐私保护、信任建立和法规合规。

> Large language models (LLMs) have transformed the way computers understand and process human language, but using them effectively across different organizations remains still difficult. When organizations work together to improve LLMs, they face several main challenges. First, organizations hesitate to share their valuable data with others. Second, competition between organizations creates trust problems during collaboration. Third, new privacy laws require organizations to be able to delete specific data when requested, which is especially difficult when multiple organizations are learning from shared data. Traditional federated learning approaches do not address these interconnected challenges, particularly in scenarios where participants cannot fully trust each other or the central aggregator. To overcome these limitations, we propose a hybrid blockchain-based federated learning framework that uniquely combines public and private blockchain architectures with multi-agent reinforcement learning. Our framework enables transparent sharing of model update through the public blockchain while protecting sensitive computations in private chains. Each organization operates as an intelligent agent, using Q-learning to optimize its participation strategy and resource allocation, thus aligning individual incentives with collective goals. Notably, we introduce an efficient unlearning mechanism based on Low-Rank Adaptation (LoRA) that enables selective removal of specific data contributions without compromising the model's overall performance. Through extensive experimentation on real-world datasets, we demonstrate that our framework effectively balances privacy protection, trust establishment, and regulatory compliance while maintaining high model performance.

[Arxiv](https://arxiv.org/abs/2412.13551)