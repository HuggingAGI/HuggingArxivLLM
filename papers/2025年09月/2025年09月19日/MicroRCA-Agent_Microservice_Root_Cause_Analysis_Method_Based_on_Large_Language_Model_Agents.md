# MicroRCA-Agent：基于大型语言模型智能体的微服务根因分析方法

发布时间：2025年09月19日

`Agent` `工业与制造`

> MicroRCA-Agent: Microservice Root Cause Analysis Method Based on Large Language Model Agents

# 摘要

> 本文提出了MicroRCA-Agent——一种基于大型语言模型智能体的微服务根因分析创新方案，它构建了一个融合多模态数据的智能故障根因定位系统。其技术创新体现在三个核心方面：第一，我们将预训练的Drain日志解析算法与多级数据过滤机制相结合，高效地将海量日志压缩为高质量故障特征；第二，我们采用双异常检测方法，将孤立森林无监督学习算法与状态码验证相融合，实现了全面的追踪异常识别；第三，我们设计了统计对称比过滤机制，并结合两阶段LLM分析策略，完成了跨节点-服务-容器（pod）层级的全栈现象总结。多模态根因分析模块通过精心设计的跨模态提示词深度融合多模态异常信息，充分发挥大型语言模型的跨模态理解与逻辑推理能力，生成包含故障组件、根因描述及推理轨迹的结构化分析结果。全面的消融实验验证了各模态数据的互补价值和系统架构的有效性。该方案在复杂微服务故障场景中表现优异，最终得分为50.71。代码已发布于：https://github.com/tangpan360/MicroRCA-Agent。

> This paper presents MicroRCA-Agent, an innovative solution for microservice root cause analysis based on large language model agents, which constructs an intelligent fault root cause localization system with multimodal data fusion. The technical innovations are embodied in three key aspects: First, we combine the pre-trained Drain log parsing algorithm with multi-level data filtering mechanism to efficiently compress massive logs into high-quality fault features. Second, we employ a dual anomaly detection approach that integrates Isolation Forest unsupervised learning algorithms with status code validation to achieve comprehensive trace anomaly identification. Third, we design a statistical symmetry ratio filtering mechanism coupled with a two-stage LLM analysis strategy to enable full-stack phenomenon summarization across node-service-pod hierarchies. The multimodal root cause analysis module leverages carefully designed cross-modal prompts to deeply integrate multimodal anomaly information, fully exploiting the cross-modal understanding and logical reasoning capabilities of large language models to generate structured analysis results encompassing fault components, root cause descriptions, and reasoning trace. Comprehensive ablation studies validate the complementary value of each modal data and the effectiveness of the system architecture. The proposed solution demonstrates superior performance in complex microservice fault scenarios, achieving a final score of 50.71. The code has been released at: https://github.com/tangpan360/MicroRCA-Agent.

[Arxiv](https://arxiv.org/abs/2509.15635)