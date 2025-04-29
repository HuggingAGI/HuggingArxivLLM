# 基于上下文引导的动态检索，助力提升RAG模型的生成质量

发布时间：2025年04月27日

`RAG`

> Context-Guided Dynamic Retrieval for Improving Generation Quality in RAG Models

# 摘要

> 本文致力于优化检索增强生成（RAG）架构，提出了一种基于状态的动态知识检索机制，旨在提升大型语言模型在开放领域问答和复杂生成任务中的表现。通过引入多层级感知检索向量构建策略和可微分的文档匹配路径，实现了检索模块与生成模块的端到端联合训练与协同优化，有效克服了传统静态RAG结构在上下文适应和知识获取方面的不足。实验在Natural Questions数据集上进行，覆盖了GPT-4、GPT-4o和DeepSeek等多种大型模型。多角度对比与消融实验结果表明，该方法显著提升了BLEU和ROUGE-L指标表现。在语义模糊和多文档融合任务中，其展现出更强的鲁棒性和生成一致性。这些成果凸显了该方法在构建高质量语言生成系统方面的广泛应用潜力和实用价值。

> This paper focuses on the dynamic optimization of the Retrieval-Augmented Generation (RAG) architecture. It proposes a state-aware dynamic knowledge retrieval mechanism to enhance semantic understanding and knowledge scheduling efficiency in large language models for open-domain question answering and complex generation tasks. The method introduces a multi-level perceptive retrieval vector construction strategy and a differentiable document matching path. These components enable end-to-end joint training and collaborative optimization of the retrieval and generation modules. This effectively addresses the limitations of static RAG structures in context adaptation and knowledge access. Experiments are conducted on the Natural Questions dataset. The proposed structure is thoroughly evaluated across different large models, including GPT-4, GPT-4o, and DeepSeek. Comparative and ablation experiments from multiple perspectives confirm the significant improvements in BLEU and ROUGE-L scores. The approach also demonstrates stronger robustness and generation consistency in tasks involving semantic ambiguity and multi-document fusion. These results highlight its broad application potential and practical value in building high-quality language generation systems.

[Arxiv](https://arxiv.org/abs/2504.19436)