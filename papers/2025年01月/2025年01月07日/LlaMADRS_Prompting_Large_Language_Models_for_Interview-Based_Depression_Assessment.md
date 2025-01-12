# LlaMADRS: 利用大型语言模型进行访谈式抑郁症评估

发布时间：2025年01月07日

`LLM应用

理由：该论文主要探讨了如何利用开源大型语言模型（LLMs）来自动评估抑郁严重程度，属于将LLM应用于特定领域（心理健康评估）的实际应用场景。因此，分类为“LLM应用”是合适的。` `心理健康` `临床评估`

> LlaMADRS: Prompting Large Language Models for Interview-Based Depression Assessment

# 摘要

> 本研究提出了LlaMADRS框架，利用开源大型语言模型（LLMs）自动评估抑郁严重程度，基于蒙哥马利-阿斯伯格抑郁评定量表（MADRS）。我们采用零-shot提示策略，通过精心设计的提示引导模型解读和评分临床访谈。在CAMI数据集的236个真实访谈中测试，结果显示与临床医生评估高度相关。Qwen 2.5--72b模型在多数MADRS项目上接近人类评分者的一致性，ICC值接近人类评分者间的相关系数。我们全面分析了模型在不同MADRS项目上的表现，指出了其优势和局限。研究表明，适当提示下，LLMs可作为心理健康评估的有效工具，尤其在资源有限的环境中提升可及性。然而，评估依赖非语言线索的症状仍具挑战，未来需探索多模态方法。

> This study introduces LlaMADRS, a novel framework leveraging open-source Large Language Models (LLMs) to automate depression severity assessment using the Montgomery-Asberg Depression Rating Scale (MADRS). We employ a zero-shot prompting strategy with carefully designed cues to guide the model in interpreting and scoring transcribed clinical interviews. Our approach, tested on 236 real-world interviews from the Context-Adaptive Multimodal Informatics (CAMI) dataset, demonstrates strong correlations with clinician assessments. The Qwen 2.5--72b model achieves near-human level agreement across most MADRS items, with Intraclass Correlation Coefficients (ICC) closely approaching those between human raters. We provide a comprehensive analysis of model performance across different MADRS items, highlighting strengths and current limitations. Our findings suggest that LLMs, with appropriate prompting, can serve as efficient tools for mental health assessment, potentially increasing accessibility in resource-limited settings. However, challenges remain, particularly in assessing symptoms that rely on non-verbal cues, underscoring the need for multimodal approaches in future work.

[Arxiv](https://arxiv.org/abs/2501.03624)