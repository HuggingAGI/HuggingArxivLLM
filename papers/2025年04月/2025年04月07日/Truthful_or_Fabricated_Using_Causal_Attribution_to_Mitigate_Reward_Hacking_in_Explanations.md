# 真实还是捏造？利用因果归因缓解解释中的奖励操纵问题

发布时间：2025年04月07日

`LLM理论

理由：这篇论文探讨了大型语言模型（LLM）在生成解释时的忠实度问题，特别是奖励模型（RM）在优化过程中可能带来的影响。研究关注的是模型内部的决策过程和解释生成的一致性，属于对LLM内在机制和理论的分析与改进，因此归类为LLM理论。` `人工智能` `机器学习`

> Truthful or Fabricated? Using Causal Attribution to Mitigate Reward Hacking in Explanations

# 摘要

> 链式思维解释在检查 LLM 的决策过程和评估模型输出可信度方面发挥着关键作用，这对人机协作至关重要。我们发现，对齐阶段的核心环节——偏好优化——可能无意中削弱解释的忠实度。这是因为引导对齐的奖励模型 (RM) 需要在优化响应质量的同时，确保解释的恰当性（如减少偏见或遵守安全标准），这种双重任务可能导致冲突。然而，RM 缺乏评估模型内部决策过程与生成解释之间一致性的机制。因此，LLM 可能会通过生成高分响应并提供经过调整以最大化奖励而非准确反映推理过程的解释来进行“奖励黑客”。为解决这一问题，我们提出通过为 RM 的输入添加对预测的因果归因，使其能够检测生成的自我解释与模型决策过程之间的不一致。在受控实验中，我们证明这种方法可以有效降低 LLM 生成误导性解释的倾向。

> Chain-of-thought explanations are widely used to inspect the decision process of large language models (LLMs) and to evaluate the trustworthiness of model outputs, making them important for effective collaboration between LLMs and humans. We demonstrate that preference optimization - a key step in the alignment phase - can inadvertently reduce the faithfulness of these explanations. This occurs because the reward model (RM), which guides alignment, is tasked with optimizing both the expected quality of the response and the appropriateness of the explanations (e.g., minimizing bias or adhering to safety standards), creating potential conflicts. The RM lacks a mechanism to assess the consistency between the model's internal decision process and the generated explanation. Consequently, the LLM may engage in "reward hacking" by producing a final response that scores highly while giving an explanation tailored to maximize reward rather than accurately reflecting its reasoning. To address this issue, we propose enriching the RM's input with a causal attribution of the prediction, allowing the RM to detect discrepancies between the generated self-explanation and the model's decision process. In controlled settings, we show that this approach reduces the tendency of the LLM to generate misleading explanations.

[Arxiv](https://arxiv.org/abs/2504.05294)