# WorkForceAgent-R1：利用强化学习提升基于LLM的网络代理的推理性能

发布时间：2025年05月28日

`LLM应用` `代理系统`

> WorkForceAgent-R1: Incentivizing Reasoning Capability in LLM-based Web Agents via Reinforcement Learning

# 摘要

> 大型语言模型（LLMs）赋能的网络代理能够实现企业环境中复杂、实时的网页导航任务自动化。然而，现有依赖监督微调（SFT）的网络代理在处理网页交互的动态本质时，往往因推理能力不足而面临泛化性和鲁棒性方面的挑战。本研究引入WorkForceAgent-R1，这是一种基于LLMs的网络代理，采用专为增强面向业务的网页导航任务的单步推理和规划能力而设计的基于规则的R1风格强化学习框架进行训练。我们采用了一种结构化的奖励函数，既评估输出格式的遵循度，也评估动作的正确性，使WorkForceAgent-R1能够隐式学习稳健的中间推理，而无需显式标注或大量专家演示。在WorkArena基准上的广泛实验表明，WorkForceAgent-R1在面向职场的网页导航任务中显著优于SFT基线，性能提升了10.26-16.59%，并达到了与专有LLM代理（如gpt-4o）相当的竞争力。

> Large language models (LLMs)-empowered web agents enables automating complex, real-time web navigation tasks in enterprise environments. However, existing web agents relying on supervised fine-tuning (SFT) often struggle with generalization and robustness due to insufficient reasoning capabilities when handling the inherently dynamic nature of web interactions. In this study, we introduce WorkForceAgent-R1, an LLM-based web agent trained using a rule-based R1-style reinforcement learning framework designed explicitly to enhance single-step reasoning and planning for business-oriented web navigation tasks. We employ a structured reward function that evaluates both adherence to output formats and correctness of actions, enabling WorkForceAgent-R1 to implicitly learn robust intermediate reasoning without explicit annotations or extensive expert demonstrations. Extensive experiments on the WorkArena benchmark demonstrate that WorkForceAgent-R1 substantially outperforms SFT baselines by 10.26-16.59%, achieving competitive performance relative to proprietary LLM-based agents (gpt-4o) in workplace-oriented web navigation tasks.

[Arxiv](https://arxiv.org/abs/2505.22942)