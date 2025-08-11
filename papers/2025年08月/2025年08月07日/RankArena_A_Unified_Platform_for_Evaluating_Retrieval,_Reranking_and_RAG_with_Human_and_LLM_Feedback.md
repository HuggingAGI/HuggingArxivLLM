# RankArena是一个统一平台，用于通过人类和LLM反馈评估检索、重排序和RAG。

发布时间：2025年08月07日

`RAG` `信息检索` `搜索引擎优化`

> RankArena: A Unified Platform for Evaluating Retrieval, Reranking and RAG with Human and LLM Feedback

# 摘要

> 评估检索增强生成（RAG）和文档重排序系统的质量仍然充满挑战，因为缺乏可扩展、以用户为中心且多角度的评估工具。我们引入了RankArena，一个统一的平台，用于通过结构化的人员和基于大语言模型（LLM）的反馈来比较和分析检索流水线、重排序器和RAG系统的性能，同时也用于收集此类反馈。

RankArena支持多种评估模式：直接重排序可视化、盲测对比（可选人工或LLM投票）、监督式人工文档标注以及端到端RAG回答质量评估。它通过成对偏好和全列表标注捕捉细粒度的相关性反馈，同时记录辅助元数据，如移动指标、标注时间和质量评分。该平台还集成了LLM作为评估裁判的功能，支持模型生成排序与人工真实标注之间的对比。

所有交互都被存储为结构化的评估数据集，可用于训练重排序器、奖励模型、判断代理或检索策略选择器。我们的平台公开可用，地址是https://rankarena.ngrok.io/，并提供了演示视频https://youtu.be/jIYAP4PaSSI。


> Evaluating the quality of retrieval-augmented generation (RAG) and document reranking systems remains challenging due to the lack of scalable, user-centric, and multi-perspective evaluation tools. We introduce RankArena, a unified platform for comparing and analysing the performance of retrieval pipelines, rerankers, and RAG systems using structured human and LLM-based feedback as well as for collecting such feedback. RankArena supports multiple evaluation modes: direct reranking visualisation, blind pairwise comparisons with human or LLM voting, supervised manual document annotation, and end-to-end RAG answer quality assessment. It captures fine-grained relevance feedback through both pairwise preferences and full-list annotations, along with auxiliary metadata such as movement metrics, annotation time, and quality ratings. The platform also integrates LLM-as-a-judge evaluation, enabling comparison between model-generated rankings and human ground truth annotations. All interactions are stored as structured evaluation datasets that can be used to train rerankers, reward models, judgment agents, or retrieval strategy selectors. Our platform is publicly available at https://rankarena.ngrok.io/, and the Demo video is provided https://youtu.be/jIYAP4PaSSI.

[Arxiv](https://arxiv.org/abs/2508.05512)