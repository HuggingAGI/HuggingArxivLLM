# 重新审视大型语言模型的不确定性估计与校准

发布时间：2025年05月28日

`LLM理论

摘要主要讨论了大型语言模型（LLMs）的不确定性估计，研究了不同模型架构和规模下的性能，并提出了新的评估方法。这属于模型理论层面的研究。` `人工智能`

> Revisiting Uncertainty Estimation and Calibration of Large Language Models

# 摘要

> 随着大型语言模型 (LLMs) 在高风险场景中的广泛应用，确保其安全可靠部署的关键在于稳健的不确定性估计。我们开展了迄今最全面的 LLM 不确定性估计研究，评估了涵盖开源与闭源模型、密集架构与专家混合 (MoE) 架构、推理与非推理模式、量化变体以及从 0.6B 到 671B 参数规模的 80 种模型。我们聚焦于三种代表性黑箱单次评估方法：基于 token 概率的不确定性 (TPU)、基于数值语言的不确定性 (NVU) 和基于语言表达的不确定性 (LVU)，通过具有挑战性的 MMLU-Pro 基准，系统评估了不确定性校准和选择性分类。研究发现，LVU 在校准强度、辨别能力和可解释性方面均优于 TPU 和 NVU。值得注意的是，高准确性并不必然意味着可靠的不确定性，模型规模、后训练、推理能力和量化都会显著影响估计性能。此外，LLMs 在推理任务上的不确定性评估优于知识密集型任务，良好的校准并不一定带来有效的错误排序。这些发现凸显了多角度评估的重要性，同时也将 LVU 定位为提升 LLMs 在实际应用中可靠性的实用工具。

> As large language models (LLMs) are increasingly deployed in high-stakes applications, robust uncertainty estimation is essential for ensuring the safe and trustworthy deployment of LLMs. We present the most comprehensive study to date of uncertainty estimation in LLMs, evaluating 80 models spanning open- and closed-source families, dense and Mixture-of-Experts (MoE) architectures, reasoning and non-reasoning modes, quantization variants and parameter scales from 0.6B to 671B. Focusing on three representative black-box single-pass methods, including token probability-based uncertainty (TPU), numerical verbal uncertainty (NVU), and linguistic verbal uncertainty (LVU), we systematically evaluate uncertainty calibration and selective classification using the challenging MMLU-Pro benchmark, which covers both reasoning-intensive and knowledge-based tasks. Our results show that LVU consistently outperforms TPU and NVU, offering stronger calibration and discrimination while being more interpretable. We also find that high accuracy does not imply reliable uncertainty, and that model scale, post-training, reasoning ability and quantization all influence estimation performance. Notably, LLMs exhibit better uncertainty estimates on reasoning tasks than on knowledge-heavy ones, and good calibration does not necessarily translate to effective error ranking. These findings highlight the need for multi-perspective evaluation and position LVU as a practical tool for improving the reliability of LLMs in real-world settings.

[Arxiv](https://arxiv.org/abs/2505.23854)