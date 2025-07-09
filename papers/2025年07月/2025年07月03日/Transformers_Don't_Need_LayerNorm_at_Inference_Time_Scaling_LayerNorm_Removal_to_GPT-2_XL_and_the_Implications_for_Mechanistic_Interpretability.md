# Transformers 推理无需 LayerNorm：扩展至 GPT-2 XL 与机制可解释性的启示

发布时间：2025年07月03日

`LLM理论` `机器学习`

> Transformers Don't Need LayerNorm at Inference Time: Scaling LayerNorm Removal to GPT-2 XL and the Implications for Mechanistic Interpretability

# 摘要

> 层归一化（LN）几乎是所有基于Transformer的大型语言模型的核心组成部分。虽然其对训练稳定性的影响已被充分研究，但其在推理阶段的作用仍不明确。此外，LN层通过引入额外的非线性关系和增加模型组件间的相互关联性，给模型的可解释性带来了挑战。我们发现，可以完全移除GPT-2模型中的所有LN层，仅导致验证损失轻微增加（例如，GPT-2 XL的交叉熵损失增加0.03）。这表明LN并非语言建模中不可或缺的组件。研究还显示，移除LN所需的微调数据量随模型参数增长呈亚线性关系，这意味着对更大模型的扩展是可行的。我们在Hugging Face上发布了无LN层的GPT-2模型系列。进一步的实验表明，无LN层模型在可解释性技术上表现独特：直接logit归因能够准确反映各组件的直接影响，而归因补丁的准确性并未显著提升。此外，我们证实了GPT-2的“置信神经元”在无LN层模型中处于非活跃状态。本研究明确了LN层在语言建模中的角色，证明了GPT-2类模型可以在没有LN层的情况下正常运作。我们希望这些无LN层的GPT-2变体将推动更精准的可解释性研究，从而深化我们对语言模型的理解。

> Layer-wise normalization (LN) is an essential component of virtually all transformer-based large language models. While its effects on training stability are well documented, its role at inference time is poorly understood. Additionally, LN layers hinder mechanistic interpretability by introducing additional nonlinearities and increasing the interconnectedness of individual model components. Here, we show that all LN layers can be removed from every GPT-2 model with only a small increase in validation loss (e.g. +0.03 cross-entropy loss for GPT-2 XL). Thus, LN cannot play a substantial role in language modeling. We find that the amount of fine-tuning data needed for LN removal grows sublinearly with model parameters, suggesting scaling to larger models is feasible. We release a suite of LN-free GPT-2 models on Hugging Face. Furthermore, we test interpretability techniques on LN-free models. Direct logit attribution now gives the exact direct effect of individual components, while the accuracy of attribution patching does not significantly improve. We also confirm that GPT-2's "confidence neurons" are inactive in the LN-free models. Our work clarifies the role of LN layers in language modeling, showing that GPT-2-class models can function without LN layers. We hope that our LN-free analogs of the GPT-2 family of models will enable more precise interpretability research and improve our understanding of language models.

[Arxiv](https://arxiv.org/abs/2507.02559)