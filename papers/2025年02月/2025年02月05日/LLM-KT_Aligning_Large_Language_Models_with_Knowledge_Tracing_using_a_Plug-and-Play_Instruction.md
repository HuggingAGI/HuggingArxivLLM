# LLM-KT: 通过即插即用指令实现大型语言模型与知识追踪的精准对齐

发布时间：2025年02月05日

`LLM应用

理由：这篇论文提出了一种基于大型语言模型（LLMs）的知识追踪框架（LLM-KT），旨在通过结合LLMs的优势与传统序列交互模型来解决知识追踪问题。论文的核心是利用LLMs的丰富知识和推理能力来提升个性化教育中的学生行为预测。因此，这篇论文属于LLM应用领域，因为它探讨了如何将LLMs应用于具体的教育场景中，并展示了其在提升任务性能方面的潜力。` `个性化学习`

> LLM-KT: Aligning Large Language Models with Knowledge Tracing using a Plug-and-Play Instruction

# 摘要

> 知识追踪（KT）问题是个性化教育中的关键课题，旨在通过学生的历史答题记录预测其未来答题表现。以往研究多依赖ID或文本信息来学习行为序列，但缺乏对问题相关知识的深入推理，难以全面捕捉学生行为模式。本文提出了一种基于大型语言模型（LLMs）的KT框架——\texttt{\textbf{LLM-KT}}，融合了LLMs与传统序列交互模型的优势。在任务层面，我们设计了即插即用指令，利用LLMs的丰富知识与推理能力，实现与KT任务的对齐。在模态层面，通过插件上下文和序列设计，整合了传统方法的多模态学习能力。为捕捉长历史记录，我们提出了一种插件上下文机制，利用问题与概念特定标记，将压缩的上下文嵌入灵活注入LLMs。此外，通过序列适配器引入插件序列，增强了LLMs对传统序列模型学习的行为表示能力。实验表明，\texttt{\textbf{LLM-KT}}在四个典型数据集上，与约20个强基线相比，取得了最先进的性能。

> The knowledge tracing (KT) problem is an extremely important topic in personalized education, which aims to predict whether students can correctly answer the next question based on their past question-answer records. Prior work on this task mainly focused on learning the sequence of behaviors based on the IDs or textual information. However, these studies usually fail to capture students' sufficient behavioral patterns without reasoning with rich world knowledge about questions. In this paper, we propose a large language models (LLMs)-based framework for KT, named \texttt{\textbf{LLM-KT}}, to integrate the strengths of LLMs and traditional sequence interaction models. For task-level alignment, we design Plug-and-Play instruction to align LLMs with KT, leveraging LLMs' rich knowledge and powerful reasoning capacity. For modality-level alignment, we design the plug-in context and sequence to integrate multiple modalities learned by traditional methods. To capture the long context of history records, we present a plug-in context to flexibly insert the compressed context embedding into LLMs using question-specific and concept-specific tokens. Furthermore, we introduce a plug-in sequence to enhance LLMs with sequence interaction behavior representation learned by traditional sequence models using a sequence adapter. Extensive experiments show that \texttt{\textbf{LLM-KT}} obtains state-of-the-art performance on four typical datasets by comparing it with approximately 20 strong baselines.

[Arxiv](https://arxiv.org/abs/2502.02945)