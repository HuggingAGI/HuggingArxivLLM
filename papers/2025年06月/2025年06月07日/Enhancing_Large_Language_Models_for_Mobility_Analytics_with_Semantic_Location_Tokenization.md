# 增强大型语言模型的移动分析能力：基于语义位置分词的方法

发布时间：2025年06月07日

`LLM应用` `位置分析`

> Enhancing Large Language Models for Mobility Analytics with Semantic Location Tokenization

# 摘要

> 基于位置的服务广泛应用，产生了海量移动数据，为建模城市环境中的用户移动动态提供了重要机遇。近期研究集中于将大型语言模型（LLMs）应用于移动分析。然而，现有方法存在两大主要限制：位置语义表示不足（即离散ID）和LLMs中对移动信号建模不够（即单模板指令微调）。为解决这些问题，我们提出了QT-Mob，一个显著提升LLMs移动分析能力的新型框架。QT-Mob引入了位置分词模块，学习紧凑且语义丰富的分词来表示位置，既保留上下文信息，又确保与LLMs的兼容性。此外，QT-Mob还集成了多个互补的微调目标，使学习到的分词与LLMs的内部表示对齐，从而提升模型对序列移动模式和位置语义的理解能力。QT-Mob框架不仅增强了LLMs解读移动数据的能力，还为各种移动分析任务提供了一个更具通用性的方法。在三个真实世界数据集上的实验结果展示了在下一位置预测和移动恢复任务中的优越性能，超越了现有的深度学习和基于LLMs的方法。

> The widespread adoption of location-based services has led to the generation of vast amounts of mobility data, providing significant opportunities to model user movement dynamics within urban environments. Recent advancements have focused on adapting Large Language Models (LLMs) for mobility analytics. However, existing methods face two primary limitations: inadequate semantic representation of locations (i.e., discrete IDs) and insufficient modeling of mobility signals within LLMs (i.e., single templated instruction fine-tuning). To address these issues, we propose QT-Mob, a novel framework that significantly enhances LLMs for mobility analytics. QT-Mob introduces a location tokenization module that learns compact, semantically rich tokens to represent locations, preserving contextual information while ensuring compatibility with LLMs. Furthermore, QT-Mob incorporates a series of complementary fine-tuning objectives that align the learned tokens with the internal representations in LLMs, improving the model's comprehension of sequential movement patterns and location semantics. The proposed QT-Mob framework not only enhances LLMs' ability to interpret mobility data but also provides a more generalizable approach for various mobility analytics tasks. Experiments on three real-world dataset demonstrate the superior performance in both next-location prediction and mobility recovery tasks, outperforming existing deep learning and LLM-based methods.

[Arxiv](https://arxiv.org/abs/2506.11109)