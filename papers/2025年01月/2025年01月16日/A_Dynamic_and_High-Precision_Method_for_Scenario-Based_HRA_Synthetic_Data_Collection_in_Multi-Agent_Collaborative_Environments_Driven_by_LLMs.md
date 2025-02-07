# 一种动态高精度的场景化HRA合成数据收集方法，专为LLMs驱动的多智能体协作环境设计

发布时间：2025年01月16日

`LLM应用

解释：这篇论文摘要描述了一种基于微调大型语言模型（LLMs）的场景驱动工作负荷估计方法，用于自动化收集HRA数据。该方法通过在实际操作数据上训练LLMs，实时模拟人类行为和认知负荷，动态适应操作员工作负荷变化。这表明该研究主要关注LLM在实际应用中的使用，特别是在协作环境中测量工作负荷。因此，将其分类为“LLM应用”是合适的。` `人因工程`

> A Dynamic and High-Precision Method for Scenario-Based HRA Synthetic Data Collection in Multi-Agent Collaborative Environments Driven by LLMs

# 摘要

> HRA（人类可靠性分析）数据对推进HRA方法至关重要，但现有数据收集方法粒度不足，且大多无法捕捉动态特征。此外，许多方法依赖专家知识，耗时费力。为此，我们提出了一种自动化收集HRA数据的新范式，专注于人为错误的关键指标，特别是在协作环境中测量工作负荷。本研究引入了一种基于微调大型语言模型（LLMs）的场景驱动工作负荷估计方法。通过在高温气冷堆（HTGRs）的实际操作数据上训练LLMs，我们实时模拟了多种协作场景中的人类行为和认知负荷。该方法动态适应操作员工作负荷变化，提供更准确、灵活且可扩展的估计。结果表明，所提出的WELLA（基于LLMs和代理的工作负荷估计）在预测准确性上优于现有商业LLM方法。

> HRA (Human Reliability Analysis) data is crucial for advancing HRA methodologies. however, existing data collection methods lack the necessary granularity, and most approaches fail to capture dynamic features. Additionally, many methods require expert knowledge as input, making them time-consuming and labor-intensive. To address these challenges, we propose a new paradigm for the automated collection of HRA data. Our approach focuses on key indicators behind human error, specifically measuring workload in collaborative settings. This study introduces a novel, scenario-driven method for workload estimation, leveraging fine-tuned large language models (LLMs). By training LLMs on real-world operational data from high-temperature gas-cooled reactors (HTGRs), we simulate human behavior and cognitive load in real time across various collaborative scenarios. The method dynamically adapts to changes in operator workload, providing more accurate, flexible, and scalable workload estimates. The results demonstrate that the proposed WELLA (Workload Estimation with LLMs and Agents) outperforms existing commercial LLM-based methods in terms of prediction accuracy.

[Arxiv](https://arxiv.org/abs/2502.00022)