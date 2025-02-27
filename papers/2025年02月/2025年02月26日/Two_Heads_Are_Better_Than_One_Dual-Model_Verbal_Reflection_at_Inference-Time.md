# 两个头脑胜过一个：推理阶段的双模型语言反思

发布时间：2025年02月26日

`LLM应用` `人工智能` `模型优化`

> Two Heads Are Better Than One: Dual-Model Verbal Reflection at Inference-Time

# 摘要

> 在处理复杂推理场景时，大型语言模型（LLMs）常常面临挑战。偏好优化方法虽能通过训练提升推理性能，却难以解释为何偏好某一推理结果。言语反思技术虽增强了可解释性，但LLMs的自我批判与改进能力仍显不足。为应对这些挑战，我们提出了一种对比反思合成管道，旨在提升LLMs生成反思的准确性和深度。我们进一步在言语强化学习框架中引入了双模型推理方案，将推理过程中的自我反思分解为专门训练的批判与改进模型。实验结果表明，我们的方法在各项评估指标上均超越传统偏好优化方法。研究还证实，“双管齐下胜于单兵作战”——与单模型方法相比，协作的推理-批评模型在推理性能和透明度方面更具优势。

> Large Language Models (LLMs) often struggle with complex reasoning scenarios. While preference optimization methods enhance reasoning performance through training, they often lack transparency in why one reasoning outcome is preferred over another. Verbal reflection techniques improve explainability but are limited in LLMs' critique and refinement capacity. To address these challenges, we introduce a contrastive reflection synthesis pipeline that enhances the accuracy and depth of LLM-generated reflections. We further propose a dual-model reasoning framework within a verbal reinforcement learning paradigm, decoupling inference-time self-reflection into specialized, trained models for reasoning critique and refinement. Extensive experiments show that our framework outperforms traditional preference optimization methods across all evaluation metrics. Our findings also show that "two heads are better than one", demonstrating that a collaborative Reasoner-Critic model achieves superior reasoning performance and transparency, compared to single-model approaches.

[Arxiv](https://arxiv.org/abs/2502.19230)