# Arch-Router：让 LLM 路由与人类偏好完美契合

发布时间：2025年06月19日

`LLM应用` `图像编辑`

> Arch-Router: Aligning LLM Routing with Human Preferences

# 摘要

> 随着大型语言模型（LLMs）的迅速普及——每种模型都针对不同的优势、风格或延迟/成本进行了优化——路由技术已成为实现不同模型实用化应用的关键。然而，现有的LLM路由方法存在两个主要限制：它们使用的基准测试往往无法捕捉到由主观评价标准驱动的人类偏好；并且它们通常只能从有限的模型池中进行选择。本研究提出了一种与偏好对齐的路由框架，通过将查询与用户定义的领域（例如旅行）或动作类型（例如图像编辑）相匹配，来指导模型选择，从而提供了一种在路由决策中编码偏好的实用机制。具体来说，我们引入了	extbf{Arch-Router}，一个紧凑的1.5B规模模型，它能够学习将查询映射到领域-动作偏好，从而为模型路由决策提供支持。我们的方法还支持无缝添加新的模型进行路由，而无需重新训练或修改架构。在对话数据集上的实验表明，我们的方法在将查询与人类偏好匹配方面实现了最先进的（SOTA）结果，超越了顶级专有模型。我们的方法能够捕捉主观评价标准，使路由决策更加透明和灵活。我们的模型可在以下链接获取：	exttt{https://huggingface.co/katanemo/Arch-Router-1.5B}。

> With the rapid proliferation of large language models (LLMs) -- each optimized for different strengths, style, or latency/cost profile -- routing has become an essential technique to operationalize the use of different models. However, existing LLM routing approaches are limited in two key ways: they evaluate performance using benchmarks that often fail to capture human preferences driven by subjective evaluation criteria, and they typically select from a limited pool of models. In this work, we propose a preference-aligned routing framework that guides model selection by matching queries to user-defined domains (e.g., travel) or action types (e.g., image editing) -- offering a practical mechanism to encode preferences in routing decisions. Specifically, we introduce \textbf{Arch-Router}, a compact 1.5B model that learns to map queries to domain-action preferences for model routing decisions. Our approach also supports seamlessly adding new models for routing without requiring retraining or architectural modifications. Experiments on conversational datasets demonstrate that our approach achieves state-of-the-art (SOTA) results in matching queries with human preferences, outperforming top proprietary models. Our approach captures subjective evaluation criteria and makes routing decisions more transparent and flexible. Our model is available at: \texttt{https://huggingface.co/katanemo/Arch-Router-1.5B}.

[Arxiv](https://arxiv.org/abs/2506.16655)