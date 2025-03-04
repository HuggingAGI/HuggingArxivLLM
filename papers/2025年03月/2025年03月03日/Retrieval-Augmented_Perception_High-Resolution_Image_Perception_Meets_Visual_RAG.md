# # 检索增强感知：高分辨率图像感知邂逅视觉 RAG

发布时间：2025年03月03日

`RAG` `计算机视觉`

> Retrieval-Augmented Perception: High-Resolution Image Perception Meets Visual RAG

# 摘要

> 高分辨率图像感知仍是多模态大型语言模型中的重要挑战。本文摒弃传统启发式方法，转而通过提升模型的长上下文能力来优化 HR 感知，这一思路受到检索增强生成（RAG）等技术的启发。我们首次将 RAG 应用于 HR 感知研究，提出了一种无需训练的 RAP 框架，通过检索和融合图像片段并保留空间上下文来提升感知效果。为了适应不同任务需求，我们设计了动态选择最优图像片段数量的 RE-Search 方法，基于模型置信度和检索得分进行优化。实验结果表明，RAP 在 HR 基准测试中表现优异，LLaVA-v1.5-13B 在 $V^*$ Bench 和 HR-Bench 上分别提升了 43% 和 19%。


> High-resolution (HR) image perception remains a key challenge in multimodal large language models (MLLMs). To overcome the limitations of existing methods, this paper shifts away from prior dedicated heuristic approaches and revisits the most fundamental idea to HR perception by enhancing the long-context capability of MLLMs, driven by recent advances in long-context techniques like retrieval-augmented generation (RAG) for general LLMs. Towards this end, this paper presents the first study exploring the use of RAG to address HR perception challenges. Specifically, we propose Retrieval-Augmented Perception (RAP), a training-free framework that retrieves and fuses relevant image crops while preserving spatial context using the proposed Spatial-Awareness Layout. To accommodate different tasks, the proposed Retrieved-Exploration Search (RE-Search) dynamically selects the optimal number of crops based on model confidence and retrieval scores. Experimental results on HR benchmarks demonstrate the significant effectiveness of RAP, with LLaVA-v1.5-13B achieving a 43% improvement on $V^*$ Bench and 19% on HR-Bench.

[Arxiv](https://arxiv.org/abs/2503.01222)