# 基于医学概念对齐的LLM增强框架：用于放射科报告生成（MCA-RG）

发布时间：2025年07月09日

`LLM应用` `知识图谱`

> MCA-RG: Enhancing LLMs with Medical Concept Alignment for Radiology Report Generation

# 摘要

> 尽管大型语言模型在放射报告生成方面取得了显著进展，但临床应用仍面临两大挑战：一是难以准确将病理和解剖特征转化为精准的文本描述，二是语义无关特征提取限制了诊断报告的准确性。为解决这些问题，我们提出了医学概念对齐的放射报告生成（MCA-RG），这是一种知识驱动框架，通过将视觉特征与特定医学概念显式对齐，从而优化报告生成过程。

MCA-RG 采用两个精心整理的概念库：包含病变相关知识的病理库，以及包含详细解剖描述的解剖库。视觉特征与这些医学概念对齐后，会经过定制化增强处理。我们还创新性地提出了一种基于解剖的对比学习方法，以提升解剖特征的泛化能力，并结合病理特征的匹配损失，以优先关注临床相关区域。此外，引入特征门控机制，有效过滤低质量的概念特征。

在两个公共基准数据集（MIMIC-CXR 和 CheXpert Plus）上的实验结果表明，MCA-RG 实现了更优的性能，充分证明了其在放射报告生成中的有效性。

> Despite significant advancements in adapting Large Language Models (LLMs) for radiology report generation (RRG), clinical adoption remains challenging due to difficulties in accurately mapping pathological and anatomical features to their corresponding text descriptions. Additionally, semantic agnostic feature extraction further hampers the generation of accurate diagnostic reports. To address these challenges, we introduce Medical Concept Aligned Radiology Report Generation (MCA-RG), a knowledge-driven framework that explicitly aligns visual features with distinct medical concepts to enhance the report generation process. MCA-RG utilizes two curated concept banks: a pathology bank containing lesion-related knowledge, and an anatomy bank with anatomical descriptions. The visual features are aligned with these medical concepts and undergo tailored enhancement. We further propose an anatomy-based contrastive learning procedure to improve the generalization of anatomical features, coupled with a matching loss for pathological features to prioritize clinically relevant regions. Additionally, a feature gating mechanism is employed to filter out low-quality concept features. Finally, the visual features are corresponding to individual medical concepts, and are leveraged to guide the report generation process. Experiments on two public benchmarks (MIMIC-CXR and CheXpert Plus) demonstrate that MCA-RG achieves superior performance, highlighting its effectiveness in radiology report generation.

[Arxiv](https://arxiv.org/abs/2507.06992)