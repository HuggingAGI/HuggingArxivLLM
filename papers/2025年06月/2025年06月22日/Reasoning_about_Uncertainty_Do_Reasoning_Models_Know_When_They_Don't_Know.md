# 推理中的不确定性：模型能否感知自己的知识边界？

发布时间：2025年06月22日

`LLM理论` `人工智能` `模型评估`

> Reasoning about Uncertainty: Do Reasoning Models Know When They Don't Know?

# 摘要

> 推理语言模型在多个挑战性基准测试中创下了最先进的（SOTA）记录，这得益于强化学习驱动的多步推理。然而，与传统语言模型类似，推理模型容易生成看似合理却错误的回答（幻觉）。了解何时及在多大程度上信任这些模型，对实际应用中推理模型的安全部署至关重要。为此，本研究探讨了推理模型的不确定性量化。具体而言，我们提出以下三个核心问题：首先，推理模型是否具备良好的校准能力？其次，更深入的推理是否能提升模型的校准效果？最后，受人类自我反思能力启发，我们探究：推理模型能否通过显式分析其思维链轨迹来改善校准？为此，我们引入了反思性不确定性量化（UQ）方法。在覆盖广泛基准测试的先进推理模型评估中，我们发现：（i）推理模型通常过于自信，尤其在错误回答时，其自我表达的信心常超过85%；（ii）更深入的推理进一步加剧了过度自信；（iii）部分模型（如o3-Mini和DeepSeek R1）通过反思可改善校准，但并非所有模型（如Claude 3.7 Sonnet的校准效果反而变差）。最后，我们提出了设计必要UQ基准测试及提升推理模型校准能力的重要研究方向。

> Reasoning language models have set state-of-the-art (SOTA) records on many challenging benchmarks, enabled by multi-step reasoning induced using reinforcement learning. However, like previous language models, reasoning models are prone to generating confident, plausible responses that are incorrect (hallucinations). Knowing when and how much to trust these models is critical to the safe deployment of reasoning models in real-world applications. To this end, we explore uncertainty quantification of reasoning models in this work. Specifically, we ask three fundamental questions: First, are reasoning models well-calibrated? Second, does deeper reasoning improve model calibration? Finally, inspired by humans' innate ability to double-check their thought processes to verify the validity of their answers and their confidence, we ask: can reasoning models improve their calibration by explicitly reasoning about their chain-of-thought traces? We introduce introspective uncertainty quantification (UQ) to explore this direction. In extensive evaluations on SOTA reasoning models across a broad range of benchmarks, we find that reasoning models: (i) are typically overconfident, with self-verbalized confidence estimates often greater than 85% particularly for incorrect responses, (ii) become even more overconfident with deeper reasoning, and (iii) can become better calibrated through introspection (e.g., o3-Mini and DeepSeek R1) but not uniformly (e.g., Claude 3.7 Sonnet becomes more poorly calibrated). Lastly, we conclude with important research directions to design necessary UQ benchmarks and improve the calibration of reasoning models.

[Arxiv](https://arxiv.org/abs/2506.18183)