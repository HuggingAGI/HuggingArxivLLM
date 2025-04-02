# WikiVideo：多视频文章生成

发布时间：2025年04月01日

`RAG` `内容生成` `多模态处理`

> WikiVideo: Article Generation from Multiple Videos

# 摘要

> 我们提出了一个具有挑战性的任务：自动创建一篇类似维基百科的高质量文章，该文章从多个关于现实世界事件（如自然灾害或政治选举）的多样化视频中汇总信息。视频作为检索增强生成（RAG）的直觉来源，但当代RAG工作流程多聚焦于文本，而现有视频摘要方法侧重于低级别场景理解，而非高级别事件语义。为填补这一空白，我们引入了WikiVideo，这是一个包含专家撰写文章和密集标注视频的基准数据集，视频为文章主张提供证据，促进视频在RAG流水线中的整合，支持基于多模态来源创建深入内容。我们还提出了协作式文章生成（CAG），这是一种从多个视频创建文章的新型交互方法。CAG通过r1风格推理模型与VideoLLM的迭代交互，实现对目标事件的高层次推理，超越VideoLLM单独使用时仅关注低级别视觉特征的局限。我们在oracle检索和RAG设置下对最先进的VideoLLM和CAG进行了基准测试，发现CAG始终优于其他方法，同时为未来研究提供了有趣思路。

> We present the challenging task of automatically creating a high-level Wikipedia-style article that aggregates information from multiple diverse videos about real-world events, such as natural disasters or political elections. Videos are intuitive sources for retrieval-augmented generation (RAG), but most contemporary RAG workflows focus heavily on text and existing methods for video-based summarization focus on low-level scene understanding rather than high-level event semantics. To close this gap, we introduce WikiVideo, a benchmark consisting of expert-written articles and densely annotated videos that provide evidence for articles' claims, facilitating the integration of video into RAG pipelines and enabling the creation of in-depth content that is grounded in multimodal sources. We further propose Collaborative Article Generation (CAG), a novel interactive method for article creation from multiple videos. CAG leverages an iterative interaction between an r1-style reasoning model and a VideoLLM to draw higher level inferences about the target event than is possible with VideoLLMs alone, which fixate on low-level visual features. We benchmark state-of-the-art VideoLLMs and CAG in both oracle retrieval and RAG settings and find that CAG consistently outperforms alternative methods, while suggesting intriguing avenues for future work.

[Arxiv](https://arxiv.org/abs/2504.00939)