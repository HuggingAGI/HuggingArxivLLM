# 基于合成CodeGym的可泛化端到端工具使用强化学习

发布时间：2025年09月21日

`Agent` `基础理论`

> Generalizable End-to-End Tool-Use RL with Synthetic CodeGym

# 摘要

> 工具增强型大型语言模型（LLMs），以下简称LLM智能体，借助外部工具处理各类任务并与现实世界交互。然而，当前训练方法多依赖静态轨迹的监督微调（SFT）或狭窄任务上的强化学习（RL），在开发环境外泛化能力薄弱，面对新工具和未知工作流时表现脆弱。由于代码执行蕴含现实工作流的诸多结构，编程问题为构建智能体训练环境提供了天然基础。受此启发，我们提出可扩展框架CodeGym，它能为智能体强化学习（RL）生成多样化、可验证且可控的多轮工具使用环境，助力LLM智能体主动探索并掌握各类工作流。CodeGym通过提取原子函数或逻辑为可调用工具，将静态编程问题转化为交互式环境，进而生成涵盖多种工具执行工作流的可验证任务。在CodeGym中训练的不同规模及思维链配置模型，均展现出稳定的分布外泛化能力；例如，Qwen2.5-32B-Instruct在分布外基准【数学公式】-Bench上的绝对准确率提升了8.7个百分点。

> Tool-augmented large language models (LLMs), hereafter LLM agents, leverage external tools to solve diverse tasks and interface with the real world. However, current training practices largely rely on supervised fine-tuning (SFT) over static trajectories or reinforcement learning (RL) on narrow tasks, and generalize poorly beyond development settings, leading to brittleness with new tools and unseen workflows. Because code execution reflects many structures of real-world workflows, coding problems provide a natural basis for building agent training environments. Motivated by this, we introduce CodeGym, a scalable framework that synthesizes diverse, verifiable, and controllable multi-turn tool-use environments for agent RL, enabling LLM agents to explore and master various workflows actively. CodeGym rewrites static coding problems into interactive environments by extracting atomic functions or logic into callable tools, yielding verifiable tasks that span various tool-execution workflows. Models of varying sizes and chain-of-thought configurations, trained in CodeGym, exhibit consistent out-of-distribution generalizability; for example, Qwen2.5-32B-Instruct achieves an absolute accuracy gain of 8.7 points on the OOD benchmark $τ$-Bench. These results highlight CodeGym as a step toward scalable general-purpose RL environments that align with real-world agent workflows.

[Arxiv](https://arxiv.org/abs/2509.17325)