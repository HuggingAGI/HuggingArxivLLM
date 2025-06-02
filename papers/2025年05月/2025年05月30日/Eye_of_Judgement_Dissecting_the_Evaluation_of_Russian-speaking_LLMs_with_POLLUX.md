# # 判断之眼：借助POLLUX剖析俄语大型语言模型的评估

发布时间：2025年05月30日

`LLM应用

理由：这篇论文介绍了一个用于评估大型语言模型（LLMs）在俄语中生成能力的开源基准测试工具POLLUX。它专注于评估方法的创新，提供了一种更可解释和透明的评估方式，并且涵盖了多种生成任务类型。这些内容属于LLM的应用层面，因为它关注如何使用和优化LLMs，而不是其理论基础。` `模型评估`

> Eye of Judgement: Dissecting the Evaluation of Russian-speaking LLMs with POLLUX

# 摘要

> 我们很高兴推出 POLLUX，一个全面的开源基准测试工具，专为评估大型语言模型（LLMs）在俄语中的生成能力而设计。其核心创新在于一种全新的评估方法，显著提升了LLM评估的可解释性。针对每种任务类型，我们制定了详尽的评估标准，并设计了一套评分协议，让模型不仅能评估回答，还能为评分提供理由。这种创新方法实现了透明、基于标准的评估，超越了传统资源密集型的人工逐一比较。POLLUX 包含一个细致的任务类型分类系统，涵盖了35种不同的生成领域，包括代码生成、创意写作以及实用助手型应用场景，总计2,100个由人工精心设计并经专业撰写提示。每项任务按难度（简单/中等/困难）分类，且所有数据集均由专家从零开始构建。此外，我们还发布了LLM-as-a-Judge（7B和32B）评估器系列，这些模型经过训练，能够对生成输出进行细致入微的评估。这种方法为模型开发提供了可扩展、可解释的评估和标注工具，有效地取代了成本高昂且精度较低的人工判断，为LLM的开发和优化提供了强大支持。

> We introduce POLLUX, a comprehensive open-source benchmark designed to evaluate the generative capabilities of large language models (LLMs) in Russian. Our main contribution is a novel evaluation methodology that enhances the interpretability of LLM assessment. For each task type, we define a set of detailed criteria and develop a scoring protocol where models evaluate responses and provide justifications for their ratings. This enables transparent, criteria-driven evaluation beyond traditional resource-consuming, side-by-side human comparisons. POLLUX includes a detailed, fine-grained taxonomy of 35 task types covering diverse generative domains such as code generation, creative writing, and practical assistant use cases, totaling 2,100 manually crafted and professionally authored prompts. Each task is categorized by difficulty (easy/medium/hard), with experts constructing the dataset entirely from scratch. We also release a family of LLM-as-a-Judge (7B and 32B) evaluators trained for nuanced assessment of generative outputs. This approach provides scalable, interpretable evaluation and annotation tools for model development, effectively replacing costly and less precise human judgments.

[Arxiv](https://arxiv.org/abs/2505.24616)