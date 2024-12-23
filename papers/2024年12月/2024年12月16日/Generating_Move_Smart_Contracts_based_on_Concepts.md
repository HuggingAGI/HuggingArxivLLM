# 基于概念生成 Move 智能合约

发布时间：2024年12月16日

`LLM应用` `智能合约` `代码生成`

> Generating Move Smart Contracts based on Concepts

# 摘要

> 智能合约对正式验证的采用日益广泛，从而推动了诸如 Move 这类新的可验证语言的发展。但这些语言的训练数据有限，致使大型语言模型（LLMs）难以有效地生成代码。本文提出了 ConMover 这一新颖框架，它借助 Move 概念的知识图谱和少量已验证的代码示例，强化了基于 LLM 的 Move 代码生成。ConMover 在迭代过程中整合了概念检索、规划、编码和调试代理，以完善生成的代码。通过多种开源 LLMs 进行的评估显示，其准确性相比基线模型有大幅提升。这些结果凸显了 ConMover 在应对低资源代码生成挑战方面的潜力，填补了自然语言描述与可靠的智能合约开发之间的空白。

> The growing adoption of formal verification for smart contracts has spurred the development of new verifiable languages like Move. However, the limited availability of training data for these languages hinders effective code generation by large language models (LLMs). This paper presents ConMover, a novel framework that enhances LLM-based code generation for Move by leveraging a knowledge graph of Move concepts and a small set of verified code examples. ConMover integrates concept retrieval, planning, coding, and debugging agents in an iterative process to refine generated code. Evaluations with various open-source LLMs demonstrate substantial accuracy improvements over baseline models. These results underscore ConMover's potential to address low-resource code generation challenges, bridging the gap between natural language descriptions and reliable smart contract development.

[Arxiv](https://arxiv.org/abs/2412.12513)