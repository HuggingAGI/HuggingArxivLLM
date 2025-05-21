# MLZero：专为端到端机器学习自动化打造的多智能体系统

发布时间：2025年05月20日

`LLM应用

理由：这篇论文介绍了MLZero，一个基于大型语言模型的多智能体框架，用于实现多模态数据的端到端自动化，减少人为干预。它展示了LLM在自动化机器学习任务中的应用，特别是在多模态数据处理方面。虽然提到了一些改进方法，但核心是应用层面的创新。` `人工智能` `机器学习`

> MLZero: A Multi-Agent System for End-to-end Machine Learning Automation

# 摘要

> 尽管现有的AutoML系统推动了机器学习的自动化，但在处理多模态数据时仍需大量人工干预。我们推出MLZero——一个基于大型语言模型的全新多智能体框架，实现多种数据模态下的端到端自动化，大幅减少人为干预。MLZero通过认知感知模块将多模态输入转化为感知上下文，指导后续流程。针对LLMs的幻觉代码生成和过时API知识等问题，我们引入语义和情节记忆提升代码生成质量。在MLE-Bench Lite基准测试中，MLZero以65%的成功率远超现有方法，摘得六项桂冠。在更具挑战性的多模态AutoML代理基准测试中，MLZero的成功率高达0.92（+263.6%），平均排名2.28，大幅领先现有方法。值得注意的是，即使采用精简的8B LLM，MLZero依然保持了强大的性能表现，优于现有解决方案的完整系统。

> Existing AutoML systems have advanced the automation of machine learning (ML); however, they still require substantial manual configuration and expert input, particularly when handling multimodal data. We introduce MLZero, a novel multi-agent framework powered by Large Language Models (LLMs) that enables end-to-end ML automation across diverse data modalities with minimal human intervention. A cognitive perception module is first employed, transforming raw multimodal inputs into perceptual context that effectively guides the subsequent workflow. To address key limitations of LLMs, such as hallucinated code generation and outdated API knowledge, we enhance the iterative code generation process with semantic and episodic memory. MLZero demonstrates superior performance on MLE-Bench Lite, outperforming all competitors in both success rate and solution quality, securing six gold medals. Additionally, when evaluated on our Multimodal AutoML Agent Benchmark, which includes 25 more challenging tasks spanning diverse data modalities, MLZero outperforms the competing methods by a large margin with a success rate of 0.92 (+263.6\%) and an average rank of 2.28. Our approach maintains its robust effectiveness even with a compact 8B LLM, outperforming full-size systems from existing solutions.

[Arxiv](https://arxiv.org/abs/2505.13941)