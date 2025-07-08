# CoT-Segmenter: 借助链式思维推理优化密集道路场景下的域外检测效果

发布时间：2025年07月05日

`LLM应用` `自动驾驶` `智能驾驶`

> CoT-Segmenter: Enhancing OOD Detection in Dense Road Scenes via Chain-of-Thought Reasoning

# 摘要

> 在复杂道路环境中，确保语义分割模型的可靠性需要有效的出分布 (OOD) 检测。尽管大型语言模型 (LLMs) 近年来取得了显著进展，特别是 GPT-4 通过链式思维 (CoT) 提示显著提升了多模态推理能力，但基于 CoT 的视觉推理在 OOD 语义分割中的应用仍然鲜有探索。通过对道路场景异常的深入分析，我们识别出三个当前最先进的 OOD 分割方法普遍面临的挑战场景：(1) 密集且重叠的物体，(2) 远距离场景中的小物体，(3) 大型前景主导的物体。为应对这些挑战，我们提出了一种面向道路异常场景 OOD 检测的新型 CoT 框架。我们的方法充分利用了基础模型（如 GPT-4）的广泛知识和推理能力，通过改进图像理解以及与观察到的问题场景属性相契合的提示式推理，显著增强了 OOD 检测能力。大量实验表明，我们的框架在标准基准测试以及我们新定义的更具挑战性的 RoadAnomaly 数据集子集上，均显著优于现有的最先进方法，为复杂驾驶环境中的 OOD 语义分割提供了强大且可解释的解决方案。

> Effective Out-of-Distribution (OOD) detection is criti-cal for ensuring the reliability of semantic segmentation models, particularly in complex road environments where safety and accuracy are paramount. Despite recent advancements in large language models (LLMs), notably GPT-4, which significantly enhanced multimodal reasoning through Chain-of-Thought (CoT) prompting, the application of CoT-based visual reasoning for OOD semantic segmentation remains largely unexplored. In this paper, through extensive analyses of the road scene anomalies, we identify three challenging scenarios where current state-of-the-art OOD segmentation methods consistently struggle: (1) densely packed and overlapping objects, (2) distant scenes with small objects, and (3) large foreground-dominant objects. To address the presented challenges, we propose a novel CoT-based framework targeting OOD detection in road anomaly scenes. Our method leverages the extensive knowledge and reasoning capabilities of foundation models, such as GPT-4, to enhance OOD detection through improved image understanding and prompt-based reasoning aligned with observed problematic scene attributes. Extensive experiments show that our framework consistently outperforms state-of-the-art methods on both standard benchmarks and our newly defined challenging subset of the RoadAnomaly dataset, offering a robust and interpretable solution for OOD semantic segmentation in complex driving environments.

[Arxiv](https://arxiv.org/abs/2507.03984)