# 迈向多轮个性化对话：隐式推理的大规模数据集与层次化树结构框架

发布时间：2025年03月10日

`LLM应用` `对话系统`

> Toward Multi-Session Personalized Conversation: A Large-Scale Dataset and Hierarchical Tree Framework for Implicit Reasoning

# 摘要

> 近年来，基于大型语言模型（LLM）的对话代理在根据多轮对话历史生成回复方面得到了广泛应用。然而，现有的长期开放领域对话数据集在复杂的真实个性化方面存在不足，并且未能捕捉到隐式推理——即相关信息并非通过显式陈述，而是嵌入在微妙的句法或语义联系中。在这种情况下，传统检索方法难以捕捉相关上下文，长上下文建模也因大量复杂的个性化细节而效率低下。为了解决这一问题，我们推出了ImplexConv，一个包含2,500个示例的大型长期数据集，每个示例包含约100个对话轮次，专门用于研究个性化对话中的隐式推理。此外，我们提出了TaciTree，一个创新的层次树框架，将对话历史结构化为多个级别的总结。与传统的暴力数据搜索不同，TaciTree通过一个基于级别的高效检索过程，使模型能够逐步优化搜索，选择相关细节。实验结果表明，TaciTree显著提升了LLMs在长期对话中处理隐式上下文依赖的能力。

> There has been a surge in the use of large language models (LLM) conversational agents to generate responses based on long-term history from multiple sessions. However, existing long-term open-domain dialogue datasets lack complex, real-world personalization and fail to capture implicit reasoning-where relevant information is embedded in subtle, syntactic, or semantically distant connections rather than explicit statements. In such cases, traditional retrieval methods fail to capture relevant context, and long-context modeling also becomes inefficient due to numerous complicated persona-related details. To address this gap, we introduce ImplexConv, a large-scale long-term dataset with 2,500 examples, each containing approximately 100 conversation sessions, designed to study implicit reasoning in personalized dialogues. Additionally, we propose TaciTree, a novel hierarchical tree framework that structures conversation history into multiple levels of summarization. Instead of brute-force searching all data, TaciTree enables an efficient, level-based retrieval process where models refine their search by progressively selecting relevant details. Our experiments demonstrate that TaciTree significantly improves the ability of LLMs to reason over long-term conversations with implicit contextual dependencies.

[Arxiv](https://arxiv.org/abs/2503.07018)