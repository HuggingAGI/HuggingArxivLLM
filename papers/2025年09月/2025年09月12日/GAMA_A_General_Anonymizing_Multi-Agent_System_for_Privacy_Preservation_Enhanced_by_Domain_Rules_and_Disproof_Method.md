# GAMA：基于领域规则与反证法增强的通用匿名化多智能体隐私保护系统

发布时间：2025年09月12日

`Agent` `基础理论`

> GAMA: A General Anonymizing Multi-Agent System for Privacy Preservation Enhanced by Domain Rules and Disproof Method

# 摘要

> 随着大型语言模型（LLM）的飞速发展，基于LLM的智能体在自然语言理解与生成上表现卓越，推动了基于LLM的多智能体系统（MAS）中类人化的协作与信息传递。高性能LLM通常部署在公共网络的远程服务器中。当任务涉及隐私数据时，若不采取隐私保护措施，MAS便无法安全调用这些LLM。为应对这一挑战，我们提出通用匿名化多智能体系统（GAMA），它将智能体的工作空间划分为私有域与公共域，并借助匿名化机制实现隐私保护。私有域内，智能体处理敏感数据；公共域中，则仅使用匿名化数据。GAMA还集成了两个关键模块，用于缓解匿名化带来的语义损失：基于领域规则的知识增强（DRKE）与基于反证的逻辑增强（DLE）。我们在两个公开问答数据集（Trivia Creative Writing和Logic Grid Puzzle）上对GAMA进行了评估，结果显示其性能优于当前最先进模型。为进一步验证其隐私保护能力，我们还设计了两个新数据集：知识隐私保护数据集与逻辑隐私保护数据集。最终结果证实，GAMA在任务处理与隐私保护上均表现出卓越效能。

> With the rapid advancement of Large Language Model (LLM), LLM-based agents exhibit exceptional abilities in understanding and generating natural language, facilitating human-like collaboration and information transmission in LLM-based Multi-Agent System (MAS). High-performance LLMs are often hosted on remote servers in public spaces. When tasks involve privacy data, MAS cannot securely utilize these LLMs without implementing privacy-preserving mechanisms. To address this challenge, we propose a General Anonymizing Multi-Agent system (GAMA), which divides the agents' workspace into private and public spaces and protects privacy through the anonymizing mechanism. In the private space, agents handle sensitive data, while in the public space, only anonymized data is utilized. GAMA incorporates two key modules to mitigate semantic loss caused by anonymization: Domain-Rule-based Knowledge Enhancement (DRKE) and Disproof-based Logic Enhancement (DLE). We evaluate GAMA on two public question-answering datasets: Trivia Creative Writing and Logic Grid Puzzle. The results demonstrate that GAMA has superior performance compared to the state-of-the-art models. To further assess its privacy-preserving capabilities, we designed two new datasets: Knowledge Privacy Preservation and Logic Privacy Preservation. The final results highlight GAMA's exceptional effectiveness in both task processing and privacy preservation.

[Arxiv](https://arxiv.org/abs/2509.10018)