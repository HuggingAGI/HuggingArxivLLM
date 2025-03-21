# 大型语言模型助力胰腺癌分期：检索增强生成的作用

发布时间：2025年03月19日

`RAG` `放射学`

> Enhancing Pancreatic Cancer Staging with Large Language Models: The Role of Retrieval-Augmented Generation

# 摘要

> 目的: 检索增强生成（RAG）是一种通过从可靠外部知识（REK）中检索相关信息来提升大型语言模型（LLMs）功能和可靠性的技术。RAG在放射学领域备受关注，我们此前已报告了NotebookLM（一种具备RAG功能的大型语言模型，简称RAG-LLM）在肺癌分期中的应用。然而，由于对比的LLM与NotebookLM的内部模型存在差异，尚不清楚其优势是源于RAG功能还是模型本身的差异。为了更好地孤立RAG的影响并评估其在不同癌症中的实用性，我们在胰腺癌分期实验中将NotebookLM与其内部的LLM Gemini 2.0 Flash进行了对比。

材料和方法: 我们采用日本胰腺癌分期指南的摘要作为可靠外部知识（REK），并基于CT检查结果对100例虚构的胰腺癌病例进行分期。研究对象分为三组：REK+/RAG+（NotebookLM结合REK）、REK+/RAG-（Gemini 2.0 Flash结合REK）、REK-/RAG-（Gemini 2.0 Flash不结合REK）。分期标准包括TNM分类、局部侵犯因素和可切除性分类。在REK+/RAG+组中，我们根据检索到的REK摘录的充分性来量化检索准确性。

结果: REK+/RAG+组的分期准确率达到70%，显著优于REK+/RAG-组（38%）和REK-/RAG-组（35%）。在TNM分类方面，REK+/RAG+组的准确率为80%，高于REK+/RAG-组（55%）和REK-/RAG-组（50%）。此外，REK+/RAG+组能够明确展示检索到的REK摘录，检索准确率达到92%。

结论: 在胰腺癌分期实验中，NotebookLM（一种RAG-LLM）的表现优于其内部的LLM Gemini 2.0 Flash，表明RAG功能可能显著提升LLM的分期准确性。此外，NotebookLM能够检索并展示REK摘录，为医生提供透明的依据，凸显了其在临床诊断和分类中的应用潜力。

> Purpose: Retrieval-augmented generation (RAG) is a technology to enhance the functionality and reliability of large language models (LLMs) by retrieving relevant information from reliable external knowledge (REK). RAG has gained interest in radiology, and we previously reported the utility of NotebookLM, an LLM with RAG (RAG-LLM), for lung cancer staging. However, since the comparator LLM differed from NotebookLM's internal model, it remained unclear whether its advantage stemmed from RAG or inherent model differences. To better isolate RAG's impact and assess its utility across different cancers, we compared NotebookLM with its internal LLM, Gemini 2.0 Flash, in a pancreatic cancer staging experiment.
  Materials and Methods: A summary of Japan's pancreatic cancer staging guidelines was used as REK. We compared three groups - REK+/RAG+ (NotebookLM with REK), REK+/RAG- (Gemini 2.0 Flash with REK), and REK-/RAG- (Gemini 2.0 Flash without REK) - in staging 100 fictional pancreatic cancer cases based on CT findings. Staging criteria included TNM classification, local invasion factors, and resectability classification. In REK+/RAG+, retrieval accuracy was quantified based on the sufficiency of retrieved REK excerpts.
  Results: REK+/RAG+ achieved a staging accuracy of 70%, outperforming REK+/RAG- (38%) and REK-/RAG- (35%). For TNM classification, REK+/RAG+ attained 80% accuracy, exceeding REK+/RAG- (55%) and REK-/RAG- (50%). Additionally, REK+/RAG+ explicitly presented retrieved REK excerpts, achieving a retrieval accuracy of 92%.
  Conclusion: NotebookLM, a RAG-LLM, outperformed its internal LLM, Gemini 2.0 Flash, in a pancreatic cancer staging experiment, suggesting that RAG may improve LLM's staging accuracy. Furthermore, its ability to retrieve and present REK excerpts provides transparency for physicians, highlighting its applicability for clinical diagnosis and classification.

[Arxiv](https://arxiv.org/abs/2503.15664)