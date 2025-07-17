# # 基于LLM引导的智能体目标检测实现开放世界理解
大型语言模型 (LLM) 引导的智能体目标检测实现开放世界理解。

发布时间：2025年07月14日

`LLM应用

摘要中提到，论文提出了一种由大语言模型 (LLM) 引导的自主目标检测框架 (LAOD)，通过提示 LLM 生成场景特定的对象名称，实现了完全无标签的零样本检测。这表明 LLM 被应用于目标检测任务中，属于 LLM 的具体应用。因此，这篇论文应归类为LLM应用。` `计算机视觉` `开放世界理解`

> LLM-Guided Agentic Object Detection for Open-World Understanding

# 摘要

> 传统目标检测依赖固定类别集合，面对新物体时往往需要高昂的重新训练成本。尽管开放世界（OWOD）和开放词汇目标检测（OVOD）提升了灵活性，但 OWOD 缺乏对未知物体的语义标注，而 OVOD 对用户提示的依赖限制了其自主性。我们提出了一种由大语言模型 (LLM) 引导的自主目标检测框架 (LAOD)，通过提示 LLM 生成场景特定的对象名称，实现了完全无标签的零样本检测。这些名称被传递给开放词汇检测器进行定位，使系统能够动态调整目标。为评估这一方法，我们引入了两个新指标：类不可知平均精度 (CAAP) 和语义命名平均精度 (SNAP)，分别用于评估定位和命名性能。在 LVIS、COCO 和 COCO-OOD 数据集上的实验验证了我们的方法，结果显示其在检测和命名新物体方面表现出色。这一方法为开放世界理解提供了更强大的自主性和适应性。


> Object detection traditionally relies on fixed category sets, requiring costly re-training to handle novel objects. While Open-World and Open-Vocabulary Object Detection (OWOD and OVOD) improve flexibility, OWOD lacks semantic labels for unknowns, and OVOD depends on user prompts, limiting autonomy. We propose an LLM-guided agentic object detection (LAOD) framework that enables fully label-free, zero-shot detection by prompting a Large Language Model (LLM) to generate scene-specific object names. These are passed to an open-vocabulary detector for localization, allowing the system to adapt its goals dynamically. We introduce two new metrics, Class-Agnostic Average Precision (CAAP) and Semantic Naming Average Precision (SNAP), to separately evaluate localization and naming. Experiments on LVIS, COCO, and COCO-OOD validate our approach, showing strong performance in detecting and naming novel objects. Our method offers enhanced autonomy and adaptability for open-world understanding.

[Arxiv](https://arxiv.org/abs/2507.10844)