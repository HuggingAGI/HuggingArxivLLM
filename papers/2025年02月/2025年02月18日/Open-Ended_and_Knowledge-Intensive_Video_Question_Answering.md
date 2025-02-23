# 开放式知识密集型视频问答

发布时间：2025年02月18日

`RAG` `问答系统`

> Open-Ended and Knowledge-Intensive Video Question Answering

# 摘要

> 视频问答中需要超越视觉内容的外部知识仍然是AI系统的一大难题。现有模型虽能有效回答基于视觉观察的问题，但面对需要更广泛知识储备的问题时往往力不从心。为此，我们通过多模态检索增强生成的方法，深入研究了知识密集型视频问答（KI-VideoQA），尤其关注开放性问题的处理。我们采用前沿的检索与视觉语言模型，全面测试了零样本与微调配置下的多种检索增强策略。研究重点围绕以下维度展开：信息源与模态间的交互作用、多模态上下文整合策略，以及查询构建与检索结果利用的动态平衡。研究发现，检索增强虽能显著提升模型性能，但其效果 heavily 取决于模态选择与检索方法。同时，查询构建与检索深度优化在知识整合中扮演着关键角色。通过我们的方法，在KnowIT VQA数据集的多选题测试中，准确率实现了17.5%的显著提升，树立了新的性能标杆。

> Video question answering that requires external knowledge beyond the visual content remains a significant challenge in AI systems. While models can effectively answer questions based on direct visual observations, they often falter when faced with questions requiring broader contextual knowledge. To address this limitation, we investigate knowledge-intensive video question answering (KI-VideoQA) through the lens of multi-modal retrieval-augmented generation, with a particular focus on handling open-ended questions rather than just multiple-choice formats. Our comprehensive analysis examines various retrieval augmentation approaches using cutting-edge retrieval and vision language models, testing both zero-shot and fine-tuned configurations. We investigate several critical dimensions: the interplay between different information sources and modalities, strategies for integrating diverse multi-modal contexts, and the dynamics between query formulation and retrieval result utilization. Our findings reveal that while retrieval augmentation shows promise in improving model performance, its success is heavily dependent on the chosen modality and retrieval methodology. The study also highlights the critical role of query construction and retrieval depth optimization in effective knowledge integration. Through our proposed approach, we achieve a substantial 17.5% improvement in accuracy on multiple choice questions in the KnowIT VQA dataset, establishing new state-of-the-art performance levels.

[Arxiv](https://arxiv.org/abs/2502.11747)