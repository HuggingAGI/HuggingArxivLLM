# # 高效且有效的大型语言模型对齐方法

发布时间：2025年06月10日

`LLM理论` `人工智能`

> Towards Efficient and Effective Alignment of Large Language Models

# 摘要

> 大型语言模型（LLMs）在各类任务中表现卓越，但如何高效且有效地与人类期望保持一致仍是一项关键挑战。本论文通过创新的数据收集、训练和评估方法，推动了LLM对齐技术的发展。在数据收集方面，我们提出了Lion框架，通过对抗蒸馏方法迭代优化训练数据，显著提升了零样本推理能力。同时，我们开发了WebR框架，能够从原始网络文档中自动合成指令微调数据，大幅提升了数据多样性和可扩展性。在训练优化方面，我们开发了Learning to Edit（LTE）框架，使LLMs能够高效整合新知识同时保留现有信息。此外，我们改进了Direct Preference Optimization（DPO），提出了Bridging and Modeling Correlations（BMC），能够显式捕捉偏好数据中的令牌级相关性，显著提升了问答和数学推理任务的对齐效果。在评估方面，我们开发了FollowBench基准测试，用于评估LLMs在不同指令类型下遵循复杂约束的能力。我们的研究揭示了当前模型在约束遵守方面的关键弱点，为未来改进提供了重要参考。

> Large language models (LLMs) exhibit remarkable capabilities across diverse tasks, yet aligning them efficiently and effectively with human expectations remains a critical challenge. This thesis advances LLM alignment by introducing novel methodologies in data collection, training, and evaluation. We first address alignment data collection. Existing approaches rely heavily on manually curated datasets or proprietary models. To overcome these limitations, we propose Lion, an adversarial distillation framework that iteratively refines training data by identifying and generating challenging instructions, enabling state-of-the-art zero-shot reasoning. Additionally, we introduce Web Reconstruction (WebR), a fully automated framework that synthesizes instruction-tuning data directly from raw web documents, significantly improving data diversity and scalability over existing synthetic data methods. Next, we enhance alignment training through novel optimization techniques. We develop Learning to Edit (LTE), a framework that enables LLMs to efficiently integrate new knowledge while preserving existing information. LTE leverages meta-learning to improve both real-time and batch knowledge updates. Furthermore, we introduce Bridging and Modeling Correlations (BMC), a refinement of Direct Preference Optimization (DPO) that explicitly captures token-level correlations in preference data, leading to superior alignment across QA and mathematical reasoning tasks. Finally, we tackle the challenge of evaluating alignment. Existing benchmarks emphasize response quality but overlook adherence to specific constraints. To bridge this gap, we introduce FollowBench, a multi-level, fine-grained benchmark assessing LLMs' ability to follow complex constraints across diverse instruction types. Our results expose key weaknesses in current models' constraint adherence, offering insights for future improvements.

[Arxiv](https://arxiv.org/abs/2506.09329)