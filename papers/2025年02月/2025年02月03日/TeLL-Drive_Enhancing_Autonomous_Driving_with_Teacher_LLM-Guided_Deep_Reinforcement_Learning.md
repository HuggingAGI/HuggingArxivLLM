# TeLL-Drive：利用教师LLM引导的深度强化学习提升自动驾驶性能

发布时间：2025年02月03日

`Agent

**理由**：这篇论文提出了一个混合框架TeLL-Drive，结合了大型语言模型（LLM）和深度强化学习（DRL）来提升自动驾驶决策的性能。该框架通过LLM生成高级驾驶策略，并通过DRL代理进行实时决策，属于智能体（Agent）的研究范畴，特别是涉及多模态智能体的设计与优化。因此，将其分类为Agent是合适的。` `自动驾驶`

> TeLL-Drive: Enhancing Autonomous Driving with Teacher LLM-Guided Deep Reinforcement Learning

# 摘要

> 尽管深度强化学习（DRL）和大型语言模型（LLMs）在自动驾驶决策中各有优势，但DRL常受高样本复杂性困扰，而LLMs则难以实现实时决策。为此，我们提出了TeLL-Drive，一个融合教师LLM与基于注意力的学生DRL策略的混合框架。通过将风险指标、历史场景检索和领域启发式方法融入上下文提示，LLM通过链式思维推理生成高级驾驶策略。自注意力机制随后将这些策略与DRL代理的探索结合，加速策略收敛并提升在各种驾驶条件下的鲁棒性。我们在多个交通场景下的实验表明，TeLL-Drive在成功率、平均回报和实时可行性上均优于现有基线方法，包括其他基于LLM的方案。消融研究揭示了各模型组件的重要性，尤其是注意力机制与LLM指导的协同效应。这些发现表明，TeLL-Drive显著提升了自动驾驶系统的适应性和安全性，同时为策略学习提供了更高效、可扩展的解决方案。完整验证结果请访问我们的网站。

> Although Deep Reinforcement Learning (DRL) and Large Language Models (LLMs) each show promise in addressing decision-making challenges in autonomous driving, DRL often suffers from high sample complexity, while LLMs have difficulty ensuring real-time decision making. To address these limitations, we propose TeLL-Drive, a hybrid framework that integrates an Teacher LLM to guide an attention-based Student DRL policy. By incorporating risk metrics, historical scenario retrieval, and domain heuristics into context-rich prompts, the LLM produces high-level driving strategies through chain-of-thought reasoning. A self-attention mechanism then fuses these strategies with the DRL agent's exploration, accelerating policy convergence and boosting robustness across diverse driving conditions. Our experimental results, evaluated across multiple traffic scenarios, show that TeLL-Drive outperforms existing baseline methods, including other LLM-based approaches, in terms of success rates, average returns, and real-time feasibility. Ablation studies underscore the importance of each model component, especially the synergy between the attention mechanism and LLM-driven guidance. These findings suggest that TeLL-Drive significantly enhances both the adaptability and safety of autonomous driving systems, while offering a more efficient and scalable approach for policy learning. Full validation results are available on our website.

[Arxiv](https://arxiv.org/abs/2502.01387)