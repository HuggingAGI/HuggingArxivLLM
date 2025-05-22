# 探究强化学习在推理与搜索交织的LLM代理中的应用效果

发布时间：2025年05月21日

`Agent` `智能体`

> An Empirical Study on Reinforcement Learning for Reasoning-Search Interleaved LLM Agents

# 摘要

> 强化学习（RL）在训练具备复杂推理能力的大型语言模型（LLMs）方面展现出强大的潜力，尤其在解决实际问题上表现突出。近期，RL被用于打造结合推理与搜索引擎使用的复杂智能体，这些智能体在处理信息时展现出色的综合能力。然而，尽管RL在训练搜索智能体方面前景光明，但如何设计最优智能体仍是一个未解之谜。其中，奖励函数设计、LLM的选择与特性，以及搜索引擎在RL中的角色，是亟待深入探索的关键因素。本研究通过全面的实证分析，系统性地揭示了这些因素的影响，并为实践提供了切实可行的指导。我们的研究发现：格式化奖励对提升最终性能尤为有效，而中间检索奖励的作用相对有限；LLM的规模和初始化方式（通用型与推理专用型）显著影响RL结果；搜索引擎的选择对训练过程的动力学特性和智能体推理时的鲁棒性起着决定性作用。这些发现为在实际应用中成功构建和部署LLM驱动的搜索智能体提供了重要指导。相关代码已开源，可在https://github.com/PeterGriffinJin/Search-R1获取。

> Reinforcement learning (RL) has demonstrated strong potential in training large language models (LLMs) capable of complex reasoning for real-world problem solving. More recently, RL has been leveraged to create sophisticated LLM-based search agents that adeptly combine reasoning with search engine use. While the use of RL for training search agents is promising, the optimal design of such agents remains not fully understood. In particular, key factors -- such as (1) reward formulation, (2) the choice and characteristics of the underlying LLM, and (3) the role of the search engine in the RL process -- require further investigation. In this work, we conduct comprehensive empirical studies to systematically investigate these and offer actionable insights. We highlight several key findings: format rewards are effective in improving final performance, whereas intermediate retrieval rewards have limited impact; the scale and initialization of the LLM (general-purpose vs. reasoning-specialized) significantly influence RL outcomes; and the choice of search engine plays a critical role in shaping RL training dynamics and the robustness of the trained agent during inference. These establish important guidelines for successfully building and deploying LLM-based search agents in real-world applications. Code is available at https://github.com/PeterGriffinJin/Search-R1.

[Arxiv](https://arxiv.org/abs/2505.15117)