# 大型语言模型与静态分析器的融合，打造智能代码审查生成方案

发布时间：2025年02月10日

`RAG` `软件工程` `代码审查`

> Combining Large Language Models with Static Analyzers for Code Review Generation

# 摘要

> 代码审查是软件开发中关键但复杂、主观且耗时的活动。多年来，人们一直在努力实现这一过程的自动化。早期方法主要集中在知识系统（KBS），利用基于规则的机制检测代码问题，虽然能提供精准反馈，但在处理复杂、依赖上下文的情况时效果欠佳。近期研究转向微调预训练语言模型进行代码审查，虽然扩大了问题覆盖面，但通常以牺牲精确度为代价。本文提出了一种混合方法，结合知识系统（KBS）和学习系统（LBS）的优势，生成高质量、全面的代码审查。我们的方法在语言模型管道的三个不同阶段整合知识：数据准备阶段（数据增强训练，DAT）、推理阶段（检索增强生成，RAG）和推理后阶段（输出的简单拼接，NCO）。我们通过实证评估，将组合策略与独立的KBS和LBS（在真实数据集上微调）进行对比。结果显示，这些混合策略显著提升了审查注释的相关性、完整性和整体质量，有效弥合了基于规则工具和深度学习模型之间的差距。

> Code review is a crucial but often complex, subjective, and time-consuming activity in software development. Over the past decades, significant efforts have been made to automate this process. Early approaches focused on knowledge-based systems (KBS) that apply rule-based mechanisms to detect code issues, providing precise feedback but struggling with complex, context-dependent cases. More recent work has shifted toward fine-tuning pre-trained language models for code review, enabling broader issue coverage but often at the expense of precision. In this paper, we propose a hybrid approach that combines the strengths of KBS and learning-based systems (LBS) to generate high-quality, comprehensive code reviews. Our method integrates knowledge at three distinct stages of the language model pipeline: during data preparation (Data-Augmented Training, DAT), at inference (Retrieval-Augmented Generation, RAG), and after inference (Naive Concatenation of Outputs, NCO). We empirically evaluate our combination strategies against standalone KBS and LBS fine-tuned on a real-world dataset. Our results show that these hybrid strategies enhance the relevance, completeness, and overall quality of review comments, effectively bridging the gap between rule-based tools and deep learning models.

[Arxiv](https://arxiv.org/abs/2502.06633)