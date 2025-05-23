# # 摘要  
你的预训练 LLM 暗藏玄机，默默扮演无监督置信度校准器。

发布时间：2025年05月22日

`LLM理论

理由：这篇论文探讨了大型语言模型（LLMs）后训练阶段的置信度校准问题，提出了新的方法来优化模型的参数。研究的核心在于理解模型在后训练阶段的行为及其理论上的改进，属于对LLM理论的深入分析和贡献。` `人工智能`

> Your Pre-trained LLM is Secretly an Unsupervised Confidence Calibrator

# 摘要

> 大型语言模型的后训练对于将预训练语言模型 (PLMs) 与人类偏好和下游任务对齐至关重要。尽管 PLMs 通常表现出良好的置信度校准，但后训练语言模型 (PoLMs) 常常面临过度自信的问题，对正确和错误输出都赋予高置信度，这可能削弱其在关键应用中的可靠性。校准 PoLMs 的一个主要障碍是针对特定下游任务标注数据的稀缺性。为此，我们提出了一种新的无监督方法——基于分歧感知置信度对齐 (DACA)，用于优化后置信心校准中的参数（例如温度 $τ$）。我们的方法受到 PLM 和 PoLM 之间预测分歧导致的欠自信问题的启发，通过温度缩放对齐它们的置信度。从理论上讲，PLM 的置信度低估了 PoLM 在分歧示例上的预测准确性，导致较大的 $τ$ 并产生欠自信的预测。DACA 通过仅使用一致的示例进行校准来缓解这一问题，从而有效消除分歧的影响。通过这种方式，我们的方法避免了由于分歧示例导致的温度缩放中过大的 $τ$，从而提高了校准性能。大量实验表明了我们方法的有效性，将开源和基于 API 的 LLM（如 GPT-4o）在常见基准测试中的平均 ECE 提高了高达 15.08$\%$。

> Post-training of large language models is essential for adapting pre-trained language models (PLMs) to align with human preferences and downstream tasks. While PLMs typically exhibit well-calibrated confidence, post-trained language models (PoLMs) often suffer from over-confidence, assigning high confidence to both correct and incorrect outputs, which can undermine reliability in critical applications. A major obstacle in calibrating PoLMs is the scarcity of labeled data for individual downstream tasks. To address this, we propose Disagreement-Aware Confidence Alignment (DACA), a novel unsupervised method to optimize the parameters (e.g., temperature $τ$) in post-hoc confidence calibration. Our method is motivated by the under-confidence issue caused by prediction disagreement between the PLM and PoLM while aligning their confidence via temperature scaling. Theoretically, the PLM's confidence underestimates PoLM's prediction accuracy on disagreement examples, causing a larger $τ$ and producing under-confident predictions. DACA mitigates this by selectively using only agreement examples for calibration, effectively decoupling the influence of disagreement. In this manner, our method avoids an overly large $τ$ in temperature scaling caused by disagreement examples, improving calibration performance. Extensive experiments demonstrate the effectiveness of our method, improving the average ECE of open-sourced and API-based LLMs (e.g. GPT-4o) by up to 15.08$\%$ on common benchmarks.

[Arxiv](https://arxiv.org/abs/2505.16690)