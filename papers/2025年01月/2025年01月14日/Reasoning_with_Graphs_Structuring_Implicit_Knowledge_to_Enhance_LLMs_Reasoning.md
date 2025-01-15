# 图推理：结构化隐式知识，提升LLMs推理能力

发布时间：2025年01月14日

`LLM应用

理由：该论文主要探讨了如何通过构建显式图来增强大型语言模型（LLMs）在推理任务中的表现，特别是逻辑推理和多跳问答任务。这属于LLM在实际应用中的改进和优化，因此归类为“LLM应用”。` `推理系统`

> Reasoning with Graphs: Structuring Implicit Knowledge to Enhance LLMs Reasoning

# 摘要

> 大型语言模型（LLMs）在众多任务中表现出色，但在需要理解和推断文本中信息片段间关系的推理任务中仍面临挑战，尤其是在逻辑推理和多跳问答等多步骤任务中。图作为基本数据结构，能够明确表示实体间关系，为提升LLMs的推理能力提供了可能。尽管外部图在支持LLMs完成多项任务中效果显著，但许多推理任务中并无现成的图结构。本文提出基于图的推理（RwG），通过从上下文中构建显式图，并利用这些图来增强LLMs在推理任务中的表现。大量实验验证了该方法在提升逻辑推理和多跳问答任务效果上的有效性。

> Large language models (LLMs) have demonstrated remarkable success across a wide range of tasks; however, they still encounter challenges in reasoning tasks that require understanding and inferring relationships between distinct pieces of information within text sequences. This challenge is particularly pronounced in tasks involving multi-step processes, such as logical reasoning and multi-hop question answering, where understanding implicit relationships between entities and leveraging multi-hop connections in the given context are crucial. Graphs, as fundamental data structures, explicitly represent pairwise relationships between entities, thereby offering the potential to enhance LLMs' reasoning capabilities. External graphs have proven effective in supporting LLMs across multiple tasks. However, in many reasoning tasks, no pre-existing graph structure is provided. Can we structure implicit knowledge derived from context into graphs to assist LLMs in reasoning? In this paper, we propose Reasoning with Graphs (RwG) by first constructing explicit graphs from the context and then leveraging these graphs to enhance LLM reasoning performance on reasoning tasks. Extensive experiments demonstrate the effectiveness of the proposed method in improving both logical reasoning and multi-hop question answering tasks.

[Arxiv](https://arxiv.org/abs/2501.07845)