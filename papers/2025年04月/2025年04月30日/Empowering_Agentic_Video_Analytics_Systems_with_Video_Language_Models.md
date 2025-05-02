# # 摘要
最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。

发布时间：2025年04月30日

`LLM应用` `视频分析` `视频语言模型`

> Empowering Agentic Video Analytics Systems with Video Language Models

# 摘要

> AI驱动的视频分析在多个领域发挥着越来越重要的作用。然而，现有系统往往受限于特定的预定义任务，难以适应开放性分析场景。近期，作为变革性技术的视频语言模型（VLMs）的出现，为实现开放式的视频理解、推理和分析带来了巨大潜力。然而，它们有限的上下文窗口在处理超长视频内容时带来了挑战，而这类内容在现实应用中非常普遍。为了解决这一问题，我们推出了AVA——一个基于VLM的系统，专为开放式的高级视频分析设计。AVA的两大创新点包括：（1）准实时构建事件知识图谱（EKGs），以便高效索引长或连续的视频流；（2）一种基于EKGs的智能检索生成机制，能够处理复杂多样的查询。在LVBench和VideoMME-Long这两个公共基准测试上的全面评估表明，AVA表现优异，分别达到了62.3%和64.1%的准确率，远超现有视频语言模型和视频检索增强生成（RAG）系统。此外，为了评估超长开放世界视频场景下的视频分析效果，我们引入了一个新的基准测试AVA-100。该基准包含8个视频，每个视频时长超过10小时，以及120个手动标注的多样化复杂问答对。在AVA-100上，AVA表现卓越，准确率达到75.8%。

> AI-driven video analytics has become increasingly pivotal across diverse domains. However, existing systems are often constrained to specific, predefined tasks, limiting their adaptability in open-ended analytical scenarios. The recent emergence of Video-Language Models (VLMs) as transformative technologies offers significant potential for enabling open-ended video understanding, reasoning, and analytics. Nevertheless, their limited context windows present challenges when processing ultra-long video content, which is prevalent in real-world applications. To address this, we introduce AVA, a VLM-powered system designed for open-ended, advanced video analytics. AVA incorporates two key innovations: (1) the near real-time construction of Event Knowledge Graphs (EKGs) for efficient indexing of long or continuous video streams, and (2) an agentic retrieval-generation mechanism that leverages EKGs to handle complex and diverse queries. Comprehensive evaluations on public benchmarks, LVBench and VideoMME-Long, demonstrate that AVA achieves state-of-the-art performance, attaining 62.3% and 64.1% accuracy, respectively, significantly surpassing existing VLM and video Retrieval-Augmented Generation (RAG) systems. Furthermore, to evaluate video analytics in ultra-long and open-world video scenarios, we introduce a new benchmark, AVA-100. This benchmark comprises 8 videos, each exceeding 10 hours in duration, along with 120 manually annotated, diverse, and complex question-answer pairs. On AVA-100, AVA achieves top-tier performance with an accuracy of 75.8%.

[Arxiv](https://arxiv.org/abs/2505.00254)