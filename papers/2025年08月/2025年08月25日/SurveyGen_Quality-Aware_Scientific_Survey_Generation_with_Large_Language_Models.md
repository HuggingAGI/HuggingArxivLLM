# SurveyGen：借助大型语言模型的质量感知科学综述生成

发布时间：2025年08月25日

`RAG` `基础理论`

> SurveyGen: Quality-Aware Scientific Survey Generation with Large Language Models

# 摘要

> 自动综述生成已成为科学文献处理领域的关键任务。大型语言模型（LLMs）虽在综述文本生成上展现潜力，但标准化评估数据集的缺失严重阻碍了其与人类撰写综述的严格性能对比。为此，本研究提出SurveyGen数据集——一个涵盖4200余篇跨多个科学领域的人类撰写综述、242,143篇被引文献，以及综述与被引论文丰富质量相关元数据的大规模资源。基于该数据集，我们构建了QUAL-SG框架：这一新颖的质量感知综述生成框架通过将质量感知指标融入文献检索，评估并筛选更高质量的源论文，从而增强了标准的检索增强生成（RAG）管道。利用该数据集与框架，我们系统评估了最先进的大型语言模型在不同人类参与程度下的表现——从全自动生成到人类引导写作。实验结果与人类评估显示，尽管半自动管道能取得部分具有竞争力的结果，但全自动综述生成仍存在引用质量低和批判性分析不足的问题。

> Automatic survey generation has emerged as a key task in scientific document processing. While large language models (LLMs) have shown promise in generating survey texts, the lack of standardized evaluation datasets critically hampers rigorous assessment of their performance against human-written surveys. In this work, we present SurveyGen, a large-scale dataset comprising over 4,200 human-written surveys across diverse scientific domains, along with 242,143 cited references and extensive quality-related metadata for both the surveys and the cited papers. Leveraging this resource, we build QUAL-SG, a novel quality-aware framework for survey generation that enhances the standard Retrieval-Augmented Generation (RAG) pipeline by incorporating quality-aware indicators into literature retrieval to assess and select higher-quality source papers. Using this dataset and framework, we systematically evaluate state-of-the-art LLMs under varying levels of human involvement - from fully automatic generation to human-guided writing. Experimental results and human evaluations show that while semi-automatic pipelines can achieve partially competitive outcomes, fully automatic survey generation still suffers from low citation quality and limited critical analysis.

[Arxiv](https://arxiv.org/abs/2508.17647)