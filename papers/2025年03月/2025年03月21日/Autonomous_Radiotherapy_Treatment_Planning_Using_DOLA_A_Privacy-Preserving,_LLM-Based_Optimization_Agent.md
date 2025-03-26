# # 自主放射治疗计划制定：基于DOLA的隐私保护LLM优化代理

发布时间：2025年03月21日

`Agent` `放射治疗`

> Autonomous Radiotherapy Treatment Planning Using DOLA: A Privacy-Preserving, LLM-Based Optimization Agent

# 摘要

> 放射治疗计划是一个复杂且耗时的过程，常受制于规划者之间的差异性和主观决策。为了解决这些问题，我们引入了剂量优化语言代理（DOLA），这是一个基于大型语言模型（LLM）的自主代理，旨在优化放射治疗计划的同时严格保护患者隐私。DOLA将LLaMa3.1 LLM直接集成到商业治疗计划系统中，采用链式思维提示、检索增强生成（RAG）和强化学习（RL）。该代理完全在安全的本地基础设施内运行，从而避免了外部数据共享。我们使用18名接受60 Gy分20次放疗的前列腺癌患者的回顾性队列对DOLA进行了评估，比较了不同模型规模（80亿 vs. 700亿参数）和优化策略（无RAG、RAG和RAG+RL）在10次规划迭代中的表现。700B模型表现出显著更优的性能，最终得分比80B模型高出约16.4%。RAG方法比无RAG基线高出19.8%，而加入RL加速了收敛，突显了基于检索的记忆与强化学习的协同作用。最优温度超参数分析发现，0.4在探索与开发之间提供了最佳平衡。这项概念验证研究代表了首个成功部署本地托管的LLM代理，用于商业放射治疗计划系统中治疗计划的自主优化。通过借助可解释的自然语言推理扩展人机交互，DOLA提供了一个可扩展且注重隐私的框架，在临床实施和工作流程改进方面具有巨大潜力。

> Radiotherapy treatment planning is a complex and time-intensive process, often impacted by inter-planner variability and subjective decision-making. To address these challenges, we introduce Dose Optimization Language Agent (DOLA), an autonomous large language model (LLM)-based agent designed for optimizing radiotherapy treatment plans while rigorously protecting patient privacy. DOLA integrates the LLaMa3.1 LLM directly with a commercial treatment planning system, utilizing chain-of-thought prompting, retrieval-augmented generation (RAG), and reinforcement learning (RL). Operating entirely within secure local infrastructure, this agent eliminates external data sharing. We evaluated DOLA using a retrospective cohort of 18 prostate cancer patients prescribed 60 Gy in 20 fractions, comparing model sizes (8 billion vs. 70 billion parameters) and optimization strategies (No-RAG, RAG, and RAG+RL) over 10 planning iterations. The 70B model demonstrated significantly improved performance, achieving approximately 16.4% higher final scores than the 8B model. The RAG approach outperformed the No-RAG baseline by 19.8%, and incorporating RL accelerated convergence, highlighting the synergy of retrieval-based memory and reinforcement learning. Optimal temperature hyperparameter analysis identified 0.4 as providing the best balance between exploration and exploitation. This proof of concept study represents the first successful deployment of locally hosted LLM agents for autonomous optimization of treatment plans within a commercial radiotherapy planning system. By extending human-machine interaction through interpretable natural language reasoning, DOLA offers a scalable and privacy-conscious framework, with significant potential for clinical implementation and workflow improvement.

[Arxiv](https://arxiv.org/abs/2503.17553)