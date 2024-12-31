# Verbosity-Aware Rationale Reduction: 基于原则性标准有效削减冗余理由

发布时间：2024年12月30日

`LLM应用` `语言模型` `推理优化`

> Verbosity-Aware Rationale Reduction: Effective Reduction of Redundant Rationale via Principled Criteria

# 摘要

> 大型语言模型（LLMs）需生成众多中间推理单元（比如标记、句子），以提升各类复杂任务的最终答案质量。虽说生成多条推理路径或反复优化推理过程能有效提升性能，但这些方式必然会大幅增加推理成本。在本研究中，我们提出了一种创新的句子级推理简化训练框架，它借助基于可能性的标准——冗长性，来识别并去除冗余的推理句子。和以往利用标记级简化的方法不同，我们的句子级简化框架在缩短生成长度的同时保持了模型性能，保留了 LLMs 原本的推理能力，在各种模型和任务中平均降低了 17.15%的生成成本。

> Large Language Models (LLMs) rely on generating extensive intermediate reasoning units (e.g., tokens, sentences) to enhance final answer quality across a wide range of complex tasks. While generating multiple reasoning paths or iteratively refining rationales proves effective for improving performance, these approaches inevitably result in significantly higher inference costs. In this work, we propose a novel sentence-level rationale reduction training framework that leverages likelihood-based criteria, verbosity, to identify and remove redundant reasoning sentences. Unlike previous approaches that utilize token-level reduction, our sentence-level reduction framework maintains model performance while reducing generation length. This preserves the original reasoning abilities of LLMs and achieves an average 17.15% reduction in generation costs across various models and tasks.

[Arxiv](https://arxiv.org/abs/2412.21006)