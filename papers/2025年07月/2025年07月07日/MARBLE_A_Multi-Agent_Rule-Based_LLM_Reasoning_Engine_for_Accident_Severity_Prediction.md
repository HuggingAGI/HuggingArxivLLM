# MARBLE：基于多智能体规则的LLM推理引擎，用于事故严重性预测

发布时间：2025年07月07日

`LLM应用` `人工智能`

> MARBLE: A Multi-Agent Rule-Based LLM Reasoning Engine for Accident Severity Prediction

# 摘要

> 事故严重性预测对交通安全系统至关重要，但因数据不完整、特征强依赖和类别严重失衡（罕见高严重性案例难以检测）而极具挑战性。现有方法多依赖单体模型或黑箱提示，难以在真实嘈杂环境中扩展，且解释性不足。为此，我们提出MARBLE——一种多智能体规则基LLM引擎，将严重性预测任务分解为多个专门推理智能体的协作，包括可互换的ML支持智能体。每个智能体专注于特定特征子集（如空间、环境、时间），实现模块化推理和提示，避免提示饱和风险。预测通过规则或LLM引导的共识机制协调，兼顾类别稀少性和置信度动态。系统保留智能体推理轨迹，支持深入解释和诊断。在英国和美国数据集上，MARBLE超越传统机器学习和先进提示方法（如CoT、L2M、ToT），准确率近90%，远超其他方法的48%上限。这重新定义了噪声和极端失衡下事故分类的实际性能。结果表明，MARBLE是安全关键应用中不确定性推理的通用可解释框架。

> Accident severity prediction plays a critical role in transportation safety systems but is a persistently difficult task due to incomplete data, strong feature dependencies, and severe class imbalance in which rare but high-severity cases are underrepresented and hard to detect. Existing methods often rely on monolithic models or black box prompting, which struggle to scale in noisy, real-world settings and offer limited interpretability. To address these challenges, we propose MARBLE a multiagent rule based LLM engine that decomposes the severity prediction task across a team of specialized reasoning agents, including an interchangeable ML-backed agent. Each agent focuses on a semantic subset of features (e.g., spatial, environmental, temporal), enabling scoped reasoning and modular prompting without the risk of prompt saturation. Predictions are coordinated through either rule-based or LLM-guided consensus mechanisms that account for class rarity and confidence dynamics. The system retains structured traces of agent-level reasoning and coordination outcomes, supporting in-depth interpretability and post-hoc performance diagnostics. Across both UK and US datasets, MARBLE consistently outperforms traditional machine learning classifiers and state-of-the-art (SOTA) prompt-based reasoning methods including Chain-of-Thought (CoT), Least-to-Most (L2M), and Tree-of-Thought (ToT) achieving nearly 90% accuracy where others plateau below 48%. This performance redefines the practical ceiling for accident severity classification under real world noise and extreme class imbalance. Our results position MARBLE as a generalizable and interpretable framework for reasoning under uncertainty in safety-critical applications.

[Arxiv](https://arxiv.org/abs/2507.04893)