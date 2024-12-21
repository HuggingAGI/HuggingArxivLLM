# Phi-4 技术报告

发布时间：2024年12月12日

`LLM应用` `语言模型` `问答系统`

> Phi-4 Technical Report

# 摘要

> 摘要：我们带来了 phi-4，这是一个具有 140 亿参数的语言模型，其训练配方重点聚焦于数据质量。和多数主要基于网络内容或代码等有机数据源进行预训练的语言模型不同，phi-4 在整个训练流程中策略性地融入了合成数据。Phi 家族的先前模型大多提炼了教师模型（特别是 GPT-4）的能力，而 phi-4 在以 STEM 为重点的问答能力上大幅超越了其教师模型，这表明我们的数据生成和后训练技术不止于提炼。尽管对 phi-3 架构的改动微乎其微，但凭借数据的优化、训练课程以及后训练方案的创新，phi-4 相对于自身规模取得了出色的性能——特别是在以推理为重点的基准测试中。

> 
Abstract:We present phi-4, a 14-billion parameter language model developed with a training recipe that is centrally focused on data quality. Unlike most language models, where pre-training is based primarily on organic data sources such as web content or code, phi-4 strategically incorporates synthetic data throughout the training process. While previous models in the Phi family largely distill the capabilities of a teacher model (specifically GPT-4), phi-4 substantially surpasses its teacher model on STEM-focused QA capabilities, giving evidence that our data-generation and post-training techniques go beyond distillation. Despite minimal changes to the phi-3 architecture, phi-4 achieves strong performance relative to its size -- especially on reasoning-focused benchmarks -- due to improved data, training curriculum, and innovations in the post-training scheme.
    

[Arxiv](https://arxiv.org/pdf/2412.08905)