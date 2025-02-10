# 对比学习增强型大型语言模型助力单体到微服务分解

发布时间：2025年02月06日

`LLM应用

摘要中提到MonoEmbed利用大型语言模型（LLMs）和表示学习技术来自动化分解单体应用，生成微服务。这表明研究重点在于应用LLMs技术解决实际问题，属于LLM的应用领域。` `软件工程` `架构设计`

> Contrastive Learning-Enhanced Large Language Models for Monolith-to-Microservice Decomposition

# 摘要

> 随着单体应用的发展，维护和改进变得日益困难，导致了扩展性和组织结构上的问题。微服务架构以其模块化、灵活性和可扩展性，为大型应用提供了适应用户增长需求的解决方案。尽管微服务架构优势明显，但迁移到微服务架构的成本高昂且复杂，尤其是分解步骤。本研究通过MonoEmbed这一基于语言模型的自动化分解方法来解决这一挑战。MonoEmbed利用先进的大型语言模型（LLMs）和表示学习技术，为单体组件生成表示向量，并通过聚类形成微服务。通过评估各种预训练模型，并应用对比学习和低秩适配（LoRA）等微调技术，MonoEmbed优化了这些表示以实现微服务划分。实验结果表明，与传统方法相比，微调后的模型显著提升了表示向量的质量。与现有分解方法的对比测试显示，MonoEmbed在为不同规模的单体应用生成连贯且均衡的微服务方面表现更优。

> As Monolithic applications evolve, they become increasingly difficult to maintain and improve, leading to scaling and organizational issues. The Microservices architecture, known for its modularity, flexibility and scalability, offers a solution for large-scale applications allowing them to adapt and meet the demand on an ever increasing user base. Despite its advantages, migrating from a monolithic to a microservices architecture is often costly and complex, with the decomposition step being a significant challenge. This research addresses this issue by introducing MonoEmbed, a Language Model based approach for automating the decomposition process. MonoEmbed leverages state-of-the-art Large Language Models (LLMs) and representation learning techniques to generate representation vectors for monolithic components, which are then clustered to form microservices. By evaluating various pre-trained models and applying fine-tuning techniques such as Contrastive Learning and Low Rank Adaptation (LoRA), MonoEmbed aims to optimize these representations for microservice partitioning. The evaluation of the fine-tuned models showcases that they were able to significantly improve the quality of the representation vectors when compared with pre-trained models and traditional representations. The proposed approach was benchmarked against existing decomposition methods, demonstrating superior performance in generating cohesive and balanced microservices for monolithic applications with varying scales.

[Arxiv](https://arxiv.org/abs/2502.04604)