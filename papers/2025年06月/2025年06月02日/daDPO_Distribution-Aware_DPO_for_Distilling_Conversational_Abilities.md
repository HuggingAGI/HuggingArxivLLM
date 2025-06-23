# daDPO：基于分布感知的对话能力蒸馏方法

发布时间：2025年06月02日

`LLM应用` `对话系统`

> daDPO: Distribution-Aware DPO for Distilling Conversational Abilities

# 摘要

> 大型语言模型（LLMs）在各类应用中表现优异，但模型规模的缩小会导致对话能力显著下降，这对资源受限环境中的部署构成了挑战。基于直接偏好优化的知识蒸馏（dDPO）作为一种有潜力的方法，利用更大模型的知识来提升小模型的对话能力。然而，现有方法主要关注仅使用教师模型输出的“黑箱”蒸馏，忽视了教师模型提供的输出分布信息。本文提出daDPO（分布感知DPO），一种统一的偏好优化和基于分布的蒸馏方法，填补了这一研究空白。通过严格的理论分析和实证验证，我们发现daDPO在恢复剪枝模型性能和提升小型LLM模型方面表现更优。值得注意的是，在领域内评估中，我们的方法使20%剪枝的Vicuna1.5-7B模型达到接近教师模型的性能（与dDPO相比，偏好率仅降低7.3%），并使Qwen2.5-1.5B模型偶尔超越其7B教师模型（获胜率为14.0%）。

> Large language models (LLMs) have demonstrated exceptional performance across various applications, but their conversational abilities decline sharply as model size decreases, presenting a barrier to their deployment in resource-constrained environments. Knowledge distillation with Direct Preference Optimization (dDPO) has emerged as a promising approach to enhancing the conversational abilities of smaller models using a larger teacher model. However, current methods primarily focus on 'black-box' KD, which only uses the teacher's responses, overlooking the output distribution offered by the teacher. This paper addresses this gap by introducing daDPO (Distribution-Aware DPO), a unified method for preference optimization and distribution-based distillation. We provide rigorous theoretical analysis and empirical validation, showing that daDPO outperforms existing methods in restoring performance for pruned models and enhancing smaller LLM models. Notably, in in-domain evaluation, our method enables a 20% pruned Vicuna1.5-7B to achieve near-teacher performance (-7.3% preference rate compared to that of dDPO's -31%), and allows Qwen2.5-1.5B to occasionally outperform its 7B teacher model (14.0% win rate).

[Arxiv](https://arxiv.org/abs/2506.15717)