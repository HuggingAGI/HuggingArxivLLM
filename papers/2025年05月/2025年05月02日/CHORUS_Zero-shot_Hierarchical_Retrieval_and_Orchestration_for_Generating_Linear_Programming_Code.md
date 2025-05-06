# CHORUS: 通过零样本分层检索与编排生成线性规划代码

发布时间：2025年05月02日

`RAG` `运筹学`

> CHORUS: Zero-shot Hierarchical Retrieval and Orchestration for Generating Linear Programming Code

# 摘要

> 线性规划（LP）问题旨在寻找在约束条件下的最优解。这类问题通常需要领域知识、数学技能和编程能力，对非专家来说具有很大挑战性。本研究探讨了大型语言模型（LLMs）在生成特定求解器的LP代码方面的效率。我们提出了CHORUS，一个用于从自然语言问题描述中合成基于Gurobi的LP代码的检索增强生成（RAG）框架。CHORUS采用层次树状的分块策略处理理论内容，并基于文档中的代码示例生成额外的元数据，以促进自洽且语义连贯的检索。CHORUS的两阶段检索方法结合交叉编码器重新排序，进一步确保了上下文的相关性。最后，精心设计的提示和结构化解析器，结合推理步骤，显著提升了代码生成性能。在NL4Opt-Code基准上的实验表明，与基线和传统RAG方法相比，CHORUS显著提升了开源LLMs（如Llama3.1 (8B)、Llama3.3 (70B)、Phi4 (14B)、Deepseek-r1 (32B)和Qwen2.5-coder (32B)）的性能。它还使这些开源LLMs能够超越或匹配性能更强的基线GPT3.5和GPT4，同时消耗远少的计算资源。消融研究进一步证明了专家提示、层次分块和结构化推理的重要性。

> Linear Programming (LP) problems aim to find the optimal solution to an objective under constraints. These problems typically require domain knowledge, mathematical skills, and programming ability, presenting significant challenges for non-experts. This study explores the efficiency of Large Language Models (LLMs) in generating solver-specific LP code. We propose CHORUS, a retrieval-augmented generation (RAG) framework for synthesizing Gurobi-based LP code from natural language problem statements. CHORUS incorporates a hierarchical tree-like chunking strategy for theoretical contents and generates additional metadata based on code examples from documentation to facilitate self-contained, semantically coherent retrieval. Two-stage retrieval approach of CHORUS followed by cross-encoder reranking further ensures contextual relevance. Finally, expertly crafted prompt and structured parser with reasoning steps improve code generation performance significantly. Experiments on the NL4Opt-Code benchmark show that CHORUS improves the performance of open-source LLMs such as Llama3.1 (8B), Llama3.3 (70B), Phi4 (14B), Deepseek-r1 (32B), and Qwen2.5-coder (32B) by a significant margin compared to baseline and conventional RAG. It also allows these open-source LLMs to outperform or match the performance of much stronger baselines-GPT3.5 and GPT4 while requiring far fewer computational resources. Ablation studies further demonstrate the importance of expert prompting, hierarchical chunking, and structured reasoning.

[Arxiv](https://arxiv.org/abs/2505.01485)