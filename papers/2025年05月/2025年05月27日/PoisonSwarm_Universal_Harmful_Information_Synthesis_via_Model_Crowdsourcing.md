# # PoisonSwarm：一种通过模型众包实现的通用有害信息合成方法

发布时间：2025年05月27日

`LLM应用

理由：这篇论文探讨了如何利用大型语言模型（LLMs）生成有害数据，并提出了一种新的框架PoisonSwarm来提高生成数据的可靠性和多样性。它主要关注的是LLMs在生成特定类型数据（有害信息）中的应用，因此属于LLM应用类别。` `AI安全` `数据安全`

> PoisonSwarm: Universal Harmful Information Synthesis via Model Crowdsourcing

# 摘要

> 构建负责任且安全的AI应用，离不开有害信息数据在对抗测试和保护措施开发中的广泛应用。目前的研究主要借助大型语言模型（LLMs）合成数据，以大规模获取高质量任务数据集，从而避免繁琐且昂贵的人工标注。然而，受限于LLMs的安全对齐机制，有害数据的合成在生成可靠性和内容多样性方面仍存在挑战。针对这一问题，我们提出了一种名为PoisonSwarm的新型有害信息合成框架，通过模型众包策略，不仅生成多样化有害数据，还保持了高成功率。具体而言，我们采用反事实方式生成大量良性数据作为基础模板。随后，将每个基础模板分解为多个语义单元，通过动态模型切换实现单元级别的毒化和最终优化，从而确保合成成功。实验结果表明，PoisonSwarm在合成不同类别的有害数据方面达到了顶尖水平，同时具备高可扩展性和多样性，为相关研究提供了有力支持。

> To construct responsible and secure AI applications, harmful information data is widely utilized for adversarial testing and the development of safeguards. Existing studies mainly leverage Large Language Models (LLMs) to synthesize data to obtain high-quality task datasets at scale, thereby avoiding costly human annotation. However, limited by the safety alignment mechanisms of LLMs, the synthesis of harmful data still faces challenges in generation reliability and content diversity. In this study, we propose a novel harmful information synthesis framework, PoisonSwarm, which applies the model crowdsourcing strategy to generate diverse harmful data while maintaining a high success rate. Specifically, we generate abundant benign data as the based templates in a counterfactual manner. Subsequently, we decompose each based template into multiple semantic units and perform unit-by-unit toxification and final refinement through dynamic model switching, thus ensuring the success of synthesis. Experimental results demonstrate that PoisonSwarm achieves state-of-the-art performance in synthesizing different categories of harmful data with high scalability and diversity.

[Arxiv](https://arxiv.org/abs/2505.21184)