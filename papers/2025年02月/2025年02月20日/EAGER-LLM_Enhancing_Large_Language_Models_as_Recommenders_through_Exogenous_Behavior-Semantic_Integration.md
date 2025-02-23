# EAGER-LLM：通过整合外部行为与语义，提升大型语言模型的推荐能力

发布时间：2025年02月20日

`LLM应用` `推荐系统` `电子商务`

> EAGER-LLM: Enhancing Large Language Models as Recommenders through Exogenous Behavior-Semantic Integration

# 摘要

> 大型语言模型（LLMs）正越来越多地被用作先进推荐系统开发的基础架构，凭借其广泛的知識和推理能力提供了增强的功能。现有的基于LLM的推荐系统（RSs）常常面临挑战，这是由于预训练LLMs的语言语义与推荐系统所需的协作语义之间存在显著差异。这些系统利用预训练的语言语义，但通过LLM主干从头开始学习协作语义。然而，LLMs并不是为推荐而设计的，导致协作学习效率低下、结果相关性较弱，以及传统RS功能的整合效果不佳。

为了解决这些问题，我们提出了EAGER-LLM，这是一个基于解码器-only LLM的生成推荐框架，以一种非侵入式的方式整合了内源和外源的行为及语义信息。具体来说，我们提出了以下创新：

1. 双源知识丰富的项目索引，整合了外源信号的索引序列，实现了高效的全链路处理；
2. 非侵入式的多尺度对齐重构任务，引导模型更深入地理解协作和语义信号；
3. 一种退火适配器，旨在精细平衡模型的推荐性能与理解能力。

我们通过在三个公共基准上的严格测试，展示了EAGER-LLM的有效性。

> Large language models (LLMs) are increasingly leveraged as foundational backbones in the development of advanced recommender systems, offering enhanced capabilities through their extensive knowledge and reasoning. Existing llm-based recommender systems (RSs) often face challenges due to the significant differences between the linguistic semantics of pre-trained LLMs and the collaborative semantics essential for RSs. These systems use pre-trained linguistic semantics but learn collaborative semantics from scratch via the llm-Backbone. However, LLMs are not designed for recommendations, leading to inefficient collaborative learning, weak result correlations, and poor integration of traditional RS features. To address these challenges, we propose EAGER-LLM, a decoder-only llm-based generative recommendation framework that integrates endogenous and exogenous behavioral and semantic information in a non-intrusive manner. Specifically, we propose 1)dual-source knowledge-rich item indices that integrates indexing sequences for exogenous signals, enabling efficient link-wide processing; 2)non-invasive multiscale alignment reconstruction tasks guide the model toward a deeper understanding of both collaborative and semantic signals; 3)an annealing adapter designed to finely balance the model's recommendation performance with its comprehension capabilities. We demonstrate EAGER-LLM's effectiveness through rigorous testing on three public benchmarks.

[Arxiv](https://arxiv.org/abs/2502.14735)