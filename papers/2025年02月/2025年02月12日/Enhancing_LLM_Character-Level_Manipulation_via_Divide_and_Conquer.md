# 利用分而治之策略提升 LLM 的字符级操作能力

发布时间：2025年02月12日

`LLM理论` `字符级操作`

> Enhancing LLM Character-Level Manipulation via Divide and Conquer

# 摘要

> 大型语言模型（LLMs）在自然语言处理（NLP）任务中展现出了强大的泛化能力。然而，它们在字符级字符串操作方面存在明显弱点，难以完成字符删除、插入和替换等基础操作。这些挑战主要源于分词约束，尽管这些操作在数据预处理和代码生成中扮演着关键角色。通过系统性分析，我们得出两个重要结论：（1）LLMs在利用内在分词知识进行字符级推理方面面临显著困难；（2）原子化词结构能够大幅增强LLMs处理分词级结构信息的能力。基于这些洞察，我们提出了一种名为“分治法实现字符级操作”的全新方法，旨在弥合分词级处理与字符级操作之间的鸿沟。我们的方法将复杂操作分解为明确的字符级子任务，并结合受控的分词重构阶段，显著提升了准确率。无需额外训练，我们的方法在【数学公式】任务上的准确率有了显著提升。为了支持进一步研究，我们开源了我们的实现和基准测试。


> Large Language Models (LLMs) have demonstrated strong generalization capabilities across a wide range of natural language processing (NLP) tasks. However, they exhibit notable weaknesses in character-level string manipulation, struggling with fundamental operations such as character deletion, insertion, and substitution. These challenges stem primarily from tokenization constraints, despite the critical role of such operations in data preprocessing and code generation. Through systematic analysis, we derive two key insights: (1) LLMs face significant difficulties in leveraging intrinsic token knowledge for character-level reasoning, and (2) atomized word structures can substantially enhance LLMs' ability to process token-level structural information. Building on these insights, we propose Character-Level Manipulation via Divide and Conquer, a novel approach designed to bridge the gap between token-level processing and character-level manipulation. Our method decomposes complex operations into explicit character-level subtasks coupled with controlled token reconstruction phases, leading to significant improvements in accuracy. Without additional training, our method significantly improves accuracies on the $\texttt{Deletion}$, $\texttt{Insertion}$, and $\texttt{Substitution}$ tasks. To support further research, we open-source our implementation and benchmarks.

[Arxiv](https://arxiv.org/abs/2502.08180)