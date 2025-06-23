# # SHREC 和 PHEONA：借助大型语言模型推动下一代计算表型学的发展

发布时间：2025年06月19日

`LLM应用` `生物医学`

> SHREC and PHEONA: Using Large Language Models to Advance Next-Generation Computational Phenotyping

# 摘要

> 目标：计算表型分析是一项核心信息学活动，支持多种应用，但传统方法因人工数据审查、自动化不足及跨数据源适应困难而耗时较长。鉴于LLMs在文本处理方面的能力，我们认为它们在重复性人工审查任务中将表现出色。为此，我们开发了SHREC框架，用于将LLMs整合到端到端的表型分析流程中。

材料与方法：我们测试了Gemma2（270亿参数）、Mistral Small（240亿参数）和Phi-4（140亿参数）三个轻量级LLMs，评估它们在概念分类和患者表型分析方面的表现。

结果：所有模型在概念分类上表现优异，Mistral模型达到了0.896的AUROC。在表型分析中，模型在所有表型上均表现出色，Mistral模型在单疗法表型上达到了0.853的平均AUROC。

讨论：LLMs在计算表型分析中具有多项优势，包括仅通过提示工程即可适应新任务，以及能够处理原始电子健康记录（EHR）数据。未来研究将探索生物医学数据整合策略、LLMs推理机制及生成模型方法。

结论：轻量级LLMs在处理资源密集型表型分析任务（如人工数据审查）方面具有实际应用价值。


> Objective: Computational phenotyping is a central informatics activity with resulting cohorts supporting a wide variety of applications. However, it is time-intensive because of manual data review, limited automation, and difficulties in adapting algorithms across sources. Since LLMs have demonstrated promising capabilities for text classification, comprehension, and generation, we posit they will perform well at repetitive manual review tasks traditionally performed by human experts. To support next-generation computational phenotyping methods, we developed SHREC, a framework for comprehensive integration of LLMs into end-to-end phenotyping pipelines. Materials and Methods: We applied and tested the ability of three lightweight LLMs (Gemma2 27 billion, Mistral Small 24 billion, and Phi-4 14 billion) to classify concepts and phenotype patients using previously developed phenotypes for ARF respiratory support therapies. Results: All models performed well on concept classification, with the best model (Mistral) achieving an AUROC of 0.896 across all relevant concepts. For phenotyping, models demonstrated near-perfect specificity for all phenotypes, and the top-performing model (Mistral) reached an average AUROC of 0.853 for single-therapy phenotypes, despite lower performance on multi-therapy phenotypes. Discussion: There are several advantages of LLMs that support their application to computational phenotyping, such as their ability to adapt to new tasks with prompt engineering alone and their ability to incorporate raw EHR data. Future steps to advance next-generation phenotyping methods include determining optimal strategies for integrating biomedical data, exploring how LLMs reason, and advancing generative model methods. Conclusion: Current lightweight LLMs can feasibly assist researchers with resource-intensive phenotyping tasks such as manual data review.

[Arxiv](https://arxiv.org/abs/2506.16359)