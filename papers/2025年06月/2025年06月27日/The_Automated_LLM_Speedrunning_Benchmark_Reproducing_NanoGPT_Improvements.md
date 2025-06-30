# # 自动化LLM速通基准测试：再现NanoGPT优化成果

发布时间：2025年06月27日

`LLM应用` `科学研究` `人工智能`

> The Automated LLM Speedrunning Benchmark: Reproducing NanoGPT Improvements

# 摘要

> 快速发展的大型语言模型 (LLMs) 有望助力科学进步。实现这一目标的关键能力在于能够复现实验结果。为了评估 AI 代理在活跃研究领域中复现实验结果的能力，我们引入了自动化 LLM 速通基准测试，利用研究社区在 NanoGPT 速通比赛中的贡献，该比赛旨在以最短时间训练出 GPT-2 模型。每个包含在 19 个速通任务中的任务都会为代理提供之前记录的训练脚本，并可选地搭配三种提示格式之一，从伪代码到类似论文的改进描述不等。记录设计上运行迅速，速通改进涵盖多种代码级别变化，从高层次算法进步到硬件感知优化。这些特性使该基准测试成为提升 LLM 训练前沿问题的可行且现实的工具。我们发现，即使在提供详细提示的情况下，结合最新推理 LLM 和 SoTA 框架的模型也难以在我们的基准测试中重新实现已知创新。因此，我们的基准测试提供了一个简单且未饱和的衡量指标，用于评估 LLM 自动化科学复现的能力，这是自主研究代理所需（但非充分）的关键技能。


> Rapid advancements in large language models (LLMs) have the potential to assist in scientific progress. A critical capability toward this endeavor is the ability to reproduce existing work. To evaluate the ability of AI agents to reproduce results in an active research area, we introduce the Automated LLM Speedrunning Benchmark, leveraging the research community contributions on the NanoGPT speedrun, a competition to train a GPT-2 model in the shortest time. Each of the 19 speedrun tasks provides the agent with the previous records training script, optionally paired with one of three hint formats, ranging from pseudocode to paper-like descriptions of the new records improvements. Records execute quickly by design and speedrun improvements encompass diverse code-level changes, ranging from high-level algorithmic advancements to hardware-aware optimizations. These features make the benchmark both accessible and realistic for the frontier problem of improving LLM training. We find that recent reasoning LLMs combined with SoTA scaffolds struggle to reimplement already-known innovations in our benchmark, even when given detailed hints. Our benchmark thus provides a simple, non-saturated measure of an LLMs ability to automate scientific reproduction, a necessary (but not sufficient) skill for an autonomous research agent.

[Arxiv](https://arxiv.org/abs/2506.22419)