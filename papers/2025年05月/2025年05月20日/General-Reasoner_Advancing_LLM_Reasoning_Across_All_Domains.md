# 通用推理者：引领大型语言模型推理跨越全领域

发布时间：2025年05月20日

`LLM应用

摘要分析：论文探讨了如何通过强化学习提升大型语言模型的推理能力，并提出了一种新的训练范式General-Reasoner。研究涉及模型的应用和训练方法，而非基础理论，因此归类为LLM应用。` `知识密集型领域` `跨学科`

> General-Reasoner: Advancing LLM Reasoning Across All Domains

# 摘要

> 强化学习（RL）在提升大型语言模型（LLMs）推理能力方面展现出巨大潜力。Deepseek-R1-Zero提出的"Zero"强化学习方法，无需中间监督微调阶段，可直接对基础LLMs进行RL训练。尽管如此，现有LLM推理研究主要集中在数学和编程领域，受限于数据丰富性和答案验证便捷性。这限制了模型在更广泛领域的应用，因这些领域常面临多样化答案表现和数据稀缺性问题。为此，我们提出了General-Reasoner，一种全新的训练范式，旨在增强LLM在多样化领域的推理能力。我们的主要贡献包括：（1）通过网络爬虫构建了一个大规模、高质量的问题数据集，涵盖广泛学科，所有问题均具有可验证答案；（2）开发了一种基于生成模型的答案验证器，它通过链式思维和上下文感知能力，取代了传统基于规则的验证方法。我们在涵盖物理、化学、金融、电子等多个领域的12个基准数据集（如MMLU-Pro、GPQA、SuperGPQA、TheoremQA、BBEH和MATH AMC）上，全面评估了训练的模型。结果表明，General-Reasoner超越现有基线方法，在保持数学推理任务卓越有效性的同时，实现了稳健且可泛化的推理性能。

> Reinforcement learning (RL) has recently demonstrated strong potential in enhancing the reasoning capabilities of large language models (LLMs). Particularly, the "Zero" reinforcement learning introduced by Deepseek-R1-Zero, enables direct RL training of base LLMs without relying on an intermediate supervised fine-tuning stage. Despite these advancements, current works for LLM reasoning mainly focus on mathematical and coding domains, largely due to data abundance and the ease of answer verification. This limits the applicability and generalization of such models to broader domains, where questions often have diverse answer representations, and data is more scarce. In this paper, we propose General-Reasoner, a novel training paradigm designed to enhance LLM reasoning capabilities across diverse domains. Our key contributions include: (1) constructing a large-scale, high-quality dataset of questions with verifiable answers curated by web crawling, covering a wide range of disciplines; and (2) developing a generative model-based answer verifier, which replaces traditional rule-based verification with the capability of chain-of-thought and context-awareness. We train a series of models and evaluate them on a wide range of datasets covering wide domains like physics, chemistry, finance, electronics etc. Our comprehensive evaluation across these 12 benchmarks (e.g. MMLU-Pro, GPQA, SuperGPQA, TheoremQA, BBEH and MATH AMC) demonstrates that General-Reasoner outperforms existing baseline methods, achieving robust and generalizable reasoning performance while maintaining superior effectiveness in mathematical reasoning tasks.

[Arxiv](https://arxiv.org/abs/2505.14652)