# 多模态指令微调的重新构想：从表示视角出发

发布时间：2025年03月01日

`LLM应用` `多模态` `模型优化`

> Re-Imagining Multimodal Instruction Tuning: A Representation View

# 摘要

> 多模态指令微调已被证实是实现零-shot 泛化的有效策略，通过使用指令遵循数据对预训练的大型多模态模型（LMMs）进行微调。然而，随着 LMMs 规模的持续扩大，完全微调这些模型变得高度依赖参数。尽管参数高效微调（PEFT）方法减少了可调参数的数量，但与完全微调相比仍存在显著性能差距。此外，现有的 PEFT 方法通常高度依赖参数，难以解释和控制。为此，我们提出了多模态表示微调（MRT），专注于直接编辑语义丰富的多模态表示，以实现强劲性能并提供直观的 LMMs 控制。实证结果显示，我们的方法超越了现有最先进基准，性能显著提升（例如，1580.40 MME 分数），同时仅需少量可调参数（例如，0.03%）。此外，我们在多模态表示中对工具提示标记进行编辑实验，证明了直接操作这些表示能够实现对网络行为的简单而有效的控制。

> Multimodal instruction tuning has proven to be an effective strategy for achieving zero-shot generalization by fine-tuning pre-trained Large Multimodal Models (LMMs) with instruction-following data. However, as the scale of LMMs continues to grow, fully fine-tuning these models has become highly parameter-intensive. Although Parameter-Efficient Fine-Tuning (PEFT) methods have been introduced to reduce the number of tunable parameters, a significant performance gap remains compared to full fine-tuning. Furthermore, existing PEFT approaches are often highly parameterized, making them difficult to interpret and control. In light of this, we introduce Multimodal Representation Tuning (MRT), a novel approach that focuses on directly editing semantically rich multimodal representations to achieve strong performance and provide intuitive control over LMMs. Empirical results show that our method surpasses current state-of-the-art baselines with significant performance gains (e.g., 1580.40 MME score) while requiring substantially fewer tunable parameters (e.g., 0.03% parameters). Additionally, we conduct experiments on editing instrumental tokens within multimodal representations, demonstrating that direct manipulation of these representations enables simple yet effective control over network behavior.

[Arxiv](https://arxiv.org/abs/2503.00723)