# LLaVA-CMoE：探索大型视觉语言模型的持续专家混合模型

发布时间：2025年03月27日

`LLM理论

理由：这篇论文探讨了大型语言模型（LLM）中的专家混合模型（MoE）架构，提出了一种新的持续学习方法，涉及模型扩展和路由算法的改进。这些内容属于LLM的理论和架构层面，因此归类为LLM理论。` `大型语言模型` `人工智能`

> LLaVA-CMoE: Towards Continual Mixture of Experts for Large Vision-Language Models

# 摘要

> 尽管专家混合模型（MoE）在大型语言模型中被广泛认为是持续学习的有效策略，但其应用仍面临两大挑战：(1) 随任务增长，简单参数扩展会导致模型过于庞大；(2) 修改现有路由器参数会侵蚀已有知识。为此，我们提出了一种无需回放数据的持续MoE架构——LLaVA-CMoE。我们开发了基于探针的知识扩展方法（PGKE），通过探针专家评估特定层是否需要扩展，使模型能根据任务分布自适应扩展参数，显著提升扩展效率。此外，我们设计了分层路由算法——概率任务定位器（PTL），通过高层路由捕获任务间信息，底层路由专注任务内细节，确保新任务专家不会干扰现有专家。实验表明，LLaVA-CMoE在Coin基准测试中显著提升了模型性能，同时保持了合理的参数规模。

> Although applying Mixture of Experts to large language models for learning new tasks is widely regarded as an effective strategy for continuous learning, there still remain two major challenges: (1) As the number of tasks grows, simple parameter expansion strategies can lead to excessively large models. (2) Modifying the parameters of the existing router results in the erosion of previously acquired knowledge. In this paper, we present an innovative framework named LLaVA-CMoE, which is a continuous Mixture of Experts (MoE) architecture without any replay data. Specifically, we have developed a method called Probe-Guided Knowledge Extension (PGKE), which employs probe experts to assess whether additional knowledge is required for a specific layer. This approach enables the model to adaptively expand its network parameters based on task distribution, thereby significantly improving the efficiency of parameter expansion. Additionally, we introduce a hierarchical routing algorithm called Probabilistic Task Locator (PTL), where high-level routing captures inter-task information and low-level routing focuses on intra-task details, ensuring that new task experts do not interfere with existing ones. Our experiments shows that our efficient architecture has substantially improved model performance on the Coin benchmark while maintaining a reasonable parameter count.

[Arxiv](https://arxiv.org/abs/2503.21227)