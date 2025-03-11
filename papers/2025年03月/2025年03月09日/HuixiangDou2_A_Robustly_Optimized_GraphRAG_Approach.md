# # HuixiangDou2: 一种基于GraphRAG的鲁棒优化方法

发布时间：2025年03月09日

`RAG` `信息检索` `知识库`

> HuixiangDou2: A Robustly Optimized GraphRAG Approach

# 摘要

> 大型语言模型（LLMs）在常见查询上表现优异，但面对专业或新兴主题时往往力不从心。基于图的增强生成式检索（GraphRAG）通过将领域知识结构化为图的形式，实现了动态检索以应对这一挑战。然而，现有实现流程复杂，难以单独评估各组件影响。同时，由于数据集与LLM预训练数据存在重叠，检索效果评估也面临困难。本文介绍的HuixiangDou2是一个经过强化优化的GraphRAG框架。我们借助双层检索的有效性，在32k上下文窗口中优化其性能以实现最大精度，并对比逻辑检索与双层检索以提升整体功能。在测试集上的对比实验中，初始版本Qwen2.5-7B-Instruct表现欠佳，但通过我们的方法，得分显著提升，从60提升至74.5（如图所示）。在特定领域数据集上的实验表明，双层检索增强了模糊匹配能力，而基于逻辑形式的检索则提升了结构化推理水平。此外，我们提出了一种多阶段验证机制，在不增加计算开销的情况下提升了检索的鲁棒性。实证结果表明，与基线相比，我们的方法在准确性方面取得了显著提升，突显了自适应检索的重要性。为了支持研究与应用，我们已将HuixiangDou2开源，访问地址为https://github.com/tpoisonooo/huixiangdou2。

> Large Language Models (LLMs) perform well on familiar queries but struggle with specialized or emerging topics. Graph-based Retrieval-Augmented Generation (GraphRAG) addresses this by structuring domain knowledge as a graph for dynamic retrieval. However, existing pipelines involve complex engineering workflows, making it difficult to isolate the impact of individual components. Evaluating retrieval effectiveness is also challenging due to dataset overlap with LLM pretraining data. In this work, we introduce HuixiangDou2, a robustly optimized GraphRAG framework. Specifically, we leverage the effectiveness of dual-level retrieval and optimize its performance in a 32k context for maximum precision, and compare logic-based retrieval and dual-level retrieval to enhance overall functionality. Our implementation includes comparative experiments on a test set, where Qwen2.5-7B-Instruct initially underperformed. With our approach, the score improved significantly from 60 to 74.5, as illustrated in the Figure. Experiments on domain-specific datasets reveal that dual-level retrieval enhances fuzzy matching, while logic-form retrieval improves structured reasoning. Furthermore, we propose a multi-stage verification mechanism to improve retrieval robustness without increasing computational cost. Empirical results show significant accuracy gains over baselines, highlighting the importance of adaptive retrieval. To support research and adoption, we release HuixiangDou2 as an open-source resource https://github.com/tpoisonooo/huixiangdou2.

[Arxiv](https://arxiv.org/abs/2503.06474)