# 借助大型语言模型实现老年痴呆症的少样本诊断：基于表格化生物标志物数据的研究

发布时间：2025年07月30日

`LLM应用` `生物医学`

> Enabling Few-Shot Alzheimer's Disease Diagnosis on Tabular Biomarker Data with LLMs

# 摘要

> 阿尔茨海默病（AD）作为一种复杂的神经退行性疾病，其早期和准确诊断需要分析异质性生物标志物（如神经影像、遗传风险因素、认知测试和脑脊液蛋白质），这些数据通常以表格形式呈现。借助灵活的少样本推理能力、多模态整合以及基于自然语言的可解释性，大型语言模型（LLMs）为利用结构化生物医学数据进行预测提供了前所未有的机遇。

我们提出了一种名为TAP-GPT（表格式阿尔茨海默病预测GPT）的新框架，该框架将最初为商业智能任务开发的多模态表格专用LLM——TableGPT2，适应于利用小样本结构化生物标志数据进行AD诊断。我们的方法通过使用结构化生物医学数据中的上下文学习示例构建少样本表格提示，并使用参数高效的qLoRA适配方法对TableGPT2进行微调，以解决AD或认知正常（CN）的临床二分类任务。

TAP-GPT框架充分利用了TableGPT2强大的表格理解能力和LLMs编码的先验知识，超越了更先进的通用LLMs和专门用于预测任务的表格基础模型（TFM）。据我们所知，这是首次将LLMs应用于利用表格生物标志数据进行预测任务，为未来基于LLMs的生物医学信息学多智能体框架铺平了道路。

> Early and accurate diagnosis of Alzheimer's disease (AD), a complex neurodegenerative disorder, requires analysis of heterogeneous biomarkers (e.g., neuroimaging, genetic risk factors, cognitive tests, and cerebrospinal fluid proteins) typically represented in a tabular format. With flexible few-shot reasoning, multimodal integration, and natural-language-based interpretability, large language models (LLMs) offer unprecedented opportunities for prediction with structured biomedical data. We propose a novel framework called TAP-GPT, Tabular Alzheimer's Prediction GPT, that adapts TableGPT2, a multimodal tabular-specialized LLM originally developed for business intelligence tasks, for AD diagnosis using structured biomarker data with small sample sizes. Our approach constructs few-shot tabular prompts using in-context learning examples from structured biomedical data and finetunes TableGPT2 using the parameter-efficient qLoRA adaption for a clinical binary classification task of AD or cognitively normal (CN). The TAP-GPT framework harnesses the powerful tabular understanding ability of TableGPT2 and the encoded prior knowledge of LLMs to outperform more advanced general-purpose LLMs and a tabular foundation model (TFM) developed for prediction tasks. To our knowledge, this is the first application of LLMs to the prediction task using tabular biomarker data, paving the way for future LLM-driven multi-agent frameworks in biomedical informatics.

[Arxiv](https://arxiv.org/abs/2507.23227)