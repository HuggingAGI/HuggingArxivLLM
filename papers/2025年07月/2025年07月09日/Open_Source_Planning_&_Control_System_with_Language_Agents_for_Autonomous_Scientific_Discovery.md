# 基于语言代理的开源规划与控制系统，助力自主科学发现

发布时间：2025年07月09日

`Agent` `科学自动化`

> Open Source Planning & Control System with Language Agents for Autonomous Scientific Discovery

# 摘要

> 我们开发了一款名为 cmbagent 的多智能体系统，用于实现科学任务的自动化。该系统由约30个大型语言模型（LLM）智能体构成，采用规划与控制策略编排智能体工作流程，整个流程无需人工干预。每个智能体专注于不同任务，如检索科学论文和代码库、编写代码、解读结果、评估其他智能体的输出，且支持本地代码执行。我们成功将 cmbagent 应用于一项博士级别的宇宙学任务（利用超新星数据测量宇宙学参数），并在两个基准数据集上评估其性能，发现其表现优于当前最先进的 LLM。源代码可在 GitHub 上获取，演示视频也已发布，该系统已部署在 HuggingFace 并即将在云端上线。

> We present a multi-agent system for automation of scientific research tasks, cmbagent. The system is formed by about 30 Large Language Model (LLM) agents and implements a Planning & Control strategy to orchestrate the agentic workflow, with no human-in-the-loop at any point. Each agent specializes in a different task (performing retrieval on scientific papers and codebases, writing code, interpreting results, critiquing the output of other agents) and the system is able to execute code locally. We successfully apply cmbagent to carry out a PhD level cosmology task (the measurement of cosmological parameters using supernova data) and evaluate its performance on two benchmark sets, finding superior performance over state-of-the-art LLMs. The source code is available on GitHub, demonstration videos are also available, and the system is deployed on HuggingFace and will be available on the cloud.

[Arxiv](https://arxiv.org/abs/2507.07257)