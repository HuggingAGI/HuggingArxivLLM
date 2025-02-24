# # 基于视觉语言模型的工业故障诊断问答系统：FaultGPT

发布时间：2025年02月21日

`LLM应用

LLM应用

**Step-by-Step Explanation:**

1. **阅读论文摘要**：论文介绍了一个名为FaultGPT的新模型，结合大型视觉-语言模型（LVLM）和文本监督，用于从机械振动信号生成故障诊断报告。

2. **识别关键词**：大型语言模型（LLM）、故障诊断、工业应用、端到端故障诊断问答（FDQA）。

3. **分析内容**：论文展示了如何将LLM应用于实际工业场景中的故障诊断，属于应用层面的研究。

4. **分类依据**：论文讨论了LLM在特定领域的应用，因此归类为LLM应用。

LLM应用` `故障诊断`

> FaultGPT: Industrial Fault Diagnosis Question Answering System by Vision Language Models

# 摘要

> 基于机械振动信号的单模态大型语言模型作为调优预测器，为智能故障诊断带来了全新视角。然而，这些方法在多模态数据应用上的潜力尚未充分挖掘，尤其是在复杂机械系统中，单一数据源难以全面捕捉故障信息。本文提出FaultGPT，一种直接从原始振动信号生成故障诊断报告的新模型。通过结合大型视觉-语言模型（LVLM）与文本监督，FaultGPT实现了端到端的故障诊断问答（FDQA），与传统分类或回归方法不同。我们构建了一个大规模FDQA指令数据集，用于对LVLM进行指令微调，包含振动时频图像-文本标签对及人机指令-真实标签对。为了提升生成高质量诊断报告的能力，我们设计了多尺度跨模态图像解码器提取精细故障语义，并在不引入额外训练参数的情况下完成指令微调。实验结果表明，FaultGPT在故障诊断报告生成、多数据集的少样本和零样本评估中表现出色，验证了其在工业场景中的优越性能和适应性。

> Recently, employing single-modality large language models based on mechanical vibration signals as Tuning Predictors has introduced new perspectives in intelligent fault diagnosis. However, the potential of these methods to leverage multimodal data remains underexploited, particularly in complex mechanical systems where relying on a single data source often fails to capture comprehensive fault information. In this paper, we present FaultGPT, a novel model that generates fault diagnosis reports directly from raw vibration signals. By leveraging large vision-language models (LVLM) and text-based supervision, FaultGPT performs end-to-end fault diagnosis question answering (FDQA), distinguishing itself from traditional classification or regression approaches. Specifically, we construct a large-scale FDQA instruction dataset for instruction tuning of LVLM. This dataset includes vibration time-frequency image-text label pairs and human instruction-ground truth pairs. To enhance the capability in generating high-quality fault diagnosis reports, we design a multi-scale cross-modal image decoder to extract fine-grained fault semantics and conducted instruction tuning without introducing additional training parameters into the LVLM. Extensive experiments, including fault diagnosis report generation, few-shot and zero-shot evaluation across multiple datasets, validate the superior performance and adaptability of FaultGPT in diverse industrial scenarios.

[Arxiv](https://arxiv.org/abs/2502.15481)