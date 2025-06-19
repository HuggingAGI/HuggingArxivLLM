# HeurAgenix: 利用大型语言模型的强大能力应对复杂组合优化难题

发布时间：2025年06月18日

`LLM应用

理由：这篇论文展示了如何将大型语言模型（LLMs）应用于组合优化问题，提出了一种两阶段的超启发式框架HeurAgenix。它利用LLMs来进化启发式算法，并动态选择最优方案，属于LLM在特定任务中的应用。` `组合优化` `运筹学`

> HeurAgenix: Leveraging LLMs for Solving Complex Combinatorial Optimization Challenges

# 摘要

> 启发式算法在组合优化（CO）问题中至关重要，但传统设计依赖人工专业知识，难以泛化。我们提出	extbf{HeurAgenix}，一个由LLMs驱动的两阶段超启发式框架，先进化启发式算法，再自动选择最优方案。在进化阶段，HeurAgenix利用LLM对比种子启发式与更优解，提取可复用策略。在求解阶段，它基于LLM的感知能力，动态选择最适合当前状态的启发式方法。为提高灵活性，选择器可选先进LLM或轻量级微调模型，以降低推理成本。针对CO复杂性导致的监督信号不足，我们采用双奖励机制微调选择器，结合选择偏好和状态感知信号，在噪声标注下实现稳健选择。实验表明，HeurAgenix不仅超越现有LLM基超启发式方法，还与专用求解器相匹敌。代码已开源：https://github.com/microsoft/HeurAgenix。

> Heuristic algorithms play a vital role in solving combinatorial optimization (CO) problems, yet traditional designs depend heavily on manual expertise and struggle to generalize across diverse instances. We introduce \textbf{HeurAgenix}, a two-stage hyper-heuristic framework powered by large language models (LLMs) that first evolves heuristics and then selects among them automatically. In the heuristic evolution phase, HeurAgenix leverages an LLM to compare seed heuristic solutions with higher-quality solutions and extract reusable evolution strategies. During problem solving, it dynamically picks the most promising heuristic for each problem state, guided by the LLM's perception ability. For flexibility, this selector can be either a state-of-the-art LLM or a fine-tuned lightweight model with lower inference cost. To mitigate the scarcity of reliable supervision caused by CO complexity, we fine-tune the lightweight heuristic selector with a dual-reward mechanism that jointly exploits singals from selection preferences and state perception, enabling robust selection under noisy annotations. Extensive experiments on canonical benchmarks show that HeurAgenix not only outperforms existing LLM-based hyper-heuristics but also matches or exceeds specialized solvers. Code is available at https://github.com/microsoft/HeurAgenix.

[Arxiv](https://arxiv.org/abs/2506.15196)