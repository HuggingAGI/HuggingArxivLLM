# 从 RAG 到记忆：大型语言模型的持续学习新突破

发布时间：2025年02月20日

`RAG` `知识图谱`

> From RAG to Memory: Non-Parametric Continual Learning for Large Language Models

# 摘要

> 持续获取、组织和利用知识的能力是人类智能的显著特征，也是 AI 系统发挥潜力的关键。面对大型语言模型（LLMs）在持续学习中的挑战，检索增强生成（RAG）成为引入新信息的主要方式。然而，传统 RAG 对向量检索的依赖限制了其模拟人类长期记忆动态特性的能力。

近期研究通过结合知识图谱等结构增强向量嵌入，改进了 RAG 的意义理解和联想能力。然而，这些改进在基础事实记忆任务上的表现却显著低于标准 RAG。针对这一问题，我们推出了 HippoRAG 2，一个在事实、意义理解和联想记忆任务上全面超越标准 RAG 的框架。

HippoRAG 2 在原有个性化 PageRank 算法基础上，通过更深入的段落整合和更高效的在线 LLM 使用进行了全面优化。这一创新使 RAG 系统更接近人类长期记忆的效果，在联想记忆任务上比现有模型提升了 7% 的表现，同时在事实知识和意义理解能力上也实现了突破。这项研究为 LLM 的非参数持续学习奠定了基础。

我们的代码和数据已在 https://github.com/OSU-NLP-Group/HippoRAG 上开源，欢迎交流与合作。

> Our ability to continuously acquire, organize, and leverage knowledge is a key feature of human intelligence that AI systems must approximate to unlock their full potential. Given the challenges in continual learning with large language models (LLMs), retrieval-augmented generation (RAG) has become the dominant way to introduce new information. However, its reliance on vector retrieval hinders its ability to mimic the dynamic and interconnected nature of human long-term memory. Recent RAG approaches augment vector embeddings with various structures like knowledge graphs to address some of these gaps, namely sense-making and associativity. However, their performance on more basic factual memory tasks drops considerably below standard RAG. We address this unintended deterioration and propose HippoRAG 2, a framework that outperforms standard RAG comprehensively on factual, sense-making, and associative memory tasks. HippoRAG 2 builds upon the Personalized PageRank algorithm used in HippoRAG and enhances it with deeper passage integration and more effective online use of an LLM. This combination pushes this RAG system closer to the effectiveness of human long-term memory, achieving a 7% improvement in associative memory tasks over the state-of-the-art embedding model while also exhibiting superior factual knowledge and sense-making memory capabilities. This work paves the way for non-parametric continual learning for LLMs. Our code and data will be released at https://github.com/OSU-NLP-Group/HippoRAG.

[Arxiv](https://arxiv.org/abs/2502.14802)