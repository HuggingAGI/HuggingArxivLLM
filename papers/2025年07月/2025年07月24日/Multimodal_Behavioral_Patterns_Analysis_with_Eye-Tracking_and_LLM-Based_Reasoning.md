# 融合眼动追踪与LLM推理的多模态行为分析

发布时间：2025年07月24日

`LLM应用

论文摘要：眼动追踪数据揭示了用户认知状态的宝贵见解，但其结构化和非语言的特性使分析颇具挑战。大型语言模型（LLMs）虽擅长文本推理，却在时间序列和数值数据处理上表现欠佳。本文提出了一种多模态人机协作框架，旨在提升从眼动信号中提取认知模式的能力。该框架包含三个核心组件：（1）一个多阶段流水线，结合水平和垂直分割技术与LLM推理，揭示潜在的注视模式；（2）一个专家-模型联合评分模块，整合专家判断与LLM输出，为行为解释生成信任评分；（3）一个混合异常检测模块，结合基于LSTM的时间建模与LLM驱动的语义分析。我们的实验结果表明，该框架在多种LLMs和提示策略下，一致性、可解释性和性能均显著提升，其中难度预测任务的准确率最高可达50%。这一方法为认知建模提供了可扩展且可解释的解决方案，并在自适应学习、人机交互和教育分析领域具有广泛应用潜力。` `认知科学` `教育科技`

> Multimodal Behavioral Patterns Analysis with Eye-Tracking and LLM-Based Reasoning

# 摘要

> 眼动追踪数据揭示了用户认知状态的宝贵见解，但其结构化和非语言的特性使分析颇具挑战。大型语言模型（LLMs）虽擅长文本推理，却在时间序列和数值数据处理上表现欠佳。本文提出了一种多模态人机协作框架，旨在提升从眼动信号中提取认知模式的能力。该框架包含三个核心组件：（1）一个多阶段流水线，结合水平和垂直分割技术与LLM推理，揭示潜在的注视模式；（2）一个专家-模型联合评分模块，整合专家判断与LLM输出，为行为解释生成信任评分；（3）一个混合异常检测模块，结合基于LSTM的时间建模与LLM驱动的语义分析。我们的实验结果表明，该框架在多种LLMs和提示策略下，一致性、可解释性和性能均显著提升，其中难度预测任务的准确率最高可达50%。这一方法为认知建模提供了可扩展且可解释的解决方案，并在自适应学习、人机交互和教育分析领域具有广泛应用潜力。

> Eye-tracking data reveals valuable insights into users' cognitive states but is difficult to analyze due to its structured, non-linguistic nature. While large language models (LLMs) excel at reasoning over text, they struggle with temporal and numerical data. This paper presents a multimodal human-AI collaborative framework designed to enhance cognitive pattern extraction from eye-tracking signals. The framework includes: (1) a multi-stage pipeline using horizontal and vertical segmentation alongside LLM reasoning to uncover latent gaze patterns; (2) an Expert-Model Co-Scoring Module that integrates expert judgment with LLM output to generate trust scores for behavioral interpretations; and (3) a hybrid anomaly detection module combining LSTM-based temporal modeling with LLM-driven semantic analysis. Our results across several LLMs and prompt strategies show improvements in consistency, interpretability, and performance, with up to 50% accuracy in difficulty prediction tasks. This approach offers a scalable, interpretable solution for cognitive modeling and has broad potential in adaptive learning, human-computer interaction, and educational analytics.

[Arxiv](https://arxiv.org/abs/2507.18252)