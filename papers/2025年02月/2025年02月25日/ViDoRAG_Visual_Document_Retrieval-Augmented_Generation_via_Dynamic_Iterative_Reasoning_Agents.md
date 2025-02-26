# ViDoRAG: 视觉文档检索增强生成的动态迭代推理代理方法

发布时间：2025年02月25日

`RAG` `视觉文档` `复杂推理`

> ViDoRAG: Visual Document Retrieval-Augmented Generation via Dynamic Iterative Reasoning Agents

# 摘要

> 理解视觉丰富文档中的信息对传统检索增强生成（RAG）方法仍具挑战性。现有基准主要关注基于图像的问题回答（QA），却忽视了在密集视觉文档中高效检索、理解和推理的关键挑战。为此，我们推出了ViDoSeek——一个专为评估复杂推理场景下RAG性能设计的新数据集。基于ViDoSeek，我们发现当前RAG方法存在两大关键问题：其一，纯视觉检索方法难以有效整合文本与视觉特征；其二，现有方案常因分配的推理标记不足而影响效果。为解决这些难题，我们提出了ViDoRAG——一个专为视觉文档复杂推理设计的多智能体RAG框架。ViDoRAG采用基于高斯混合模型（GMM）的混合策略，实现高效多模态检索。为进一步挖掘模型推理潜力，我们设计了一个包含探索、总结与反思的迭代智能体工作流，为研究RAG领域的测试时扩展提供了全新框架。在ViDoSeek上的大量实验证明了我们方法的卓越效果和广泛适用性。尤为值得一提的是，ViDoRAG在具有竞争力的ViDoSeek基准测试中，超越现有方法10%以上。

> Understanding information from visually rich documents remains a significant challenge for traditional Retrieval-Augmented Generation (RAG) methods. Existing benchmarks predominantly focus on image-based question answering (QA), overlooking the fundamental challenges of efficient retrieval, comprehension, and reasoning within dense visual documents. To bridge this gap, we introduce ViDoSeek, a novel dataset designed to evaluate RAG performance on visually rich documents requiring complex reasoning. Based on it, we identify key limitations in current RAG approaches: (i) purely visual retrieval methods struggle to effectively integrate both textual and visual features, and (ii) previous approaches often allocate insufficient reasoning tokens, limiting their effectiveness. To address these challenges, we propose ViDoRAG, a novel multi-agent RAG framework tailored for complex reasoning across visual documents. ViDoRAG employs a Gaussian Mixture Model (GMM)-based hybrid strategy to effectively handle multi-modal retrieval. To further elicit the model's reasoning capabilities, we introduce an iterative agent workflow incorporating exploration, summarization, and reflection, providing a framework for investigating test-time scaling in RAG domains. Extensive experiments on ViDoSeek validate the effectiveness and generalization of our approach. Notably, ViDoRAG outperforms existing methods by over 10% on the competitive ViDoSeek benchmark.

[Arxiv](https://arxiv.org/abs/2502.18017)