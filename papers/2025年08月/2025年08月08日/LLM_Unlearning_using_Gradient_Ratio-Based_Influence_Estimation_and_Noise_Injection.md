# 基于梯度比率影响估计与噪声注入的 LLM 反向学习方法

发布时间：2025年08月08日

`LLM理论` `数据安全` `隐私保护`

> LLM Unlearning using Gradient Ratio-Based Influence Estimation and Noise Injection

# 摘要

> 随着大型语言模型 (LLMs) 面临越来越多的法律和伦理审查，实现有效的机器遗忘变得尤为重要，尤其是对于敏感或未经授权的数据。现有的经验方法往往因定位不准而导致遗忘不完全，甚至可能无意中破坏了无关的知识。为此，我们提出了 GRIN：一个模块化且有针对性的 LLM 遗忘框架。GRIN 创新性地引入了一种基于梯度比的度量方法，精准识别最负责记住遗忘数据的参数。通过在微调前对这些参数进行选择性噪声注入，我们不仅提升了遗忘效果，还保持了模型的实用性。最后，我们为 LLM 场景量身定制了新的评估指标，并在 TOFU、WMDP 和 SafePKU 等标准基准上验证了 GRIN 的有效性。

> The growing legal and ethical scrutiny of large language models (LLMs) necessitates effective machine unlearning, particularly for sensitive or unauthorized data. Existing empirical methods often yield incomplete forgetting or unintended degradation of unrelated knowledge due to poor localization. In this work, we propose GRIN: a modular and targeted framework for LLM unlearning. GRIN introduces a novel gradient-ratio-based metric to identify parameters most responsible for memorizing forget data. We then perform selective noise injection into these parameters prior to fine-tuning, which improves unlearning performance while maintaining model utility. Finally, we propose new evaluation metrics tailored to the LLM setting and validate our approach on standard benchmarks such as TOFU, WMDP, and SafePKU.

[Arxiv](https://arxiv.org/abs/2508.06467)