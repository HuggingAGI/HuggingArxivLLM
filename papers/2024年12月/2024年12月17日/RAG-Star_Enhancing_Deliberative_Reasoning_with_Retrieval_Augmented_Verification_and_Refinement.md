# RAG-Star：借助检索增强的验证与改进来强化审议推理

发布时间：2024年12月17日

`RAG` `语言模型` `推理任务`

> RAG-Star: Enhancing Deliberative Reasoning with Retrieval Augmented Verification and Refinement

# 摘要

> 现有的大型语言模型（LLMs）具备出色的问题解决能力，然而在复杂推理任务上可能会力不从心。尽管思维链和基于树的搜索方法有所成效，但它们主要依靠LLMs的内部知识来搜索中间推理步骤，只适用于处理推理步骤较少的简单任务。在本文中，我们提出了	extbf{RAG-Star}这一创新的RAG方法，它融合了检索到的信息，用以引导基于LLMs固有知识的基于树的审议推理流程。借助蒙特卡罗树搜索，RAG-Star会迭代规划中间子查询及答案，以基于LLM自身进行推理。为整合内部和外部知识，我们提出了一种检索增强验证，其利用查询和答案感知奖励建模为LLMs的固有推理提供反馈。我们针对Llama-3.1-8B-Instruct和GPT-4o开展的实验表明，RAG-Star明显优于以往的RAG和推理方法。

> Existing large language models (LLMs) show exceptional problem-solving capabilities but might struggle with complex reasoning tasks. Despite the successes of chain-of-thought and tree-based search methods, they mainly depend on the internal knowledge of LLMs to search over intermediate reasoning steps, limited to dealing with simple tasks involving fewer reasoning steps. In this paper, we propose \textbf{RAG-Star}, a novel RAG approach that integrates the retrieved information to guide the tree-based deliberative reasoning process that relies on the inherent knowledge of LLMs. By leveraging Monte Carlo Tree Search, RAG-Star iteratively plans intermediate sub-queries and answers for reasoning based on the LLM itself. To consolidate internal and external knowledge, we propose an retrieval-augmented verification that utilizes query- and answer-aware reward modeling to provide feedback for the inherent reasoning of LLMs. Our experiments involving Llama-3.1-8B-Instruct and GPT-4o demonstrate that RAG-Star significantly outperforms previous RAG and reasoning methods.

[Arxiv](https://arxiv.org/abs/2412.12881)