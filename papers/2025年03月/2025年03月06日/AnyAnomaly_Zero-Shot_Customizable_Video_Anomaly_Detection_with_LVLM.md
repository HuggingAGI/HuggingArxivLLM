# AnyAnomaly：基于 LVLM 的零样本可定制视频异常检测方案

发布时间：2025年03月06日

`其他` `视频监控` `计算机视觉`

> AnyAnomaly: Zero-Shot Customizable Video Anomaly Detection with LVLM

# 摘要

> 视频异常检测（VAD）在计算机视觉领域的视频分析和监控中发挥着重要作用。然而，现有的 VAD 模型依赖于学习到的正常模式，这使得它们难以适应多样化的实际环境。用户通常需要重新训练模型或为新环境开发专门的 AI 模型，这不仅需要专业的机器学习知识，还需要高性能硬件和大量数据收集，这大大限制了 VAD 的实际应用。为了解决这些难题，本研究提出了一种创新的可定制视频异常检测（C-VAD）技术，并开发了 AnyAnomaly 模型。C-VAD 允许用户通过自定义文本定义异常事件，并能在视频中自动识别包含这些事件的帧。我们采用了一种基于上下文的视觉问答方法成功实现了 AnyAnomaly，而无需对大型视觉语言模型进行额外的微调。为了验证这一方法的有效性，我们构建了专门的 C-VAD 数据集，并通过实验展示了 AnyAnomaly 的显著优势。此外，我们的方法在多个 VAD 基准数据集上表现优异，在 UBnormal 数据集上达到了当前最优的性能水平，并在所有数据集上展现了强大的通用性。我们的代码已开源，可在 github.com/SkiddieAhn/Paper-AnyAnomaly 查看和下载。

> Video anomaly detection (VAD) is crucial for video analysis and surveillance in computer vision. However, existing VAD models rely on learned normal patterns, which makes them difficult to apply to diverse environments. Consequently, users should retrain models or develop separate AI models for new environments, which requires expertise in machine learning, high-performance hardware, and extensive data collection, limiting the practical usability of VAD. To address these challenges, this study proposes customizable video anomaly detection (C-VAD) technique and the AnyAnomaly model. C-VAD considers user-defined text as an abnormal event and detects frames containing a specified event in a video. We effectively implemented AnyAnomaly using a context-aware visual question answering without fine-tuning the large vision language model. To validate the effectiveness of the proposed model, we constructed C-VAD datasets and demonstrated the superiority of AnyAnomaly. Furthermore, our approach showed competitive performance on VAD benchmark datasets, achieving state-of-the-art results on the UBnormal dataset and outperforming other methods in generalization across all datasets. Our code is available online at github.com/SkiddieAhn/Paper-AnyAnomaly.

[Arxiv](https://arxiv.org/abs/2503.04504)