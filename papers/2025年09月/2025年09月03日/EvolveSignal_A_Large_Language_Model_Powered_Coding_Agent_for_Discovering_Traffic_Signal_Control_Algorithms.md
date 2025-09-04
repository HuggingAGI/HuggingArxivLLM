# EvolveSignal：基于大型语言模型的交通信号控制算法发现编码智能体

发布时间：2025年09月03日

`Agent` `交通运输`

> EvolveSignal: A Large Language Model Powered Coding Agent for Discovering Traffic Signal Control Algorithms

# 摘要

> 在交通工程领域，固定配时交通信号控制凭借成本低廉、运行稳定且易于解释的优势，至今仍被广泛应用。但它的设计依赖人工推导的公式（如Webster公式），且需工程师手动重新配时以适应交通需求变化——这种方式不仅耗费大量人力，在交通流异构或拥堵的情况下还常导致控制效果欠佳。为此，本文提出了EvolveSignal——一个由大型语言模型（LLMs）驱动的编码智能体，旨在自动发现全新的交通信号控制算法。我们将该问题建模为程序合成任务：候选算法被表示为输入输出结构固定的Python函数，通过外部评估（如交通模拟器）与进化搜索进行迭代优化。在信号控制交叉口的实验显示，新算法性能超越Webster基准，平均延误降低20.1%，平均停车次数减少47.1%。值得注意的是，消融与增量分析表明，EvolveSignal的改进设计（如调整周期长度范围、考虑右转需求、优化绿灯分配比例等），能为交通工程师提供具有实际应用价值的见解。这项研究通过AI赋能交通信号控制算法设计，架起了程序合成与交通工程领域的桥梁，开辟了全新的研究方向。

> In traffic engineering, the fixed-time traffic signal control remains widely used for its low cost, stability, and interpretability. However, its design depends on hand-crafted formulas (e.g., Webster) and manual re-timing by engineers to adapt to demand changes, which is labor-intensive and often yields suboptimal results under heterogeneous or congested conditions. This paper introduces the EvolveSignal, a large language models (LLMs) powered coding agent to automatically discover new traffic signal control algorithms. We formulate the problem as program synthesis, where candidate algorithms are represented as Python functions with fixed input-output structures, and iteratively optimized through external evaluations (e.g., a traffic simulator) and evolutionary search. Experiments on a signalized intersection demonstrate that the discovered algorithms outperform Webster's baseline, reducing average delay by 20.1% and average stops by 47.1%. Beyond performance, ablation and incremental analyses reveal that EvolveSignal modifications-such as adjusting cycle length bounds, incorporating right-turn demand, and rescaling green allocations-can offer practically meaningful insights for traffic engineers. This work opens a new research direction by leveraging AI for algorithm design in traffic signal control, bridging program synthesis with transportation engineering.

[Arxiv](https://arxiv.org/abs/2509.03335)