# 大型多模态模型地图解析用于文本位置地理标注

发布时间：2025年07月11日

`LLM应用

理由：这篇论文主要探讨了如何利用大型多模态模型（LMM）在地理标注任务中的应用，属于LLM应用类别。` `自然历史` `地理信息系统`

> Large Multi-modal Model Cartographic Map Comprehension for Textual Locality Georeferencing

# 摘要

> 数百万生物样本记录存档于自然历史收藏中，尚未地理标注。对复杂地理位置描述的地理标注是一项耗时费力的工作，采集机构深感困扰。现有自动化方法均未利用地图这一地理标注的必备工具。我们介绍了一种新颖方法，利用近期大型多模态模型（LMM）的多模态能力，使模型能够通过视觉方式理解地理位置描述中的空间关系。我们采用基于网格的方法，在零样本设置下将自回归模型适配于该任务。实验结果表明，相较于大型语言模型和现有工具的单模态地理标注，我们的方法（平均距离误差约1公里）表现优异。本文还探讨了LMM理解精细地图的能力，并提出了一种实用框架，将此方法整合到地理标注工作流程中。

> Millions of biological sample records collected in the last few centuries archived in natural history collections are un-georeferenced. Georeferencing complex locality descriptions associated with these collection samples is a highly labour-intensive task collection agencies struggle with. None of the existing automated methods exploit maps that are an essential tool for georeferencing complex relations. We present preliminary experiments and results of a novel method that exploits multi-modal capabilities of recent Large Multi-Modal Models (LMM). This method enables the model to visually contextualize spatial relations it reads in the locality description. We use a grid-based approach to adapt these auto-regressive models for this task in a zero-shot setting. Our experiments conducted on a small manually annotated dataset show impressive results for our approach ($\sim$1 km Average distance error) compared to uni-modal georeferencing with Large Language Models and existing georeferencing tools. The paper also discusses the findings of the experiments in light of an LMM's ability to comprehend fine-grained maps. Motivated by these results, a practical framework is proposed to integrate this method into a georeferencing workflow.

[Arxiv](https://arxiv.org/abs/2507.08575)