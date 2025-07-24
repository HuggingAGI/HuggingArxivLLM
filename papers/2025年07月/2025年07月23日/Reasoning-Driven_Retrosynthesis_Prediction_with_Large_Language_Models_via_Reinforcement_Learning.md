# 基于推理驱动的逆合成预测：利用强化学习实现的大型语言模型方法

发布时间：2025年07月23日

`LLM应用` `药物发现`

> Reasoning-Driven Retrosynthesis Prediction with Large Language Models via Reinforcement Learning

# 摘要

> 逆合成规划在有机合成与药物发现中扮演着关键角色，AI技术的突破为其带来了革命性提升。然而，现有方法在适用性与可解释性上仍有诸多局限。传统基于图模型与序列到序列模型往往缺乏通用化学知识，导致预测结果既不准确也不易解释。为解决这些问题，我们开发了专门针对化学逆合成的基于推理的大型语言模型——RetroDFM-R。通过结合化学验证奖励机制的大规模强化学习，RetroDFM-R显著提升了预测准确性和可解释性。在USPTO-50K基准测试中，RetroDFM-R达到了65.0%的top-1准确率，显著超越现有最优方法。双盲人工评估进一步验证了其预测结果的化学合理性和实用价值。该模型不仅能够准确预测文献中报道的多步逆合成路径，适用于真实药物分子及钙钛矿材料，其明确的推理过程还提供了可被人理解的见解，从而在实际逆合成应用中增强了信任度和实用价值。

> Retrosynthesis planning, essential in organic synthesis and drug discovery, has greatly benefited from recent AI-driven advancements. Nevertheless, existing methods frequently face limitations in both applicability and explainability. Traditional graph-based and sequence-to-sequence models often lack generalized chemical knowledge, leading to predictions that are neither consistently accurate nor easily explainable. To address these challenges, we introduce RetroDFM-R, a reasoning-based large language model (LLM) designed specifically for chemical retrosynthesis. Leveraging large-scale reinforcement learning guided by chemically verifiable rewards, RetroDFM-R significantly enhances prediction accuracy and explainability. Comprehensive evaluations demonstrate that RetroDFM-R significantly outperforms state-of-the-art methods, achieving a top-1 accuracy of 65.0% on the USPTO-50K benchmark. Double-blind human assessments further validate the chemical plausibility and practical utility of RetroDFM-R's predictions. RetroDFM-R also accurately predicts multistep retrosynthetic routes reported in the literature for both real-world drug molecules and perovskite materials. Crucially, the model's explicit reasoning process provides human-interpretable insights, thereby enhancing trust and practical value in real-world retrosynthesis applications.

[Arxiv](https://arxiv.org/abs/2507.17448)