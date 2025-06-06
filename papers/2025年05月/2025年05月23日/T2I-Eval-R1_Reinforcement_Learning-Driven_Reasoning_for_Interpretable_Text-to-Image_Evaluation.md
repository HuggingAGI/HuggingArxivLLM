# T2I-Eval-R1：基于强化学习的推理，实现可解释的文本到图像评估

发布时间：2025年05月23日

`LLM应用` `生成式AI` `内容生成`

> T2I-Eval-R1: Reinforcement Learning-Driven Reasoning for Interpretable Text-to-Image Evaluation

# 摘要

> 基于扩散模型的文本到图像（T2I）生成技术的迅猛发展，迫切需要可解释的自动评估方法来评估生成图像的质量，从而减轻人工标注负担。为了降低依赖商业模型进行大规模评估的高昂成本，并提升开源模型的推理能力， recent research has explored supervised fine-tuning (SFT) of multimodal large language models (MLLMs) 作为专门的 T2I 评估器。然而，SFT 方法通常依赖高质量的批评数据集，这些数据集要么由专有 LLM 生成（可能存在问题，如偏见和不一致性），要么由人工标注，成本高昂，这限制了其扩展性和通用性。为了解决这些问题，我们提出了 T2I-Eval-R1，这是一种仅使用粗粒度质量分数训练开源 MLLMs 的新型强化学习框架，从而避免了标注高质量可解释评估理由的需要。我们的方法将 Group Relative Policy Optimization (GRPO) 集成到指令微调过程中，使模型能够仅使用易于访问的标注判断分数或偏好生成标量分数和可解释推理链。此外，我们引入了一种连续奖励公式，鼓励分数多样性并提供稳定的优化信号，从而实现更稳健和辨别力更强的评估行为。在三个 established T2I 元评估基准上的实验结果表明，与强大的基线方法相比，T2I-Eval-R1 与人工评估的一致性显著提高，并提供了更准确的可解释分数理由。

> The rapid progress in diffusion-based text-to-image (T2I) generation has created an urgent need for interpretable automatic evaluation methods that can assess the quality of generated images, therefore reducing the human annotation burden. To reduce the prohibitive cost of relying on commercial models for large-scale evaluation, and to improve the reasoning capabilities of open-source models, recent research has explored supervised fine-tuning (SFT) of multimodal large language models (MLLMs) as dedicated T2I evaluators. However, SFT approaches typically rely on high-quality critique datasets, which are either generated by proprietary LLMs-with potential issues of bias and inconsistency-or annotated by humans at high cost, limiting their scalability and generalization. To address these limitations, we propose T2I-Eval-R1, a novel reinforcement learning framework that trains open-source MLLMs using only coarse-grained quality scores, thereby avoiding the need for annotating high-quality interpretable evaluation rationale. Our approach integrates Group Relative Policy Optimization (GRPO) into the instruction-tuning process, enabling models to generate both scalar scores and interpretable reasoning chains with only easy accessible annotated judgment scores or preferences. Furthermore, we introduce a continuous reward formulation that encourages score diversity and provides stable optimization signals, leading to more robust and discriminative evaluation behavior. Experimental results on three established T2I meta-evaluation benchmarks demonstrate that T2I-Eval-R1 achieves significantly higher alignment with human assessments and offers more accurate interpretable score rationales compared to strong baseline methods.

[Arxiv](https://arxiv.org/abs/2505.17897)