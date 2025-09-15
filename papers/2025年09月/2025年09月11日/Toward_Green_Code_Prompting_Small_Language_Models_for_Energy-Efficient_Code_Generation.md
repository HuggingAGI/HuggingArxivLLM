# 迈向绿色代码：提示小型语言模型生成节能代码

发布时间：2025年09月11日

`LLM应用` `能源与环保`

> Toward Green Code: Prompting Small Language Models for Energy-Efficient Code Generation

# 摘要

> 大型语言模型（LLMs）在软件开发中的环境影响日益受到关注，尤其是其高能耗与碳足迹问题。相比之下，小型语言模型（SLMs）作为更可持续的替代方案，所需计算资源更少，却仍能胜任基础编程任务。本研究探讨提示工程能否提升SLMs在代码生成中的能效，为此评估了四个开源SLMs——StableCode-Instruct-3B、Qwen2.5-Coder-3B-Instruct、CodeLlama-7B-Instruct及Phi-3-Mini-4K-Instruct，在150道LeetCode Python题目（均匀分布于简单、中等、困难三类）上的表现。每个模型均测试了四种提示策略：角色提示、零样本、少样本及思维链（CoT）。我们对生成方案的运行时间、内存占用和能耗进行测量，并与人工编写的基线对比。结果显示，思维链（CoT）提示能为Qwen2.5-Coder和StableCode-3B带来持续的节能效果，而CodeLlama-7B与Phi-3-Mini-4K在所有提示策略下均未能超越人工基线。这些发现表明，提示工程的效果具有模型依赖性，精心设计的提示可引导SLMs助力更绿色的软件开发实践。

> There is a growing concern about the environmental impact of large language models (LLMs) in software development, particularly due to their high energy use and carbon footprint. Small Language Models (SLMs) offer a more sustainable alternative, requiring fewer computational resources while remaining effective for fundamental programming tasks. In this study, we investigate whether prompt engineering can improve the energy efficiency of SLMs in code generation. We evaluate four open-source SLMs, StableCode-Instruct-3B, Qwen2.5-Coder-3B-Instruct, CodeLlama-7B-Instruct, and Phi-3-Mini-4K-Instruct, across 150 Python problems from LeetCode, evenly distributed into easy, medium, and hard categories. Each model is tested under four prompting strategies: role prompting, zero-shot, few-shot, and chain-of-thought (CoT). For every generated solution, we measure runtime, memory usage, and energy consumption, comparing the results with a human-written baseline. Our findings show that CoT prompting provides consistent energy savings for Qwen2.5-Coder and StableCode-3B, while CodeLlama-7B and Phi-3-Mini-4K fail to outperform the baseline under any prompting strategy. These results highlight that the benefits of prompting are model-dependent and that carefully designed prompts can guide SLMs toward greener software development.

[Arxiv](https://arxiv.org/abs/2509.09947)