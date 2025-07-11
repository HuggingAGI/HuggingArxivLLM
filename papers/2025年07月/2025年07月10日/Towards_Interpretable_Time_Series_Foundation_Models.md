# 走向可解释的时间序列基础模型研究

发布时间：2025年07月10日

`LLM应用` `数据分析` `智能系统`

> Towards Interpretable Time Series Foundation Models

# 摘要

> 本文研究了将时间序列推理能力蒸馏到小型指令微调语言模型中，旨在构建可解释的时间序列基础模型。我们通过合成数据集（包含系统性变化趋势和噪声水平的均值回复时间序列），使用大型多模态模型生成自然语言注释，并基于这些注释监督紧凑型Qwen模型的微调。我们提出评估蒸馏推理质量的指标，重点分析趋势方向、噪声强度和极值定位，结果显示微调后的模型获得了有意义的解释能力。研究结果表明，将时间序列理解压缩到适合设备端或隐私敏感场景部署的轻量级语言模型中是可行的。这项工作为开发能够用自然语言解释时间模式的小型可解释模型奠定了坚实基础。

> In this paper, we investigate the distillation of time series reasoning capabilities into small, instruction-tuned language models as a step toward building interpretable time series foundation models. Leveraging a synthetic dataset of mean-reverting time series with systematically varied trends and noise levels, we generate natural language annotations using a large multimodal model and use these to supervise the fine-tuning of compact Qwen models. We introduce evaluation metrics that assess the quality of the distilled reasoning - focusing on trend direction, noise intensity, and extremum localization - and show that the post-trained models acquire meaningful interpretive capabilities. Our results highlight the feasibility of compressing time series understanding into lightweight, language-capable models suitable for on-device or privacy-sensitive deployment. This work contributes a concrete foundation toward developing small, interpretable models that explain temporal patterns in natural language.

[Arxiv](https://arxiv.org/abs/2507.07439)