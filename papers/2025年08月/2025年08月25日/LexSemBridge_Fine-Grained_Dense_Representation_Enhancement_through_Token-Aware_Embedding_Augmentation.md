# LexSemBridge：基于标记感知嵌入增强的细粒度密集表示优化

发布时间：2025年08月25日

`RAG` `基础理论`

> LexSemBridge: Fine-Grained Dense Representation Enhancement through Token-Aware Embedding Augmentation

# 摘要

> 在大型语言模型（LLMs）驱动的检索增强生成（RAG）管道中，查询正变得愈发复杂多样。尽管密集检索模型在语义匹配上表现出色，却常在细粒度检索任务中捉襟见肘——这类任务要求精确的关键词对齐与跨度定位，即便存在高词汇重叠（直观上检索应更简单）也不例外。为系统评估这一局限，我们设计了关键词检索与段落部分检索两个针对性任务，以模拟实际细粒度场景。基于这些发现，我们提出LexSemBridge——一个通过细粒度、输入感知向量调制增强密集查询表示的统一框架。该框架通过统计型（SLR）、学习型（LLR）和上下文型（CLR）三种范式从输入标记构建潜在增强向量，并经元素级交互与密集嵌入融合。理论分析表明，这种调制在保留语义方向的同时，能选择性放大判别维度。LexSemBridge作为即插即用模块，无需修改主干编码器，且可自然扩展至文本与视觉模态。在语义及细粒度检索任务上的大量实验验证了该方法的有效性与通用性。所有代码和模型已公开于https://github.com/Jasaxion/LexSemBridge/

> As queries in retrieval-augmented generation (RAG) pipelines powered by large language models (LLMs) become increasingly complex and diverse, dense retrieval models have demonstrated strong performance in semantic matching. Nevertheless, they often struggle with fine-grained retrieval tasks, where precise keyword alignment and span-level localization are required, even in cases with high lexical overlap that would intuitively suggest easier retrieval. To systematically evaluate this limitation, we introduce two targeted tasks, keyword retrieval and part-of-passage retrieval, designed to simulate practical fine-grained scenarios. Motivated by these observations, we propose LexSemBridge, a unified framework that enhances dense query representations through fine-grained, input-aware vector modulation. LexSemBridge constructs latent enhancement vectors from input tokens using three paradigms: Statistical (SLR), Learned (LLR), and Contextual (CLR), and integrates them with dense embeddings via element-wise interaction. Theoretically, we show that this modulation preserves the semantic direction while selectively amplifying discriminative dimensions. LexSemBridge operates as a plug-in without modifying the backbone encoder and naturally extends to both text and vision modalities. Extensive experiments across semantic and fine-grained retrieval tasks validate the effectiveness and generality of our approach. All code and models are publicly available at https://github.com/Jasaxion/LexSemBridge/

[Arxiv](https://arxiv.org/abs/2508.17858)