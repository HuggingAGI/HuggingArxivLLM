# # 摘要
最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。

发布时间：2025年02月09日

`LLM应用

论文摘要：大型语言模型（LLMs）的迅猛发展为多模态任务带来了巨大潜力，这些任务涉及文本和视觉数据的同时处理。然而，将其应用于医学影像，尤其是胸片（CXR），面临两大挑战：精确的视觉-文本对齐和关键诊断细节的保留。本文提出了一种全新的多阶段自适应视觉-语言微调框架（MAViLT），旨在提升胸片理解的多模态推理与生成能力。MAViLT通过整合临床梯度加权标记化过程和层次化微调策略，实现了三大核心功能：生成准确的放射报告、从文本合成逼真的胸片、解答基于视觉的临床问题。我们在MIMIC-CXR和印第安纳大学胸片两个基准数据集上对MAViLT进行了全面评估，所有任务均达到了最先进水平。通过人类评估进一步验证了MAViLT的临床相关性和实用性，使其成为医学领域实际应用的有力工具。这项研究不仅展示了利用LLMs进行多模态医学影像的可行性，还成功解决了视觉-语言整合中的关键挑战。

LLM应用` `医学影像` `多模态`

> A Generative Framework for Bidirectional Image-Report Understanding in Chest Radiography

# 摘要

> 大型语言模型（LLMs）的迅猛发展为多模态任务带来了巨大潜力，这些任务涉及文本和视觉数据的同时处理。然而，将其应用于医学影像，尤其是胸片（CXR），面临两大挑战：精确的视觉-文本对齐和关键诊断细节的保留。本文提出了一种全新的多阶段自适应视觉-语言微调框架（MAViLT），旨在提升胸片理解的多模态推理与生成能力。MAViLT通过整合临床梯度加权标记化过程和层次化微调策略，实现了三大核心功能：生成准确的放射报告、从文本合成逼真的胸片、解答基于视觉的临床问题。我们在MIMIC-CXR和印第安纳大学胸片两个基准数据集上对MAViLT进行了全面评估，所有任务均达到了最先进水平。通过人类评估进一步验证了MAViLT的临床相关性和实用性，使其成为医学领域实际应用的有力工具。这项研究不仅展示了利用LLMs进行多模态医学影像的可行性，还成功解决了视觉-语言整合中的关键挑战。

> The rapid advancements in large language models (LLMs) have unlocked their potential for multimodal tasks, where text and visual data are processed jointly. However, applying LLMs to medical imaging, particularly for chest X-rays (CXR), poses significant challenges due to the need for precise visual-textual alignment and the preservation of critical diagnostic details. In this paper, we propose Multi-Stage Adaptive Vision-Language Tuning (MAViLT), a novel framework designed to enhance multimodal reasoning and generation for CXR understanding. MAViLT incorporates a clinical gradient-weighted tokenization process and a hierarchical fine-tuning strategy, enabling it to generate accurate radiology reports, synthesize realistic CXRs from text, and answer vision-based clinical questions. We evaluate MAViLT on two benchmark datasets, MIMIC-CXR and Indiana University CXR, achieving state-of-the-art results across all tasks. Human evaluations further validate the clinical relevance and utility of MAViLT, making it a robust tool for real-world medical applications. This work demonstrates the feasibility of leveraging LLMs for multimodal medical imaging while addressing key challenges in vision-language integration.

[Arxiv](https://arxiv.org/abs/2502.05926)