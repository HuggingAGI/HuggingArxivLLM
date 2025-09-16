# 基于大型语言模型的时间序列推理与智能体系统综述

发布时间：2025年09月15日

`其他` `基础理论`

> A Survey of Reasoning and Agentic Systems in Time Series with Large Language Models

# 摘要

> 时间序列推理以时间为核心维度，将中间证据直接融入答案。本综述界定了这一问题，并基于推理拓扑结构将相关文献分为三类：一步直接推理、含显式中间步骤的线性链推理，以及用于探索、修正与聚合的分支结构推理。拓扑结构与该领域的核心目标相互交织，涵盖传统时间序列分析、解释与理解、因果推断与决策及时间序列生成；同时，一个紧凑的标签集覆盖这些维度，包含分解与验证、集成、工具使用、知识访问、多模态、智能体循环及LLM对齐机制。本文跨领域梳理了方法与系统，揭示了每种拓扑的能力边界以及在忠实性或鲁棒性上的短板，并提供了支持研究与部署的精选数据集、基准及资源（https://github.com/blacksnail789521/Time-Series-Reasoning-Survey）。重点介绍了保持证据可见性和时间对齐的评估方法，并提炼出以下指导原则：根据不确定性选择拓扑、通过可观测结果实现锚定、针对偏移和流数据场景进行规划、将成本与延迟纳入设计预算考量。我们认为，推理结构需在锚定与自修正能力、计算成本及可重复性之间取得平衡；未来的突破可能取决于将推理质量与实际效用关联的基准测试，以及在偏移感知、流数据和长期场景下权衡成本与风险的闭环测试平台。综上所述，这些方向标志着研究重心从狭隘的准确性转向大规模可靠性，助力构建不仅能分析，还能理解、解释动态世界并基于可追溯证据和可信结果采取行动的系统。

> Time series reasoning treats time as a first-class axis and incorporates intermediate evidence directly into the answer. This survey defines the problem and organizes the literature by reasoning topology with three families: direct reasoning in one step, linear chain reasoning with explicit intermediates, and branch-structured reasoning that explores, revises, and aggregates. The topology is crossed with the main objectives of the field, including traditional time series analysis, explanation and understanding, causal inference and decision making, and time series generation, while a compact tag set spans these axes and captures decomposition and verification, ensembling, tool use, knowledge access, multimodality, agent loops, and LLM alignment regimes. Methods and systems are reviewed across domains, showing what each topology enables and where it breaks down in faithfulness or robustness, along with curated datasets, benchmarks, and resources that support study and deployment (https://github.com/blacksnail789521/Time-Series-Reasoning-Survey). Evaluation practices that keep evidence visible and temporally aligned are highlighted, and guidance is distilled on matching topology to uncertainty, grounding with observable artifacts, planning for shift and streaming, and treating cost and latency as design budgets. We emphasize that reasoning structures must balance capacity for grounding and self-correction against computational cost and reproducibility, while future progress will likely depend on benchmarks that tie reasoning quality to utility and on closed-loop testbeds that trade off cost and risk under shift-aware, streaming, and long-horizon settings. Taken together, these directions mark a shift from narrow accuracy toward reliability at scale, enabling systems that not only analyze but also understand, explain, and act on dynamic worlds with traceable evidence and credible outcomes.

[Arxiv](https://arxiv.org/abs/2509.11575)