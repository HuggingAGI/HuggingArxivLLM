# YuLan-Mini：一款开放的、数据利用高效的语言模型

发布时间：2024年12月23日

`LLM应用` `模型预训练`

> YuLan-Mini: An Open Data-efficient Language Model

# 摘要

> 大型语言模型（LLMs）的有效预训练颇具挑战，原因在于资源需求庞大以及所涉技术流程繁杂。本文针对 YuLan-Mini 给出了一份详尽的技术报告，这是一个拥有 2.42B 参数的高性能基础模型，在同等参数规模的模型中表现顶尖。我们的预训练方式着重通过三项关键技术贡献来提升训练效能：精心打造的数据管道将数据清理与数据调度策略相融合，稳健的优化方法以缓解训练的不稳定性，以及有效的退火方法，此方法涵盖了有针对性的数据选择和长上下文训练。尤为显著的是，在 1.08T 标记上训练的 YuLan-Mini 取得了可与需要更多数据的行业领先模型相媲美的性能。为方便重现，我们公布了每个训练阶段数据构成的完整细节。项目详情可通过以下链接获取：https://github.com/RUC-GSAI/YuLan-Mini。

> Effective pre-training of large language models (LLMs) has been challenging due to the immense resource demands and the complexity of the technical processes involved. This paper presents a detailed technical report on YuLan-Mini, a highly capable base model with 2.42B parameters that achieves top-tier performance among models of similar parameter scale. Our pre-training approach focuses on enhancing training efficacy through three key technical contributions: an elaborate data pipeline combines data cleaning with data schedule strategies, a robust optimization method to mitigate training instability, and an effective annealing approach that incorporates targeted data selection and long context training. Remarkably, YuLan-Mini, trained on 1.08T tokens, achieves performance comparable to industry-leading models that require significantly more data. To facilitate reproduction, we release the full details of the data composition for each training phase. Project details can be accessed at the following link: https://github.com/RUC-GSAI/YuLan-Mini.

[Arxiv](https://arxiv.org/abs/2412.17743)