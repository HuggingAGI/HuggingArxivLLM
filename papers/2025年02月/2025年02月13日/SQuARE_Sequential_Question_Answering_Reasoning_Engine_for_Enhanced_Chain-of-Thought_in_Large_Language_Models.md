# # SQuARE: 顺序问答推理引擎，提升大型语言模型的思维链能力
SQuARE 是一种顺序问答推理引擎，专为提升大型语言模型的链式思维能力而设计。

发布时间：2025年02月13日

`LLM应用` `问答系统`

> SQuARE: Sequential Question Answering Reasoning Engine for Enhanced Chain-of-Thought in Large Language Models

# 摘要

> 在快速发展的自然语言处理领域，大型语言模型（LLMs）正面临日益复杂的推理挑战。传统方法如链式思维提示虽有潜力，但往往难以充分发挥模型的推理能力。本文介绍了SQuARE（顺序问答推理引擎），这是一种基于自我质询范式的新型提示技术，旨在提升推理能力。基于链式思维框架，SQuARE引导模型在处理主问题前生成并解决多个辅助问题，从而更全面地探索主题的各个方面。通过使用Llama 3和GPT-4o模型在多个问答数据集上进行的广泛评估表明，SQuARE显著超越了传统链式思维提示和现有的改写-响应方法。通过系统分解查询，SQuARE推动了LLM在推理任务中的能力提升。代码可在https://github.com/IntelLabs/RAG-FiT/tree/square公开获取。

> In the rapidly evolving field of Natural Language Processing, Large Language Models (LLMs) are tasked with increasingly complex reasoning challenges. Traditional methods like chain-of-thought prompting have shown promise but often fall short in fully leveraging a model's reasoning capabilities. This paper introduces SQuARE (Sequential Question Answering Reasoning Engine), a novel prompting technique designed to improve reasoning through a self-interrogation paradigm. Building upon CoT frameworks, SQuARE prompts models to generate and resolve multiple auxiliary questions before tackling the main query, promoting a more thorough exploration of various aspects of a topic. Our expansive evaluations, conducted with Llama 3 and GPT-4o models across multiple question-answering datasets, demonstrate that SQuARE significantly surpasses traditional CoT prompts and existing rephrase-and-respond methods. By systematically decomposing queries, SQuARE advances LLM capabilities in reasoning tasks. The code is publicly available at https://github.com/IntelLabs/RAG-FiT/tree/square.

[Arxiv](https://arxiv.org/abs/2502.09390)