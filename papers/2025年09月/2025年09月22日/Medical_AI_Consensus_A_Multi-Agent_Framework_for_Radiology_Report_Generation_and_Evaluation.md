# # Medical AI Consensus: A Multi-Agent Framework for Radiology Report Generation and Evaluation
医疗AI共识：面向放射学报告生成与评估的多智能体框架

发布时间：2025年09月22日

`Agent` `医疗健康`

> Medical AI Consensus: A Multi-Agent Framework for Radiology Report Generation and Evaluation

# 摘要

> 放射科报告的自动化生成面临双重挑战：既要构建临床可靠的系统，又要设计严谨的评估方案。为此，我们提出了一个多智能体强化学习框架，它既是放射科生态系统中多模态临床推理的基准，也是评估环境。该框架采用模块化架构，集成了大型语言模型（LLMs）与大型视觉模型（LVMs），并包含十个专用智能体，分别负责图像分析、特征提取、报告生成、审查及评估。这种设计支持在智能体层面（如检测与分割精度）和共识层面（如报告质量与临床相关性）进行精细化评估。我们在公共放射科数据集上基于chatGPT-4o进行了实践验证，LLMs在此过程中与放射科医生的反馈共同承担评估任务。通过将评估方案与LLM的开发生命周期（涵盖预训练、微调、对齐和部署阶段）相匹配，该基准为构建可信的偏差驱动型放射科报告生成系统指明了方向。

> Automating radiology report generation poses a dual challenge: building clinically reliable systems and designing rigorous evaluation protocols. We introduce a multi-agent reinforcement learning framework that serves as both a benchmark and evaluation environment for multimodal clinical reasoning in the radiology ecosystem. The proposed framework integrates large language models (LLMs) and large vision models (LVMs) within a modular architecture composed of ten specialized agents responsible for image analysis, feature extraction, report generation, review, and evaluation. This design enables fine-grained assessment at both the agent level (e.g., detection and segmentation accuracy) and the consensus level (e.g., report quality and clinical relevance). We demonstrate an implementation using chatGPT-4o on public radiology datasets, where LLMs act as evaluators alongside medical radiologist feedback. By aligning evaluation protocols with the LLM development lifecycle, including pretraining, finetuning, alignment, and deployment, the proposed benchmark establishes a path toward trustworthy deviance-based radiology report generation.

[Arxiv](https://arxiv.org/abs/2509.17353)