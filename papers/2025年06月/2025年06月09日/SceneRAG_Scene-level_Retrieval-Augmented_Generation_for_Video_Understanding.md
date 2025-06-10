# SceneRAG：基于场景级别的检索增强生成方法，助力视频理解

发布时间：2025年06月09日

`RAG` `视频处理` `知识图谱`

> SceneRAG: Scene-level Retrieval-Augmented Generation for Video Understanding

# 摘要

> 尽管视频理解领域的检索增强生成（RAG）取得了进展，但长视频内容的理解仍具挑战。现有方法常将视频分割为固定片段，破坏了场景的连贯性。我们提出SceneRAG框架，通过处理ASR文本和时间元数据，利用大型语言模型将视频分割为叙事一致的场景。SceneRAG通过轻量级启发式方法优化场景边界，并融合视觉与文本信息构建知识图谱，实现跨场景的多跳检索与生成。在LongerVideos基准测试中，SceneRAG显著超越了现有方法，在生成任务中胜率高达72.5%。

> Despite recent advances in retrieval-augmented generation (RAG) for video understanding, effectively understanding long-form video content remains underexplored due to the vast scale and high complexity of video data. Current RAG approaches typically segment videos into fixed-length chunks, which often disrupts the continuity of contextual information and fails to capture authentic scene boundaries. Inspired by the human ability to naturally organize continuous experiences into coherent scenes, we present SceneRAG, a unified framework that leverages large language models to segment videos into narrative-consistent scenes by processing ASR transcripts alongside temporal metadata. SceneRAG further sharpens these initial boundaries through lightweight heuristics and iterative correction. For each scene, the framework fuses information from both visual and textual modalities to extract entity relations and dynamically builds a knowledge graph, enabling robust multi-hop retrieval and generation that account for long-range dependencies. Experiments on the LongerVideos benchmark, featuring over 134 hours of diverse content, confirm that SceneRAG substantially outperforms prior baselines, achieving a win rate of up to 72.5 percent on generation tasks.

[Arxiv](https://arxiv.org/abs/2506.07600)