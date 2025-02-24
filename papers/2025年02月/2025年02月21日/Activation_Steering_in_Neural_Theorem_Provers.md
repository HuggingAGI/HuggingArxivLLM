# # 神经定理证明器中的激活引导

发布时间：2025年02月21日

`LLM应用` `定理证明` `形式化数学`

> Activation Steering in Neural Theorem Provers

# 摘要

> 大型语言模型（LLMs）在使用如Lean等证明助手来证明正式定理方面展现出潜力。然而，当前最先进的语言模型在预测证明的下一步时存在困难，因此从业者采用不同的采样技术来提升LLMs的能力。我们发现，LLM能够预测正确的策略，但在候选策略集中正确排名方面存在挑战，影响了整体选择过程。为解决这一问题，我们采用激活引导来指导LLMs的响应，以提高推理时的生成能力。我们的研究结果表明，激活引导为提升LLMs的定理证明能力提供了一种轻量级的解决方案，特别是在资源受限的环境中具有重要价值。

> Large Language Models (LLMs) have shown promise in proving formal theorems using proof assistants like Lean. However, current state of the art language models struggles to predict next step in proofs leading practitioners to use different sampling techniques to improve LLMs capabilities. We observe that the LLM is capable of predicting the correct tactic; however, it faces challenges in ranking it appropriately within the set of candidate tactics, affecting the overall selection process. To overcome this hurdle, we use activation steering to guide LLMs responses to improve the generations at the time of inference. Our results suggest that activation steering offers a promising lightweight alternative to specialized fine-tuning for enhancing theorem proving capabilities in LLMs, particularly valuable in resource-constrained environments.

[Arxiv](https://arxiv.org/abs/2502.15507)