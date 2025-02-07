# RadVLM: 放射学多任务对话视觉-语言模型

发布时间：2025年02月05日

`LLM应用

理由：这篇论文介绍了RadVLM，一个专为胸部X光片（CXRs）解读设计的紧凑型多任务对话基础模型。该模型通过大规模指令数据集进行微调，展示了在报告生成、异常分类、视觉定位等任务中的优异表现。虽然论文中提到了视觉语言模型（VLMs），但核心内容集中在如何利用这些模型进行具体的医学图像解读和对话交互，属于LLM在实际应用中的具体实现，因此归类为LLM应用。` `放射学`

> RadVLM: A Multitask Conversational Vision-Language Model for Radiology

# 摘要

> # 摘要
胸部X光片（CXRs）的广泛应用和放射科医生的短缺，催生了自动化CXR分析和AI辅助报告的强烈需求。尽管现有视觉语言模型（VLMs）在报告生成、异常检测等特定任务中表现不俗，但它们在交互式诊断能力上仍有不足。为此，我们推出了RadVLM，一个专为CXR解读设计的紧凑型多任务对话基础模型。我们构建了一个包含100多万张图像-指令对的大规模指令数据集，涵盖单轮任务（如报告生成、异常分类、视觉定位）和多轮多任务对话交互。通过对该数据集进行微调，我们评估了RadVLM在多项任务中的表现，并与基线VLMs进行了对比。结果显示，RadVLM在对话能力和视觉定位上达到了业界领先水平，同时在其他放射学任务中保持竞争力。消融实验进一步表明，多任务联合训练在标注数据有限的情况下尤为有效。这些成果展示了RadVLM作为临床AI助手的潜力，它能够提供结构化的CXR解读和对话功能，助力更高效、便捷的诊断流程。

> The widespread use of chest X-rays (CXRs), coupled with a shortage of radiologists, has driven growing interest in automated CXR analysis and AI-assisted reporting. While existing vision-language models (VLMs) show promise in specific tasks such as report generation or abnormality detection, they often lack support for interactive diagnostic capabilities. In this work we present RadVLM, a compact, multitask conversational foundation model designed for CXR interpretation. To this end, we curate a large-scale instruction dataset comprising over 1 million image-instruction pairs containing both single-turn tasks -- such as report generation, abnormality classification, and visual grounding -- and multi-turn, multi-task conversational interactions. After fine-tuning RadVLM on this instruction dataset, we evaluate it across different tasks along with re-implemented baseline VLMs. Our results show that RadVLM achieves state-of-the-art performance in conversational capabilities and visual grounding while remaining competitive in other radiology tasks. Ablation studies further highlight the benefit of joint training across multiple tasks, particularly for scenarios with limited annotated data. Together, these findings highlight the potential of RadVLM as a clinically relevant AI assistant, providing structured CXR interpretation and conversational capabilities to support more effective and accessible diagnostic workflows.

[Arxiv](https://arxiv.org/abs/2502.03333)