# RadAlign: 利用视觉-语言概念对齐技术提升放射学报告生成

发布时间：2025年01月13日

`LLM应用

**理由**：这篇论文主要讨论了如何结合视觉语言模型（VLM）和大型语言模型（LLM）来生成详细的放射学报告，并提到了使用检索增强生成机制（RAG）来提升报告质量。虽然涉及了RAG技术，但核心应用场景是LLM在医学影像报告生成中的应用，因此归类为LLM应用更为合适。` `放射学`

> RadAlign: Advancing Radiology Report Generation with Vision-Language Concept Alignment

# 摘要

> # 自动胸部X光片解读
自动胸部X光片解读不仅要求精准的疾病分类，还需生成详尽的放射学报告，这对临床工作流程提出了巨大挑战。现有方法要么过于追求分类准确性而牺牲了可解释性，要么通过图像字幕技术生成详细但可能不可靠的报告。本研究提出的RadAlign框架，巧妙结合了视觉语言模型（VLM）的预测能力和大型语言模型（LLM）的推理能力。受放射科医生工作流程启发，RadAlign首先利用专门的VLM将视觉特征与关键医学概念对齐，在多种疾病分类中取得了平均AUC为0.885的优异表现。这些识别出的医学状况，在对齐的视觉语言空间中转化为文本概念，进而用于引导基于LLM的报告生成。通过检索增强生成机制，将输出与类似历史案例相结合，RadAlign在报告质量上表现出色，GREEN得分达到0.678，超越了现有最佳方法的0.634。该框架在减少幻觉的同时保持了高度的临床可解释性，通过整合预测与生成AI，推动了自动化医学成像和报告分析的进步。代码已开源，详见https://github.com/difeigu/RadAlign。

> Automated chest radiographs interpretation requires both accurate disease classification and detailed radiology report generation, presenting a significant challenge in the clinical workflow. Current approaches either focus on classification accuracy at the expense of interpretability or generate detailed but potentially unreliable reports through image captioning techniques. In this study, we present RadAlign, a novel framework that combines the predictive accuracy of vision-language models (VLMs) with the reasoning capabilities of large language models (LLMs). Inspired by the radiologist's workflow, RadAlign first employs a specialized VLM to align visual features with key medical concepts, achieving superior disease classification with an average AUC of 0.885 across multiple diseases. These recognized medical conditions, represented as text-based concepts in the aligned visual-language space, are then used to prompt LLM-based report generation. Enhanced by a retrieval-augmented generation mechanism that grounds outputs in similar historical cases, RadAlign delivers superior report quality with a GREEN score of 0.678, outperforming state-of-the-art methods' 0.634. Our framework maintains strong clinical interpretability while reducing hallucinations, advancing automated medical imaging and report analysis through integrated predictive and generative AI. Code is available at https://github.com/difeigu/RadAlign.

[Arxiv](https://arxiv.org/abs/2501.07525)