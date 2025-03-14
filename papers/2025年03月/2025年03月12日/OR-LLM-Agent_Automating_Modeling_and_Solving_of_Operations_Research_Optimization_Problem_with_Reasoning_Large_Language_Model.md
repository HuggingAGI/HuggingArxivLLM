# # OR-LLM-Agent：基于推理型大语言模型的运筹优化问题自动化建模与求解

发布时间：2025年03月12日

`Agent` `供应链管理` `运筹学`

> OR-LLM-Agent: Automating Modeling and Solving of Operations Research Optimization Problem with Reasoning Large Language Model

# 摘要

> 运筹学 (OR) 在资源分配、生产计划和供应链管理等领域得到了广泛应用。然而，解决现实中的运筹学问题需要运筹专家进行数学建模，同时程序员需要开发求解算法。这种依赖专家的传统方法成本高昂且开发周期长，严重限制了运筹学技术的广泛应用。很少有人考虑使用人工智能 (AI) 来替代专业人士，以实现运筹问题的全自动解决方案。我们提出了 OR-LLM-Agent，这是首个能够实现端到端自动化解决现实世界运筹问题的人工智能代理。OR-LLM-Agent 利用大型语言模型 (LLMs) 的链式思维 (CoT) 推理能力，将自然语言问题描述转化为正式的数学模型，并自动生成 Gurobi 求解器代码。在 OR-LLM-Agent 中，OR-CodeAgent 被设计用于在沙盒环境中自动化代码执行和修复，从而推导出最终解决方案。由于缺乏专门用于评估运筹问题自动求解的基准数据集，我们构建了一个包含 83 个现实世界自然语言描述的运筹问题的基准数据集。我们与包括 GPT-o3-mini、DeepSeek-R1 和 Gemini 2.0 Flash Thinking 在内的最新 (SOTA) 推理 LLM 进行了对比实验。OR-LLM-Agent 实现了 100% 的最高通过率和 85% 的最高解决方案准确率，证明了运筹问题自动求解的可行性。数据和代码已在 https://github.com/bwz96sco/or_llm_agent 公开提供。

> Operations Research (OR) has been widely applied in various fields such as resource allocation, production planning, and supply chain management. However, addressing real-world OR problems requires OR experts to perform mathematical modeling and programmers to develop solution algorithms. This traditional method, heavily reliant on experts, is costly and has long development cycles, severely limiting the widespread adoption of OR techniques. Few have considered using Artificial Intelligence (AI) to replace professionals to achieve fully automated solutions for OR problems. We propose OR-LLM-Agent, the first AI agent that enables end-to-end automation for solving real-world OR problems. OR-LLM-Agent leverages the Chain-of-Thought (CoT) reasoning capabilities of Large Language Models (LLMs) to translate natural language problem descriptions into formal mathematical models and automatically generate Gurobi solver code. In OR-LLM-Agent, OR-CodeAgent is designed to automate code execution and repair within a sandbox environment, facilitating the derivation of the final solution. Due to the lack of dedicated benchmark datasets for evaluating the automated solving of OR problems, we construct a benchmark dataset comprising 83 real-world OR problems described in natural language. We conduct comparative experiments with state-of-the-art (SOTA) reasoning LLMs, including GPT-o3-mini, DeepSeek-R1, and Gemini 2.0 Flash Thinking. The OR-LLM-Agent achieved the highest pass rate of 100% and the highest solution accuracy of 85%, demonstrating the feasibility of automated OR problem-solving. Data and code have been publicly available at https://github.com/bwz96sco/or_llm_agent.

[Arxiv](https://arxiv.org/abs/2503.10009)