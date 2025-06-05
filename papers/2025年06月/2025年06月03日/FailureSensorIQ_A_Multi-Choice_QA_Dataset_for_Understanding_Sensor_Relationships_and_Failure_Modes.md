# FailureSensorIQ：一个理解传感器关系与故障模式的多选问答数据集

发布时间：2025年06月03日

`LLM应用` `故障诊断`

> FailureSensorIQ: A Multi-Choice QA Dataset for Understanding Sensor Relationships and Failure Modes

# 摘要

> 我们很高兴推出 FailureSensorIQ，一个创新的多选问答（MCQA）基准测试系统，专注于评估大型语言模型（LLMs）在工业4.0复杂场景下的推理与理解能力。与传统问答系统不同，FailureSensorIQ不仅关注单一问题，还深入分析故障模式、传感器数据及其相互关系，全面评估模型在不同工业资产中的推理表现。

通过 FailureSensorIQ，我们希望推动建模决策的范式转变：不仅要依靠统计工具（如相关性分析和显著性测试）驱动的数据，更要结合专业化的LLMs进行领域知识驱动的推理，帮助识别关键影响因素和潜在模式。

我们对包括GPT-4、Llama和Mistral在内的十余种LLMs进行了全面评估，采用了多种评测方法：扰动-不确定性-复杂性分析、专家评估、资产特定知识缺口分析，以及结合外部知识库的ReAct代理。尽管部分闭源模型表现接近专家水平，但基准测试结果显示，这些模型在面对扰动、干扰和知识缺口时表现脆弱，性能显著下降。

此外，我们还通过真实案例展示了LLMs在三个不同故障预测数据集中的应用价值。我们开放了以下资源：(a) 专家策划的多选题集，涵盖多种工业资产；(b) 基于ISO文档非文本数据构建的FailureSensorIQ基准测试及Hugging Face排行榜；(c) LLMFeatureSelector——一个基于LLM的特征选择scikit-learn工具包。欢迎访问https://github.com/IBM/FailureSensorIQ获取更多信息。

> We introduce FailureSensorIQ, a novel Multi-Choice Question-Answering (MCQA) benchmarking system designed to assess the ability of Large Language Models (LLMs) to reason and understand complex, domain-specific scenarios in Industry 4.0. Unlike traditional QA benchmarks, our system focuses on multiple aspects of reasoning through failure modes, sensor data, and the relationships between them across various industrial assets. Through this work, we envision a paradigm shift where modeling decisions are not only data-driven using statistical tools like correlation analysis and significance tests, but also domain-driven by specialized LLMs which can reason about the key contributors and useful patterns that can be captured with feature engineering. We evaluate the Industrial knowledge of over a dozen LLMs-including GPT-4, Llama, and Mistral-on FailureSensorIQ from different lens using Perturbation-Uncertainty-Complexity analysis, Expert Evaluation study, Asset-Specific Knowledge Gap analysis, ReAct agent using external knowledge-bases. Even though closed-source models with strong reasoning capabilities approach expert-level performance, the comprehensive benchmark reveals a significant drop in performance that is fragile to perturbations, distractions, and inherent knowledge gaps in the models. We also provide a real-world case study of how LLMs can drive the modeling decisions on 3 different failure prediction datasets related to various assets. We release: (a) expert-curated MCQA for various industrial assets, (b) FailureSensorIQ benchmark and Hugging Face leaderboard based on MCQA built from non-textual data found in ISO documents, and (c) LLMFeatureSelector, an LLM-based feature selection scikit-learn pipeline. The software is available at https://github.com/IBM/FailureSensorIQ.

[Arxiv](https://arxiv.org/abs/2506.03278)