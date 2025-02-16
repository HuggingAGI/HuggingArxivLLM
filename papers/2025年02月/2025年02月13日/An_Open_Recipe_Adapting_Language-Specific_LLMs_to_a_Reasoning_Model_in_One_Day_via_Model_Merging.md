# 一种开放方案：仅需一天，通过模型合并将语言特定的LLM适配为推理模型

发布时间：2025年02月13日

`LLM应用` `多语言模型` `语言技术`

> An Open Recipe: Adapting Language-Specific LLMs to a Reasoning Model in One Day via Model Merging

# 摘要

> 本文研究了如何将DeepSeek R1的先进推理能力整合到特定语言的大型语言模型（LLM）中，特别关注泰语LLM。我们的目标是在保持其语言能力的同时，增强其推理能力。DeepSeek R1在推理方面表现出色，但主要造福于英语和中文等高资源语言。然而，由于以英语为中心的训练数据和模型优化占据主导地位，资源匮乏的语言仍然无法获得足够的支持，导致了不可靠的语言混用以及在低资源语言任务上的效果减弱。与此同时，地方和区域的LLM计划试图通过开发专注于提升本地语言保真度的语言特定LLM来弥合这一差距。我们证明，仅使用公开可用的数据集和120美元的计算预算，就有可能在不降低目标语言任务性能的前提下，增强特定语言LLM的推理能力，使其达到DeepSeek R1的水平。

> This paper investigates data selection and model merging methodologies aimed at incorporating advanced reasoning capabilities such as those of DeepSeek R1 into language-specific large language models (LLMs), with a particular focus on the Thai LLM. Our goal is to enhance the reasoning capabilities of language-specific LLMs while maintaining their target language abilities. DeepSeek R1 excels in reasoning but primarily benefits high-resource languages such as English and Chinese. However, low-resource languages remain underserved due to the dominance of English-centric training data and model optimizations, which limit performance in these languages. This limitation results in unreliable code-switching and diminished effectiveness on tasks in low-resource languages. Meanwhile, local and regional LLM initiatives have attempted to bridge this gap by developing language-specific LLMs that focus on improving local linguistic fidelity. We demonstrate that, with only publicly available datasets and a computational budget of $120, it is possible to enhance the reasoning capabilities of language-specific LLMs to match the level of DeepSeek R1, without compromising their performance on target language tasks.

[Arxiv](https://arxiv.org/abs/2502.09056)