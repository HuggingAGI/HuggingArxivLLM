# LifeIR 在第18届 NTCIR 生命日志-6 任务中的表现

发布时间：2025年05月27日

`LLM应用` `可穿戴设备` `图像检索`

> LifeIR at the NTCIR-18 Lifelog-6 Task

# 摘要

> 近年来，通过智能手表、运动手表和GoPro等可穿戴设备记录的生活日志分享逐渐风靡。这些日志涵盖了图像、视频和GPS数据等多种信息类型，记录了用户的日常生活方式、饮食习惯和身体活动。在NTCIR-18 Lifelog-6挑战中，生活日志语义访问任务（LSAT）专注于根据描述动作或事件的文本查询，从大规模用户生活日志中检索相关图像，旨在帮助用户在历史生活日志中快速找到特定场景的图像。

针对这一基于文本搜索图像的任务，我们提出了一套多阶段的处理流程，以应对生活日志检索中的各种挑战。我们的流程包括：**过滤模糊图像**、**重写查询以明确意图**、**基于事件扩展候选集以纳入具有时间关联性的图像**，以及**使用具有更强相关性判断能力的多模态大型语言模型（MLLM）重新排序结果**。实验评估表明，我们提交的方案在各个阶段以及整体流程上均表现出了有效性。

> In recent years, sharing lifelogs recorded through wearable devices such as sports watches and GoPros, has gained significant popularity. Lifelogs involve various types of information, including images, videos, and GPS data, revealing users' lifestyles, dietary patterns, and physical activities. The Lifelog Semantic Access Task(LSAT) in the NTCIR-18 Lifelog-6 Challenge focuses on retrieving relevant images from a large scale of users' lifelogs based on textual queries describing an action or event. It serves users' need to find images about a scenario in the historical moments of their lifelogs. We propose a multi-stage pipeline for this task of searching images with texts, addressing various challenges in lifelog retrieval. Our pipeline includes: filtering blurred images, rewriting queries to make intents clearer, extending the candidate set based on events to include images with temporal connections, and reranking results using a multimodal large language model(MLLM) with stronger relevance judgment capabilities. The evaluation results of our submissions have shown the effectiveness of each stage and the entire pipeline.

[Arxiv](https://arxiv.org/abs/2505.20987)