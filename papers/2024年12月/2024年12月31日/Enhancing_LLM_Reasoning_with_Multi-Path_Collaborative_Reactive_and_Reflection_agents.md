# 提升LLM推理：多路径协作反应与反思代理

发布时间：2024年12月31日

`Agent

理由：这篇论文主要讨论的是通过多路径推理的反应与反思代理（RR-MP）框架来提升大型语言模型（LLM）在科学推理任务中的表现。论文的核心内容是围绕代理（Agent）的设计和优化，特别是如何通过多路径推理机制来增强代理的推理能力。因此，这篇论文应归类为Agent。` `科学推理`

> Enhancing LLM Reasoning with Multi-Path Collaborative Reactive and Reflection agents

# 摘要

> # 摘要
代理通过大型语言模型在科学推理任务中展现了巨大潜力，但在处理复杂推理任务时，常面临准确性不足和思维退化等挑战。为此，我们提出了多路径推理的反应与反思代理（RR-MP）框架，旨在提升LLMs的推理能力。该框架通过多路径推理机制，每条路径由反应代理和反思代理协作，避免单代理依赖导致的思维退化。RR-MP框架无需额外训练，利用多对话实例和总结器整合各路径见解，融合多样化观点，强化推理能力。我们在道德场景、大学物理和数学任务上进行了零-shot和少-shot评估，实验结果显示，RR-MP框架在复杂科学推理任务中表现优异，显著优于基线方法。

> Agents have demonstrated their potential in scientific reasoning tasks through large language models. However, they often face challenges such as insufficient accuracy and degeneration of thought when handling complex reasoning tasks, which impede their performance. To overcome these issues, we propose the Reactive and Reflection agents with Multi-Path Reasoning (RR-MP) Framework, aimed at enhancing the reasoning capabilities of LLMs. Our approach improves scientific reasoning accuracy by employing a multi-path reasoning mechanism where each path consists of a reactive agent and a reflection agent that collaborate to prevent degeneration of thought inherent in single-agent reliance. Additionally, the RR-MP framework does not require additional training; it utilizes multiple dialogue instances for each reasoning path and a separate summarizer to consolidate insights from all paths. This design integrates diverse perspectives and strengthens reasoning across each path. We conducted zero-shot and few-shot evaluations on tasks involving moral scenarios, college-level physics, and mathematics. Experimental results demonstrate that our method outperforms baseline approaches, highlighting the effectiveness and advantages of the RR-MP framework in managing complex scientific reasoning tasks.

[Arxiv](https://arxiv.org/abs/2501.00430)