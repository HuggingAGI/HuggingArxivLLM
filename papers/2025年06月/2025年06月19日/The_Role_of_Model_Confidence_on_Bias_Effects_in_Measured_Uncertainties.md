# 模型信心对测量不确定性中偏见效应的作用

发布时间：2025年06月19日

`LLM理论` `视觉问答` `模型评估`

> The Role of Model Confidence on Bias Effects in Measured Uncertainties

# 摘要

> 大型语言模型（LLMs）在开放任务中的广泛应用凸显了准确评估模型知识局限性的重要性。然而，由于随机不确定性（多个有效答案引发）的存在，量化本体论不确定性颇具挑战性。尽管偏见可能干扰不确定性估计，但也可能减少随机噪声。我们通过视觉问答（VQA）任务实验发现，缓解提示偏见能显著提升GPT-4o的不确定性量化能力。基于LLMs在低置信度时倾向于复制输入信息的研究，我们进一步分析了不同无偏置信度水平下，提示偏见对GPT-4o和Qwen2-VL的不确定性测量影响。研究发现，所有偏见在无偏置信度较低时对不确定性的影响更大。值得注意的是，较低的无偏置信度会导致本体论不确定性低估（即过度自信），而对随机不确定性估计无显著影响。这些发现加深了我们对偏见缓解的理解，并为更先进技术的发展提供了方向。

> With the growing adoption of Large Language Models (LLMs) for open-ended tasks, accurately assessing epistemic uncertainty, which reflects a model's lack of knowledge, has become crucial to ensuring reliable outcomes. However, quantifying epistemic uncertainty in such tasks is challenging due to the presence of aleatoric uncertainty, which arises from multiple valid answers. While bias can introduce noise into epistemic uncertainty estimation, it may also reduce noise from aleatoric uncertainty. To investigate this trade-off, we conduct experiments on Visual Question Answering (VQA) tasks and find that mitigating prompt-introduced bias improves uncertainty quantification in GPT-4o. Building on prior work showing that LLMs tend to copy input information when model confidence is low, we further analyze how these prompt biases affect measured epistemic and aleatoric uncertainty across varying bias-free confidence levels with GPT-4o and Qwen2-VL. We find that all considered biases induce greater changes in both uncertainties when bias-free model confidence is lower. Moreover, lower bias-free model confidence leads to greater underestimation of epistemic uncertainty (i.e. overconfidence) due to bias, whereas it has no significant effect on the direction of changes in aleatoric uncertainty estimation. These distinct effects deepen our understanding of bias mitigation for uncertainty quantification and potentially inform the development of more advanced techniques.

[Arxiv](https://arxiv.org/abs/2506.16724)