# Look & Mark: 基于多模态大型语言模型的放射科医生视线固定点和边界框，实现胸部X光报告自动生成

发布时间：2025年05月28日

`LLM应用

理由：这篇论文讨论了多模态大型语言模型在医学图像分析中的应用，特别是在生成放射科报告方面，并提出了一种新的策略来提高模型的性能和可靠性。虽然提到了模型的改进，但重点在于实际应用中的表现和效果，因此归类为LLM应用。` `医学影像`

> Look & Mark: Leveraging Radiologist Eye Fixations and Bounding boxes in Multimodal Large Language Models for Chest X-ray Report Generation

# 摘要

> 多模态大型语言模型（LLMs）的最新进展显著提升了医学图像分析的自动化水平，尤其在从胸部X光片（CXR）生成放射科报告方面表现突出。然而，这些模型仍存在幻觉现象和临床上重要的错误，限制了其在实际应用中的可靠性。本研究提出了一种名为Look & Mark (L&M) 的新型接地固定策略，该策略将放射科医生的注视点（Look）和边界框标注（Mark）整合到LLM提示框架中。与传统的微调方法不同，L&M 利用上下文学习无需重新训练即可实现显著的性能提升。在多个领域特定模型和通用模型上的评估表明，L&M表现优异。与基线提示相比，CXR-LLaVA的整体指标（A.AVG）提升了1.2%，而LLaVA-Med更是大幅提升了9.2%。通用模型在结合上下文学习和L&M后也表现出色，LLaVA-OV在临床平均表现（C.AVG）上达到了87.3%——这是所有模型中的最高水平，甚至超过了专门针对CXR报告生成训练的模型。专家评估进一步证实，L&M减少了临床上重要的错误（平均每份报告减少0.43个错误），如错误预测和遗漏，从而提高了准确性和可靠性。这些发现凸显了L&M在AI辅助放射学中的可扩展性和高效性潜力，为资源有限的临床环境中改进诊断工作流程铺平了道路。

> Recent advancements in multimodal Large Language Models (LLMs) have significantly enhanced the automation of medical image analysis, particularly in generating radiology reports from chest X-rays (CXR). However, these models still suffer from hallucinations and clinically significant errors, limiting their reliability in real-world applications. In this study, we propose Look & Mark (L&M), a novel grounding fixation strategy that integrates radiologist eye fixations (Look) and bounding box annotations (Mark) into the LLM prompting framework. Unlike conventional fine-tuning, L&M leverages in-context learning to achieve substantial performance gains without retraining. When evaluated across multiple domain-specific and general-purpose models, L&M demonstrates significant gains, including a 1.2% improvement in overall metrics (A.AVG) for CXR-LLaVA compared to baseline prompting and a remarkable 9.2% boost for LLaVA-Med. General-purpose models also benefit from L&M combined with in-context learning, with LLaVA-OV achieving an 87.3% clinical average performance (C.AVG)-the highest among all models, even surpassing those explicitly trained for CXR report generation. Expert evaluations further confirm that L&M reduces clinically significant errors (by 0.43 average errors per report), such as false predictions and omissions, enhancing both accuracy and reliability. These findings highlight L&M's potential as a scalable and efficient solution for AI-assisted radiology, paving the way for improved diagnostic workflows in low-resource clinical settings.

[Arxiv](https://arxiv.org/abs/2505.22222)