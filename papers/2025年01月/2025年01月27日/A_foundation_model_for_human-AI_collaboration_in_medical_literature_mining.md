# 一个支持人类与AI协作的医学文献挖掘基础模型

发布时间：2025年01月27日

`LLM应用

理由：这篇论文介绍了一个名为LEADS的AI基础模型，该模型专门为医学文献搜索、筛选和数据提取设计。它基于大量的指令数据进行训练，并在多项任务上优于通用的大型语言模型（LLMs）。论文还展示了LEADS在实际医学研究中的应用效果，表明其在提升医学文献挖掘质量和效率方面的潜力。因此，这篇论文属于LLM应用类别，因为它专注于将大型语言模型应用于特定领域（医学文献挖掘）的实际问题。` `文献挖掘`

> A foundation model for human-AI collaboration in medical literature mining

# 摘要

> # 摘要
系统文献综述是循证医学的基石，需要对临床试验文献进行全面分析。然而，AI模型在医学文献挖掘中的应用因广泛治疗领域和多样化任务中训练和评估不足而受限。本文介绍LEADS，一个专为医学文献搜索、筛选和数据提取设计的AI基础模型。该模型基于LEADSInstruct中的633,759个指令数据点进行训练，数据源自21,335篇系统综述、453,625篇临床试验文献和27,015个临床试验注册表。LEADS在六项任务上持续优于四种前沿通用LLMs。此外，LEADS通过提供专家请求的支持性参考文献，简化流程并保持高质量结果。一项涉及14个机构16名临床医生和医学研究人员的研究显示，与LEADS合作的专家在研究选择中的召回率达0.81，高于单独工作的0.77，时间节省22.6%。在数据提取任务中，使用LEADS的专家准确率达0.85，高于未使用时的0.80，时间节省26.9%。这些发现表明，专业医学文献基础模型在超越通用模型方面具有潜力，集成到医学文献挖掘的专家工作流程中可显著提升质量和效率。

> Systematic literature review is essential for evidence-based medicine, requiring comprehensive analysis of clinical trial publications. However, the application of artificial intelligence (AI) models for medical literature mining has been limited by insufficient training and evaluation across broad therapeutic areas and diverse tasks. Here, we present LEADS, an AI foundation model for study search, screening, and data extraction from medical literature. The model is trained on 633,759 instruction data points in LEADSInstruct, curated from 21,335 systematic reviews, 453,625 clinical trial publications, and 27,015 clinical trial registries. We showed that LEADS demonstrates consistent improvements over four cutting-edge generic large language models (LLMs) on six tasks. Furthermore, LEADS enhances expert workflows by providing supportive references following expert requests, streamlining processes while maintaining high-quality results. A study with 16 clinicians and medical researchers from 14 different institutions revealed that experts collaborating with LEADS achieved a recall of 0.81 compared to 0.77 experts working alone in study selection, with a time savings of 22.6%. In data extraction tasks, experts using LEADS achieved an accuracy of 0.85 versus 0.80 without using LEADS, alongside a 26.9% time savings. These findings highlight the potential of specialized medical literature foundation models to outperform generic models, delivering significant quality and efficiency benefits when integrated into expert workflows for medical literature mining.

[Arxiv](https://arxiv.org/abs/2501.16255)