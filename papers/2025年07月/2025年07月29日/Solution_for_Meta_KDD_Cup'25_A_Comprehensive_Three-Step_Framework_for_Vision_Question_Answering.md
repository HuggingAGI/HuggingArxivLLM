# Meta KDD Cup'25参赛方案：面向视觉问答的系统性三步框架

发布时间：2025年07月29日

`RAG` `计算机视觉` `多模态处理`

> Solution for Meta KDD Cup'25: A Comprehensive Three-Step Framework for Vision Question Answering

# 摘要

> 视觉大型语言模型（VLLMs）在多模态理解和视觉问答（VQA）方面表现优异，但幻觉答案的问题仍然存在。多模态检索增强生成（RAG）通过引入外部信息帮助解决这些问题，但在视觉上下文理解、多源检索和多轮交互方面仍面临挑战。为应对这些挑战，Meta构建了CRAG-MM基准，并在KDD Cup 2025中发起了CRAG-MM挑战赛，该挑战赛包含三个任务。本文描述了Meta KDD Cup'25比赛中BlackPearl团队在所有任务中的解决方案。我们为每个任务使用单一模型，关键方法包括数据增强、RAG、重排序和多任务微调。我们的解决方案在三个任务的自动评估中分别取得了第3、第3和第1名，并在人工评估后Task3获得第二名。

> Vision Large Language Models (VLLMs) have improved multi-modal understanding and visual question answering (VQA), but still suffer from hallucinated answers. Multi-modal Retrieval-Augmented Generation (RAG) helps address these issues by incorporating external information, yet challenges remain in visual context comprehension, multi-source retrieval, and multi-turn interactions. To address these challenges, Meta constructed the CRAG-MM benchmark and launched the CRAG-MM Challenge at KDD Cup 2025, which consists of three tasks. This paper describes the solutions of all tasks in Meta KDD Cup'25 from BlackPearl team. We use a single model for each task, with key methods including data augmentation, RAG, reranking, and multi-task fine-tuning. Our solution achieve automatic evaluation rankings of 3rd, 3rd, and 1st on the three tasks, and win second place in Task3 after human evaluation.

[Arxiv](https://arxiv.org/abs/2507.21520)