# AIstorian：基于知识图谱的多智能体系统，让 AI 成为历史学家，准确生成人物传记

发布时间：2025年03月14日

`Agent` `历史研究`

> AIstorian lets AI be a historian: A KG-powered multi-agent system for accurate biography generation

# 摘要

> 华为一直致力于探索AI在历史研究中的应用。自传生成作为一种特殊的摘要形式，在历史研究中扮演着重要角色，但现有大型语言模型（LLMs）难以应对这一领域面临的独特挑战。这些挑战包括保持与历史写作规范一致的写作风格、确保事实准确性，以及处理多文档中分散的信息。

我们提出了AIstorian，这是一个创新的端到端智能体系统，具有基于知识图谱（KG）增强的检索增强生成（RAG）和抗幻觉多智能体功能。具体来说，AIstorian引入了一种基于上下文学习的分块策略和基于KG的索引，以实现准确高效的参考检索。同时，AIstorian协调多个智能体进行实时幻觉检测和错误类型感知的校正。

此外，为了教授LLMs某种语言风格，我们基于一种结合数据增强强化的监督微调和风格偏好优化的两步训练方法对LLMs进行了微调。在真实历史进士数据集上的广泛实验表明，与现有基线相比，AIstorian在事实准确性上实现了3.8倍的提升，并将幻觉率降低了47.6%。数据和代码可在以下链接获取：https://github.com/ZJU-DAILY/AIstorian。

> Huawei has always been committed to exploring the AI application in historical research. Biography generation, as a specialized form of abstractive summarization, plays a crucial role in historical research but faces unique challenges that existing large language models (LLMs) struggle to address. These challenges include maintaining stylistic adherence to historical writing conventions, ensuring factual fidelity, and handling fragmented information across multiple documents. We present AIstorian, a novel end-to-end agentic system featured with a knowledge graph (KG)-powered retrieval-augmented generation (RAG) and anti-hallucination multi-agents. Specifically, AIstorian introduces an in-context learning based chunking strategy and a KG-based index for accurate and efficient reference retrieval. Meanwhile, AIstorian orchestrates multi-agents to conduct on-the-fly hallucination detection and error-type-aware correction. Additionally, to teach LLMs a certain language style, we finetune LLMs based on a two-step training approach combining data augmentation-enhanced supervised fine-tuning with stylistic preference optimization. Extensive experiments on a real-life historical Jinshi dataset demonstrate that AIstorian achieves a 3.8x improvement in factual accuracy and a 47.6% reduction in hallucination rate compared to existing baselines. The data and code are available at: https://github.com/ZJU-DAILY/AIstorian.

[Arxiv](https://arxiv.org/abs/2503.11346)