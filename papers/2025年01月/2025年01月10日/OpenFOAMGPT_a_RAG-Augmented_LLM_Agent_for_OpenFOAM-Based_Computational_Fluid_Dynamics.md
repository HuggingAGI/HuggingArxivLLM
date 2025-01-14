# OpenFOAMGPT: 一个RAG增强的LLM代理，专为OpenFOAM计算流体动力学设计

发布时间：2025年01月10日

`Agent

理由：这篇论文介绍了一个基于LLM的代理OpenFOAMGPT，专为OpenFOAM的CFD模拟设计。该代理结合了OpenAI的GPT-4o和具备链式思维（CoT）的o1预览模型，能够处理复杂任务，并通过迭代校正高效处理多种工程场景。论文还提到采用RAG管道嵌入领域知识，展示了如何利用现有模拟设置进一步专业化代理。尽管论文涉及RAG和LLM应用，但其核心内容是围绕一个具体的代理（Agent）展开的，因此更适合归类为Agent。` `航空航天`

> OpenFOAMGPT: a RAG-Augmented LLM Agent for OpenFOAM-Based Computational Fluid Dynamics

# 摘要

> # 摘要
本文介绍了一个基于LLM的代理OpenFOAMGPT，专为OpenFOAM的CFD模拟设计，结合了OpenAI的GPT-4o和具备链式思维（CoT）的o1预览模型。尽管o1模型的代币成本是GPT-4o的六倍，但它在处理复杂任务时表现更优，涵盖从零-shot案例设置到边界条件修改、湍流模型调整和代码翻译。通过迭代校正，该代理高效处理了单相流、多相流、热传递、RANS、LES等工程场景，通常以低代币成本在有限迭代内收敛。我们采用RAG管道嵌入领域知识，展示了如何利用现有模拟设置进一步专业化代理，适用于能源和航空航天等子领域。尽管代理表现出色，人类监督仍是确保准确性和适应变化环境的关键。模型性能的波动表明在关键任务应用中需要持续监控。虽然演示集中在OpenFOAM上，但该框架的适应性为开发LLM驱动的代理进入广泛的求解器和代码提供了可能。通过简化CFD模拟，这一方法有望加速基础研究和工业工程的进步。

> This work presents a large language model (LLM)-based agent OpenFOAMGPT tailored for OpenFOAM-centric computational fluid dynamics (CFD) simulations, leveraging two foundation models from OpenAI: the GPT-4o and a chain-of-thought (CoT)-enabled o1 preview model. Both agents demonstrate success across multiple tasks. While the price of token with o1 model is six times as that of GPT-4o, it consistently exhibits superior performance in handling complex tasks, from zero-shot case setup to boundary condition modifications, turbulence model adjustments, and code translation. Through an iterative correction loop, the agent efficiently addressed single- and multi-phase flow, heat transfer, RANS, LES, and other engineering scenarios, often converging in a limited number of iterations at low token costs. To embed domain-specific knowledge, we employed a retrieval-augmented generation (RAG) pipeline, demonstrating how preexisting simulation setups can further specialize the agent for sub-domains such as energy and aerospace. Despite the great performance of the agent, human oversight remains crucial for ensuring accuracy and adapting to shifting contexts. Fluctuations in model performance over time suggest the need for monitoring in mission-critical applications. Although our demonstrations focus on OpenFOAM, the adaptable nature of this framework opens the door to developing LLM-driven agents into a wide range of solvers and codes. By streamlining CFD simulations, this approach has the potential to accelerate both fundamental research and industrial engineering advancements.

[Arxiv](https://arxiv.org/abs/2501.06327)