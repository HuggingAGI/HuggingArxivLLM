# 问题解决了吗？基于LLMs的布局丰富文档信息抽取设计空间

发布时间：2025年02月25日

`LLM应用` `文档处理`

> Problem Solved? Information Extraction Design Space for Layout-Rich Documents using LLMs

# 摘要

> 本文定义并探索了使用大型语言模型（LLMs）从布局丰富的文档中进行信息提取（IE）的设计空间。使用LLMs进行布局感知信息提取的三大核心挑战是：1）数据结构化，2）模型参与，3）输出精炼。我们的研究深入探讨了这些核心挑战中的子问题，如输入表示、分块、提示以及LLMs和多模态模型的选择。通过一个新的布局感知IE测试套件，我们评估了不同设计选择的成果，并与最先进的（SoA）模型LayoutLMv3进行了基准对比。结果显示，单因素试验（OFAT）的配置实现了接近最优的结果，F1分数比基线模型提升了14.1分，而全面因子探索仅带来了15.1分的微小提升，但token使用量却增加了36倍。我们证明，经过良好配置的通用型LLMs可以与专用模型相媲美，提供了一种具有成本效益的替代方案。我们的测试套件可在https://github.com/gayecolakoglu/LayIE-LLM免费获取。

> This paper defines and explores the design space for information extraction (IE) from layout-rich documents using large language models (LLMs). The three core challenges of layout-aware IE with LLMs are 1) data structuring, 2) model engagement, and 3) output refinement. Our study delves into the sub-problems within these core challenges, such as input representation, chunking, prompting, and selection of LLMs and multimodal models. It examines the outcomes of different design choices through a new layout-aware IE test suite, benchmarking against the state-of-art (SoA) model LayoutLMv3. The results show that the configuration from one-factor-at-a-time (OFAT) trial achieves near-optimal results with 14.1 points F1-score gain from the baseline model, while full factorial exploration yields only a slightly higher 15.1 points gain at around 36x greater token usage. We demonstrate that well-configured general-purpose LLMs can match the performance of specialized models, providing a cost-effective alternative. Our test-suite is freely available at https://github.com/gayecolakoglu/LayIE-LLM.

[Arxiv](https://arxiv.org/abs/2502.18179)