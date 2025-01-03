# 基于大型语言模型和去噪扩散框架的自然语言命令微结构定向设计

发布时间：2024年09月22日

`LLM应用

理由：这篇论文描述了一个集成自然语言处理（NLP）、大型语言模型（LLMs）和去噪扩散概率模型（DDPMs）的框架，用于通过自然语言命令实现微观结构设计。该框架利用预训练的LLM来增强数据生成和处理，展示了LLM在实际应用中的使用，特别是在材料科学领域的应用。因此，这篇论文应被分类为“LLM应用”。` `材料科学` `微观结构设计`

> A Large Language Model and Denoising Diffusion Framework for Targeted Design of Microstructures with Commands in Natural Language

# 摘要

> # 摘要
微观结构在材料宏观性能中扮演着关键角色，广泛应用于合金设计、MEMS设备和组织工程等领域。尽管已有计算框架能够捕捉微观结构与材料行为间的复杂关系，但领域知识和复杂算法的高门槛限制了这些工具的普及。为此，我们提出了一种集成自然语言处理（NLP）、大型语言模型（LLMs）和去噪扩散概率模型（DDPMs）的框架，通过直观的自然语言命令实现微观结构设计。该框架利用预训练LLM驱动的上下文数据增强，生成并扩展多样化的微观结构描述符数据集。重新训练的NER模型从用户输入中提取相关描述符，DDPM则生成具有目标机械性能和拓扑特征的微观结构。NLP和DDPM组件模块化设计，支持单独训练和验证，确保框架适应不同数据集和用例的灵活性。代理模型系统根据生成样本与目标属性的一致性进行筛选和排序。通过在非线性超弹性微观结构数据库上的演示，该框架为从自然语言命令出发的微观结构逆向设计提供了原型。

> Microstructure plays a critical role in determining the macroscopic properties of materials, with applications spanning alloy design, MEMS devices, and tissue engineering, among many others. Computational frameworks have been developed to capture the complex relationship between microstructure and material behavior. However, despite these advancements, the steep learning curve associated with domain-specific knowledge and complex algorithms restricts the broader application of these tools. To lower this barrier, we propose a framework that integrates Natural Language Processing (NLP), Large Language Models (LLMs), and Denoising Diffusion Probabilistic Models (DDPMs) to enable microstructure design using intuitive natural language commands. Our framework employs contextual data augmentation, driven by a pretrained LLM, to generate and expand a diverse dataset of microstructure descriptors. A retrained NER model extracts relevant microstructure descriptors from user-provided natural language inputs, which are then used by the DDPM to generate microstructures with targeted mechanical properties and topological features. The NLP and DDPM components of the framework are modular, allowing for separate training and validation, which ensures flexibility in adapting the framework to different datasets and use cases. A surrogate model system is employed to rank and filter generated samples based on their alignment with target properties. Demonstrated on a database of nonlinear hyperelastic microstructures, this framework serves as a prototype for accessible inverse design of microstructures, starting from intuitive natural language commands.

[Arxiv](https://arxiv.org/abs/2409.14473)