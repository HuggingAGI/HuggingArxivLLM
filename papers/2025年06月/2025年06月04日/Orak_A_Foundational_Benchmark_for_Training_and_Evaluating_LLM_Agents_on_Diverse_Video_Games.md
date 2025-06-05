# Orak：专为多种视频游戏打造的LLM代理训练与评估基础基准

发布时间：2025年06月04日

`LLM应用` `智能体`

> Orak: A Foundational Benchmark for Training and Evaluating LLM Agents on Diverse Video Games

# 摘要

> 大型语言模型（LLM）智能体正在重塑游戏行业，尤其是通过更加智能和符合人类偏好的游戏角色。然而，现有游戏基准存在不足：它们未能全面评估LLM在不同游戏类型中的多样化能力，也未深入研究复杂游戏玩法中至关重要的智能体模块，更缺乏用于将预训练LLM调整为游戏智能体的微调数据集。为解决这些问题，我们推出	extbf{enchname{}}, 一个专注于训练和评估跨多种现实世界视频游戏的LLM智能体的基础基准。与现有基准不同，Orak收录了涵盖所有主要游戏类型的12款热门视频游戏，为研究LLM能力和复杂游戏场景中不可或缺的智能体模块提供了全面支持。为了确保对LLM的一致评估，我们开发了一个基于模型上下文协议（MCP）的即插即用接口，使LLM能够无缝连接游戏并操作智能体模块。此外，我们还提出了一种微调数据集，包含跨多种游戏类型的LLM游戏轨迹。Orak提供了一个全面的评估框架，包括通用游戏得分排行榜、LLM竞技场以及对视觉输入状态、智能体策略和微调效果的深入分析，为构建通用游戏智能体奠定了坚实基础。代码可在https://github.com/krafton-ai/Orak获取。

> Large Language Model (LLM) agents are reshaping the game industry, particularly with more intelligent and human-preferable game characters. However, existing game benchmarks fall short of practical needs: they lack evaluations of diverse LLM capabilities across various game genres, studies of agentic modules crucial for complex gameplay, and fine-tuning datasets for aligning pre-trained LLMs into gaming agents. To fill these gaps, we present \textbf{\benchname{}}, a foundational benchmark designed to train and evaluate LLM agents across diverse real-world video games. Unlike existing benchmarks, Orak includes 12 popular video games spanning all major genres, enabling comprehensive studies of LLM capabilities and agentic modules essential for intricate game scenarios. To support consistent evaluation of LLMs, we introduce a plug-and-play interface based on Model Context Protocol (MCP) that enables LLMs to seamlessly connect with games and manipulate agentic modules. Additionally, we propose a fine-tuning dataset, consisting of LLM gameplay trajectories across diverse game genres. Orak offers a comprehensive evaluation framework, encompassing general game score leaderboards, LLM battle arenas, and in-depth analyses of visual input state, agentic strategies, and fine-tuning effects, establishing a foundation towards building generic gaming agents. Code is available at https://github.com/krafton-ai/Orak.

[Arxiv](https://arxiv.org/abs/2506.03610)