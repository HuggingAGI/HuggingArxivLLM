# Cyber-Zero：无需运行时的网络安全代理训练

发布时间：2025年07月29日

`LLM应用` `网络安全`

> Cyber-Zero: Training Cybersecurity Agents without Runtime

# 摘要

> 当配备可执行运行时环境时，大型语言模型（LLMs）在软件工程任务中表现出色，尤其是在处理GitHub问题方面。然而，这种优势在网络安全等其他领域受限，因为挑战配置和执行上下文往往短暂或受限。我们推出Cyber-Zero，首个无需运行时环境的框架，专为训练网络安全领域的LLMs而设计。Cyber-Zero基于公开的CTF解题报告，通过角色驱动的LLM仿真，逆向工程运行时行为，无需实际环境即可生成真实且长期的交互序列。在三个著名CTF基准测试中，使用Cyber-Zero合成轨迹训练的LLM代理，相比基线模型实现了高达13.1%的绝对性能提升。我们的最佳模型Cyber-Zero-32B在开源模型中达到新高度，其能力可与DeepSeek-V3-0324和Claude-3.5-Sonnet等专有系统相媲美，同时具备更优的成本效益，证明了无运行时轨迹合成在推动最先进网络安全代理开发方面的有效性。

> Large Language Models (LLMs) have achieved remarkable success in software engineering tasks when trained with executable runtime environments, particularly in resolving GitHub issues. However, such runtime environments are often unavailable in other domains, especially cybersecurity, where challenge configurations and execution contexts are ephemeral or restricted. We present Cyber-Zero, the first runtime-free framework for synthesizing high-quality agent trajectories to train cybersecurity LLMs. Cyber-Zero leverages publicly available CTF writeups and employs persona-driven LLM simulation to reverse-engineer runtime behaviors and generate realistic, long-horizon interaction sequences without actual environments. Using trajectories synthesized by Cyber-Zero, we train LLM-based agents that achieve up to 13.1% absolute performance gains over baseline models on three prominent CTF benchmarks: InterCode-CTF, NYU CTF Bench, and Cybench. Our best model, Cyber-Zero-32B, establishes new state-of-the-art performance among open-weight models, matching the capabilities of proprietary systems like DeepSeek-V3-0324 and Claude-3.5-Sonnet while offering superior cost-effectiveness, and demonstrating that runtime-free trajectory synthesis can effectively democratize the development of state-of-the-art cybersecurity agents.

[Arxiv](https://arxiv.org/abs/2508.00910)