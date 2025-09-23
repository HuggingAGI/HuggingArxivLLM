# AirQA：面向人工智能研究的综合问答数据集——支持实例级评估

发布时间：2025年09月21日

`Agent` `基础理论`

> AirQA: A Comprehensive QA Dataset for AI Research with Instance-Level Evaluation

# 摘要

> 学术论文数量激增，让研究者难以高效提取关键信息。虽然基于大型语言模型（LLMs）的智能体可自动化科学论文的问答（QA）工作流，但评估其能力的全面且真实的基准仍付阙如。此外，由于缺乏高质量交互轨迹，针对该特定任务训练交互智能体也面临阻碍。本研究中，我们提出了AirQA——一个人工智能（AI）领域的人工标注综合论文问答数据集，涵盖13,948篇论文与1,246个问题，支持多任务、多模态及实例级评估。同时，我们还提出了ExTrActor——一个用于指令数据合成的自动化框架。该框架通过三个基于LLM的智能体，可在无人干预下完成示例生成与轨迹收集。对多个开源和专有模型的评估显示，大多数模型在AirQA上表现欠佳，印证了我们数据集的质量。大量实验证实，ExTrActor能持续提升小模型的多轮工具使用能力，使其性能可与更大模型媲美。

> The growing volume of academic papers has made it increasingly difficult for researchers to efficiently extract key information. While large language models (LLMs) based agents are capable of automating question answering (QA) workflows for scientific papers, there still lacks a comprehensive and realistic benchmark to evaluate their capabilities. Moreover, training an interactive agent for this specific task is hindered by the shortage of high-quality interaction trajectories. In this work, we propose AirQA, a human-annotated comprehensive paper QA dataset in the field of artificial intelligence (AI), with 13,948 papers and 1,246 questions, that encompasses multi-task, multi-modal and instance-level evaluation. Furthermore, we propose ExTrActor, an automated framework for instruction data synthesis. With three LLM-based agents, ExTrActor can perform example generation and trajectory collection without human intervention. Evaluations of multiple open-source and proprietary models show that most models underperform on AirQA, demonstrating the quality of our dataset. Extensive experiments confirm that ExTrActor consistently improves the multi-turn tool-use capability of small models, enabling them to achieve performance comparable to larger ones.

[Arxiv](https://arxiv.org/abs/2509.16952)