# DiaLLMs: 基于EHR的临床对话系统，助力临床测试推荐与诊断预测

发布时间：2025年06月24日

`LLM应用` `临床决策支持`

> DiaLLMs: EHR Enhanced Clinical Conversational System for Clinical Test Recommendation and Diagnosis Prediction

# 摘要

> 大型语言模型（LLMs）的最新进展为医疗咨询带来了显著突破。然而，现有医疗LLMs忽视了电子健康记录（EHR）的关键作用，主要聚焦于诊断推荐，限制了其临床应用。我们提出DiaLLM，首个将异质性电子健康记录数据整合到临床对话中的医疗LLM，实现临床检查推荐、检查结果解读和诊断预测，使其更贴近真实医疗实践。为从EHR构建基于临床的对话，我们设计了一种临床检查参考（CTR）策略，将每个临床代码映射到其对应描述，并将检查结果分类为“正常”或“异常”。此外，DiaLLM采用强化学习框架进行证据获取和自动化诊断。为应对较大的动作空间，我们引入拒绝采样策略以减少冗余并提高探索效率。此外，我们设计了确认奖励和类别敏感诊断奖励，以指导准确的诊断预测。大量实验结果表明，DiaLLM在临床检查推荐和诊断预测方面优于基线模型。

> Recent advances in Large Language Models (LLMs) have led to remarkable progresses in medical consultation. However, existing medical LLMs overlook the essential role of Electronic Health Records (EHR) and focus primarily on diagnosis recommendation, limiting their clinical applicability. We propose DiaLLM, the first medical LLM that integrates heterogeneous EHR data into clinically grounded dialogues, enabling clinical test recommendation, result interpretation, and diagnosis prediction to better align with real-world medical practice. To construct clinically grounded dialogues from EHR, we design a Clinical Test Reference (CTR) strategy that maps each clinical code to its corresponding description and classifies test results as "normal" or "abnormal". Additionally, DiaLLM employs a reinforcement learning framework for evidence acquisition and automated diagnosis. To handle the large action space, we introduce a reject sampling strategy to reduce redundancy and improve exploration efficiency. Furthermore, a confirmation reward and a class-sensitive diagnosis reward are designed to guide accurate diagnosis prediction. Extensive experimental results demonstrate that DiaLLM outperforms baselines in clinical test recommendation and diagnosis prediction.

[Arxiv](https://arxiv.org/abs/2506.20059)