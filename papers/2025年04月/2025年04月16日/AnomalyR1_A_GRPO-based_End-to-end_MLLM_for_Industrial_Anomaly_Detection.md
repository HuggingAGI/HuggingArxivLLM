# AnomalyR1：基于 GRPO 的端到端多语言模型，专为工业异常检测设计。

发布时间：2025年04月16日

`LLM应用

论文摘要：工业异常检测（IAD）面临的一大难题是缺陷样本稀缺，亟需部署具备强大泛化能力的模型来有效识别未知异常。传统方法受制于手工设计特征或领域特定模型，难以突破这一瓶颈，凸显了范式转变的必要性。我们推出AnomalyR1，一个开创性的框架，基于备受推崇的多模态大型语言模型（MLLM）VLM-R1，该模型以其卓越的泛化能力和可解释性著称。通过将MLLM与增强版的组相对策略优化（GRPO）相结合，并引入创新的有据结果对齐度量（ROAM），AnomalyR1实现了完全端到端的解决方案，能够自主处理图像和领域知识输入，通过分析推理生成精确的异常定位和掩膜。基于最新的多模态IAD基准测试，我们的30亿参数紧凑型模型超越了现有方法，达到了最新的技术水平。随着MLLM能力的持续提升，本研究率先推出了首个基于VLM的端到端IAD解决方案，展示了ROAM增强型GRPO的变革潜力，使我们的框架成为面向下一代智能异常检测系统的重要基石，尤其适用于工业应用中缺陷数据有限的场景。

LLM应用` `异常检测`

> AnomalyR1: A GRPO-based End-to-end MLLM for Industrial Anomaly Detection

# 摘要

> 工业异常检测（IAD）面临的一大难题是缺陷样本稀缺，亟需部署具备强大泛化能力的模型来有效识别未知异常。传统方法受制于手工设计特征或领域特定模型，难以突破这一瓶颈，凸显了范式转变的必要性。我们推出AnomalyR1，一个开创性的框架，基于备受推崇的多模态大型语言模型（MLLM）VLM-R1，该模型以其卓越的泛化能力和可解释性著称。通过将MLLM与增强版的组相对策略优化（GRPO）相结合，并引入创新的有据结果对齐度量（ROAM），AnomalyR1实现了完全端到端的解决方案，能够自主处理图像和领域知识输入，通过分析推理生成精确的异常定位和掩膜。基于最新的多模态IAD基准测试，我们的30亿参数紧凑型模型超越了现有方法，达到了最新的技术水平。随着MLLM能力的持续提升，本研究率先推出了首个基于VLM的端到端IAD解决方案，展示了ROAM增强型GRPO的变革潜力，使我们的框架成为面向下一代智能异常检测系统的重要基石，尤其适用于工业应用中缺陷数据有限的场景。


> Industrial Anomaly Detection (IAD) poses a formidable challenge due to the scarcity of defective samples, making it imperative to deploy models capable of robust generalization to detect unseen anomalies effectively. Traditional approaches, often constrained by hand-crafted features or domain-specific expert models, struggle to address this limitation, underscoring the need for a paradigm shift. We introduce AnomalyR1, a pioneering framework that leverages VLM-R1, a Multimodal Large Language Model (MLLM) renowned for its exceptional generalization and interpretability, to revolutionize IAD. By integrating MLLM with Group Relative Policy Optimization (GRPO), enhanced by our novel Reasoned Outcome Alignment Metric (ROAM), AnomalyR1 achieves a fully end-to-end solution that autonomously processes inputs of image and domain knowledge, reasons through analysis, and generates precise anomaly localizations and masks. Based on the latest multimodal IAD benchmark, our compact 3-billion-parameter model outperforms existing methods, establishing state-of-the-art results. As MLLM capabilities continue to advance, this study is the first to deliver an end-to-end VLM-based IAD solution that demonstrates the transformative potential of ROAM-enhanced GRPO, positioning our framework as a forward-looking cornerstone for next-generation intelligent anomaly detection systems in industrial applications with limited defective data.

[Arxiv](https://arxiv.org/abs/2504.11914)