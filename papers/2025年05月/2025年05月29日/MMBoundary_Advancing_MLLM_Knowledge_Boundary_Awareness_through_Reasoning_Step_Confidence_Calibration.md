# MMBoundary：通过推理步骤置信度校准提升MLLM知识边界意识

发布时间：2025年05月29日

`LLM应用` `人工智能` `多模态推理`

> MMBoundary: Advancing MLLM Knowledge Boundary Awareness through Reasoning Step Confidence Calibration

# 摘要

> 近年来，多模态大型语言模型 (MLLMs) 在多模态推理领域取得了显著进展，但仍然面临多层级（如感知、推理）和多粒度（如多步推理链）推理中的固有挑战。现有的模型置信度评估方法多关注整体响应的训练与校准，却忽视了对每个推理步骤置信度的细致评估，导致幻觉效应的累积。针对这一问题，我们提出了 MMBoundary，一个通过推理步骤置信度校准来拓展 MLLMs 知识边界意识的创新框架。为了实现这一目标，我们提出整合互补的文本和跨模态自奖励信号，从而在每一步推理过程中精准估计 MLLM 的置信度。除了在自奖励置信度估计信号集上对 MLLM 进行监督微调以预热初始置信度表达外，我们还引入了一个带有多个奖励函数的强化学习阶段，以进一步对齐模型知识并校准每一步推理的置信度，从而增强推理链的自我修正能力。实证结果表明，MMBoundary 在多样化领域数据集和指标上显著超越现有方法，实现了多模态置信度校准误差平均降低 7.5%，任务性能提升最高达 8.3%。

> In recent years, multimodal large language models (MLLMs) have made significant progress but continue to face inherent challenges in multimodal reasoning, which requires multi-level (e.g., perception, reasoning) and multi-granular (e.g., multi-step reasoning chain) advanced inferencing. Prior work on estimating model confidence tends to focus on the overall response for training and calibration, but fails to assess confidence in each reasoning step, leading to undesirable hallucination snowballing. In this work, we present MMBoundary, a novel framework that advances the knowledge boundary awareness of MLLMs through reasoning step confidence calibration. To achieve this, we propose to incorporate complementary textual and cross-modal self-rewarding signals to estimate confidence at each step of the MLLM reasoning process. In addition to supervised fine-tuning MLLM on this set of self-rewarded confidence estimation signal for initial confidence expression warm-up, we introduce a reinforcement learning stage with multiple reward functions for further aligning model knowledge and calibrating confidence at each reasoning step, enhancing reasoning chain self-correction. Empirical results show that MMBoundary significantly outperforms existing methods across diverse domain datasets and metrics, achieving an average of 7.5% reduction in multimodal confidence calibration errors and up to 8.3% improvement in task performance.

[Arxiv](https://arxiv.org/abs/2505.23224)